<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Compra de Moedas de Jogos</title>
    <style>
        /* CSS embutido */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }

        main {
            padding: 2rem;
        }

        h1, h2 {
            color: #333;
        }

        .game-selection {
            text-align: center;
        }

        .games {
            display: flex;
            justify-content: space-around;
            margin-top: 2rem;
        }

        .game {
            background-color: white;
            border: 1px solid #ddd;
            padding: 1rem;
            border-radius: 8px;
            width: 30%;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .game img {
            max-width: 600%;
            height: auto;
            border-radius: 5px;
        }

        .comprar-btn {
            background-color: #4CAF50;
            color: white;
            padding: 0.5rem 1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 1rem;
        }

        .comprar-btn:hover {
            background-color: #45a049;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Compra de Moedas de Jogos</h1>
    </header>

    <main>
        <section class="game-selection">
            <h2>Selecione o Jogo</h2>
            <div class="games">
                <div class="game">
                    <img src="game1.jpg" alt="game1">
                    <h3>Fortnite</h3>
                    <label for="moedas1">Quantidade de Moedas:</label>
                    <select id="moedas1">
                        <option value="100">100 Moedas</option>
                        <option value="500">500 Moedas</option>
                        <option value="1000">1000 Moedas</option>
                    </select>
                    <button class="comprar-btn" onclick="comprarMoedas('Jogo 1', moedas1.value)">Comprar</button>
                </div>

                <div class="game">
                    <img src="game2.jpg" alt="game2">
                    <h3>Roblox</h3>
                    <label for="moedas2">Quantidade de Moedas:</label>
                    <select id="moedas2">
                        <option value="100">100 Moedas</option>
                        <option value="500">500 Moedas</option>
                        <option value="1000">1000 Moedas</option>
                    </select>
                    <button class="comprar-btn" onclick="comprarMoedas('Jogo 2', moedas2.value)">Comprar</button>
                </div>

                <div class="game">
                    <img src="game3.jpg" alt="game 3">
                    <h3>8 ball pol</h3>
                    <label for="moedas3">Quantidade de Moedas:</label>
                    <select id="moedas3">
                        <option value="100">100 Moedas</option>
                        <option value="500">500 Moedas</option>
                        <option value="1000">1000 Moedas</option>
                    </select>
                    <button class="comprar-btn" onclick="comprarMoedas('Jogo 3', moedas3.value)">Comprar</button>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Compra de Moedas de Jogos</p>
    </footer>

    <script>
        // JavaScript embutido
        function comprarMoedas(jogo, quantidade) {
            alert(`Você comprou ${quantidade} moedas para ${jogo}!`);
        }
    </script>
</body>
</html>
