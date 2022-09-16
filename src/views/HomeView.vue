<template>
  <div class="home">
    <HeaderUjang/>
    <HeroUjang/>
    <BannerUjang/>
    <InstaUjang/>
    <PartnerUjang/>
    <FooterUjang/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderUjang from '@/components/HeaderUjang.vue';
import HeroUjang from '@/components/HeroUjang.vue';
import BannerUjang from '@/components/BannerUjang.vue';
import InstaUjang from '@/components/InstaUjang.vue';
import PartnerUjang from '@/components/PartnerUjang.vue';
import FooterUjang from '../components/FooterUjang.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderUjang,
    HeroUjang,
    BannerUjang,
    InstaUjang,
    PartnerUjang,
    FooterUjang
}
}
</script>
