<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venta de Trades Exclusivos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
            padding: 0;
            margin: 0;
        }
        header {
            background-image: url('https://cryptologos.cc/logos/bitcoin-btc-logo.png');
            background-size: cover;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        header h1 {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 20px;
            font-size: 3em;
        }
        .container {
            padding: 20px;
        }
        .description {
            font-size: 1.2em;
            margin-bottom: 20px;
        }
        .button {
            padding: 15px 25px;
            background-color: #28a745;
            color: white;
            font-size: 1.2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #218838;
        }
        .hidden-info {
            display: none;
            margin-top: 20px;
            font-size: 1.5em;
            background-color: #f8d7da;
            color: #721c24;
            padding: 20px;
            border-radius: 5px;
        }
    </style>
    <script>
        function showTradeInfo() {
            document.getElementById('trade-info').style.display = 'block';
        }
    </script>
</head>
<body>
    <header>
        <h1>Trades Exclusivos de Criptomonedas</h1>
    </header>

    <div class="container">
        <p class="description">
            Obtén acceso a nuestras estrategias de trading más rentables. Con cada pago, desbloqueas niveles exclusivos de take profit, stop loss, y apalancamiento para maximizar tus ganancias en el mercado de criptomonedas.
        </p>

        <button class="button" onclick="window.location.href='https://buy.stripe.com/bIY8z30Ga9hP6vS6oo'; showTradeInfo();">
            Pagar y Desbloquear Información
        </button>

        <div id="trade-info" class="hidden-info">
            <h2>Información Desbloqueada</h2>
            <p><strong>Take Profit:</strong> 5% sobre el precio de entrada</p>
            <p><strong>Stop Loss:</strong> 2% bajo el precio de entrada</p>
            <p><strong>Nivel de Apalancamiento:</strong> 10x</p>
        </div>
    </div>
</body>
</html>
