<style>
  .generalContainer {
    border-top: solid gray 1px;
    padding-top: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
    padding: 10px;
  }
  .inputContainer {
    width: 98%;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 100%;
  }
</style>
<div class="generalContainer">
  <div class="inputContainer">
    <slot></slot>
  </div>
</div>