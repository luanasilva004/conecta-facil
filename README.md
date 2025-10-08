conecta-facil/
│
├── index.html
├── styles.css
└── img/
    ├── equipe.jpg
    └── banner.jpg
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conecta Fácil Soluções - Atualização de Dados e Marketing Digital</title>
    <meta name="description" content="Serviços profissionais de atualização de dados e marketing digital para o seu negócio. Catálogos digitais, anúncios locais e campanhas sazonais.">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.0/font/bootstrap-icons.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light fixed-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#home">Conecta Fácil Soluções</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#sobre">Sobre</a></li>
                    <li class="nav-item"><a class="nav-link" href="#servicos">Serviços</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
                    <li class="nav-item"><a class="nav-link" href="politica.html">Política de Privacidade</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home -->
    <section id="home" class="hero d-flex align-items-center text-center text-white">
        <div class="container">
            <h1 class="display-4 fw-bold">Bem-vindo à Conecta Fácil Soluções</h1>
            <p class="lead">Especialistas em atualização de dados precisos e marketing digital impactante. Impulsione seu negócio com eficiência e criatividade.</p>
            <a href="https://wa.me/5511943328379?text=Olá! Gostaria de saber mais sobre os serviços da Conecta Fácil." class="btn btn-primary btn-lg" target="_blank">Entre em Contato via WhatsApp</a>
        </div>
    </section>

    <!-- Sobre -->
    <section id="sobre" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5">Sobre Nós</h2>
            <div class="row align-items-center">
                <div class="col-md-6">
                    <img src="img/equipe.jpg" class="img-fluid rounded" alt="Equipe Conecta Fácil">
                </div>
                <div class="col-md-6">
                    <p>Somos uma equipe dedicada a ajudar pequenos negócios a gerenciarem seus dados e estratégias de marketing de forma simples e eficaz. Com foco em conformidade com a LGPD, oferecemos soluções personalizadas para atualização de informações e campanhas digitais que geram resultados reais.</p>
                    <p>Nossa missão: Transformar dados em oportunidades e ideias em vendas.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Serviços -->
    <section id="servicos" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Nossos Serviços</h2>
            <div class="row">
                <!-- Atualização de Dados -->
                <div class="col-md-6 col-lg-4 mb-4">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body text-center">
                            <i class="bi bi-database-fill fs-1 text-primary mb-3"></i>
                            <h5 class="card-title">Atualização de Dados</h5>
                            <p class="card-text">Atualização de contato, endereço e fotos no Google Maps.</p>
                            <ul class="list-unstyled">
                                <li>• Criação e otimização completa da ficha Google Meu Negócio</li>
                                <li>• Respostas profissionais a avaliações e comentários</li>
                                <li>• Descrições estratégicas para ranquear melhor no Google</li>
                                <li>• Relatório mensal de desempenho - visualizações e cliques</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <!-- Catálogos Digitais -->
                <div class="col-md-6 col-lg-4 mb-4">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body text-center">
                            <i class="bi bi-file-earmark-pdf fs-1 text-success mb-3"></i>
                            <h5 class="card-title">Criação de Catálogos Digitais</h5>
                            <p class="card-text">Catálogos profissionais em PDF ou Google Drive, otimizados para mobile.</p>
                            <ul class="list-unstyled">
                                <li>• Design atrativo e responsivo</li>
                                <li>• Integração com links de compra</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <!-- Social Media -->
                <div class="col-md-6 col-lg-4 mb-4">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body text-center">
                            <i class="bi bi-megaphone fs-1 text-info mb-3"></i>
                            <h5 class="card-title">Serviços de Social Media</h5>
                            <p class="card-text">Otimizamos anúncios no Google Ads, Facebook e Instagram para atrair clientes na sua região.</p>
                            <ul class="list-unstyled">
                                <li>• Criação de calendário de postagens</li>
                                <li>• Design de artes para redes sociais</li>
                                <li>• Gestão de mensagens e comentários</li>
                                <li>• Relatório de engajamento</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <!-- Campanhas Sazonais -->
                <div class="col-md-6 col-lg-4 mb-4">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body text-center">
                            <i class="bi bi-calendar-event fs-1 text-warning mb-3"></i>
                            <h5 class="card-title">Campanhas Sazonais</h5>
                            <p class="card-text">Estratégias personalizadas para datas especiais como Dia das Mães, Black Friday e Natal.</p>
                            <ul class="list-unstyled">
                                <li>• Planejamento completo</li>
                                <li>• E-mail marketing e redes sociais</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <!-- Pacotes -->
                <div class="col-md-6 col-lg-4 mb-4">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body text-center">
                            <i class="bi bi-shield-check fs-1 text-success mb-3"></i>
                            <h5 class="card-title">Pacotes de Serviços</h5>
                            <p class="card-text">Consulte um dos nossos especialistas para mais informações.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contato -->
    <section id="contato" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5">Entre em Contato</h2>
            <div class="row justify-content-center">
                <div class="col-md-8 text-center">
                    <p class="lead">Estamos prontos para ajudar! Fale conosco via WhatsApp para orçamentos personalizados.</p>
                    <a href="https://wa.me/5511943328379?text=Olá! Gostaria de saber mais sobre os serviços da Conecta Fácil." class="btn btn-success btn-lg" target="_blank">
                        <i class="bi bi-whatsapp me-2"></i> Enviar Mensagem no WhatsApp (11 94332-8379)
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Rodapé -->
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2025 Conecta Fácil Soluções. Todos os direitos reservados. | <a href="politica.html">Política de Privacidade</a></p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
    /* Reset básico */
* { margin:0; padding:0; box-sizing:border-box; font-family:'Roboto', sans-serif; }
body { background-color:#000; color:#fff; line-height:1.6; }

/* Navbar */
.navbar { background-color:#001f4d; }
.navbar-brand { color:#ffd700 !important; font-weight:700; font-size:1.5rem; }
.nav-link { color:#fff !important; transition: color 0.3s; }
.nav-link:hover { color:#ffd700 !important; }

/* Seções */
section { padding:80px 0; }
.hero { background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('img/banner.jpg') center/cover no-repeat; min-height:80vh; display:flex; justify-content:center; align-items:center; text-align:center; }
.hero h1 { font-size:3rem; color:#ffd700; margin-bottom:20px; }
.hero p { font-size:1.25rem; }

/* Botões */
.btn-primary, .btn-success { transition: all 0.3s ease; border:2px solid #ffd700; font-weight:500; }
.btn-primary { background-color:#001f4d; color:#ffd700; }
.btn-success { background-color:#001f4d; color:#ffd700; }
.btn-primary:hover, .btn-success:hover { background-color:#ffd700; color:#001f4d; transform:scale(1.1); }

/* Cartões */
.card { border:none; border-radius:12px; transition: transform 0.3s ease, box-shadow 0.3s ease; }
.card:hover { transform:translateY(-10px); box-shadow:0 10px 25px rgba(0,0,0,0.3); }
.card-title { color:#ffd700; font-weight:700; }

/* Rodapé */
footer { background-color:#001f4d; color:#fff; }
footer a { color:#ffd700; text-decoration:none; }
footer a:hover { text-decoration:underline; }

/* Imagens */
.img-fluid { border-radius:12px; }

</body>
</html>
