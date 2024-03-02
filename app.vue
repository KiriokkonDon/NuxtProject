<template>
  <div class="background">
    <h1 class="title">Hello, world!</h1>
  </div>
</template>


<script>
console.log("Hello, world!");
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital@0;1&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital@0;1&family=Open+Sans:ital,wdth@0,75..100;1,75..100&display=swap');

.montserrat {
  font-family: 'Montserrat', sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}

.open-sans {
  font-family: 'Open Sans', sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
  font-variation-settings: 'wdth';
}

.title {
  font-family: Montserrat;
  white-space: nowrap;
  overflow: hidden;
  color: transparent;
  font-size: 50px;
  text-shadow: 0px 4px 10px rgba(179, 147, 211, 0.8);
  background-image: linear-gradient(to right ,#9745e9, #cc64ce, #a651cc, #bc6ed0, #cf8cd5);
  background-size: 200%;
  background-position: -200%;
  -webkit-background-clip: text;
  background-clip: text;
  animation: typingAndGradient 5s infinite;
}

.background {
  margin: 0;
  padding: 0;
  background-image: linear-gradient(to right, #ffecec, #9ec0ea, #8d90e3);
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

@keyframes typingAndGradient {
  0% {
    width: 0ch;
    background-position: -200%;
  }
  10% {
    width: 4ch;
    background-position: -150%;
  }
  20% {
    width: 8ch;
    background-position: -100%;
  }
  30% {
    width: 12ch;
    background-position: -50%;
  }
  40% {
    width: 16ch;
    background-position: 0%;
  }
  90% {
    width: 16ch;
    background-position: 200%;
  }
  100% {
    width: 0ch;
    background-position: 200%;
  }
}


</style>
