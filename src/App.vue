<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    </v-app-bar>
    <br/>
    <br/>
    <v-main>
    <menu-component-2></menu-component-2>
      <!-- <menu-component-1></menu-component-1> -->
      <!-- <menu-component></menu-component> -->
    </v-main>
  </v-app>
</template>

<script>
import MenuComponent2 from './components/MenuComponent2.vue';
// import MenuComponent1 from './components/MenuComponent1.vue';
// import MenuComponent from './components/MenuComponent.vue';

export default {
  name: 'App',

  components: {
    //MenuComponent1
    MenuComponent2
    // MenuComponent,
  },

  data: () => ({
    //
  }),
};
</script>
