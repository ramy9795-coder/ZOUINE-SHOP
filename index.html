<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KHORDA GAMES</title>

<style>
body{
  margin:0;
  font-family:sans-serif;
  background:#0b1220;
  color:white;
}

/* HEADER */
header{
  background:#00c853;
  padding:15px;
  text-align:center;
  font-weight:bold;
  font-size:20px;
}

/* GRID */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
  gap:15px;
  padding:20px;
}

/* CARD 3D */
.card{
  background:#111a2e;
  border-radius:15px;
  overflow:hidden;
  transition:0.3s;
  transform:perspective(800px) rotateY(0deg);
}

.card:hover{
  transform:perspective(800px) rotateY(8deg) scale(1.05);
}

img{
  width:100%;
  height:140px;
  object-fit:cover;
}

/* BUTTON */
button{
  background:#00c853;
  border:none;
  padding:8px;
  width:100%;
  color:white;
  cursor:pointer;
}

/* ADMIN */
.admin{
  padding:15px;
}

input{
  padding:8px;
  margin:5px;
  width:200px;
}
</style>
</head>

<body>

<header onclick="admin()">KHORDA GAMES 🎮</header>

<div class="admin">
  <input id="title" placeholder="Game name">
  <input type="file" id="file">
  <button onclick="addGame()">Add Game</button>
</div>

<div class="grid" id="games"></div>

<script>

// LOAD DATA
let games = JSON.parse(localStorage.getItem("games")) || [];

function render(){
  let html="";
  games.forEach((g,i)=>{
    html+=`
    <div class="card">
      <img src="${g.img}">
      <h3>${g.title}</h3>
      <button onclick="del(${i})">Delete</button>
    </div>
    `;
  });
  document.getElementById("games").innerHTML=html;
}

// ADD GAME (with image upload)
function addGame(){
  let title = document.getElementById("title").value;
  let file = document.getElementById("file").files[0];

  let reader = new FileReader();

  reader.onload = function(){
    games.push({
      title:title,
      img:reader.result
    });

    localStorage.setItem("games",JSON.stringify(games));
    render();
  }

  reader.readAsDataURL(file);
}

// DELETE
function del(i){
  games.splice(i,1);
  localStorage.setItem("games",JSON.stringify(games));
  render();
}

// ADMIN LOGIN
function admin(){
  let code = prompt("Enter admin code");
  if(code=="4444"){
    alert("Admin unlocked 🔓");
  }
}

render();

</script>

</body>
</html>
