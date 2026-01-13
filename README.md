<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Serwis Telefonów – Cennik</title>
    <<meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: 'Inter', Arial, sans-serif;
            background: #0f172a;
            color: #e5e7eb;
        }
        header {
            background: linear-gradient(135deg, #2563eb, #1e40af);
            padding: 70px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 42px;
            margin: 0;
        }
        header p {
            font-size: 18px;
            opacity: 0.9;
        }
        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
        }
        .card {
            background: #020617;
            border-radius: 14px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.4);
        }
        h2 {
            color: #60a5fa;
            margin-top: 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table th, table td {
            padding: 16px;
            border-bottom: 1px solid #1e293b;
        }
        table th {
            text-align: left;
            color: #93c5fd;
        }
        .price {
            color: #22c55e;
            font-weight: bold;
        }
        footer {
            text-align: center;
            padding: 30px;
            background: #020617;
            color: #64748b;
            margin-top: 60px;
        }
        @media (max-width: 600px) {
            header h1 { font-size: 32px; }
            table th, table td { padding: 12px; }
        }
    </style>
</head>
<body>

<header>
    <h1>Serwis Telefonów</h1>
    <p>Szybka i profesjonalna naprawa smartfonów</p>
</header>

<div class="container">
    <div class="card">
        <h2>Cennik usług</h2>
        <table>
            <tr>
                <th>Usługa</th>
                <th>Cena od</th>
                <th>Czas</th>
            </tr>
            <tr>
                <td>Wymiana wyświetlacza</td>
                <td class="price">200 zł</td>
                <td>1–2 h</td>
            </tr>
            <tr>
                <td>Wymiana baterii</td>
                <td class="price">120 zł</td>
                <td>30 min</td>
            </tr>
            <tr>
                <td>Gniazdo ładowania</td>
                <td class="price">150 zł</td>
                <td>1 h</td>
            </tr>
            <tr>
                <td>Naprawa po zalaniu</td>
                <td class="price">180 zł</td>
                <td>1–3 dni</td>
            </tr>
        </table>
    </div>
</div>

<footer>
    © 2026 Serwis Telefonów
</footer>

</body>
</html># didactic-journey
