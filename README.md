# iPhone-Apple
Projeto Apple - Tudo sobre o iPhone 14 
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iPhone - Apple (Brasil)</title>
    <link rel="stylesheet" href="style.css">
    <script src="./scripts.js"></script>
</head>



<body>

    <div class="caixa-roxa">
        <img class="logo" src="logo.png">

        <ul>
            <li>Mac</li>
            <li>iPhone</li>
            <li>iPad</li>
            <li>Watch</li>
            <li>AirPods</li>
            <li>Acessórios</li>
            <li>Suporte</li>
        </ul>

    </div>

    <div class="caixa-azul">
        <div>
            <h1 class="titulo-iphone">iPhone 14</h1>

            <h2 class="titulo-secundario">Tão poderoso. Tão ao seu alcance.</h2>

            <p class="paragrafo">
                Em dois tamanhos perfeitos. Agora com um toque de amarelo.
            </p>

            <h3 class="preco">A partir de R$ 633,25/mês ou R$ 7.599*</h3>
            <button class="botao">Comprar</button>

            <p class="escolha-cor">Escolha sua cor:</p>
            <div>
                <button onclick="trocaCor('#81A5C4'); trocaImagem('iphone-azul.png')" class="azul troca-cor"></button>
                <button onclick="trocaCor('#F7DA47'); trocaImagem('iphone-amarelo.png')" class="amarelo troca-cor"></button>
                <button onclick="trocaCor('#C1C1C1'); trocaImagem('iphone-branco.png')" class="branco troca-cor"></button>
                <button onclick="trocaCor('#272D33'); trocaImagem('iphone-preto.png')" class="preto troca-cor"></button>
                <button onclick="trocaCor('#B50012'); trocaImagem('iphone-vemelho.png')" class="vermelho troca-cor"></button>
                <button onclick="trocaCor('#EDE7F1'); trocaImagem('iphone-roxo.png')" class="roxo troca-cor"></button>
            </div>
        </div>

        <div class="circulo"></div>
        <img class="iphone" src="iphone-azul.png">
    </div>

</body>

</html>
