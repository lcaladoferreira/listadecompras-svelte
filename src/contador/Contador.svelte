<script>
  let contador = 0;
</script>

<div>
  Valor: {contador}
  <button on:click={() => contador++}>Incrementar</button>
  <button on:click={() => contador--}>Decrementar</button>
</div>

<style>
  button {
    color: blue;
  }
</style>