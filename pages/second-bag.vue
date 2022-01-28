<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="logo py-1 my-4 mt-16 d-flex justify-center">
        <BentoSmall />
      </div>
        <h1 class="d-flex justify-center">
          There's a smaller bag inside!
        </h1>
        <div class="d-flex justify-center mt-16">
          <v-btn
            color="#526161"
            width="240px"
            nuxt
            to="/tada"
          >
            Unbox
          </v-btn>
        </div>
    </v-col>
  </v-row>
</template>

<script>
export default {
  data () {
    return {
      fixed: false,
      title: 'Green Light Bento',
    }
  }
}
</script>