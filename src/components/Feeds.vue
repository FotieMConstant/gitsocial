<template>
  <v-sheet rounded="lg" min-height="268">
    <!--  -->
    <v-container>
      <h3 class="font-weight-medium">Your Feed</h3>
      <div>
        <Feed v-for="item in 5" :key="item" />
      </div>
    </v-container>
  </v-sheet>
</template>
<script>
import Feed from "./Feed";
export default {
  components: {
    Feed,
  },
};
</script>