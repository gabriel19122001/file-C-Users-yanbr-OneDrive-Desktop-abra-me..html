<css /* Importação das fontes */
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #ffdde1, #fcb69f);
    color: #333;
}

header {
    text-align: center;
    margin-top: 20px;
}

header h1 {
    font-family: 'Pacifico', cursive;
    font-size: 3em;
    color: #ff6b81;
    margin-bottom: 10px;
}

header h2 {
    font-size: 1.5em;
    font-weight: 600;
    color: #333;
}

.container {
    background-color: #fff;
    border-radius: 15px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    margin: 30px auto;
    padding: 20px;
    max-width: 900px;
}

.message {
    text-align: center;
    line-height: 1.8;
    font-size: 1.1em;
}

.message span {
    color: #ff6b81;
    font-weight: bold;
}

.message .highlight {
    font-size: 1.2em;
    color: #f76c6c;
    font-weight: bold;
    margin-top: 15px;
}

.signature {
    margin-top: 20px;
    font-style: italic;
    font-size: 1.1em;
    color: #555;
}

/* Fotos */
.photos {
    text-align: center;
    margin-top: 30px;
}

.photos h3 {
    font-family: 'Pacifico', cursive;
    font-size: 2em;
    color: #ff6b81;
}

.gallery {
    display: flex;
    justify-content: center;
    gap: 15px;
    flex-wrap: wrap;
    margin-top: 15px;
}

.gallery img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    border: 3px solid #ff6b81;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s;
}

.gallery img:hover {
    transform: scale(1.1);
}
>

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Aniversário, Giovanna 💖</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
    <div class="container">
        <!-- Cabeçalho -->
        <header>
            <h1>Feliz Aniversário, Giovanna 🎉</h1>
            <h2>Hoje celebramos você e nosso 1º ano juntos 💕</h2>
        </header>

        <!-- Texto Fofo -->
        <section class="message">
            <p>
                Há exatamente <span>1 ano</span>, você entrou na minha vida e tudo ficou mais bonito.  
                Hoje, no seu dia especial, quero te lembrar o quanto você é incrível,  
                o quanto você me faz feliz e o quanto eu te amo. ❤️  
            </p>
            <p>
                Você é minha luz, minha paz e minha razão para sorrir todos os dias.  
                Obrigado por ser essa pessoa maravilhosa e por me permitir estar ao seu lado.  
            </p>
            <p class="highlight">  
                Que este seja o primeiro de muitos aniversários que passaremos juntos. 🎂  
                Eu te amo mais do que palavras podem dizer! 💖
            </p>
            <p class="signature">  
                Com todo o meu amor,  
                <br> **Gabriel**  
            </p>
        </section>

        <!-- Fotos -->
        <section class="photos">
            <h3>Nossas Memórias 📸</h3>
            <div class="gallery">
                <img src="images/foto1.jpg" alt="Foto 1">
                <img src="images/foto2.jpg" alt="Foto 2">
                <img src="images/foto3.jpg" alt="Foto 3">
            </div>
        </section>
    </div>
</body>
</html>
