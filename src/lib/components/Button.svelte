<script>
  export let label;
  export let href;

  import { goto } from "$app/navigation";
</script>

<div class="button-wrapper">
  <div class="button" on:click={goto(href)} on:keypress={goto(href)} role="button" tabindex=0>
    {label}
  </div>
</div>

<style>
  .button {
    padding: 10px;
    background-color: #0099ff;
    color: white;
    text-align: center;
    border-radius: 10px;
    width: 50px;
    cursor: pointer;
  }
</style>