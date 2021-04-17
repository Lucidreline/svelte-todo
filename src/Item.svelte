<script>
  export let task
</script>

<div class="list-item">
  <p>{task}</p>
  <span>X</span>
</div>

<style>
  .list-item {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 0.5rem;
    background-color: rgb(220, 220, 220);
  }
</style>
