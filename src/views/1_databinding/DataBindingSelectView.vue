<template>
  <div>
    <select name="" id="" v-model="selectedCity">
        <option value="01"></option>
        <option value="02">서울</option>
        <option value="03">부산</option>
        <option value="04">제주</option>

    </select>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      selectedCity: '02'
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
  methods: {}
}
</script>

<style scoped>

</style>