<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Cabeçalho da Página -->
    <header>
        <h1>Meu Portfólio</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#projetos">Projetos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>




<!-- Seção Projetos -->
<section id="projetos">
    <h2>Projetos</h2>
    <div class="projeto">
        <h3><a href="https://exemplo.com/projeto1">Projeto 1</a></h3>
        <p>Descrição do projeto 1.</p>
    </div>
    <div class="projeto">
        <h3><a href="https://exemplo.com/projeto2">Projeto 2</a></h3>
        <p>Descrição do projeto 2.</p>
    </div>
    <!-- Adicione mais projetos conforme necessário -->
</section>

    <!-- Seção Contato -->
<section id="contato">
    <h2>Contato</h2>
    <p>Se você quiser entrar em contato comigo, envie um e-mail para: <a href="mailto:cristinakailaine699@gmail.com">cristinakailaine699@gmail.com</a></p>
</section>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 Kailaine Cristina. Todos os direitos reservados.</p>
    </footer>
</body>

<link rel="stylesheet" href="style.css">



/* Estilo geral do corpo da página */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
}

/* Estilo para o cabeçalho */
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

/* Estilo para o menu de navegação */
nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    color: #ff6347; /* Tom de laranja para hover */
}

/* Estilo para as seções */
section {
    padding: 20px;
    margin: 20px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* Estilo para títulos das seções */
h2 {
    color: #333;
}

/* Estilo para os links dos projetos */
.projeto h3 a {
    color: #333;
    text-decoration: none;
}

.projeto h3 a:hover {
    color: #ff6347;
}

/* Estilo para o rodapé */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}


