<template>
  <div>
    <h1 class="text-red">Hello {{ userName }}</h1>
    <h2>{{ message }}</h2>
  </div>
</template>

<script>
export default {
  name: 'DataBindingStringView.vue',
  data () {
    return {
      userName: 'John Doe',
      message: 'Welcome',
      arr: [],
      obj: {}
    }
  }
}
</script>

<style scoped>
.text-red {
  color: red;
}
</style>
