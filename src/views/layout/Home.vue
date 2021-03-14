<template>
  <div class="home">
    <left-menu></left-menu>>
    <div :class="{ 'main-app': true, 'menu-unfold': $store.state.collapsed }">
      <slider-nav></slider-nav>
    </div>
  </div>
</template>

<script>
import LeftMenu from './components/menu.vue';
import sliderNav from './components/sliderNav.vue';

export default {
  data() {
    return {
    };
  },
  components: {
    LeftMenu,
    sliderNav,
  },
  methods: {},
};
</script>
<style lang="less">
@import url("~@/assets/css/home.less");
</style>
