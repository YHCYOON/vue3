<template>
  <div>
    <!-- readonly 를 사용해 단방향 데이터바인딩 할때는 v-bind (콜론만 남기고 생략가능) -->
    <input type="text" name="" id="" v-bind:value="userId" readonly>
    <input type="text" name="" id="" :value="userId" readonly>
    <br>
    <img :src="imgSrc" alt="" style="width:100px; height:auto;">
    <br>
    <input type="search" name="" id="" v-model="txt1"/>
    <button :disabled="txt1 === ''">조회</button>
  </div>
</template>

<script>
export default {
  components: {},
  data () {
    return {
      userId: 'severa',
      imgSrc: 'https://item.kakaocdn.net/do/d84248170c2c52303db27306a00fb8618f324a0b9c48f77dbce3a43bd11ce785',
      txt1: ''
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
  methods: {}
}
</script>
