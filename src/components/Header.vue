<template>
  <div >
    <v-card class="overflow-hidden">
      <v-app-bar
        absolute
        dark
        shrink-on-scroll
        prominent

        fade-img-on-scroll
        
      >
        <template v-slot:img="{ props }">
          <v-img v-bind="props" gradient="to top right, rgba(100,115,201,.7), rgba(25,32,72,.7)"></v-img>
        </template>



        <div class="v-app-bar-title__content" style="width: 100px;margin-top: 8%;/* padding: 80px; *//* position: absolute; */">Mi blog</div>


        <template v-slot:extension>

        </template>
      </v-app-bar>
      <v-sheet id="scrolling-techniques-3" class="overflow-y-auto" max-height="600">
        <v-container style="height: 225px;"></v-container>
      </v-sheet>
    </v-card>
  </div>
</template>

<script>
export default {
  name: "Header",

  data: () => ({
    ecosystem: [],
  }),
};
</script>

<style>
div{
  border-radius: none;
}
</style>