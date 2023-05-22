<script lang="ts">
  export let placeholder: string;
  export let type: string;
</script>
<style>
  .input {
    outline: none;
    border: none;
    color: rgb(165, 165, 165);
    background-color: #051d1f;
    padding-left: 20px;
    width: 100%;
  }
</style>

<input class="input" placeholder={placeholder} type={type}/>