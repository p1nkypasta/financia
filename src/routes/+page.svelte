<script>
    import Button from "../lib/components/Button.svelte";

    import { base } from "$app/paths";
</script>

<div class="buttons">
  <Button label="1" href="{base}/1"></Button>
  <Button label="2" href="{base}/2"></Button>
  <Button label="3" href="{base}/3"></Button>
  <Button label="4" href="{base}/4"></Button>
</div>

<style>
  .buttons {
    display: flex;
    flex-direction: row;
    gap: 10px;
  }
</style>