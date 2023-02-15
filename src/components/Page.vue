<template>
  <v-container>
    <v-card width="3000" >
    <v-carousel width="3000" >
      <v-carousel-item src="https://i.ytimg.com/vi/-DoNTfXlBbo/maxresdefault.jpg" ></v-carousel-item>

      <v-carousel-item src="https://i.kym-cdn.com/photos/images/facebook/002/270/117/448.jpg" ></v-carousel-item>

      <v-carousel-item src="https://i.ytimg.com/vi/BkgA2_sB6NM/maxresdefault.jpg" ></v-carousel-item>
    </v-carousel>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "Page",

  data: () => ({
    ecosystem: [],
  }),
};
</script>

<style>
.container{
  max-width: 1800px;
}
</style>