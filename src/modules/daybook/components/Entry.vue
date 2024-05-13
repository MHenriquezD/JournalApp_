<template>
  <div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({ name: 'entry', params: { id: 10 } })"
  >
    <!-- Tittle -->
    <div class="entry-title d-flex">
      <span class="text-success fs-5 fw-bold">24</span>&nbsp;
      <span class="mx-1 fs-5">Abril</span>&nbsp;
      <span class="mx-2 fs-light">2024, Miércoles</span>
    </div>
    <div class="entry-description">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magni, explicabo
      eum accusantium officiis rem dolorum voluptatum dolores esse provident
      nemo laudantium, fugiat quasi corrupti reprehenderit ipsam assumenda quae
      atque necessitatibus!
    </div>
  </div>
</template>

<style lang="scss" scoped>
.entry-container {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;

  &:hover {
    background-color: lighten($color: grey, $amount: 45);
  }
  .entry-description {
    font-size: 12px;
  }
}
</style>
