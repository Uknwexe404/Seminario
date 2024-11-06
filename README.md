# <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Os Retirantes - História e Impacto</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #2a3d66;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            margin: 20px;
            padding: 15px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #2a3d66;
        }

        #historico, #interatividade {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .btn {
            margin: 10px;
            padding: 10px 20px;
            background-color: #2a3d66;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        .btn:hover {
            background-color: #1a2b42;
        }

        .imagem {
            max-width: 100%;
            border-radius: 8px;
            margin-top: 15px;
        }

        footer {
            background-color: #2a3d66;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Os Retirantes - A História de uma Jornada de Esperança</h1>
</header>

<section id="historico">
    <h2>O Que Foram os Retirantes?</h2>
    <p>Os retirantes eram pessoas que, durante o período das secas no Nordeste brasileiro, eram forçadas a abandonar suas terras em busca de melhores condições de vida. 
    A migração em massa para o Sudeste e Centro-Oeste gerou um grande êxodo rural, uma das maiores mobilizações populacionais da história do Brasil.</p>
    <p>Este fenômeno social e histórico ficou marcado por cenas de sofrimento e pela busca incansável de uma nova vida, longe das terras ressecadas e sem recursos. Muitas dessas pessoas foram representadas na famosa obra do pintor Cândido Portinari, "Os Retirantes", que expressa toda a dor e a esperança dessas famílias.</p>
    <button class="btn" onclick="exibirImagem()">Ver Imagem dos Retirantes</button>
    <img id="imagem" class="imagem" style="display:none;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Os_Retirantes.jpg/1200px-Os_Retirantes.jpg" alt="Os Retirantes de Portinari">
</section>

<section id="interatividade">
    <h2>Explore mais sobre a história!</h2>
    <p>Para entender mais sobre o contexto histórico e cultural dos retirantes, podemos explorar vídeos, áudios e curiosidades. Clique abaixo para começar sua jornada interativa:</p>
    <button class="btn" onclick="mostrarCuriosidades()">Mostrar Curiosidades</button>
    <div id="curiosidades" style="display:none;">
        <ul>
            <li><strong>Curiosidade 1:</strong> O fenômeno dos retirantes foi agravado por anos consecutivos de seca e pela falta de políticas públicas efetivas para o combate à seca.</li>
            <li><strong>Curiosidade 2:</strong> A migração dos nordestinos para outras regiões do Brasil foi um dos maiores deslocamentos populacionais do século XX no país.</li>
            <li><strong>Curiosidade 3:</strong> "Os Retirantes" foi pintado por Cândido Portinari em 1944 e retrata a dor e o sofrimento de uma família nordestina enfrentando a seca.</li>
        </ul>
    </div>
</section>

<footer>
    <p>Projeto Educacional - História dos Retirantes</p>
</footer>

<script>
    function exibirImagem() {
        const imagem = document.getElementById('imagem');
        imagem.style.display = imagem.style.display === 'none' ? 'block' : 'none';
    }

    function mostrarCuriosidades() {
        const curiosidades = document.getElementById('curiosidades');
        curiosidades.style.display = curiosidades.style.display === 'none' ? 'block' : 'none';
    }
</script>

</body>
</html>
