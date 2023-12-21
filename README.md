# Portifolio
 eu
html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Débora Josué</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <nav>
        <ul>
            <li>
                <a href="index.html">Sobre mim</a>
            </li><li>
                <a href="project.html">Progetos</a>
            </li> <li>
                <a href="contact.html">Contatos</a>
            </li>
        </ul>
    </nav>
    <header>
        <div class="center">
            <img src="./img/debora josue.png">
        </div>
    </header>
        <h1>Débora Josué</h1>
        <h2>Estudante</h2>
        <main>
            <section>
                <h3>Sobre mim</h3>
                <p> 
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
                </p>
            </section>
            <section>
                <h3>Formação</h3>
                <p> 
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
                </p>
            </section>
            <section>
                <h3>Cursos</h3>
                <p> 
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
                </p>
            </section>
        </main>
        <footer> 
            <a href="https://github.com/deborajosue"target="black"rel="noopener noreferrer">
                <img src="./img/github.png"></img>
                <p> git hub</p>
            </a>
            <a href="https://www.instagram.com/debsjosue/?igshid=MzRlODBiNWFlZA"target="black"rel="noopener noreferrer">
                <img src="./img/instragram.png"></img>
                <p> instragram</p>
            </a>
            <a href="https://www.youtube.com/channel/UCS7bd0PhvT6u7T2eAs-ugLg"target="black"rel="noopener noreferrer">
                <img src="./img/youtube.png"></img>
                <p>youtube</p>
            </a>
        </footer>
    </body>
    </html>
    css
    body{
    color: white;
    background-color:black;
    font-family: Arial, Helvetica, sans-serif;
}
ul{
    display: flex;
    justify-content: space-between;
    list-style: none;
    align-items: center;
    padding: 16px;
}
a{
    color: white;
}
header img{
    width:150px;
    height:150px;
    border-radius:50%;
    border: 5px solid peru;  
}
.center{
    text-align: center;
}
h1{
    color:peru
}
footer img{
    width: 40px;
    height: 40px;
}
footer{
    display: flex;
    justify-content: center;
}
footer a {
    margin: 20px;

} 
footer p {
    margin-top: 2px;
}
