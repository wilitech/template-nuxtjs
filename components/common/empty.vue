<template>
  <div class="empty-box">
    <slot>{{ $t('common.empty') }}</slot>
  </div>
</template>

<script>
export default {
  name: 'EmptyBox'
}
</script>

<style lang="scss">
.empty-box {
  position: relative;
  display: flex;
  width: 100%;
  height: 100%;
  min-height: 5em;
  text-align: center;
  justify-content: center;
  align-items: center;
}
</style>
