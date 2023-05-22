<script lang="ts">
 export let name:string;
 export let srcImage: string;
</script>

<style>
  div {
    padding: 10px;
    display: flex;
    border-bottom: 1px solid gray;
    align-items: center;
    gap: 20px;
  }
  img {
    border-radius: 50%;
    width: 30px;
    height: 30px;
  }
  h1 {
    font-size: 20px;
    color: rgb(195, 195, 195);
  }
</style>

<div>
  <img src={srcImage} alt={`${name} photo`}/>
  <h1>{name}</h1>
</div>