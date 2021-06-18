<template>
  <v-sheet rounded="lg" min-height="268">
    <!--  -->
    <v-container class="d-flex justify-center">
      <v-row class="pa-5">
        <v-avatar size="70">
          <img src="https://avatars.githubusercontent.com/u/42372656?v=4" alt="Fotie" />
        </v-avatar>
        <div class="ml-4">
          <div>
            FotieMConstant
            <v-btn
              icon
              small
              href="https://github.com/FotieMConstant"
              target="_blank"
              title="View profile on Github"
            >
              <v-icon small class="mt-n1">mdi-open-in-new</v-icon>
            </v-btn>
          </div>
          <div class="text--disabled caption mt-n1">@fotiecodes</div>
          <div>
            <v-chip
              label
              x-small
              color="primary"
              text-color="white"
              title="gitsocial contributor"
            >14 gitsc</v-chip>
          </div>
        </div>
        <div class="pa-1 mt-4 text-subtitle-1">
          Passionate software engineer from Africa. YouTuber and Student
          Community Ambassador at OpenClassrooms, passionate about making
          open-source more accessible...
        </div>
        <div class="text--disabled caption">
          <v-icon small class="mr-1">mdi-account-multiple</v-icon>68 followers · 25 following ·
          <v-icon small class="mr-1 mt-n1">mdi-star</v-icon>90
        </div>
      </v-row>
    </v-container>
  </v-sheet>
</template>