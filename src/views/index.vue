<template>
  <div class="layout">
    <ly-head></ly-head>
    <ly-content></ly-content>
  </div>
</template>

<script>
import LyHead from '@/layout/head.vue'
import LyContent from '@/layout/content.vue'
export default {
  name: 'Layout',
  components: {
    LyHead,
    LyContent
  }
}
</script>

<style lang="scss" scoped>
.layout {
  width: 100%;
  height: 100%;
  overflow: hidden;
}
</style>
