<template>
  <div>
    <div>
      {{htmlString}}
      <div v-html="htmlString"></div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      htmlString: '<p style="color:red;">빨간색문자</p>'
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