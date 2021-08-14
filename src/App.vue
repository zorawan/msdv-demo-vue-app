<template>

  <div id="app">
    <h1>Zora's Summer Workshop Assignments</h1>
    <h3>"I am so happy that I was able to learn coding this summer, and I am glad I completed the course!"</h3>
    <img src="https://media.giphy.com/media/l3V0dy1zzyjbYTQQM/giphy.gif" id=mainImg>
      <ol>
        <li>Assignment Week 2: <a href="./Assignment_2/" target="_blank">About Me</a></li>
        <li>Assignment Week 3: <a href="/Assignment_3/" target="_blank">function Solutions</a></li>
        <li>Assignment Week 4: <a href="/Assignment_4/" target="_blank">Ghibli Films Clickable List</a></li>
        <li>Assignment Week 5: <a href="/Assignment_5/" target="_blank">Mobile Vendor Market Share Worldwide Bar Chart</a></li>
        <li>Assignment Week 6: <a href="/Assignment_6/" target="_blank">Ghibli Films Search Filter</a></li>
  </ol>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <footer>You can find me @ <a href="https://www.linkedin.com/in/zora-hsiangyun-w-513b4441/" class="fa fa-linkedin" target="_blank"></a>
  <a href="https://dribbble.com/zorawan" class="fa fa-dribbble" target="_blank"></a>
  <a href= "https://zora-wan.com/" class= "fa fa-website" target="-blank"><img src="./assets/avatar_zora.png" alt="zora-avatar" height="14px"></a>
  </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  line-height:1.5em;
}
h1{
    font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
  line-height:2em;
}
ol{
  line-height:3em;
  list-style-type: none;
}
.fa {
  padding: 10px;
  font-size: 30px;
  width: 30px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
}

.fa:hover {
    opacity: 0.7;
}
.fa-linkedin {
  background: #007bb5;
  color: white;
}
.fa-dribbble {
  background: #ea4c89;
  color: white;
}
.fa-website {
  background: #ecebed;
}
footer{
  padding:20px;
  margin:20px;
}
#mainImg{
  margin: 20px;
}
</style>
