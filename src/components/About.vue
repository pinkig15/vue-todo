<template>
  <div class="about">
    <h1>Hello {{their_name}} This is an abou page</h1>
    <p>Lorem Ipsum</p>
  </div>
</template>

<script>
export default {
  name: "Skills",
  alert: true,
  data() {
    return {
      their_name: this.$route.params.name
    };
  }
};
</script>
