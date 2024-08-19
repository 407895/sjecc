<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>01001000 01100001 01101110 01101001 01101011 01100001 00100000 01110000 01101111 01110010 00100000 01100110 01100001 01110110 01101111 01110010 00100000 01110110 01110101 01100101 01101100 01110110 01100101</title>
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: 'Courier New', Courier, monospace;
            text-align: center;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        img {
            width: 200px;
            margin-bottom: 50px;
        }
    </style>
</head>
<body>
    <div class="texto-cuneiforme">
        <h2>𒄩𒂵𒉋𒆠𒃲 𒁹</h2>
        <p>𒊕𒂝 𒇫𒋻𒍣𒅎𒋳,</p>
        <p>𒉏𒁉𒊨𒊬 𒄭𒇷.</p>
    </div>

    <form>
        <input type="text" id="respuesta" name="respuesta"><br><br>
        <button type="submit">Send</button>
    </form>

    <script>
        const input = document.querySelector('#respuesta');
        const form = document.querySelector('form');

        form.addEventListener('submit', (e) => {
            e.preventDefault();
            if (input.value === '73') {
                // Incluir aquí el código para mostrar la imagen cuando se envía la respuesta correcta
                const img = document.createElement('img');
                img.src = "https://stickerly.pstatic.net/sticker_pack/1OzmnaU2rNLhyhkZpvaJQg/5LAD7V/14/a5876573-48a0-48a6-ac00-136f3effdbdf.png";
                document.body.appendChild(img);
            }
        });
    </script>
</body>
</html>
