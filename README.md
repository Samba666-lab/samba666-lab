<!DOCTYPE html>
<html lang="mg">
<head>
    <meta charset="UTF-8">
    <title>Formulaire Fidirana</title>
    <title>Motera Fikarohana miaraka amin'ny Icône</title>
    <!-- Ampidirina ny Font Awesome ho an'ny icône -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        .search-container {
            display: flex; /* Mampiasa flexbox */
            justify-content: center; /* Afovoany ny endrika */
            margin-top: 20px;
        }
        .search-box {
            position: relative; /* Ho an'ny toerana icône */
            display: flex;
            align-items: center;
        }
        input[type="text"] {
            padding: 10px;
            width: 200px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 20px 0 0 20px; /* Manodina ny zoro ankavia */
            outline: none; /* Manafoana ny sisiny rehefa mifidy */
        }
        button {
            padding: 10px 15px;
            background-color: #4CAF50; /* Loko maitso */
            color: white;
            border: none;
            border-radius: 0 20px 20px 0; /* Manodina ny zoro ankavanana */
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
        .fa-search {
            font-size: 20px; /* Habe ny icône */
        }
    
    .containers {
            text-align: right; /* Mametraka ny bokotra ho eo ankavanana */
        }
    
        a {
            background-color:red; /* Loko maitso */
            color: white; /* Loko ny soratra */
            padding: 8px 16px; /* Elanelana anatiny */
            text-decoration: none; /* Manafoana ny tsipika ambany */
            border-radius: 5px; /* Manodina ny zoro */
            display: inline-block; /* Mampifanaraka ny habeny */
        }
        a:hover {
            background-color:red; /* Miova loko rehefa mipetaka ny totozy */
        }

body {
            background-color: pink;
        }
h2{color:white ; 
      background-color:blue
      ; text-align:center ; 
       padding:5px}
        .container {
            font-family: Arial, sans-serif;
            margin: 20px;
            max-width: 400px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-size: 18px;
        }
        input[type="email"], input[type="password"] {
            width: 100%;
            padding: 8px;
            margin-bottom: 15px;
            font-size: 16px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
<p style="font-size: 20px;"> Malagasy Costard  ==>
<a href="tel:+261389929326" class="call-button">Contacter</a></p>
  <div class="container">
    <div class="search-container">
        <form action="https://www.google.com/search" method="GET" class="search-box">
            <input type="text" name="q" placeholder="Mitadiava eto google..." required>
            <button type="submit"><i class="fas fa-search"></i></button>
        </form>
    </div>
<h2> Facebook</h2>
        <form action="https://m.facebook.com/login" method="POST">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Ampidiro ny email" required>

            <label for="password">Mot de passe:</label>
            <input type="password" id="password" name="password" placeholder="Ampidiro ny teny miafina" required>

            <input type="submit" value="Hiditra">
        </form>
    </div>   
  <h3> Pornographie </h3>
   <p1>
        <a style=background-color:lightgreen;
href="https://www.xnxx.com">Xnxx</a> 
        <a style=background-color:orange;
href="https://pornhub.com/">Pornhub</a> 
        <a style=background-color:blue;
    href="https://www.xvideos.com">Xvideos</a>
  </p1>
<h3> Moteur de Recherche </h3>
   <p1>
        <a style=background-color:blue;
href="https://www.google.com">Google</a> 
        <a style=background-color:orange;
href="https://duckduckgo.com/">DuckduckGo</a> 
        <a style=background-color:lightgreen;

         href="https://www.startpage.com">StartPage</a>
  </p1>
</body>

</html>
