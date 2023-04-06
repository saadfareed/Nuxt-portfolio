<script>
export default {
  props: ["client"],
  data: () => {
    return {
      // @todo
    };
  },
};
</script>

<template>
  <!-- About single client -->
  <div >
    <img
      :src="client.img"
      :alt="client.title"
      class="
        border border-ternary-light
        dark:border-ternary-dark
        shadow-sm
        rounded-lg
        flex
        justify-center
        mb-8
        cursor-pointer
        dark:bg-secondary-light
      "
    />
  </div>
</template>

<style lang="scss" scoped></style>
