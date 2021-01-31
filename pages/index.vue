<template>
  <div :class="$style.wrapper">
    <ComponentA :class="$style.componentA"/>
  </div>
</template>

<script>
import ComponentA from '../components/ComponentA'

export default {
  components: {
    ComponentA
  }
}
</script>

<style lang="scss" module>
.wrapper {
  padding: 50px;
}

.componentA {
  border: 1px solid green;
}
</style>
