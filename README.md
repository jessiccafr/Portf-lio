<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 1.5rem 2rem;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    font-size: 1rem;
}

nav ul li a:hover {
    text-decoration: underline;
}

.bio-section {
    display: flex;
    align-items: center;
    padding: 3rem;
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin: 2rem 0;
    border-radius: 10px;
}

.bio-section img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    object-fit: cover;
}

.bio {
    max-width: 1000px;
    text-align: justify;
}

.bio h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #0077b5;
}

.bio p {
    font-size: 1.1rem;
    line-height: 1.8;
}

.linkedin {
    display: inline-block;
    margin-top: 1.5rem;
    background-color: #0077b5;
    color: white;
    padding: 0.75rem 1.5rem;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s;
}

.linkedin:hover {
    background-color: #005f8a;
}

#projetos {
    padding: 2rem;
    background-color: #e4e4e4;
}

#projetos h2 {
    text-align: center;
    margin-bottom: 2rem;
    font-size: 2rem;
}

.card-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.card {
    background-color: white;
    padding: 1.5rem;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

.card h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
}

.card p {
    margin-bottom: 1rem;
}

.card a {
    display: inline-block;
    margin-right: 1rem;
    color: #0077b5;
    text-decoration: none;
}

.card a:hover {
    text-decoration: underline;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1.5rem 0;
    margin-top: 2rem;
    font-size: 0.9rem;
    box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.1);
}


    </style>
</head>
<body>
    <header>
        <h1>Meu Portfólio</h1>
        <nav>
            <ul>
                <li><a href="#sobre-mim">Sobre Mim</a></li>
                <li><a href="#projetos">Projetos</a></li>
            </ul>
        </nav>
    </header>

    <section id="sobre-mim" class="bio-section">
        <img src="C:\Users\User\Downloads\WhatsApp Image 2024-08-03 at 15.55.10.jpeg" alt="Foto Pessoal">
        <div class="bio">
            <h2>Quem sou eu?</h2>
            <p>Oi! Sou a Jéssica, uma analista de dados apaixonada por tecnologia e com olhar afiado para transformar dados em soluções práticas e impactantes. Com formação técnica em informática e em constante evolução como estudante de Tecnologia em Ciência de Dados, possuo conhecimento em SQL, Power BI e DAX, criando dashboards poderosos que orientam decisões estratégicas. Além disso, meu conhecimento em ERPs me permite otimizar processos empresariais, e minhas habilidades básicas em desenvolvimento web (CSS, PHP, HTML e JavaScript) tornam minhas soluções ainda mais versáteis e visuais. Com experiência no setor financeiro, aprimorei a capacidade de analisar KPIs e apresentar insights com clareza e precisão.</p>
            <a href="https://www.linkedin.com/in/jessica-ferreira-125626198/" class="linkedin">Conecte-se comigo no LinkedIn!</a>
        </div>
    </section>

    <section id="projetos">
        <h2>Projetos</h2>
        <div class="card-container">
            <div class="card">
                <h3>Overview Gestão Executiva</h3>
                <p>O Overview Gestão Executiva foi criado com o objetivo de auxiliar na análise de informações sobre o desempenho e crescimento de uma empresa Auto Elétrica. O projeto conta com uma base de dados, website para inserção das informações e um relatório em B.I</p>
                <a href="https://app.powerbi.com/view?r=eyJrIjoiMDQwNjhjYmUtODU2My00ZGRjLWE1ZjMtNGU2MWZmMzkzN2M2IiwidCI6IjkwMTIyZmQwLThkZjAtNDZkYS1iMzRiLTQ2NDNmZTlkYjY4ZSJ9" target="_blank">PowerBI</a>
            </div>

            <div class="card">
                <h3>Painel Financeiro</h3>
                <p>O Painel Financeiro foi desenvolvido para realizar a visualização do que seria um fluxo financeiro, confrontando os valores recebidos com os pagos. A base é via planilha Excel utilizando uma base fictícia.</p>
                <a href="https://app.powerbi.com/view?r=eyJrIjoiNzBjMzQzYmUtYTBlNC00ZDNjLWJlYTMtMDU0ODhiZjAwN2ViIiwidCI6IjkwMTIyZmQwLThkZjAtNDZkYS1iMzRiLTQ2NDNmZTlkYjY4ZSJ9" target="_blank">PowerBI</a>
            </div>


        </div>
    </section>

    <footer>
        <p>© 2024 Jéssica. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
