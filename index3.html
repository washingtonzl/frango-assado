<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frango Assado CL</title>
    <style>
        /* Estilos CSS para a aparência do site */
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            background-color: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
            max-width: 400px;
            width: 100%;
        }

        h1 {
            color: #333;
            margin-bottom: 20px;
        }

        .product-image {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .price {
            font-size: 28px;
            color: #28a745;
            margin-bottom: 20px;
            font-weight: bold;
        }

        .quantity-selector {
            margin-bottom: 20px;
        }

        .quantity-selector label {
            font-size: 18px;
            margin-right: 10px;
        }

        .quantity-selector input {
            width: 60px;
            padding: 8px;
            font-size: 16px;
            text-align: center;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .delivery-options {
            text-align: left;
            margin-bottom: 20px;
        }

        .delivery-options label {
            margin-right: 15px;
            font-size: 18px;
        }
        
        #endereco-input {
            width: calc(100% - 20px);
            padding: 10px;
            margin-top: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .buy-button {
            background-color: #25D366;
            color: white;
            padding: 15px 25px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 8px;
            font-weight: bold;
            transition: background-color 0.3s;
            cursor: pointer;
            border: none;
            display: inline-block;
        }

        .buy-button:hover {
            background-color: #128C7E;
        }

        footer {
            margin-top: 20px;
            font-size: 14px;
            color: #888;
        }

    </style>
</head>
<body>

    <div class="container">
        <h1>Frango Assado CL</h1>
        <img src="https://i.imgur.com/DKm2G7f.png" alt="Frango Assado" class="product-image">
        <p class="price">R$ 55,00</p>

        <div class="quantity-selector">
            <label for="quantidade">Quantidade:</label>
            <input type="number" id="quantidade" value="1" min="1">
        </div>

        <div class="delivery-options">
            <input type="radio" id="entrega" name="tipo_entrega" value="Entrega" checked onclick="toggleEndereco(true)">
            <label for="entrega">Entrega</label>
            
            <input type="radio" id="retirada" name="tipo_entrega" value="Retirada" onclick="toggleEndereco(false)">
            <label for="retirada">Retirada</label>

            <div id="endereco-div">
                <input type="text" id="endereco-input" placeholder="Digite seu endereço completo">
            </div>
        </div>


        <button class="buy-button" onclick="enviarPedido()">Comprar Agora</button>

        <footer>
            <p>Clique em "Comprar Agora" para fazer seu pedido pelo WhatsApp.</p>
        </footer>
    </div>

    <script>
        function toggleEndereco(show) {
            const enderecoDiv = document.getElementById('endereco-div');
            enderecoDiv.style.display = show ? 'block' : 'none';
        }

        // Função JavaScript para enviar o pedido
        function enviarPedido() {
            const numeroWhatsApp = "63992028047";
            const quantidade = document.getElementById("quantidade").value;
            const valorTotal = 55 * quantidade;
            const tipoEntrega = document.querySelector('input[name="tipo_entrega"]:checked').value;
            let detalhesEntrega = "";

            if (tipoEntrega === 'Entrega') {
                const endereco = document.getElementById('endereco-input').value;
                if(endereco.trim() === "") {
                    alert("Por favor, preencha o endereço para entrega.");
                    return;
                }
                detalhesEntrega = `\n*Endereço para Entrega:* ${endereco}`;
            } else {
                detalhesEntrega = `\n*Forma de Entrega:* Retirada no local`;
            }

            // Mensagem que será enviada
            const mensagem = `Olá! Gostaria de fazer um novo pedido:\n\n*Produto:* Frango Assado\n*Quantidade:* ${quantidade}\n*Valor Total:* R$ ${valorTotal.toFixed(2)}${detalhesEntrega}`;

            // Cria o link para o WhatsApp
            const linkWhatsApp = `https://wa.me/55${numeroWhatsApp}?text=${encodeURIComponent(mensagem)}`;

            // Redireciona para o WhatsApp
            window.open(linkWhatsApp, '_blank');
        }
    </script>

</body>
</html>
