<template>
  <div class="c-topbox">
    <div class="x-container">
      <div class="headline">
        <slot name="headline" />
      </div>
      <div class="content" v-if="$slots.content">
        <slot name="content" />
      </div>
    </div>
  </div>
</template>
<style lang="scss" src="./topbox.scss" scoped>
</style>
