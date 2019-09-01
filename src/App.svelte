<script>
  import Binding from './Binding.svelte';
  import Greeting from './Greeting.svelte';
  import Login from './Login.svelte';
	export let name;
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}!</h1>
<Greeting firstName="Robav" lastName="Balnav" />
<Login />
<Binding />
