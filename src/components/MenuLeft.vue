<template>
  <v-sheet rounded="lg" min-height="268">
    <!--  -->
    <v-container>Repositories</v-container>
    <RepositoriesList />
  </v-sheet>
</template>
<script>
import RepositoriesList from "./RepositoriesList";
export default {
  components: {
    RepositoriesList,
  },
};
</script>