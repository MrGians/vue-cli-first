<template>
  <div id="jumbotron">
    <figure>
      <img class="custom-img" alt="Vue logo" src="../assets/logo.png" />
    </figure>
    <h3>Sono un Jumbotron molto umile</h3>
    <button class="btn">Cliccami, ma non accadrà nulla!</button>
  </div>
</template>

<script>
export default {
  name: "HeroJumbotron",
};
</script>

<style scoped>
#jumbotron {
  background-color: teal;
  padding: 1rem;
}
h3 {
  color: white;
  padding: 1rem 0;
  text-align: center;
}

.btn {
  display: block;
  margin: 0 auto;
}
figure {
  width: fit-content;
  margin: 0 auto;
  box-shadow: 0px 65px 33px -60px black;
}
#jumbotron:hover .custom-img {
  animation: jumbo 2s linear infinite;
}
.btn {
  background-color: burlywood;
  cursor: pointer;
  padding: 1rem;
  font-size: 1.5rem;
  border-radius: 1rem;
}
@keyframes jumbo {
  0% {
    transform: rotateY(0deg);
  }
  25% {
    transform: rotateY(90deg);
  }
  50% {
    transform: rotateY(180deg);
  }
  75% {
    transform: rotateY(270deg);
  }
  100% {
    transform: rotateY(360deg);
  }
}
</style>
