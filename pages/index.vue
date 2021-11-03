<template>
  <header class='bg-primary-color paddings'>
    <Navigation />
    <hr />
    <HeroHeader />
  </header>
</template>

<script>
import BaseButton from '../components/BaseButton.vue';
import Navigation from '../pages_components/Navigation.vue';
import HeroHeader from '../pages_components/HeroHeader.vue';

export default {
  components: {
    BaseButton,
    Navigation,
    HeroHeader,
  },
};
</script>

<style lang="scss" scoped>
.flex {
  display: flex;
  flex-direction: row;
  width: 100%;
  justify-content: space-between;
align-items: center;
}

.paddings {
  padding-left: 16px;
    padding-right: 16px;
  // @media screen and (min-width: 640px) {
  //   padding-left: 32px;
  //   padding-right: 32px;
  // }
}

hr {
  width: 100%;
  height: 1px;
  // color: rgba(10, 10, 10, 0.2);
}
</style>