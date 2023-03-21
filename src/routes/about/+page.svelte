<main>
    <body>
      <div class="wrapper">
    <h1 class="info-title">About Us</h1>
    <p class="info">
      We have built a strong and integrated website where each entity and individual is instrumental to the
      accomplishment and
      success of our shared vision. We enjoy a motivating, dynamic work environment, in which colleagues can freely
      express
      their skills and ideas.Although most of our teams have a deep passion for gaming, video games and web industry.
    </p>

    <span class="desktop-cards">
      <img alt="Daenielle May- Web Developer" src="/assets/images/Daenielle_May-card.svg" />
      <img alt="Katherine Kapiga- Web Developer" src="/assets/images/Katherine-card.svg" />
      <img alt="Cordelle- Web Developer" src="/assets/images/Cordelle-card.svg" />
      <img alt="Ebrahim Ladhi- Web Developer" src="/assets/images/Ebrahim-card.svg" />
    </span>
  </div>
    </body>
  </main>

<style>

body {
  background-color: #1a0061;
  color: #f4f4f4;
  height: 100%;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  min-height: 100vh;
}

main {
  background-color: #1a0061;
}



.wrapper {
  min-height: 100vh;
}

/** Title of page **/
.info-title {
  font-family: "Hind Guntur", "Hind Vadodara", "Noto Sans", sans-serif;
  font-size: clamp(3rem, 4vw, 3.5rem);
  text-align: center;

  margin-bottom: 0;
}

/** Description **/
.info {
  font-family: "Gentium Book Basic", "David Libre", "Lustria", serif;
  font-size: clamp(1.3rem, 2vw, 1.5rem);

  text-align: center;
  margin: 1.5rem;
}

/** Container for images **/
.desktop-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;

  padding: 1rem;
}

/** Cards **/
img {
  flex: 1;
  width: auto;

  height: 250px;
  padding: 0.3rem;
}

/** Responsiveness **/
@media (min-width: 40em) {
  .desktop-cards {
    padding: 2rem;
  }
  img {
    height: 380px;
  }
  .info {
    margin: 2.5rem;
    margin-top: 1rem;
  }
}

  </style>