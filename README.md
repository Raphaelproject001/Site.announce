<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Pessoal de [Seu Nome]</title>
    <style>
        /* Estilos Gerais */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
            margin-bottom: 10px;
        }
        p {
            margin-bottom: 15px;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        /* Seção de Cabeçalho */
        header {
            background-color: #007bff;
            color: #fff;
            padding: 10px 0;
            text-align: center;
            border-top-left-radius: 8px;
            border-top-right-radius: 8px;
        }
        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }
        /* Seção de Produtos */
        .produtos {
            margin-top: 20px;
        }
        .produto {
            border: 1px solid #ccc;
            border-radius: 4px;
            padding: 10px;
            margin-bottom: 10px;
        }
        .produto img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
        }
        .produto h3 {
            margin-top: 0;
        }
        .produto p {
            margin-bottom: 0;
        }
        /* Rodapé */
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #007bff;
            color: #fff;
            border-bottom-left-radius: 8px;
            border-bottom-right-radius: 8px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Seu Nome</h1>
            <p>Divulgação de Produtos</p>
        </header>

        <section class="produtos">
            <div class="produto">
                <img src="caminho/para/imagem-produto1.jpg" alt="Produto 1">
                <h3>Nome do Produto 1</h3>
                <p>Descrição breve do Produto 1.</p>
            </div>

            <div class="produto">
                <img src="caminho/para/imagem-produto2.jpg" alt="Produto 2">
                <h3>Nome do Produto 2</h3>
                <p>Descrição breve do Produto 2.</p>
            </div>

            <!-- Adicione mais produtos conforme necessário -->
        </section>

        <footer>
            <p>&copy; 2024 Seu Nome. Todos os direitos reservados.</p>
        </footer>
    </div>
</body>
</html>
