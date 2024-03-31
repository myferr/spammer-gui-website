<style>
:root {
  font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.5;
  font-weight: 400;

  color-scheme: light dark;
  color: rgba(255, 255, 255, 0.87);
  background: rgb(204,104,200);
  background: linear-gradient(90deg, rgba(204,104,200,1) 0%, rgba(204,102,157,1) 100%);
  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  scroll-behavior: smooth;
}

#about, #credits {
  margin-top:200px;
  max-width:500px;
  background-color:#0d1117;
  padding:20px;
  border-radius:15px; 
  box-shadow:10px 0px 10px #0d1117;;
}

#credits {
  float:right;
  padding:20px;
  padding-right:350px;
  text-align:left;
  box-shadow:-10px 0px 10px #0d1117;;
}

#about>h2, #credits>h2 {
  color:#535bf2;
}

a {
  font-weight: 500;
  color: #646cff;
  text-decoration: inherit;
}
a:hover {
  color: #535bf2;
}

h1 {
  font-size: 3.2em;
  line-height: 1.1;
}

button {
  border-radius: 8px;
  border: 1.5px solid transparent;
  padding: 0.6em 1.2em;
  font-size: 1em;
  font-weight: 500;
  font-family: inherit;
  background-color: #0d1117;
  cursor: pointer;
  transition: border-color 0.25s;
}
button:hover {
  border-color: #646cff;
}
button:focus,
button:focus-visible {
  outline: 4px auto -webkit-focus-ring-color;
}

.card {
  padding: 2em;
}

#bar {
  background-color:#0d1117;
  padding:20px;
  border-radius:15px; 
  box-shadow:0px 5px 10px #0d1117;;
}

#bar>a {
  margin-right:100px;
}

#bar>b {
  margin-right:150px;
}

#main {
  text-align: center;
  margin-top:100px;
}

@media (prefers-color-scheme: light) {
  :root {
    color: #213547;
    background-color: #ffffff;
  }
  a:hover {
    color: #747bff;
  }
  button {
    background-color: #f9f9f9;
  }
}

#releases-page {
  margin-top:600px;
}

#releases-page>h1 {
  background-color:white;
  color:black;
  border-radius:15px;
  padding:15px;
  max-width: 500px;
}

.releases {
  margin-right:10px;
  font-weight:600;
  color: #747bff;
  background-color:#0f1c30;
  border-radius:100px;
  padding:5px;
  border:2px solid #474fda;
}
</style>

<template>
  <div id="bar">
    <b>Spammer GUI</b><a href="https://github.com/myferr/spammer-gui">GitHub</a><a href="https://github.com/myferr/spammer-gui/releases">Releases</a><a href="https://github/myferr/spammer-gui/files/14814049/spammer-gui.zip">Download</a>
  </div>
  <div id="main">
    <h1>Spammer GUI</h1>    
    <a href="https://github/myferr/spammer-gui/files/14814049/spammer-gui.zip"><button>Download</button></a>
  </div>
  <div id="about">
    <h2>About</h2>
    <span style="font-family:monospace;">
      Spammer GUI is a python-based message sending macro with a graphical user interface <i>(GUI)</i>
    </span>
  </div>
  <div id="credits">
    <h2>Credits</h2>
    <span style="font-family: monospace;">
      Web development by Myfer
      <br>App development by Myfer
      <br><br>> https://github.com/myferr/
    </span>
  </div>
  <div id="releases-page">
    <h1>Releases</h1>
    <span class="releases">
      <a href="https://github.com/myferr/spammer-gui/releases/latest">LATEST VERISON</a>
    </span>
    <span class="releases">
      <a href="https://github.com/myferr/spammer-gui/releases/tag/v1.0.0">spammer-gui -- v1.0.0[ALPHA]</a>
    </span>
  </div>
</template>