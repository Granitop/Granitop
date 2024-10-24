<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Granitop - Transformação de Pedra</title>
    <style>
        /* Estilos Gerais */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #4b2e2f; /* Bordô */
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #cfa07d;
        }
        /* Seção principal */
        .banner {
            background-color: #555; /* Cinza escuro */
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .banner h2 {
            font-size: 3em;
        }
        .section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .section h2 {
            font-size: 2em;
            color: #4b2e2f;
        }
        .section p {
            font-size: 1.1em;
            line-height: 1.6em;
        }
        /* Projetos */
        .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .project {
            flex: 1;
            margin: 15px;
            max-width: 30%;
            background-color: white;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .project img {
            width: 100%;
            height: auto;
        }
        .project h3 {
            padding: 15px;
            background-color: #4b2e2f;
            color: white;
            text-align: center;
        }
        /* Formulário */
        .contact-form {
            background-color: #eee;
            padding: 20px;
            border-radius: 8px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact-form button {
            background-color: #4b2e2f;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Granitop</h1>
        <p>Transformação de Pedra de Qualidade Superior</p>
    </header>

    <nav>
        <a href="#sobre">Sobre Nós</a>
        <a href="#servicos">Serviços</a>
        <a href="#projetos">Projetos</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="banner">
        <h2>Transformando Pedras Naturais em Obras de Arte</h2>
        <p>Durabilidade e beleza para qualquer projeto</p>
    </div>

    <section id="sobre" class="section">
        <h2>Sobre Nós</h2>
        <p>A Granitop é uma empresa especializada em transformação de pedras naturais. Com uma equipe de especialistas, fornecemos materiais e serviços de alta qualidade para projetos de construção e decoração.</p>
    </section>

    <section id="servicos" class="section">
        <h2>Serviços</h2>
        <p>Oferecemos uma vasta gama de serviços, desde o corte
