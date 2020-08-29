<template>
  <header>
    <img src="../assets/logoM.png" alt="Alt" />
    <a href="https://github.com/MatheusAFPimentel/"><img class="git" src="../assets/git.png" alt="Git"></a>
    <a href="https://www.linkedin.com/in/matheus-augusto-33077194/"><img class="linkedin" src="../assets/linkedin.png" alt="Linkedin"></a>
    <a href="https://www.instagram.com/matheusaugustt/"><img class="insta" src="../assets/insta.png" alt="Instagram"></a>
    <a href="https://twitter.com/MatheussAugust0"><img class="twitter" src="../assets/twitter.png" alt="Twitter"></a>
  </header>
</template>

<script>
export default {};
</script>

<style>

header img {
  margin-left: 15rem;
  margin-top: 1rem;
}

header .git {
  position: absolute;
  margin-left: 95rem;
  margin-top: -3.5rem;
}

header .linkedin {
  position: absolute;
  margin-left: 101rem;
  margin-top: -3.5rem;
}

header .insta {
  position: absolute;
  margin-left: 107rem;
  margin-top: -3.5rem;
}

header .twitter {
  position: absolute;
  margin-left: 113rem;
  margin-top: -3.5rem;
}

@media screen and (max-width:640px) {

  header img {
    position: absolute;
    margin-left: 2.1rem;
  }

  header .git {
    position: absolute;
    margin-left: 11rem;
    margin-top: 0.5rem;
  }

  header .linkedin {
    position: absolute;
    margin-left: 1.7em;
    margin-top: 0.5rem;
  }
}


</style>