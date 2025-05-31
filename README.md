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
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
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
            font-weight: 700;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 3rem 0;
            flex-wrap: wrap;
        }
        
        .hero-text {
            flex: 1;
            min-width: 300px;
            padding: 20px;
        }
        
        .hero-image {
            flex: 1;
            min-width: 300px;
            text-align: center;
        }
        
        .hero-image img {
            max-width: 100%;
            border-radius: 8px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
        }
        
        .section {
            padding: 4rem 0;
        }
        
        .section-title {
            text-align: center;
            color: var(--dark-text);
            margin-bottom: 2rem;
            font-size: 2rem;
            position: relative;
        }
        
        .section-title:after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background: var(--primary-color);
            margin: 15px auto;
            border-radius: 2px;
        }
        
        .product-info {
            background-color: var(--white);
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
            margin-bottom: 2rem;
        }
        
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 2rem;
        }
        
        .gallery img {
            width: 100%;
            border-radius: 8px;
            transition: transform 0.3s ease;
            cursor: pointer;
        }
        
        .gallery img:hover {
            transform: scale(1.03);
        }
        
        .btn {
            display: inline-block;
            background: var(--primary-color);
            color: var(--white);
            padding: 12px 24px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            margin-top: 1rem;
        }
        
        .btn:hover {
            background: var(--secondary-color);
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }
        
        footer {
            background: var(--dark-text);
            color: var(--white);
            text-align: center;
            padding: 2rem 0;
            margin-top: 3rem;
        }
        
        @media (max-width: 768px) {
            .hero {
                flex-direction: column;
            }
            
            .hero-text, .hero-image {
                flex: none;
                width: 100%;
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
    
    <section class="section">
        <div class="container hero">
            <div class="hero-text">
                <h2>Revolucionando o tratamento antidepressivo</h2>
                <p>Serenax é o mais novo avanço na farmacologia psiquiátrica, desenvolvido para oferecer alívio eficaz dos sintomas depressivos com menor incidência de efeitos colaterais.</p>
                <p>Nosso compromisso é com a qualidade de vida dos pacientes, proporcionando uma alternativa terapêutica mais tolerável e eficiente.</p>
                <a href="#saiba-mais" class="btn">Saiba mais</a>
            </div>
            <div class="hero-image">
                <img src="https://via.placeholder.com/600x400?text=Imagem+Aghata+Nunes" alt="Aghata Nunes representando a marca Serenax">
            </div>
        </div>
    </section>
    
    <section class="section" id="saiba-mais" style="background-color: var(--white);">
        <div class="container">
            <h2 class="section-title">Sobre o Serenax</h2>
            
            <div class="product-info">
                <h3>Características do Produto</h3>
                <p>Serenax é um antidepressivo de última geração que atua como um inibidor seletivo da recaptação de serotonina e noradrenalina (ISRSN), com mecanismo de ação diferenciado que proporciona:</p>
                <ul>
                    <li>Início de ação mais rápido (a partir de 7 dias)</li>
                    <li>Menor incidência de efeitos colaterais sexuais</li>
                    <li>Eficácia comprovada em depressão moderada a grave</li>
                    <li>Perfil de segurança favorável</li>
                    <li>Posologia simplificada (uma vez ao dia)</li>
                </ul>
            </div>
            
            <div class="product-info">
                <h3>Indicações Terapêuticas</h3>
                <p>Serenax está indicado para o tratamento de:</p>
                <ul>
                    <li>Episódios depressivos maiores</li>
                    <li>Transtorno de ansiedade generalizada</li>
                    <li>Transtorno de estresse pós-traumático</li>
                    <li>Transtorno obsessivo-compulsivo (em estudos)</li>
                </ul>
            </div>
        </div>
    </section>
    
    <section class="section">
        <div class="container">
            <h2 class="section-title">Campanha Publicitária</h2>
            <p>Conheça nossa campanha com a embaixadora Aghata Nunes, que representa perfeitamente a mensagem de superação e bem-estar que o Serenax promove.</p>
            
            <div class="gallery">
                <img src="https://via.placeholder.com/300x400?text=Aghata+1" alt="Aghata Nunes Campanha Serenax">
                <img src="https://via.placeholder.com/300x400?text=Aghata+2" alt="Aghata Nunes Campanha Serenax">
                <img src="https://via.placeholder.com/300x400?text=Aghata+3" alt="Aghata Nunes Campanha Serenax">
                <img src="https://via.placeholder.com/300x400?text=Aghata+4" alt="Aghata Nunes Campanha Serenax">
            </div>
        </div>
    </section>
    
    <section class="section" style="background-color: var(--white);">
        <div class="container">
            <h2 class="section-title">Dados Clínicos</h2>
            
            <div class="product-info">
                <h3>Eficácia Comprovada</h3>
                <p>Em estudos clínicos randomizados, duplo-cegos, controlados por placebo, Serenax demonstrou:</p>
                <ul>
                    <li>67% de resposta terapêutica (vs. 33% placebo)</li>
                    <li>45% de remissão dos sintomas (vs. 18% placebo)</li>
                    <li>Melhora significativa na escala HAM-D desde a 1ª semana</li>
                </ul>
                
                <h3>Perfil de Segurança</h3>
                <p>Serenax apresenta excelente tolerabilidade, com incidência de efeitos adversos comparável ao placebo para:</p>
                <ul>
                    <li>Náuseas (12% vs 8% placebo)</li>
                    <li>Cefaleia (15% vs 14% placebo)</li>
                    <li>Efeitos sexuais (9% vs 27% comparadores)</li>
                </ul>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <p>Serenax® - Todos os direitos reservados</p>
            <p>Este é um material fictício para fins educacionais. Consulte sempre um médico.</p>
            <p>Imagens meramente ilustrativas com Aghata Nunes.</p>
        </div>
    </footer>
</body>
</html
