<template>
<div class="page-wrap">
    <!-- header  -->
    <header class="header-section has-header-main">
        <!-- Header main -->
        <HeaderMain></HeaderMain>
        <!-- hero -->
        <HeroFour classname="hero-title" title="Collection" :lists="SectionData.breadcrumbData.breadcrumbList.navList"></HeroFour>
    </header>
    <!-- Explore section  -->
    <ExploreSection></ExploreSection>
    <!-- Collections -->
    <!-- <Collections></Collections> -->
    <!-- top creators -->
    <!-- <TopCreators></TopCreators> -->
    <!-- Footer  -->
    <Footer></Footer>
</div><!-- end page-wrap -->
</template>

<script>
// Import component data. You can change the data in the store to reflect in all component
import SectionData from '@/store/store.js'
import HeroFour from '@/components/section/HeroFour.vue'


export default {
  name: 'Explore',
  components: {
    HeroFour
  },
  data () {
    return {
      SectionData
    }
  }
}
</script>
