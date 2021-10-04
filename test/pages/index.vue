<template>
  <div>
  Component test ( should print "vue lazy load" in 30px ):<hr>
  <vuelazyload/>
  </div>
</template>

<script>
//import vuelazyload from "../../dist/vue-lazy-load.esm.js"
//import "../../dist/vue-lazy-load.css"
import vuelazyload from "@publishvue/vuelazyload"
import "@publishvue/vuelazyload/dist/vue-lazy-load.css"
export default {
  components:{
    vuelazyload
  }
}
</script>
