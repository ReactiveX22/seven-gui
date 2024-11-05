<script>
  let count = $state(0);
  const increment = () => {
    count += 1;
  };
</script>

<div>
  <p>Count: {count}</p>
  <button onclick={increment}>+1</button>
</div>
