<!--<template>-->
<!--  <div>-->
<!--    <svg-icon icon-class="question" @click="goto" />-->
<!--  </div>-->
<!--</template>-->

<script>
export default {
  name: 'RuoYiDoc',
  data() {
    return {
      // url: 'http://doc.ruoyi.vip/ruoyi-vue'
      url:"https://www.baidu.com/"
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
