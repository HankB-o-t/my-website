<template>
    <div id="app">
      <p class="main-p">
        This is my personal website, where I will be putting some interesting
        projects I made. Make sure to check it out!
      </p>
  
      <h2>Let's start with projects I made:</h2>
  
      <div class="row">
        <div class="column">
          <div class="card">
            <h3>MC Clone ⛏</h3>
            <p class="card-p">A little Minecraft clone I made some time ago.</p>
            <br>
          </div>
        </div>
        <div class="column">
          <div class="card">
            <h3>Discord Bot 🤖</h3>
            <p class="card-p">A bot I made for a Discord server with friends.</p>
          </div>
        </div>
        <div class="column">
          <div class="card">
            <h3>Crypto List 💲</h3>
            <p class="card-p">A crypto list I made using Vue & Coingecko API.</p>
          </div>
        </div>
        <div class="column">
          <div class="card">
            <h3>This site 💻</h3>
            <p class="card-p">
              My own portfolio website to show people the things i do.
            </p>
          </div>
        </div>
      </div>
  
      <br />
      <br />
      <br />
      <h2>Things I can do (Services):</h2>
      <ul>
        <li>• Setup Minecraft servers in linux machine 🐧</li>
        <li>• Setup not very big Discord servers 💻</li>
        <li>• Create a welcome website for you or your company 🏨</li>
      </ul>
  
      <h2>Languages I know</h2>
      <div class="row">
        <div class="column">
          <div class="card">
            <h3>Python 🐍</h3>
            <p class="card-p">
              Python Website <a href="https://www.python.org">Click Here</a>
            </p>
          </div>
        </div>
        <div class="column">
          <div class="card">
            <h3>Javascript 📃</h3>
            <p class="card-p">
              MDN Web Docs <a href="https://developer.mozilla.org">Click Here</a>
            </p>
          </div>
        </div>
        <div class="column">
          <div class="card">
            <h3>Rust 🦀</h3>
            <p class="card-p">
              Rust Website <a href="https://www.rust-lang.org">Click Here</a>
            </p>
            <br>
          </div>
        </div>
        <div class="column">
          <div class="card">
            <h3>HTML 📕 + CSS 📘</h3>
            <p class="card-p">
              MDN Web Docs <a href="https://developer.mozilla.org">Click Here</a>
            </p>
          </div>
        </div>
      </div>

      <br />
      <br />
      <br />
      <h2 >Who I am:</h2>
      <div class="card">
        <h4 class="h4">
          I'm a "developer" (because i do this for hobby) who likes to develop some not-so-big websites with vue.js, like this one, I do this things because I have some free time and I don't need to work for someone currently
        </h4>
      </div>
      <br />
      <br />
      <br />
      <h2>How to contact me:</h2>
      <div class="card2" id="bottomPage">
        <p class="card-p2">
          Via github: <a href="https://github.com/HankB-o-t">Here</a> 🐱‍👤
        </p>
      </div>
      <div class="card2">
        <p class="card-p2">
          Via Discord: slaim#0095 💀
        </p>
      </div>
    </div>
</template>
  
<script>


</script>
  
<style>
  .h4 {
    margin-left: 53px;
  }

  .text {
    margin-left: 50px;
    padding: 1.5%;
    border-radius: 2%;
  }
  .welcome {
    margin-top: 0px;
    margin-left: 0px;
    color: rgb(63, 63, 63);
  }
  
  .main-p {
    font-size: 20px;
    max-width: 500px;
    max-height: 500px;
    margin-left: 350px;
  }
  
  .card-p {
    font-size: 15px;
  }
  
  h2 {
    margin-top: 0px;
    margin-left: 50px;
    color: rgb(63, 63, 63);
    font-size: 30px;
  }
  
  h3 {
    margin-top: 0px;
    margin-left: 0px;
    color: rgb(63, 63, 63);
    font-size: 20px;
  }
  
  * {
    box-sizing: border-box;
  }
  
  body {
    font-family: Arial, Helvetica, sans-serif;
  }
  
  .column {
    float: left;
    width: 25%;
    padding: 0 10px;
  }
  .row {
    margin: 0 -5px;
  }
  
  .row:after {
    content: "";
    display: table;
    clear: both;
  }
  .card {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */
    padding: 16px;
    text-align: center;
    background-color: #f1f1f1;
    border-radius: 5%;
  }
  
  /* Responsive columns - one column layout (vertical) on small screens */
  @media screen and (max-width: 600px) {
    .column {
      width: 100%;
      display: block;
      margin-bottom: 20px;
    }
  }
  
  li {
    list-style: none;
    position: relative;
    padding: 0 0 0 20px;
    font-size: 20px;
  }

  .card2 {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */
    padding: 5px;
    margin-top: 10px;
    text-align: center;
    background-color: #f1f1f1;
    border-radius: 2.5%;
  }

  .card-p {
    font-size: 20px;
    font-weight: bold;
  }
</style>