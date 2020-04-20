<template>
  <div>
    <h1>Uh Oh!</h1>
    <h3>It looks like you're having a network issue.</h3>
    <router-link :to="{ name: 'event-list' }">
      Here's the home page if you want to go there.
    </router-link>
  </div>
</template>

<script>
  export default {};
</script>

<style scoped></style>
