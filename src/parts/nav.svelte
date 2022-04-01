<nav>
  <img src="icon.svg" alt="Nextcord icon" />
  <h1>Nextcord</h1>
  <div class="grow" />
  <a href="https://docs.nextcord.dev"><button>Docs</button></a>
  <a href="https://discord.gg/nextcord"><button>Discord</button></a>
  <a href="https://github.com/nextcord"><button>GitHub</button></a>
</nav>

<style lang="scss">
  $nav-height: 2.5rem;

  nav {
    display: flex;
    flex-direction: row;
    align-items: center;
    height: $nav-height;
    background-color: $col-bg-light;

    img {
      width: calc($nav-height * 0.8);
      height: calc($nav-height * 0.8);
      margin-right: 0.5rem;
    }

    button {
      height: $nav-height;
      padding: 0 0.65rem;
      margin: 0 0.15rem;
      border: none;
      background-color: $col-bg-light;
      color: $col-fg;
    }

    button:hover {
      background-color: $col-bg-lighter;
    }

    button:active {
      background-color: $col-bg-light;
    }
  }

  @media (min-width: $breakpoint-tablet) {
    nav {
      padding-left: 5rem;
      padding-right: 5rem;
    }
  }
</style>
