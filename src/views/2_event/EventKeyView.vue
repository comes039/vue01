<template>
  <div>
<!--    <input type="search" name="" id="" v-model="searchText" @keyup="checkEnter($event)">-->
<!--    <button @click="doSearch">조회</button>-->
    <input type="search" name="" id="" v-model="searchText" @keyup.enter="doSearch">
    <button @click="doSearch">조회</button>
  </div>
</template>

<script>
// .delete : delete, backspace key 키 인식
// .enter, .tab, .esc, .space, .up, .down, .left, .right
// .prevent -> event.preventDefault()
export default {
  components: {},
  data() {
    return {
      searchText: ''
    }
  },
  setup() {
  },
  created() {
  },
  mounted() {
  },
  unmounted() {
  },
  methods: {
    doSearch(){
      console.log(this.searchText)
    },
    checkEnter(event){
      if(event.keyCode === 13){
        this.doSearch()
      }
    }
  }
}
</script>

<style scoped>

</style>