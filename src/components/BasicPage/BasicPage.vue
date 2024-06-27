<script>

</script>

<template>
  <div class="content-page">
    <div class="content-page_card">
      <div class="content-page_card__banner">
        <img
          class="content-page_card__banner-img"
          src="https://cdn.discordapp.com/banners/407247061977792543/a_876dfe5eaf7d4ef3a9efdfac09dfb54a.gif?size=2048"
          alt="discord-banner"
        >

      </div>
    </div>
    <div class="content-page_card">
      1
    </div>
  </div>
</template>

<style lang="scss">
.content-page {
  @apply absolute flex w-full h-full justify-center pt-[5%] bg-[#18191C];

  &_card {
    @apply absolute rounded-lg w-[20%] min-h-[500px] bg-[#373E50];

    &__banner {
      @apply relative w-full h-1.5 z-10;

      &-img {
        @apply rounded-tr-lg rounded-tl-lg;
      }
    }
  }
}
</style>