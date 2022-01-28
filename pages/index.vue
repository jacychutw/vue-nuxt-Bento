<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="logo py-1 my-4 d-flex justify-center">
        <BentoLarge />
      </div>
        <h1 class="d-flex justify-center">
          What's in the bag?
        </h1>
        <div class="d-flex justify-center mt-16">
          <v-btn
            color="#526161"
            width="240px"
            nuxt
            to="/second-bag"
          >
            Unbox
          </v-btn>
        </div>
    </v-col>
  <!-- <img
    class="bento-large"
    alt="Bento Large"
    src="../assets/images/bags/blue.png"
  >
  <img
    class="bento-large"
    alt="Bento Large"
    src="../assets/images/items/1.png"
  >
  <img
    class="bento-large"
    alt="Bento Large"
    src="../assets/images/items/2.png"
  >
  <img
    class="bento-large"
    alt="Bento Large"
    src="../assets/images/items/3.png"
  >
  <img
    class="bento-large"
    alt="Bento Large"
    src="../assets/images/items/4.png"
  > -->
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage',
  data () {
    return {
      bags: ['../assets/images/bags/blue.png','../assets/images/bags/gray.png','../assets/images/bags/orange.png','../assets/images/bags/pink.png','../assets/images/bags/purple.png','../assets/images/bags/red.png','../assets/images/bags/rose.png','../assets/images/bags/white.png']
    }
  },
}
</script>
