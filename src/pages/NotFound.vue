<template>
<section>
  <base-card>
    <h2>Page Not Found</h2>
    <p>
      This page could not be found. Maybe check out all of our
      <router-link to="/coaches"> coaches</router-link>.
    </p>
  </base-card>
</section>
</template>

<script>
export default {
  name: "notFound"
}
</script>

<style scoped>

</style>