# GeteOliver
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <!-- Arquivos externos (CSS, JS)e metadados-->
         <meta charset="utf-8">
         <title>Meu Website</title>
         <meta name="viewport" content="width=device-width, initial-scale=1">
         <style>
 ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #1f1e1e;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  background-color: #181717;
  
}
li a:hover {
  background-color: #111;
}
.active {
  background-color: #181717;
  
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
}

/* Style the header */
.header {
  background-color: #f1f1f1;
  padding: 20px;
  text-align: center;
  
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #000000;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 24px 16px;
  text-decoration: none;
}
 #header.header {
  background-color: #1a4646;
  padding: 90px;
  text-align: center;
}
header p {
  background-color: #ececec;
  padding: 30px;
  text-align: center;
}


/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Create three unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
}

/* Left and right column */
.column.side {
  width: 25%;
}

/* Middle column */
.column.middle {
  width: 50%;
}

/* Clear floats after the columns */
.row::after {
  content: "";
  display: table;
  clear: both;
}


/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}
.footer {

  background-color: #131212;
  text-align: center;
  padding: 110px;
  margin: 0;
  
}
         </style>
    </head>
    <body>
        <!-- Prefira CLASS em vez de id para CSS; id é principalmente para js-->

         <header class="header" id="header">
            <img src="https://i.4cdn.org/w/1715263974147894.jpg" alt="">
            <div>
                <h1 class="active"></h1>
            </div>
         </header>
         <nav class="nav">
            <ul>
                
                <li style="float:right"><a class="active" href="#home">Criar Conta</a></li>
                <li><a href="news.asp">Página Principal</a></li>
                <li><a href="contact.asp">Sobre</a></li>
                <li><a href="about.asp">projetos</a></li>
                <li><a href="about.asp">Participe</a></li>
                
            </ul> 
         </nav>

         <main class="content">
            <div class="row">
                <div class="column side">
                  <h2></h2>
                  
                <p></p>
                </div>
                
                <div class="column middle">
                  <h2>Sobre CSS</h2>
                  <p>Hello, there! Se você está aprendendo a programar em CSS, provavelmente já encontrou os termos margin e padding, e talvez tenha ficado em dúvida de como eles funcionam.

                    Embora ambos afetem o espaço ao redor de um elemento, eles têm propósitos diferentes e são aplicados de maneiras distintas. Então hoje você vai aprender exatamente qual é a diferença entre margin e padding e como você pode aplicá-los de maneira eficaz em seus projetos. Let's go!</p>
                </div>
                
                <div class="colum side">

                </div>

              </div>
               <body>

                <div>
          
                </div>

                <article>
                    <header></header>
                    <section class="introduction">

                    </section>
                    <section class="content">

                    </section>
                     <section class="summary">

                     </section>
                </article>
         </main>

        <section id="comments">
        </section>

         <footer class="footer">
         </footer>
    </body>
</html>
