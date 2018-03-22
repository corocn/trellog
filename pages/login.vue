<template>
  <div id="netlify-modal"></div>  
</template>

<script>
import netlifyIdentity from "netlify-identity-widget";

export default {
  mounted() {
    netlifyIdentity.init({
      container: "#netlify-modal",
    });
    netlifyIdentity.open();
  }
};
</script>