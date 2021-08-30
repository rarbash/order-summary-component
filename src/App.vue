<template>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <body>
    <!-- <img
      src="../order-summary-component-main/images/pattern-background-desktop.svg"
      alt="background"
    /> -->

    <div class="box">
      <img
        src="../order-summary-component-main/images/illustration-hero.svg"
        alt="illustration-hero"
      />

      <h1>Order Summary</h1>

      <p style="width: 20em">
        You can now listen to millions of songs, audiobooks, and podcasts on any
        device anywhere you like!
      </p>
      <br />
      <div class="music-box padding-lr">
        <div style="align-self: center">
          <img
            src="../order-summary-component-main/images/icon-music.svg"
            alt="music-icon"
          />
        </div>

        <div style="align-self: center">
          <p style="margin: 0"><strong>Annual Plan</strong></p>
          <p style="margin: 0">$59.99/year</p>
        </div>

        <div style="align-self: center">
          <a href="" style="color: hsl(228, 45%, 44%)">Change</a>
        </div>
      </div>
      <br />

      <div class="button">
        <p style="margin: 0"><strong>Proceed to Payment</strong></p>
      </div>
      <br />
      <a href="" style="color: hsl(228, 45%, 44%)">Cancel Order</a>
    </div>
  </body>
</template>

// <script>
// export default {
//   name: "App",
// };
//
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@500&display=swap");

#app {
  font-family: "Red Hat Display", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  justify-content: center;
  align-content: center;
}

body {
  background-color: hsl(225, 100%, 94%);
  height: 100%;
}

.box {
  background-color: white;
  width: 450px;
  border-radius: 30px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding-bottom: 2em;
  color: hsl(223, 47%, 23%);
  float: center;
}

.music-box {
  background-color: hsl(225, 100%, 98%);
  display: inline-grid;
  grid-template-columns: 20% 50% auto;
  border-radius: 10px;
  height: 5.5em;
  width: 20em;
}

.button {
  height: 3.5em;
  width: 20em;
  color: white;
  background-color: hsl(245, 75%, 52%);
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 10px;
}
</style>
