<template>
  <div class="home">
    <headers/>
    <welcome/>
    <verify/>
  </div>
</template>

<script>
import headers from '@/components/headers.vue'
import welcome from '@/components/welcome.vue'
import verify from '@/components/verify.vue'

export default {
  name: 'Home',
  components: { headers, welcome, verify },
  mounted: function() {
    document.title = "NiceToken"
  }
}
</script>

<style scoped>

</style>
