<template>
  <div>
    <svg-icon icon-class="question" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'lbdzDoc',
  data() {
    return {
      url: 'http://doc.lbdz.vip/lbdz-vue'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>