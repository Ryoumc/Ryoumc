<template>
  <div class="home">
    <button type="text" @click="dialogVisible =!dialogVisible ">dailog</button>
    <Dailog :dialogVisible="dialogVisible"></Dailog>
  </div>
</template>

<script>

import Dailog from '@/components/Dailog-element.vue'
export default {
  components: {
    Dailog,
  },
  data(){
    return{
      dialogVisible: false,
    }
  }
}
</script>
