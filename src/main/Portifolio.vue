<template>
  <div class="Title">
    <h1>Olá, sou Matheus.</h1>
    <h2>Front-end developer.</h2>
    <p>
      5.º período de Sistemas de informação pela UNINASSAU e graduado em Ciências Contábeis pela Faculdade Santa Helena.
      Sou apaixonado por tecnologia e a contabilidade foi o pontapé para conseguir arrecadar fundos e investir na minha carreira em tecnologia que é meu principal objetivo. Alguns dos meus conhecimentos: Java, HTML, CSS, JavaScript, TypeScript, SQL, MongoDB, React, VueJS, Angular.
    </p>

    <div class="middle">
      <a href="mailto:matheusaf.pimentel@gmail.com" class="btn btn4">Contacte-me</a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.Title {
  position: absolute;
  margin-left: 4vh;
  margin-top: 40vh;
  color: white;
}
p {
  text-align: justify;
  width: 100vh;
}
h1 {
  font-weight: 700;
  font-size: 8vh;
  letter-spacing: -0.0416666667rem;
  line-height: 1;
  margin: 0 0 0.6666666667rem;
  padding-top: 0.6666666667rem;
  color: white;
  font-family: "Russo One", sans-serif;
}

* {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  font-family: "Roboto Mono", monospace;
}

body {
  margin: 0;
  width: 50%;
  height: 0vh;
  border-right: 120rem solid transparent;
  border-bottom: 60.5rem solid #1e272e;
  background: #10ac84;
  line-height: 1.5;
}

.middle {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  margin-top: 27vh;
  margin-left: -38vh;
}

.btn {
  position: relative;
  display: block;
  color: white;
  font-size: 14px;
  font-family: "montserrat";
  text-decoration: none;
  margin: 30px 0;
  border: 2px solid #10ac84;
  padding: 14px 60px;
  text-transform: uppercase;
  overflow: hidden;
  transition: 1s all ease;
}
.btn::before {
  background: #10ac84;
  content: "";
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: -1;
  transition: all 0.6s ease;
}

.btn4::before {
  width: 100%;
  height: 0%;
  transform: translate(-50%, -50%) rotate(-45deg);
}
.btn4:hover::before {
  height: 380%;
}

@media screen and (max-width:640px){
  .Title {
    color: white;
    margin-top: 7rem;
  }
  p {
    font-size: 0.8rem;
    width: 50vh;
  }
  h1 {
    font-size: 2rem;
    color: white;
    font-family: "Russo One", sans-serif;
  }

  body {
    border-right: 43rem solid transparent;
    border-bottom: 60.5rem solid #1e272e;
  }
  .middle {
  transform: translate(-50%, -50%);
  margin-top: 40vh;
  margin-left: -10vh;
}

}
</style>