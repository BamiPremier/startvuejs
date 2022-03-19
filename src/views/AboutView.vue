

<template>
  <div class="about">
    <h1>This is an about page</h1>
    <AboutWorld msg="Data" />
  </div>
</template>



<script>
// @ is an alias to /src
import AboutWorld from "@/components/AboutComponent.vue";

export default {
  name: "AboutView",
  components: {
    AboutWorld,
  },
};
</script>
