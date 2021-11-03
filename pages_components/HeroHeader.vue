<template>
  <div class="flexx">
    <div class="left">
      <h1>Le bien être au naturel</h1>
      <p class="description">
        <span>Découvre</span> et <span>partage</span> tes recettes naturelles
        faites maison préférées
      </p>

      <BaseButton typeOfButton="primaryButtonWhite" class="heybtn"
        >Inscris toi</BaseButton
      >
      <p class="text-inscription">
        Tu fais pas partie d'ici ? <href>Inscris-toi.</href>
      </p>
    </div>
    <img class="img" src="../assets/img/icons/hero-header-icon.svg" alt="" />
  </div>
</template>

<style lang="scss" scoped>
.flexx {
  @media screen and (min-width: 640px) {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
  }
    padding-bottom: 32px;

}

.heybtn {
  margin-bottom: 20px;
}

.left {
  display: flex;
  flex-direction: column;
  width: 60%;
}
h1 {
  color: #fafafa;
  font-family: "Oswald", sans-serif;
  letter-spacing: 4%;
  font-weight: 600;
  font-size: 24px;
  text-transform: uppercase;
  margin-bottom: 16px;
  margin-top: 16px;
}

span {
  font-weight: 600;
}

.img {
  display: none;
  @media screen and (min-width: 640px) {
    display: block;
    width: 40%;
  }
}

.text-inscription {
  font-weight: lighter;
  font-size: 10px;

  & href {
    color: rgb(218, 23, 55);
  }
  @media screen and (min-width: 640px) {
    font-size: 12px;
  }
}

.description {
  margin-bottom: 60px;
  @media screen and (min-width: 640px) {
    font-size: 30px;
  }
}
</style>