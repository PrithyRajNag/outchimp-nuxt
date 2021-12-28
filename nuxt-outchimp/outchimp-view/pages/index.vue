<template>
  <section>
    <Nuxt/>
    <default/>
    <div class="container">
      <h3 class="text-center my-5">Home</h3>
    </div>
  </section>
</template>
<script>
import Default from "~/layouts/default";

export default {
  components: {Default}
};
</script>

