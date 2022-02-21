<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
    <title>Truco Bot - O melhor para sua diversão!</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Righteous&family=Sarala:wght@400;700&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Righteous&family=Sarala:wght@400;700&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
}

body{
    font-size: 100%;
    background: linear-gradient(to right, #650005, #8C000B 30%);
}

.cabecalho{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    padding: 24px;
}

.cabecalho-imagem{
    height: 72px;
}

.cabecalho-escrito{
    display: flex;
    gap: 32px;
}

.cabecalho-escrito-item{
    font-family: 'sarala', sans-serif;
    color: white;
    font-weight: 400;
    font-size: 18px;
}

.conteudo{
    border-top: 0.4px solid white;
    margin-bottom: 48px;
}

.conteudo-principal{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    padding: 42px;
}

.conteudo-principal-escrito{
    display: flex;
    flex-direction: column;
    gap: 32px;
}

.conteudo-principal-escrito-titulo{
    font-family: 'Righteous', cursive;
    font-weight: 400;
    font-size: 64px;
    color: white;
}

.conteudo-principal-escrito-subtitulo{
    font-family: 'sarala', sans-serif;
    font-weight: 400;
    font-size: 24px;
    color: white;
}

.conteudo-principal-escrito-botao{
    background-color: white;
    width: 180px;
    height: 60px;
    border: none;
    border-radius: 20px;
    box-shadow: 4px 5px 4px rgba(0, 0, 0, 0.25);
    font-family: 'sarala', sans-serif;
    font-weight: 400;
    font-size: 24px;
    color: black;
}

.conteudo-principal-escrito-botao:hover{
    background-color: rgba(236, 214, 196, 0.53);
}

.conteudo-principal-imagem{
    height: 300px;
}

.conteudo-secundario{
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 24px;
    margin-top: 48px;
}

.conteudo-secundario-titulo{
    border-top: 0.4px solid white;
    padding-top: 48px;
    font-family: 'Righteous', cursive;
    font-weight: 400;
    font-size: 24px;
    color: white;
    margin-bottom: 16px;
}

.conteudo-secundario-paragrafo{
    font-family: 'sarala', sans-serif;
    font-weight: 300;
    font-size: 18px;
    color: white;
}

.rodape{
    padding: 32px;
    border-top: 0.4px solid white;
}

.rodape-imagem{
    height: 64px;
    display: block;
    margin: 0 auto;
}
    </style>
</head>
<body>
    <header class="cabecalho">
        <img class="cabecalho-imagem" width="64" height="64" src="imagens/logo-branco.png" alt="logo bot-truco">
        <nav class="cabecalho-escrito">
            <a class="cabecalho-escrito-item">Comunidade</a>
            <a class="cabecalho-escrito-item">Tutorial</a>
            <a class="cabecalho-escrito-item">Open Source</a>
            <a class="cabecalho-escrito-item">Comandos</a>
        </nav>
    </header>
    <main class="conteudo">
        <section class="conteudo-principal">
            <div class="conteudo-principal-escrito">
                <h1 class="conteudo-principal-escrito-titulo">Truco Bot</h1>
                <h2 class="conteudo-principal-escrito-subtitulo">Deixe a sua comunidade mais divertida!</h2>
                <button class="conteudo-principal-escrito-botao">Me adicione!</button>
            </div>
            <img class="conteudo-principal-imagem" src="imagens/baralho-certo.png" alt="imagem truco bot">
        </section>
        <section class="conteudo-secundario">
            <h3 class="conteudo-secundario-titulo">O que ele pode te oferecer?</h3>
            <p class="conteudo-secundario-paragrafo">1. Cria uma <strong>de divisão de cartas igualmente balanceado</strong>  para não ocorrer problemas</p>
            <p class="conteudo-secundario-paragrafo">2. Um bot voltado ao seu lazer e de seus amigos, <strong>perfeito para você jogar em grupo</strong>  sem ter que sair da plataforma do discord</p>
            <p class="conteudo-secundario-paragrafo">3. Modo de jogo de <strong>2, 4 ou 6 pessoas</strong>  para jogar com amigos</p>
        </section>
    </main>
    <footer class="rodape">
        <img class="rodape-imagem" src="imagens/rodape-branco.png" alt="rodape imagem">
    </footer>
</body>
</html>
