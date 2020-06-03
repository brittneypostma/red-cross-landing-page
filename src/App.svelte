<style>
  @import url("https://fonts.googleapis.com/css2?family=Open+Sans&display=swap");
  main {
    background-image: url("/assets/bg-red-cross.jpg");
    min-height: 100vh;
    height: 100vh;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    font-family: "Open Sans", sans-serif;
    font-family: "Open Sans", sans-serif;
    overflow: hidden;
    display: grid;
    grid-template-rows: 150px 1fr 250px;
  }

  header {
    padding: 20px;
  }

  .center {
    display: flex;
    align-items: center;
    align-content: center;
    justify-content: center;
    width: 100vw;
  }

  button {
    background-color: transparent;
    padding-left: 25px;
    border-radius: 30px;
    outline: none;
    border: none;
    transition: all 0.2s linear;
  }

  button:hover {
    background-color: rgba(255, 255, 255, 0.5);
  }

  button > a {
    text-decoration: none;
    display: flex;
    align-items: center;
    background-color: transparent;
  }

  h1 {
    font-size: 6vh;
    text-shadow: -1px -1px 1px rgba(255, 255, 255, 0.1),
      1px 1px 1px rgba(0, 0, 0, 0.5);
  }

  .red {
    color: #9a0000;
  }

  .black {
    color: #111;
  }

  footer {
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: flex-start;
  }

  .links {
    display: grid;
    justify-items: center;
  }

  .links > a {
    display: grid;
    justify-items: center;
    position: relative;
    top: -1px;
    text-decoration: none;
    color: white;
    font-weight: bold;
    outline: none;
    text-shadow: -1px -1px 1px rgba(255, 255, 255, 0.1),
      1px 1px 1px rgba(0, 0, 0, 0.5);
  }

  .links > a > img {
    display: grid;
    justify-items: center;
    padding: 5px;
    border-radius: 30px;
    background-color: rgba(1, 1, 1, 0.5);
    transition: background-color 0.2s linear;
  }

  .links > a > img:hover {
    background-color: rgba(1, 1, 1, 0.7);
  }

  p {
    font-size: 2vh;
  }

  @media only screen and (max-width: 600px) {
    main {
      grid-template-rows: 100px 1fr 1fr;
    }
    .blood-drop {
      width: 150px;
    }

    footer {
      display: grid;
    }
  }
</style>

<main>
  <header>
    <img src="./assets/redcrosslogo.png" alt="Red Cross Logo" width="25%" />
  </header>
  <div class="center">
    <button>
      <a
        href="https://www.redcross.org/give-blood.html"
        target="_blank"
        rel="noopener noreferrer">
        <div>
          <h1 class="red">GIVE BLOOD</h1>
          <h1 class="black">SAVE LIVES</h1>
        </div>
        <img
          src="./assets/redcross.png"
          alt="blood drop logo"
          width="200px"
          class="blood-drop" />
      </a>
    </button>
  </div>
  <footer>
    <div class="links">
      <a
        href="https://www.redcross.org/about-us.html"
        target="_blank"
        rel="noopener noreferrer">
        <img
          src="./assets/donate-blood-white.png"
          alt="donate blood"
          width="30%" />
        <p>About Us</p>
      </a>
    </div>
    <div class="links">
      <a
        href="https://www.redcross.org/volunteer/become-a-volunteer.html/"
        target="_blank"
        rel="noopener noreferrer"
        class="volunteer">
        <img src="./assets/volunteer.png" alt="Volunteer" width="30%" />
        <p>Volunteer</p>
      </a>
    </div>
    <div class="links">
      <a
        href="https://www.redcross.org/donate/donation.html/"
        target="_blank"
        rel="noopener noreferrer">
        <img
          src="./assets/donate-money-white.png"
          alt="donate blood"
          width="30%" />
        <p>Donate Money</p>
      </a>
    </div>
  </footer>
</main>
