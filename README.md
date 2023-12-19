- 👋 Hi, I’m @Wemerson32
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Wemerson32/Wemerson32 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Divulgue Sua Loja</title>
</head>
<body>
    <header>
        <h1>Divulgue Sua Loja</h1>
    </header>
    <main>
        <section id="form-section">
            <h2>Divulgue Sua Loja</h2>
            <form id="store-form">
                <label for="store-name">Nome da Loja:</label>
                <input type="text" id="store-name" required>

                <label for="store-description">Descrição da Loja:</label>
                <textarea id="store-description" required></textarea>

                <label for="store-image">Imagem da Loja:</label>
                <input type="file" id="store-image" accept="image/*" required>

                <label for="store-video">Vídeo da Loja (URL):</label>
                <input type="url" id="store-video">

                <label for="product-values">Valores dos Produtos:</label>
                <textarea id="product-values" placeholder="Insira os valores dos produtos" required></textarea>

                <button type="button" onclick="processPayment()">Divulgar por R$25</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Divulgue Sua Loja</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
