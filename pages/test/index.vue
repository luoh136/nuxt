<template>
  <div>
    {{ msg }}
    <div>
      <span>
        {{ test }}
      </span>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: 'hello world',
      test: 'this is my first test'
    }
  },
  head: function() {
    return {
      title: this.test,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'My custom description'
        },
        {
          name: 'keywords',
          content: 'My keywords'
        }
      ]
    }
  }
}
</script>

<style>
span {
  color: red;
}
</style>
