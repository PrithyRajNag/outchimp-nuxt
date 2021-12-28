<template>
  <div>
    <Nuxt/>
    <default/>
    <div class="container">
      <h3 class="text-center my-5">Welcome to Outchimp Dashboard</h3>
    </div>
  </div>
</template>
<script>
import Default from "~/layouts/default";
export default {
  components: {Default}
};
</script>
