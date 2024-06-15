<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Construtora XYZ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            padding: 20px;
        }
        .hero {
            background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
            height: 600px;
            color: #fff;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        .hero h1 {
            font-size: 4em;
            margin: 0;
        }
        .hero p {
            font-size: 1.5em;
        }
        .services, .portfolio, .testimonials, .contact, .about, .blog {
            margin: 40px 0;
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .service-item, .portfolio-item, .testimonial-item, .blog-post {
            margin-bottom: 20px;
        }
        .service-item img, .portfolio-item img {
            max-width: 100%;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            max-width: 600px;
            margin: 0 auto;
        }
        .contact form input, .contact form textarea {
            padding: 10px;
            margin: 10px 0;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Construtora XYZ</h1>
    </header>
    <nav>
        <a href="#home">Início</a>
        <a href="#about">Sobre Nós</a>
        <a href="#services">Serviços</a>
        <a href="#portfolio">Portfólio</a>
        <a href="#testimonials">Depoimentos</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contato</a>
    </nav>
    <div class="hero" id="home">
        <h1>Bem-vindo à Construtora XYZ</h1>
        <p>Excelência em construção e reformas residenciais e comerciais</p>
    </div>
    <div class="container">
        <section class="about" id="about">
            <h2>Sobre Nós</h2>
            <p>Somos uma empresa especializada na construção de casas de alto padrão e na reforma de ambientes residenciais e comerciais. Nossa missão é transformar sonhos em realidade com qualidade e profissionalismo.</p>
        </section>
        <section class="services" id="services">
            <h2>Serviços</h2>
            <div class="service-item">
                <h3>Construção de Casas de Alto Padrão</h3>
                <p>Realizamos projetos personalizados de acordo com as necessidades e desejos dos nossos clientes, entregando sempre o mais alto nível de qualidade e sofisticação.</p>
            </div>
            <div class="service-item">
                <h3>Reforma Residencial</h3>
                <p>Transformamos ambientes residenciais com reformas que aliam funcionalidade e design, garantindo conforto e modernidade.</p>
            </div>
            <div class="service-item">
                <h3>Reforma Comercial</h3>
                <p>Especialistas em reformas de espaços comerciais, como salas, lojas e shoppings, focando na otimização do espaço e na melhor experiência para os clientes.</p>
            </div>
        </section>
        <section class="portfolio" id="portfolio">
            <h2>Portfólio</h2>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/800x400" alt="Projeto 1">
                <p>Descrição do projeto 1</p>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/800x400" alt="Projeto 2">
                <p>Descrição do projeto 2</p>
            </div>
            <!-- Adicione mais projetos conforme necessário -->
        </section>
        <section class="testimonials" id="testimonials">
            <h2>Depoimentos</h2>
            <div class="testimonial-item">
                <p>"Excelente trabalho! Superou nossas expectativas em todos os aspectos."</p>
                <p>- Cliente Satisfeito</p>
            </div>
            <div class="testimonial-item">
                <p>"Profissionais dedicados e competentes. Recomendo a todos."</p>
                <p>- Outro Cliente Satisfeito</p>
            </div>
        </section>
        <section class="blog" id="blog">
            <h2>Blog</h2>
            <div class="blog-post">
                <h3>Título do Post 1</h3>
                <p>Resumo do post 1...</p>
            </div>
            <div class="blog-post">
                <h3>Título do Post 2</h3>
                <p>Resumo do post 2...</p>
            </div>
            <!-- Adicione mais posts conforme necessário -->
        </section>
        <section class="contact" id="contact">
            <h2>Contato</h2>
            <form>
                <input type="text" name="name" placeholder="Nome" required>
                <input type="email" name="email" placeholder="Email" required>
                <textarea name="message" placeholder="Mensagem" rows="5" required></textarea>
                <button type="submit">Enviar</button>
            </form>
            <p>Email: contato@construtoraxyz.com.br</p>
            <p>Telefone: (11) 1234-5678</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Construtora XYZ. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
