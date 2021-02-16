<template>
  <div class="hello">
    <h1>About Me</h1>
    <h3>Name</h3>
    <ul>
      <li>
        Ras
      </li>
      <li>
        Kira Kawai
      </li>
    </ul>
    <h3>Belongs</h3>
    <ul>
      <li>Tokyo Institute of Technology</li>
    </ul>
    <h3>Skills</h3>
    <ul>
      <li>JavaScript</li>
      <li>Golang</li>
      <li>C++</li>
    </ul>
    <h3>Links</h3>
    <ul class="links">
      <li>
        <a href="https://github.com/Ras96" target="_blank" rel="noopener">
          <img src="../assets/github.svg" alt="github" width="100px" />
        </a>
      </li>
      <li>
        <a href="https://twitter.com/R4S777" target="_blank" rel="noopener">
          <img src="../assets/twitter.svg" alt="twitter" />
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
