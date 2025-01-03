<script>
    import Button from "../lib/components/Button.svelte";

</script>

<div class="buttons">
  <Button label="1" href="/1"></Button>
  <Button label="2" href="/2"></Button>
  <Button label="3" href="/3"></Button>
  <Button label="4" href="/4"></Button>
</div>

<style>
  .buttons {
    display: flex;
    flex-direction: row;
    gap: 10px;
  }
</style>