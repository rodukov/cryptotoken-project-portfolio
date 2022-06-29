<template>
  <div class="home">
    <headers/>
    <welcome/>
    <verify/>
    <view_all/>
    <why_we/>
    <footers/>
  </div>
</template>

<script>
import headers from '@/components/headers.vue'
import welcome from '@/components/welcome.vue'
import verify from '@/components/verify.vue'
import view_all from '@/components/view_all.vue'
import why_we from '@/components/why_we.vue'
import footers from '@/components/footers.vue'

export default {
  name: 'Home',
  components: { headers, welcome, verify, view_all, why_we, footers },
  mounted: function() {
    document.title = "NiceToken"
  }
}
</script>

<style scoped>

</style>
