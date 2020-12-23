<template>
  <div class="container-fluid">
    <app-nav />

    <app-content />
  </div>
</template>

<script>
import appNav from "@/components/menu/nav";
import appContent from "@/components/content/content";

export default {
  components: {
    appNav,
    appContent
  }
};
</script>
<style lang="scss" scoped></style>
