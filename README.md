# Bananas
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bananas com Rosto</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }

        .banana {
            width: 100px;
            height: 200px;
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            border-radius: 50px;
            background-size: cover;
            background-position: center;
        }

        .banana .rosto {
            position: absolute;
            bottom: 30px;
            width: 60px;
            height: 60px;
            background-color: white;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 20px;
            font-weight: bold;
        }

        .comum { border: 2px solid green; }
        .rara { border: 2px solid blue; }
        .epica { border: 2px solid purple; }
        .lendaria { border: 2px solid orange; }
        .mitica { border: 2px solid red; }

        .acessorio {
            position: absolute;
            top: 20px;
            font-size: 14px;
        }

        /* Estilos para acessórios e diferenças de skins */
        .acessorio.óculos { font-size: 18px; color: black; }
        .acessorio.coroa { font-size: 18px; color: gold; }
        .acessorio.fone { font-size: 18px; color: white; }
    </style>
</head>
<body>

    <!-- Variedades de Bananas com Imagens -->
    <div class="banana comum" style="background-image: url('images/banana_comum_1.png');">
        <div class="rosto">🙂</div>
        <div class="acessorio óculos">👓</div>
    </div>
    <div class="banana comum" style="background-image: url('images/banana_comum_2.png');">
        <div class="rosto">😆</div>
        <div class="acessorio fone">🎧</div>
    </div>
    <div class="banana comum" style="background-image: url('images/banana_comum_3.png');">
        <div class="rosto">😁</div>
        <div class="acessorio coroa">👑</div>
    </div>

    <div class="banana rara" style="background-image: url('images/banana_rara_1.png');">
        <div class="rosto">😜</div>
        <div class="acessorio óculos">👓</div>
    </div>
    <div class="banana rara" style="background-image: url('images/banana_rara_2.png');">
        <div class="rosto">😎</div>
        <div class="acessorio coroa">👑</div>
    </div>
    <div class="banana rara" style="background-image: url('images/banana_rara_3.png');">
        <div class="rosto">😝</div>
        <div class="acessorio fone">🎧</div>
    </div>

    <div class="banana epica" style="background-image: url('images/banana_epica_1.png');">
        <div class="rosto">🙃</div>
        <div class="acessorio coroa">👑</div>
    </div>
    <div class="banana epica" style="background-image: url('images/banana_epica_2.png');">
        <div class="rosto">😈</div>
        <div class="acessorio óculos">👓</div>
    </div>

    <div class="banana lendaria" style="background-image: url('images/banana_lendaria_1.png');">
        <div class="rosto">😇</div>
        <div class="acessorio coroa">👑</div>
    </div>

    <div class="banana mitica" style="background-image: url('images/banana_mitica_1.png');">
        <div class="rosto">🤩</div>
        <div class="acessorio óculos">👓</div>
    </div>

</body>
</html>

