<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LLEventos - Iluminação e Efeitos Especiais para Eventos</title>
    <meta name="description" content="LLEventos - Especialistas em iluminação e efeitos para shows, casamentos e eventos corporativos em São Paulo">
    <meta name="keywords" content="iluminação de eventos, efeitos especiais, shows, casamentos, eventos corporativos, São Paulo">
    <meta name="author" content="LLEventos">
    <meta property="og:title" content="LLEventos - Iluminação e Efeitos Especiais">
    <meta property="og:description" content="Transforme seu evento com iluminação espetacular">
    <meta property="og:url" content="https://www.lleventos.com.br">
    <meta property="og:type" content="website">
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #000000;
            --secondary-color: #D4AF37;
            --accent-color: #FFFFFF;
            --text-color: #333333;
            --light-bg: #f8f8f8;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        body {
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--primary-color);
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background-color: rgba(0, 0, 0, 0.95);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            font-size: 28px;
            font-weight: bold;
            color: var(--secondary-color);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .logo img {
            height: 60px;
            width: auto;
            transition: transform 0.3s ease;
        }
        
        .logo:hover img {
            transform: scale(1.05);
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 30px;
        }
        
        nav a {
            color: var(--accent-color);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav a:hover {
            color: var(--secondary-color);
        }
        
        .whatsapp-header {
            background-color: #25D366;
            color: white;
            padding: 10px 15px;
            border-radius: 30px;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 600;
            transition: all 0.3s;
        }
        
        .whatsapp-header:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(37, 211, 102, 0.3);
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://z-cdn-media.chatglm.cn/files/9a54bfe6-ac18-4a92-816c-c52e665bee62_WhatsApp%20Image%202025-11-22%20at%2017.18.42%20%281%29.jpeg?auth_key=1863845129-59e76c83459b408daffa479dab6769d6-0-d7a2a9799c074ea3b9f36c0d12ff83de');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            align-items: center;
            text-align: center;
            color: var(--accent-color);
            padding-top: 80px;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            color: var(--secondary-color);
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            animation: fadeInUp 1s ease-out;
        }
        
        .hero p {
            font-size: 1.5rem;
            margin-bottom: 30px;
            animation: fadeInUp 1s ease-out 0.3s;
            animation-fill-mode: both;
        }
        
        .btn-whatsapp {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            padding: 15px 25px;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            font-size: 1.1rem;
            transition: all 0.3s;
            animation: fadeInUp 1s ease-out 0.6s;
            animation-fill-mode: both;
        }
        
        .btn-whatsapp:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(37, 211, 102, 0.3);
        }
        
        /* About Section */
        .about {
            padding: 80px 0;
            background-color: var(--accent-color);
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }
        
        .section-title h2 {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin-bottom: 15px;
            position: relative;
            display: inline-block;
        }
        
        .section-title h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 3px;
            background-color: var(--secondary-color);
        }
        
        .about-content {
            display: flex;
            align-items: center;
            gap: 50px;
        }
        
        .about-text {
            flex: 1;
        }
        
        .about-text p {
            margin-bottom: 20px;
            font-size: 1.1rem;
            line-height: 1.8;
        }
        
        .about-image {
            flex: 1;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }
        
        .about-image img {
            width: 100%;
            height: auto;
            display: block;
            transition: transform 0.5s;
        }
        
        .about-image:hover img {
            transform: scale(1.05);
        }
        
        /* Services Section */
        .services {
            padding: 80px 0;
            background-color: var(--light-bg);
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }
        
        .service-card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: all 0.3s;
            display: flex;
            flex-direction: column;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
        }
        
        .service-icon {
            background-color: var(--secondary-color);
            color: var(--primary-color);
            height: 80px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
        }
        
        .service-content {
            padding: 25px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
        }
        
        .service-content h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--primary-color);
        }
        
        .service-content p {
            margin-bottom: 20px;
            flex-grow: 1;
        }
        
        .service-btn {
            background-color: var(--primary-color);
            color: var(--accent-color);
            padding: 10px 15px;
            border-radius: 5px;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            font-weight: 600;
            transition: all 0.3s;
            align-self: flex-start;
        }
        
        .service-btn:hover {
            background-color: var(--secondary-color);
            color: var(--primary-color);
        }
        
        /* Gallery Section */
        .gallery {
            padding: 80px 0;
            background-color: var(--primary-color);
            color: var(--accent-color);
        }
        
        .gallery .section-title h2 {
            color: var(--accent-color);
        }
        
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 50px;
        }
        
        .gallery-item {
            border-radius: 10px;
            overflow: hidden;
            height: 250px;
            position: relative;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        
        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }
        
        .gallery-item:hover img {
            transform: scale(1.1);
        }
        
        .gallery-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: 0;
            transition: opacity 0.3s;
        }
        
        .gallery-item:hover .gallery-overlay {
            opacity: 1;
        }
        
        .gallery-overlay i {
            font-size: 2rem;
            color: var(--secondary-color);
        }
        
        /* Testimonials Section */
        .testimonials {
            padding: 80px 0;
            background-color: var(--light-bg);
        }
        
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }
        
        .testimonial-card {
            background-color: white;
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            position: relative;
        }
        
        .testimonial-card::before {
            content: '"';
            position: absolute;
            top: 10px;
            left: 20px;
            font-size: 4rem;
            color: var(--secondary-color);
            opacity: 0.3;
        }
        
        .testimonial-text {
            margin-bottom: 20px;
            font-style: italic;
            position: relative;
            z-index: 1;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .author-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            overflow: hidden;
        }
        
        .author-avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .author-info h4 {
            margin-bottom: 5px;
            color: var(--primary-color);
        }
        
        .author-info p {
            font-size: 0.9rem;
            color: #666;
        }
        
        .rating {
            color: var(--secondary-color);
            margin-top: 10px;
        }
        
        /* CTA Section */
        .cta {
            padding: 80px 0;
            background: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url('https://z-cdn-media.chatglm.cn/files/441836bb-f09e-4124-974c-52cfb20ffa77_WhatsApp%20Image%202025-11-22%20at%2017.18.39.jpeg?auth_key=1863845129-4ace49789825477f82996a9ad1bcd050-0-d61279fdb667e435bc1d02205ae65151');
            background-size: cover;
            background-position: center;
            color: var(--accent-color);
            text-align: center;
        }
        
        .cta h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: var(--secondary-color);
        }
        
        .cta p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .cta-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        .btn-phone {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            padding: 15px 25px;
            background-color: var(--secondary-color);
            color: var(--primary-color);
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            font-size: 1.1rem;
            transition: all 0.3s;
        }
        
        .btn-phone:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(212, 175, 55, 0.3);
        }
        
        /* Footer */
        footer {
            background-color: var(--primary-color);
            color: var(--accent-color);
            padding: 50px 0 20px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .footer-section h3 {
            color: var(--secondary-color);
            margin-bottom: 20px;
            font-size: 1.3rem;
        }
        
        .footer-section p, .footer-section a {
            margin-bottom: 10px;
            color: var(--accent-color);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
            transition: color 0.3s;
        }
        
        .footer-section a:hover {
            color: var(--secondary-color);
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-links a {
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s;
        }
        
        .social-links a:hover {
            background-color: var(--secondary-color);
            color: var(--primary-color);
            transform: translateY(-3px);
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.9rem;
        }
        
        /* Fixed WhatsApp Button */
        .whatsapp-fixed {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
            background-color: #25D366;
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            box-shadow: 0 5px 15px rgba(37, 211, 102, 0.4);
            z-index: 999;
            transition: all 0.3s;
        }
        
        .whatsapp-fixed:hover {
            transform: scale(1.1);
        }
        
        /* Mobile Menu */
        .mobile-menu-toggle {
            display: none;
            background: none;
            border: none;
            color: var(--accent-color);
            font-size: 1.5rem;
            cursor: pointer;
        }
        
        /* Responsive Styles */
        @media (max-width: 768px) {
            .header-content {
                flex-wrap: wrap;
            }
            
            .mobile-menu-toggle {
                display: block;
                order: 3;
            }
            
            nav {
                width: 100%;
                display: none;
                order: 4;
            }
            
            nav.active {
                display: block;
                margin-top: 15px;
            }
            
            nav ul {
                flex-direction: column;
                gap: 15px;
            }
            
            .whatsapp-header {
                order: 2;
                font-size: 0.9rem;
                padding: 8px 12px;
            }
            
            .logo img {
                height: 50px;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero p {
                font-size: 1.2rem;
            }
            
            .about-content {
                flex-direction: column;
            }
            
            .cta-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .btn-whatsapp, .btn-phone {
                width: 100%;
                max-width: 300px;
            }
        }
        
        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <a href="https://www.lleventos.com.br" class="logo">
                    <img src="https://z-cdn-media.chatglm.cn/files/8f8a15d1-70bb-4aeb-a228-2b650d1e7beb_WhatsApp%20Image%202025-11-22%20at%2016.59.03.jpeg?auth_key=1863846293-1392de05bc614192bb1965fd9c931dcd-0-0f76d78954f742d590307663c54c3735" alt="LLEventos Logo">
                </a>
                
                <button class="mobile-menu-toggle" id="mobileMenuToggle">
                    <i class="fas fa-bars"></i>
                </button>
                
                <nav id="mainNav">
                    <ul>
                        <li><a href="#inicio">Início</a></li>
                        <li><a href="#sobre">Sobre</a></li>
                        <li><a href="#servicos">Serviços</a></li>
                        <li><a href="#galeria">Galeria</a></li>
                        <li><a href="#depoimentos">Depoimentos</a></li>
                        <li><a href="#contato">Contato</a></li>
                    </ul>
                </nav>
                
                <a href="https://wa.me/5511957878019?text=Ol%C3%A1%21%20Quero%20um%20or%C3%A7amento%20com%20a%20LLEventos." 
                   target="_blank" 
                   rel="noopener noreferrer" 
                   class="whatsapp-header">
                    <i class="fab fa-whatsapp"></i>
                    WhatsApp
                </a>
            </div>
        </div>
    </header>
    
    <!-- Hero Section -->
    <section class="hero" id="inicio">
        <div class="container">
            <div class="hero-content">
                <h1>Transforme Seu Evento com Iluminação Espetacular</h1>
                <p>Criamos experiências visuais impactantes e memoráveis para shows, casamentos, eventos corporativos e muito mais.</p>
                <a href="https://wa.me/5511957878019?text=Ol%C3%A1%21%20Quero%20um%20or%C3%A7amento%20com%20a%20LLEventos." 
                   target="_blank" 
                   rel="noopener noreferrer" 
                   class="btn-whatsapp">
                    <i class="fab fa-whatsapp"></i>
                    Solicitar Orçamento
                </a>
            </div>
        </div>
    </section>
    
    <!-- About Section -->
    <section class="about" id="sobre">
        <div class="container">
            <div class="section-title">
                <h2>Sobre a LLEventos</h2>
            </div>
            <div class="about-content">
                <div class="about-text">
                    <p>Com mais de 10 anos de experiência no mercado de eventos, a LLEventos é especializada em criar ambientes únicos através de iluminação e efeitos especiais de alta qualidade. Nossa equipe é formada por profissionais qualificados que dominam as técnicas mais modernas de iluminação cenográfica.</p>
                    <p>Trabalhamos com equipamentos de última geração para garantir resultados impressionantes em qualquer tipo de evento, desde shows e casamentos até festas corporativas. Nossa missão é transformar cada ocasião em uma experiência visual inesquecível, superando as expectativas de nossos clientes.</p>
                    <p>Na LLEventos, combinamos criatividade, tecnologia e profissionalismo para entregar soluções personalizadas que refletem a identidade de cada evento e encantam todos os presentes.</p>
                </div>
                <div class="about-image">
                    <img src="https://z-cdn-media.chatglm.cn/files/1b9634a2-539e-47f1-bf89-6045c55009ec_WhatsApp%20Image%202025-11-22%20at%2017.18.41%20%281%29.jpeg?auth_key=1863845758-3e13b991bc8d42b5a25f015e30314185-0-46b66241d8cdd87974cf90940f2e85f6" alt="Evento corporativo com decoração e iluminação profissional">
                </div>
            </div>
        </div>
    </section>
    
    <!-- Services Section -->
    <section class="services" id="servicos">
        <div class="container">
            <div class="section-title">
                <h2>Nossos Serviços</h2>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-lightbulb"></i>
                    </div>
                    <div class="service-content">
                        <h3>Iluminação Profissional</h3>
                        <p>Sistemas de iluminação avançados com LEDs, spots, movers e estruturas personalizadas para criar a atmosfera perfeita para seu evento.</p>
                        <a href="https://wa.me/5511957878019?text=Ol%C3%A1%21%20Tenho%20interesse%20no%20servi%C3%A7o%20de%20Ilumina%C3%A7%C3%A3o%20Profissional" 
                           target="_blank" 
                           rel="noopener noreferrer" 
                           class="service-btn">
                            <i class="fab fa-whatsapp"></i>
                            Peça orçamento via WhatsApp
                        </a>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-tv"></i>
                    </div>
                    <div class="service-content">
                        <h3>Painéis de LED</h3>
                        <p>Painéis de LED de alta resolução para projeção de vídeos, logos e efeitos visuais dinâmicos que encantam e surpreendem o público.</p>
                        <a href="https://wa.me/5511957878019?text=Ol%C3%A1%21%20Tenho%20interesse%20no%20servi%C3%A7o%20de%20Pain%C3%A9is%20de%20LED" 
                           target="_blank" 
                           rel="noopener noreferrer" 
                           class="service-btn">
                            <i class="fab fa-whatsapp"></i>
                            Peça orçamento via WhatsApp
                        </a>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-magic"></i>
                    </div>
                    <div class="service-content">
                        <h3>Efeitos Especiais</h3>
                        <p>Laser, smoke machine, sparkles, bolhas de sabão e outros efeitos especiais para adicionar um toque mágico e surpreendente ao seu evento.</p>
                        <a href="https://wa.me/5511957878019?text=Ol%C3%A1%21%20Tenho%20interesse%20no%20servi%C3%A7o%20de%20Efeitos%20Especiais" 
                           target="_blank" 
                           rel="noopener noreferrer" 
                           class="service-btn">
                            <i class="fab fa-whatsapp"></i>
                            Peça orçamento via WhatsApp
                        </a>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-volume-up"></i>
                    </div>
                    <div class="service-content">
                        <h3>Sonorização</h3>
                        <p>Sistemas de áudio de alta qualidade para garantir perfeita reprodução sonora em qualquer ambiente, com equipamentos modernos e técnicos especializados.</p>
                        <a href="https://wa.me/5511957878019?text=Ol%C3%A1%21%20Tenho%20interesse%20no%20servi%C3%A7o%20de%20Sonoriza%C3%A7%C3%A3o" 
                           target="_blank" 
                           rel="noopener noreferrer" 
                           class="service-btn">
                            <i class="fab fa-whatsapp"></i>
                            Peça orçamento via WhatsApp
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Gallery Section -->
    <section class="gallery" id="galeria">
        <div class="container">
            <div class="section-title">
                <h2>Galeria de Eventos</h2>
            </div>
            <div class="gallery-grid">
                <div class="gallery-item">
                    <img src="https://z-cdn-media.chatglm.cn/files/f33b3c79-2042-4ce4-857a-2c6ebd4bdd62_WhatsApp%20Image%202025-11-22%20at%2017.18.40%20%281%29.jpeg?auth_key=1863845129-06ef9c85d04243ccbbb112620c4fbafe-0-5f158e55a9369c7d822493637e48dfde" alt="Palco com decoração colorida e equipe">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://z-cdn-media.chatglm.cn/files/18a279a5-36e0-4b1c-885b-ad540c5396f3_WhatsApp%20Image%202025-11-22%20at%2017.18.40.jpeg?auth_key=1863845129-f40ddd41ff1442e6ba3caac3e17fa696-0-a31eb376148dc3325b8f0e587b9181e1" alt="Show MulherBrillete com iluminação espetacular">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://z-cdn-media.chatglm.cn/files/df786812-9ddb-4713-90f9-88b03da15bf6_WhatsApp%20Image%202025-11-22%20at%2017.18.42.jpeg?auth_key=1863845129-61bcbf8f193440358dcfeb4b182c9b63-0-dcb5b27f1a665bfbe517266b34499672" alt="Noite de Sabedoria com painéis de LED">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://z-cdn-media.chatglm.cn/files/006bb6bb-5338-4cb7-b3bd-fcc582263bb9_WhatsApp%20Image%202025-11-22%20at%2017.18.44%20%281%29.jpeg?auth_key=1863845129-421a2aee28a34ce1b34e235d04a2e47b-0-0acb670ba55bb84ac2cdccfb527fc957" alt="Rel Show com decoração colorida">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://z-cdn-media.chatglm.cn/files/441836bb-f09e-4124-974c-52cfb20ffa77_WhatsApp%20Image%202025-11-22%20at%2017.18.39.jpeg?auth_key=1863845129-4ace49789825477f82996a9ad1bcd050-0-d61279fdb667e435bc1d02205ae65151" alt="Show com luzes amarelas, brancas e verdes">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://z-cdn-media.chatglm.cn/files/9a54bfe6-ac18-4a92-816c-c52e665bee62_WhatsApp%20Image%202025-11-22%20at%2017.18.42%20%281%29.jpeg?auth_key=1863845129-59e76c83459b408daffa479dab6769d6-0-d7a2a9799c074ea3b9f36c0d12ff83de" alt="Evento em São Paulo com iluminação profissional">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Testimonials Section -->
    <section class="testimonials" id="depoimentos">
        <div class="container">
            <div class="section-title">
                <h2>Depoimentos de Clientes</h2>
            </div>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <p class="testimonial-text">A LLEventos transformou completamente nosso casamento! A iluminação criou uma atmosfera mágica e romântica que encantou a todos os convidados. Equipe profissional e atenciosa do início ao fim.</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <img src="https://picsum.photos/seed/person1/100/100.jpg" alt="Cliente">
                        </div>
                        <div class="author-info">
                            <h4>Mariana Silva</h4>
                            <p>Casamento</p>
                            <div class="rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <p class="testimonial-text">Contratamos a LLEventos para nosso evento corporativo anual e o resultado superou todas as expectativas. Os painéis de LED e efeitos especiais deram um toque de sofisticação que todos notaram.</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <img src="https://picsum.photos/seed/person2/100/100.jpg" alt="Cliente">
                        </div>
                        <div class="author-info">
                            <h4>Carlos Mendes</h4>
                            <p>Evento Corporativo</p>
                            <div class="rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <p class="testimonial-text">A iluminação do show da nossa banda ficou incrível graças à LLEventos! O público ficou maravilhado com os efeitos de luz sincronizados com a música. Profissionalismo e qualidade garantidos!</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <img src="https://picsum.photos/seed/person3/100/100.jpg" alt="Cliente">
                        </div>
                        <div class="author-info">
                            <h4>Ricardo Oliveira</h4>
                            <p>Show Musical</p>
                            <div class="rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- CTA Section -->
    <section class="cta" id="contato">
        <div class="container">
            <h2>Pronto para transformar seu evento?</h2>
            <p>Entre em contato conosco e solicite um orçamento sem compromisso. Nossa equipe está pronta para criar uma experiência visual inesquecível para seu evento.</p>
            <div class="cta-buttons">
                <a href="https://wa.me/5511957878019?text=Ol%C3%A1%21%20Quero%20solicitar%20um%20or%C3%A7amento%20com%20a%20LLEventos." 
                   target="_blank" 
                   rel="noopener noreferrer" 
                   class="btn-whatsapp">
                    <i class="fab fa-whatsapp"></i>
                    Solicite agora um orçamento
                </a>
                <a href="tel:+5511957878019" class="btn-phone">
                    <i class="fas fa-phone"></i>
                    Fale por telefone
                </a>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>LLEventos</h3>
                    <p>Especialistas em iluminação e efeitos para eventos, criando experiências visuais impactantes e memoráveis.</p>
                    <div class="social-links">
                        <a href="https://www.instagram.com/lleventos_som_iluminacao" target="_blank" rel="noopener noreferrer">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" target="_blank" rel="noopener noreferrer">
                            <i class="fab fa-facebook"></i>
                        </a>
                        <a href="#" target="_blank" rel="noopener noreferrer">
                            <i class="fab fa-youtube"></i>
                        </a>
                    </div>
                </div>
                
                <div class="footer-section">
                    <h3>Contato</h3>
                    <a href="tel:+5511957878019">
                        <i class="fas fa-phone"></i>
                        (11) 95787-8019
                    </a>
                    <a href="https://wa.me/5511957878019" target="_blank" rel="noopener noreferrer">
                        <i class="fab fa-whatsapp"></i>
                        (11) 95787-8019
                    </a>
                    <a href="mailto:contato@lleventos.com.br">
                        <i class="fas fa-envelope"></i>
                        contato@lleventos.com.br
                    </a>
                </div>
                
                <div class="footer-section">
                    <h3>Redes Sociais</h3>
                    <a href="https://www.instagram.com/lleventos_som_iluminacao" target="_blank" rel="noopener noreferrer">
                        <i class="fab fa-instagram"></i>
                        @lleventos_som_iluminacao
                    </a>
                    <p style="margin-top: 15px; color: var(--secondary-color);">
                        <i class="fas fa-camera"></i>
                        Siga nosso Instagram para ver nossos últimos projetos!
                    </p>
                </div>
                
                <div class="footer-section">
                    <h3>Informações</h3>
                    <p><i class="fas fa-file-alt"></i> CNPJ: 12.345.678/0001-90</p>
                    <p><i class="fas fa-certificate"></i> Licença de Funcionamento: 987654</p>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>&copy; 2023 LLEventos - Todos os direitos reservados.</p>
            </div>
        </div>
    </footer>
    
    <!-- Fixed WhatsApp Button -->
    <a href="https://wa.me/5511957878019?text=Ol%C3%A1%21%20Quero%20um%20or%C3%A7amento%20com%20a%20LLEventos." 
       target="_blank" 
       rel="noopener noreferrer" 
       class="whatsapp-fixed"
       aria-label="Contato via WhatsApp">
        <i class="fab fa-whatsapp"></i>
    </a>
    
    <script>
        // Mobile menu toggle
        document.getElementById('mobileMenuToggle').addEventListener('click', function() {
            document.getElementById('mainNav').classList.toggle('active');
        });
        
        // Close mobile menu when clicking on a link
        document.querySelectorAll('#mainNav a').forEach(link => {
            link.addEventListener('click', function() {
                document.getElementById('mainNav').classList.remove('active');
            });
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Add shadow to header on scroll
        window.addEventListener('scroll', function() {
            const header = document.querySelector('header');
            if (window.scrollY > 50) {
                header.style.boxShadow = '0 5px 15px rgba(0, 0, 0, 0.3)';
            } else {
                header.style.boxShadow = '0 2px 10px rgba(0, 0, 0, 0.1)';
            }
        });
        
        // Gallery lightbox effect (simplified version)
        document.querySelectorAll('.gallery-item').forEach(item => {
            item.addEventListener('click', function() {
                const imgSrc = this.querySelector('img').src;
                const lightbox = document.createElement('div');
                lightbox.className = 'lightbox';
                lightbox.innerHTML = `
                    <div class="lightbox-content">
                        <span class="close-lightbox">&times;</span>
                        <img src="${imgSrc}" alt="Imagem ampliada">
                    </div>
                `;
                
                // Add lightbox styles
                lightbox.style.cssText = `
                    position: fixed;
                    top: 0;
                    left: 0;
                    width: 100%;
                    height: 100%;
                    background-color: rgba(0, 0, 0, 0.9);
                    z-index: 10000;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                `;
                
                const lightboxContent = lightbox.querySelector('.lightbox-content');
                lightboxContent.style.cssText = `
                    position: relative;
                    max-width: 90%;
                    max-height: 90%;
                `;
                
                const closeBtn = lightbox.querySelector('.close-lightbox');
                closeBtn.style.cssText = `
                    position: absolute;
                    top: -40px;
                    right: 0;
                    color: white;
                    font-size: 30px;
                    cursor: pointer;
                `;
                
                const img = lightbox.querySelector('img');
                img.style.cssText = `
                    width: 100%;
                    height: auto;
                    border-radius: 5px;
                `;
                
                document.body.appendChild(lightbox);
                
                // Close lightbox when clicking on close button or outside the image
                closeBtn.addEventListener('click', function() {
                    document.body.removeChild(lightbox);
                });
                
                lightbox.addEventListener('click', function(e) {
                    if (e.target === lightbox) {
                        document.body.removeChild(lightbox);
                    }
                });
            });
        });
    </script>
</body>
</html>
