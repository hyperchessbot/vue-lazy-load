<template>
  <div class="vuelazyload">
    {{ msg }}
  </div>
</template>

<script>
export default {
  props: {    
    msg: {
      type: String,
      default: 'vue lazy load',
    },    
  },
  data() {
    return {      
    }
  },
  mounted() {    
  },
  beforeDestroy() {    
  },
  methods: {    
  },
}
</script>

<style>
.vuelazyload{
  font-size: 30px;
}
</style>