<script lang = "ts">
  let count = 0;
function addOne() {
  count += 1;
}
</script>
<style lang="scss">
  
</style>

  <button on:click={addOne}>Clicked {count} times</button>
