<script>
  export let count = 1

  $: double = count * 2
</script>

<h2>Hello {double}!</h2>

<style lang="scss">
  h2 {
    color: royalblue;
  }
</style>
