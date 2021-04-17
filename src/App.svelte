<div id="body">
  <div id="to-do-list">
    <div id="list-header">
      <ul id="list-header-content">
        <li>-</li>
        <li>Tasks</li>
        <li>+</li>
      </ul>
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

  #list-header {
    color: white;
    display: flex;
    justify-content: space-around;
  }
</style>
