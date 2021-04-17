<div id="body">
  <div id="to-do-list">
    <div id="list-header">
      <div id="list-header-content">
        <span>-</span>
        <span>Tasks</span>
        <span>+</span>
      </div>
    </div>
  </div>
</div>

<style>
  :global(body) {
    margin: 0;
    padding: 0;
  }

  #body {
    display: grid;
    place-items: center;
    width: 100%;
    height: 100vh;
    background-color: red;
  }

  #to-do-list {
    width: 15rem;
  }

  #list-header {
    background-color: orange;
  }

  #list-header-content {
    width: 100%;
    color: white;
    display: flex;
    justify-content: space-around;
    list-style: none;
    text-align: center;
    padding: 0.5rem 0;
  }

  #list-header-content span {
  }
</style>
