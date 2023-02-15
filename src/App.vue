<template>
  <v-app>
    <Header></Header>
    <v-main>
      <Page></Page>
      <Groups></Groups>
    </v-main>
    <Footer></Footer>
  </v-app>
</template>

<script>
import Header from './components/Header.vue';
import Page from './components/Page';
import Footer from './components/Footer';
import Groups from './components/Groups';
export default {
  name: 'App',

  components: {
    Header,
    Page,
    Footer,
    Groups,
  },

  data: () => ({
    //
  }),
};
</script>
