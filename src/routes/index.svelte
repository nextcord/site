<svelte:head>
  <title>Nextcord</title>
</svelte:head>

<div class="container">
  <img src="icon.svg" alt="Nextcord icon" />
  <h1>Nextcord</h1>
  <h2>An asynchronous Discord API wrapper in Python</h2>
  <div class="buttons">
    <button class="btn btn-p"
      ><div>
        <span class="material-icons-outlined btn-icon">description</span>Docs
      </div></button
    >
    <button class="btn btn-p"
      ><div><img class="btn-img btn-icon" src="github.png" alt="GitHub icon" />GitHub</div></button
    >
  </div>
</div>

<style lang="scss">
  .container {
    display: flex;
    align-items: center;
    flex-direction: column;

    img {
      width: 12rem;
      height: auto;
      margin-top: 1rem;
    }

    .btn-img {
      width: 1.5rem;
      margin-top: 0;
      height: auto;
    }

    h1 {
      font-size: 4rem;
    }

    h2 {
      margin-top: 0.5rem;
      text-align: center;
    }

    .buttons {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-top: 0.5rem;

      button {
        margin: 0.25rem 0;
      }
    }
  }

  @media (min-width: $breakpoint-tablet) {
    .container {
      margin-left: 15%;
      margin-right: 15%;

      img {
        width: 20rem;
        margin-top: 5rem;
      }

      .buttons {
        flex-direction: row;

        button {
          margin: 1rem 0.25rem;
        }
      }
    }
  }
</style>
