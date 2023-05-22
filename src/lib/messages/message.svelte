<!-- Message.svelte -->
<script lang="ts">
  export let message: string;
  export let sender: boolean;
</script>

<style>
  .message-container {
    display: flex;
    justify-content: flex-end;
    font-size: 13px;
  }

  .message {
    background-color: rgba(0,0,0,0.05);
    color: rgb(195, 195, 195);
    width: 100%;
    padding: 20px;    
    text-align: right;
  }

  .message.receiver {
    text-align: left;
    background-color: rgba(255,255,255,0.05);
  }
</style>

<div class="message-container">
  <div class={"message " + (sender ? "" : "receiver")}>
    {message}
  </div>
</div>
