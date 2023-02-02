<template>
  <div>
    <svg-icon icon-class="github" @click="goto" />
  </div>
</template>

<script>
export default {
  name: 'BeiShengGit',
  data() {
    return {
      url: 'https://github.com/Beisheng8888/BeiSheng-Admin'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
