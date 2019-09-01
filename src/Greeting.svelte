<script>
  export let firstName;
  export let lastName;

  $: name = `${firstName} ${lastName}`;
</script>

<style>
  h2 {
    font-size: 15px;
    color: red;
  }
</style>

<h2>Wesh {name} bien ou quoi ?</h2>