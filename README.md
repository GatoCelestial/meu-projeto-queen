# meu-projeto-queen
O projeto do mais mais da school
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Serenax - Portfólio Farmacêutico</title>
    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2980b9;
            --text-color: #34495e;
            --light-bg: #f8f9fa;
            --white: #ffffff;
            --dark-text: #2c3e50;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--light-bg);
            margin: 0;
            padding: 0;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--white);
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 3rem 0;
        }
        
        .hero-image {
            margin: 20px 0;
        }
        
        .hero-image img {
            max-width: 100%;
            border-radius: 8px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
        }
        
        .product-info {
            background-color: var(--white);
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.08);
            margin: 1rem 0;
            text-align: left;
        }
        
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin: 2rem 0;
        }
        
        .gallery img {
            width: 100%;
            max-width: 250px;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }
        
        .gallery img:hover {
            transform: scale(1.05);
        }
        
        .btn {
            display: inline-block;
            background: var(--primary-color);
            color: var(--white);
            padding: 10px 20px;
            border-radius: 50px;
            text-decoration: none;
            margin: 1rem 0;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            background: var(--secondary-color);
            transform: translateY(-2px);
        }
        
        footer {
            background: var(--dark-text);
            color: var(--white);
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }
        
        @media (min-width: 768px) {
            .hero {
                flex-direction: row;
                justify-content: space-between;
            }
            
            .hero-text {
                flex: 1;
                padding: 0 20px;
            }
            
            .hero-image {
                flex: 1;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Serenax</h1>
            <p>Inovação no tratamento da depressão</p>
        </div>
    </header>
    
    <main class="container">
        <section class="hero">
            <div class="hero-text">
                <h2>Revolucionando o tratamento antidepressivo</h2>
                <p>Serenax é o mais novo avanço na farmacologia, desenvolvido para oferecer alívio eficaz com menor incidência de efeitos colaterais.</p>
                <a href="#sobre" class="btn">Saiba mais</a>
            </div>
            <div class="hero-image">
                <img src="https://i.imgur.com/Jf5DPWF.jpg" alt="Agatha Nunes representando a marca Serenax">
            </div>
        </section>
        
        <section id="sobre" class="product-info">
            <h2>Sobre o Serenax</h2>
            <p>Um antidepressivo inovador que proporciona:</p>
            <ul>
                <li>Ação mais rápida (a partir de 7 dias)</li>
                <li>Menos efeitos colaterais</li>
                <li>Eficácia comprovada</li>
                <li>Perfil de segurança superior</li>
            </ul>
        </section>
        
        <section class="product-info">
            <h2>Indicações</h2>
            <p>Serenax está indicado para:</p>
            <ul>
                <li>Depressão maior</li>
                <li>Transtorno de ansiedade</li>
                <li>Estresse pós-traumático</li>
            </ul>
        </section>
        
        <section>
            <h2>Campanha com Agatha Nunes</h2>
            <p>Nossa embaixadora representa a mensagem de superação e bem-estar.</p>
            <div class="gallery">
                <img src="https://i.imgur.com/Jf5DPWF.jpg" alt="Agatha Nunes 1">
                <img src="https://i.imgur.com/Jf5DPWF.jpg" alt="Agatha Nunes 2">
                <img src="https://i.imgur.com/Jf5DPWF.jpg" alt="Agatha Nunes 3">
            </div>
        </section>
    </main>
    
    <footer>
        <div class="container">
            <p>Serenax® - Todos os direitos reservados</p>
            <p>Material fictício para fins educacionais</p>
        </div>
    </footer>
</body>
</html>
