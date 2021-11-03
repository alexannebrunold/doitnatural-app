<template>
  <nav class="flex">
    <h1>Do It Natural</h1>

    <ul class="nav">
      <li>Maison</li>
      <li>Beauté</li>
      <li>Articles</li>
      <BaseButton typeOfButton="primaryButtonWhite"> Coucou </BaseButton>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
  .nav {
    @media screen and (min-width: 640px) {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        width: 50%;
        align-items: center;
      }
  }
</style>