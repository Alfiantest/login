<!DOCTYPE html>

<html>

<head>

<title>Form Login</title>

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link href="https://fonts.googleapis.com/icon?family=Material+Icons+Outlined"

      rel="stylesheet">

<style>

  body{

  background-color: #f2f2f2;

  font-family: Arial, Helvetica, sans-serif;

  }

  h1{

  width:100%;

  text-align: center;

  }

.case{

width:300px;

height:auto;

background-color: white;

  border-radius:5px;

  box-shadow:0px 0px 4px #dbdbdb;

  margin:0 auto;

margin-top:50px;

overflow: hidden;

padding:20px;

padding-bottom:50px;

}

h3{

width:100%;

text-align: center;

font-size: 30px;

color:#4d2df1ff;

}

.grid{

display: grid;

width:100%;

height:100px;

grid-template-columns:10% 83%;

grid-gap:10px;

}

#ic{

font-size:30px;

color:#4d2df1ff;

}

.input{

width:100%;

height:20px;

outline: none;

border:0;

border-bottom:2px solid #4d2df1ff;

padding:3px;

font-size:15px;

}

.remember{

width:100%;

display: flex;

}

.checkbox{

width:15px;

height:15px;

}

.remember span{

margin-left:10px;

font-size:15px;

margin-top:2px;

}

.masuk{

background-color: #4d2df1ff;

margin-top:15px;

width: 100%;

height:40px;

border: 0;

border-radius:5px;

color:white;

font-size:15px;

outline:none;

transition: 0.3s;

}

.masuk:hover{

opacity: 0.2;

}

.forgot{

font-size:15px;

margin-top:10px;

float:right;

}

a{

text-decoration: none;

}

.exists{

display:block;

margin-top:60px;

font-size:15px;

width:100%;

text-align: center;

}

</style>

</head>

<body>

<h1>Form Login</h1>

 

  <div class='case'>

  <h3>Masuk</h3>

  <div class='grid'>

  <span class="material-icons-outlined" id="ic">account_circle</span>

  <input class="input" name="username" placeholder="Username"/>

  <span class="material-icons-outlined" id="ic">lock</span>

  <input class="input" type='password' name="password" placeholder="Password"/>

  </div>

  <div class='remember'>

  <input class="checkbox" type="checkbox"><span>Ingat Saya</span>

  </div>

  <button class='masuk'>Masuk</button>

  <a class='forgot' href="#">Lupa Password?</a>

    <span class='exists' >Sudah punya akun ? <a href="#">Masuk</a></span>

  </div>

 

  </body>

</html>
