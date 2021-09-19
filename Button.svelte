<script>
	let count = 0;

	function handleClick() {
	  count += 1;
	}
</script>

<style>
	button {
	  background: #ff3e00;
	  color: white;
	  border: none;
	  padding: 8px 12px;
	  border-radius: 10px;
	}
</style>

<button on:click={handleClick}>
   {count} {count === 1 ? 'token' : 'tokens'}
</button>