<template>
  <v-tabs
    bg-color="primary"
    grow
  >
    <v-tab>
      <v-badge
        color="pink"
        tag="span"
        dot
      >
        Item One
      </v-badge>
    </v-tab>

    <v-tab>
      <v-badge
        color="green"
        content="6"
        tag="span"
      >
        Item Two
      </v-badge>
    </v-tab>

    <v-tab>
      <v-badge
        color="deep-purple-accent-4"
        icon="$vuetify"
        tag="span"
      >
        Item Three
      </v-badge>
    </v-tab>
  </v-tabs>
</template>
