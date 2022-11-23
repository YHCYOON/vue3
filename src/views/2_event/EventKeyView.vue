<template>
  <div>
    <input type="search" name="" id="" v-model="searchText">
    <button @click="doSearch">조회</button>
  </div>
</template>

<script>
export default {
  components: {},
  data () {
    return {
      sampleData: ''
    }
  },
  setup () {
  },
  created () {
  },
  mounted () {
  },
  unmounted () {
  },
  methods: {
    doSearch () {
      console.log(this.searchText)
    }
  }
}
</script>
<style scoped>

</style>
