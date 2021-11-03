<template>
  <header class='bg-primary-color'>
    <Navigation/>

<hr>

    <h1>Le bien être au naturel</h1>
    <p>
      <span>Découvre</span> et <span>partage</span> tes recettes naturelles faites maison
préférées
</p>

<img class='img' src="../assets/img/icons/hero-header-icon.svg" alt="">

<BaseButton typeOfButton="primaryButtonWhite">Inscris toi</BaseButton>
<p class="text-inscription">Tu fais pas partie d'ici ? <href>Inscris-toi.</href></p>
  </header>
</template>

<script>
import BaseButton from '../components/BaseButton.vue';
import Navigation from '../pages_components/Navigation.vue'

export default {
  components: {
    BaseButton,
    Navigation,
  },
}
</script>

<style lang="scss" scoped>
  .flex {
    display: flex;
    flex-direction: row;
    width: 100%;
    justify-content: space-between;
    padding-left: 16px;
    padding-right: 16px;

    @media screen and (min-width: 640px) {
    padding-left: 32px;
    padding-right: 32px;
  }
  }

  hr {
    width: 100%;
    height: 1px;
    // color: rgba(10, 10, 10, 0.2);
  }

  h1 {
    color: #FAFAFA;
    font-family: 'Oswald', sans-serif;
letter-spacing: 4%;
font-weight: 600;
font-size: 24px;
text-transform: uppercase;
  }

  span {
    font-weight: 600;
  }

  .img {
    width: 100%;
  }

  .text-inscription {
    font-weight: lighter;
    font-size: 10px;

    & href {
      color: rgb(218, 23, 55);
    }
  }
</style>