# codigo_vscode_neabi
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NEABI</title>

    <style>
        /* Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* MENU */
        nav {
            background-color: #333;
            padding: 15px;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
        }

        nav ul {
            display: flex;
            list-style: none;
            justify-content: center;
            gap: 30px;
        }

        nav a {
            text-decoration: none;
            color: white;
            padding: 10px 20px;
            border-radius: 4px;
            transition: 0.3s;
        }

        nav a:hover {
            background-color: #555;
        }

       
        .container {
            padding: 100px 20px 40px 20px;
            text-align: center;
        }

       
        .texto-box {
            background: #f1f1f1;
            padding: 20px;
            max-width: 800px;
            margin: 20px auto;
            border-radius: 8px;
            text-align: left;
            font-size: 1.2rem;
        }

        
        .imagem-box {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .imagem-box img {
            width: 250px;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
            border: 2px solid #ddd;
        }

        
        footer {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
            margin-top: 40px;
        }

        footer a {
            color: #fff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Texto</a></li>
            <li><a href="#">Imagens</a></li>
            <li><a href="#">Contato</a></li>
        </ul>
    </nav>

    
    <div class="container">

        <h1>NEABI: Nucleo de estudos Afro-Brasileiros e Indigenas</h1>
        <p>Como enterder como esta cultura é tão forte?</p>

       
        <div class="texto-box">
            <h2>Qual a importancia dos indigenas para os brasileiros?</h2>
            <p>
                Os povos indígenas são fundamentais para o Brasil, pois são os primeiros habitantes da terra, com uma história que remonta a milhares de anos. 
                Eles preservam uma rica diversidade cultural e possuem vasto conhecimento sobre a natureza, contribuindo diretamente para a conservação ambiental. 
                As terras indígenas são essenciais para a proteção de florestas, rios e ecossistemas, ajudando a manter o equilíbrio ecológico do país. 
                Além disso, suas tradições, línguas e saberes ancestrais enriquecem a identidade nacional brasileira, tornando-os parte vital da nossa história e cultura.

            </p>
            <br><br>
            <p>
               Atualmente, o estado com o maior número de indígenas no Brasil é o Amazonas. A região Norte do país concentra uma grande diversidade de etnias e tribos indígenas, muitas delas vivendo em terras de difícil acesso, como na Amazônia. 
               O Amazonas abriga uma vasta quantidade de povos, como os Maraú, Tikuna, Baniwa e Kokama, entre outros. A maioria dessas populações vive em áreas de proteção, em reservas indígenas, onde podem preservar suas culturas, línguas e tradições.
               A região Norte, especialmente o Amazonas, é fundamental para a proteção das florestas tropicais e da biodiversidade global. Além disso, é nas terras indígenas da Amazônia que se encontra uma grande parte da biodiversidade brasileira, 
               com o conhecimento tradicional dos povos indígenas sendo crucial para a conservação do meio ambiente.

            </p>
        </div>

       
        <div class="imagem-box">
            <img src="criança.jfif" alt="Imagem 1">
            <img src="mulher.webp" alt="Imagem 2">
            <img src="homens.webp" alt="Imagem 3">
        </div>

    </div>

    
    <footer>
        <p>&copy; 2025 NEABI. Todos os direitos reservados.</p>
        <a href="#">Política de Privacidade</a> | <a href="#">Termos de Uso</a>
    </footer>

</body>
</html> 



[siteneabi.html](https://github.com/user-attachments/files/23629253/siteneabi.html)
