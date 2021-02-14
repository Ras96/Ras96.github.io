<template>
  <div class="hello">
    <img class="icon" alt="Vue logo" src="../assets/icon.gif" />
    <h2>Ras / Kira Kawai</h2>
    <h3>Belongs</h3>
      <div>Tokyo Institute of Technology</div>
    <h3>Skills</h3>
    <ul>
      <li>
        <div>JavaScript</div>
        <div>Golang</div>
        <div>C++</div>
      </li>
    </ul>
    <h3>Links</h3>
    <ul class="links">
      <li>
        <a href="https://github.com/Ras96" target="_blank" rel="noopener">
          <img src="../assets/github.svg" alt="github" width="100px">
        </a>
      </li>
      <li>
        <a href="https://twitter.com/R4S777" target="_blank" rel="noopener">
          <img src="../assets/twitter.svg" alt="twitter">
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "About",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.links img {
  width: 50px;
  height: 50px;
}
</style>
