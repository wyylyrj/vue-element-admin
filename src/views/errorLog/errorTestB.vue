<template>
  <div/>
</template>

<script>
const b = 'abc'
export default {
  data() {
    return {
      b: ''
    }
  },
  created() {
    this.b = b // eslint-disable-line
  }
}
</script>
