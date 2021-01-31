<template>
  <div :class="$style.wrapper">
    componentA
    <ComponentB :class="$style.componentB" />
  </div>
</template>

<script>
import ComponentB from './ComponentB'

export default {
  components: {
    ComponentB
  }
}
</script>

<style lang="scss" module>
.wrapper {
  padding: 20px;
  background: plum;
  border: 1px solid red;
}

.componentB {
  border: 1px solid royalblue;
}
</style>