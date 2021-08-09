<template>
 <h1>{{ count }}</h1>
</template>

<script>
export default {
  data() {
    return {
      count: 2
    }
  },
  created() {
    console.log('created!', this.count)
  },
  mounted() {
    console.log('mounted!')
    console.log(document.querySelector('h1'))
  }
}
</script>