<template>
  <v-app id="inspire">
    <v-app-bar app color="white" flat>
      <v-btn icon>
        <v-avatar v-if="$vuetify.breakpoint.smAndDown" size="32">
          <img src="https://avatars.githubusercontent.com/u/42372656?v=4" alt="John" />
        </v-avatar>
      </v-btn>
      <span class="subtitle-1">gitSocial</span>
      <v-spacers></v-spacers>
      <v-tabs centered class="ml-n9" color="grey darken-1">
        <v-tab>All activity</v-tab>
        <v-tab>Updates</v-tab>
        <v-tab>Profile</v-tab>
      </v-tabs>

      <v-btn icon>
        <v-avatar class="hidden-sm-and-down" color="grey darken-1 shrink" size="32">
          <img src="https://avatars.githubusercontent.com/u/42372656?v=4" alt="John" />
        </v-avatar>
      </v-btn>
    </v-app-bar>

    <v-main class="grey lighten-3 pt-0">
      <v-container class="__container">
        <v-row>
          <v-col class="__menu __leftMenu" cols="12" sm="3">
            <MenuLeft />
          </v-col>

          <v-col class="__mainContainer" cols="12" sm="6">
            <Feeds />
          </v-col>

          <v-col class="__menu __rightMenu" cols="12" sm="3">
            <MenuRight />
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import MenuLeft from "@/components/MenuLeft";
import MenuRight from "@/components/MenuRight";
import Feeds from "@/components/Feeds";
export default {
  components: {
    MenuLeft,
    MenuRight,
    Feeds,
  },
  data() {
    return {};
  },
};
</script>
<style scoped>
.__container {
  max-width: 1800px;
}

/* .__menu {
  position: fixed;
} */
.__leftMenu {
  top: 0;
}
.__rightMenu {
  top: 0;
}
</style>