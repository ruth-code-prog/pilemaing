<template>
  <div class="hello">
   <div>
      <h3 class="text-center pb-4">Godzilla vs. Kong is a 2021</h3>
      <v-layout class="pb-12" align-center justify-center row wrap>
      <video playsinline autoplay muted loop width="360px" height="340px" controls src="../assets/gvk.mp4">
      <br>
      <v-btn>play/stop</v-btn>
      </video>
      </v-layout>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
