<script>
  let count = 0;
</script>

<h1>Test!</h1>
<button on:click={() => (count += 1)}>
  Clicked {count}
  {count === 1 ? "time" : "times"}
</button>
