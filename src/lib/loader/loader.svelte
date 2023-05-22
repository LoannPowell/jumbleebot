<style>
@keyframes loading {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}

.loader {
  border: 4px dotted #4CAF50;
  border-radius: 100%;
  width: 10px;
  height: 10px;
  animation: loading 2s infinite linear;
}
</style>

<div class="loader"></div>
