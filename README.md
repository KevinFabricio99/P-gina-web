<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- SEO Meta Tags -->
    <title>SMART4GREEN 2026 | Seminario Internacional de Innovación para el Desarrollo Sostenible</title>
    <meta name="description" content="Participa en SMART4GREEN 2026, seminario internacional con feria sobre investigación científica, inteligencia artificial, sostenibilidad, innovación tecnológica y emprendimiento organizado por ESPOCH Sede Morona Santiago.">
    <meta name="keywords" content="SMART4GREEN 2026, desarrollo sostenible, inteligencia artificial, IoT, Amazonía, investigación científica, innovación tecnológica, congresos académicos, emprendimiento, sostenibilidad, ESPOCH">
    <meta name="author" content="ESPOCH Sede Morona Santiago">
    <meta name="robots" content="index, follow">

    <!-- Open Graph / Facebook / LinkedIn -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://smart4green.espoch.edu.ec/">
    <meta property="og:title" content="SMART4GREEN 2026 | I Seminario Multidisciplinario de Innovación para el Desarrollo Sostenible">
    <meta property="og:description" content="17 de noviembre de 2026. Seminario modalidda híbrida y feria presencial de emprendimientos de 09h00 a 13h00.">
    <meta property="og:image" content="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80">

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:title" content="SMART4GREEN 2026 | I Seminario Multidisciplinario">
    <meta property="twitter:description" content="Seminario modalidad híbrida el 17 de noviembre de 2026; feria presencial de 09h00 a 13h00.">
    <meta property="twitter:image" content="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=80">

    <!-- Favicon -->
    <link rel="icon" href="https://www.espoch.edu.ec/favicon.ico" type="image/x-icon">

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800&family=Open+Sans:wght@300;400;600;700&display=swap" rel="stylesheet">

    <!-- Bootstrap 5.3 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Font Awesome 6 Pro / Free Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">

    <!-- AOS (Animate On Scroll) Library -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <!-- Custom System CSS -->
    <style>
        :root {
            --primary-green: #1B5E20;
            --secondary-blue: #1565C0;
            --accent-cyan: #4FC3F7;
            --light-bg: #F8FAFC;
            --dark-text: #0F172A;
            --muted-text: #475569;
            --white: #FFFFFF;
            --card-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        body {
            font-family: 'Open Sans', sans-serif;
            color: var(--dark-text);
            background-color: var(--light-bg);
            overflow-x: hidden;
            scroll-behavior: smooth;
        }

        h1, h2, h3, h4, h5, h6, .navbar-brand {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
        }

        /* Topbar & Navbar */
        .top-bar {
            background-color: var(--primary-green);
            color: var(--white);
            font-size: 0.85rem;
            padding: 6px 0;
        }

        .navbar {
            background-color: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            box-shadow: 0 2px 15px rgba(0,0,0,0.05);
            transition: var(--transition);
        }

        .navbar-brand img {
            height: 48px;
            object-fit: contain;
        }

        .nav-link {
            font-weight: 600;
            color: var(--dark-text) !important;
            font-size: 0.92rem;
            padding: 0.5rem 0.8rem !important;
            transition: var(--transition);
        }

        .nav-link:hover, .nav-link.active {
            color: var(--secondary-blue) !important;
        }

        /* Hero Section */
        .hero-section {
            position: relative;
            min-height: 100vh;
            background: linear-gradient(135deg, rgba(27, 94, 32, 0.88), rgba(21, 101, 192, 0.85)), 
                        url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1920&q=80') center/cover no-repeat fixed;
            display: flex;
            align-items: center;
            color: var(--white);
            padding-top: 100px;
            padding-bottom: 60px;
        }

        .hero-title {
            font-size: clamp(2.5rem, 5vw, 4rem);
            font-weight: 800;
            letter-spacing: -1px;
            text-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }

        .hero-badge {
            background: rgba(79, 195, 247, 0.2);
            border: 1px solid var(--accent-cyan);
            color: #E0F7FA;
            font-weight: 600;
            padding: 8px 18px;
            border-radius: 50px;
            display: inline-block;
            margin-bottom: 1.5rem;
            backdrop-filter: blur(5px);
        }

        /* Countdown Component */
        .countdown-container {
            display: flex;
            gap: 15px;
            justify-content: center;
            margin: 2rem 0;
        }

        .countdown-box {
            background: rgba(255, 255, 255, 0.12);
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 12px;
            padding: 12px 18px;
            min-width: 80px;
            text-align: center;
        }

        .countdown-num {
            font-size: 1.8rem;
            font-weight: 800;
            color: var(--accent-cyan);
            display: block;
            line-height: 1;
        }

        .countdown-label {
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-top: 5px;
        }

        /* Buttons Styling */
        .btn-custom-primary {
            background-color: #2E7D32;
            color: var(--white);
            border: none;
            font-weight: 700;
            padding: 12px 28px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(46, 125, 50, 0.4);
            transition: var(--transition);
        }

        .btn-custom-primary:hover {
            background-color: #1B5E20;
            color: var(--white);
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(46, 125, 50, 0.6);
        }

        .btn-custom-secondary {
            background-color: var(--secondary-blue);
            color: var(--white);
            border: none;
            font-weight: 700;
            padding: 12px 28px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(21, 101, 192, 0.4);
            transition: var(--transition);
        }

        .btn-custom-secondary:hover {
            background-color: #0D47A1;
            color: var(--white);
            transform: translateY(-2px);
        }

        .btn-custom-outline {
            border: 2px solid var(--white);
            color: var(--white);
            font-weight: 700;
            padding: 10px 26px;
            border-radius: 8px;
            transition: var(--transition);
        }

        .btn-custom-outline:hover {
            background: var(--white);
            color: var(--primary-green);
        }

        /* Section Title Styling */
        .section-header {
            text-align: center;
            margin-bottom: 3.5rem;
        }

        .section-subtitle {
            color: var(--secondary-blue);
            text-transform: uppercase;
            font-weight: 700;
            font-size: 0.85rem;
            letter-spacing: 2px;
            display: block;
            margin-bottom: 0.5rem;
        }

        .section-title {
            font-size: 2.2rem;
            color: var(--dark-text);
            position: relative;
            display: inline-block;
        }

        .section-title::after {
            content: '';
            width: 60px;
            height: 4px;
            background: var(--primary-green);
            display: block;
            margin: 10px auto 0;
            border-radius: 2px;
        }

        /* Cards & Features */
        .feature-card {
            background: var(--white);
            border-radius: 16px;
            padding: 2rem;
            height: 100%;
            box-shadow: var(--card-shadow);
            border: 1px solid rgba(0,0,0,0.03);
            transition: var(--transition);
        }

        .feature-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.12);
        }

        .feature-icon {
            width: 65px;
            height: 65px;
            border-radius: 12px;
            background: rgba(21, 101, 192, 0.08);
            color: var(--secondary-blue);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            transition: var(--transition);
        }

        .feature-card:hover .feature-icon {
            background: var(--secondary-blue);
            color: var(--white);
        }

        /* Keynote Speakers IEEE Style */
        .speaker-card {
            background: var(--white);
            border-radius: 16px;
            overflow: hidden;
            box-shadow: var(--card-shadow);
            transition: var(--transition);
            border: 1px solid #E2E8F0;
        }

        .speaker-card:hover {
            transform: translateY(-5px);
        }

        .speaker-img-wrapper {
            position: relative;
            height: 280px;
            overflow: hidden;
            background-color: #E2E8F0;
        }

        .speaker-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }

        .speaker-card:hover .speaker-img {
            transform: scale(1.05);
        }

        .speaker-flag {
            position: absolute;
            top: 15px;
            right: 15px;
            font-size: 1.5rem;
            background: rgba(255,255,255,0.9);
            padding: 4px 10px;
            border-radius: 20px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.15);
        }

        /* Timeline Component */
        .timeline {
            position: relative;
            padding: 2rem 0;
        }

        .timeline::before {
            content: '';
            position: absolute;
            top: 0;
            left: 50%;
            width: 4px;
            height: 100%;
            background: #E2E8F0;
            transform: translateX(-50%);
        }

        .timeline-item {
            margin-bottom: 2.5rem;
            position: relative;
            width: 50%;
        }

        .timeline-item:nth-child(odd) {
            left: 0;
            padding-right: 40px;
            text-align: right;
        }

        .timeline-item:nth-child(even) {
            left: 50%;
            padding-left: 40px;
        }

        .timeline-dot {
            width: 20px;
            height: 20px;
            background: var(--primary-green);
            border: 4px solid var(--white);
            border-radius: 50%;
            position: absolute;
            top: 15px;
            box-shadow: 0 0 0 4px rgba(27, 94, 32, 0.2);
        }

        .timeline-item:nth-child(odd) .timeline-dot {
            right: -10px;
        }

        .timeline-item:nth-child(even) .timeline-dot {
            left: -10px;
        }

        .timeline-content {
            background: var(--white);
            padding: 1.5rem;
            border-radius: 12px;
            box-shadow: var(--card-shadow);
        }

        /* Statistics Counter Section */
        .stats-section {
            background: linear-gradient(135deg, var(--primary-green), #0D47A1);
            color: var(--white);
            padding: 5rem 0;
        }

        .stat-number {
            font-size: 3rem;
            font-weight: 800;
            color: var(--accent-cyan);
        }

        /* Floating WhatsApp Button */
        .whatsapp-float {
            position: fixed;
            bottom: 30px;
            right: 30px;
            width: 60px;
            height: 60px;
            background-color: #25d366;
            color: #FFF;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            z-index: 1000;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            transition: var(--transition);
        }

        .whatsapp-float:hover {
            transform: scale(1.1);
            color: var(--white);
        }

        /* Scroll to Top */
        .back-to-top {
            position: fixed;
            bottom: 30px;
            right: 100px;
            width: 45px;
            height: 45px;
            background-color: var(--secondary-blue);
            color: var(--white);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            opacity: 0;
            visibility: hidden;
            transition: var(--transition);
            z-index: 999;
        }

        .back-to-top.active {
            opacity: 1;
            visibility: visible;
        }

        /* Media Queries for Timeline Responsive */
        @media (max-width: 768px) {
            .timeline::before {
                left: 20px;
            }
            .timeline-item {
                width: 100% !important;
                padding-left: 50px !important;
                padding-right: 0 !important;
                text-align: left !important;
            }
            .timeline-item:nth-child(even) {
                left: 0;
            }
            .timeline-item:nth-child(odd) .timeline-dot,
            .timeline-item:nth-child(even) .timeline-dot {
                left: 10px;
            }
            .back-to-top {
                right: 20px;
                bottom: 100px;
            }
        }

        /* Logotipos de organizadores, proyectos, redes y grupos */
        .partner-card { height: 100%; background: #fff; border: 1px solid #e3e9e5; border-radius: 1rem; padding: 1.5rem; box-shadow: 0 5px 18px rgba(0,0,0,.05); text-align: center; }
        .partner-logo-box { height: 100px; display: flex; align-items: center; justify-content: center; margin-bottom: 1rem; border-radius: .75rem; background: #f5f9f6; }
        .partner-logo-box img { display: block; max-width: 85%; max-height: 78px; object-fit: contain; }
        .partner-logo-box i { font-size: 2.3rem; color: #1b5e20; }
    </style>
</head>
<body>

    <!-- TOPBAR -->
    <div class="top-bar">
        <div class="container d-flex justify-content-between align-items-center">
            <div>
                <i class="fa-solid fa-graduation-cap me-2"></i> ESPOCH Sede Morona Santiago | Seminario · 17 de noviembre de 2026
            </div>
            <div class="d-none d-md-block">
                <i class="fa-regular fa-envelope me-1"></i> investigo@istra.edu.ec
            </div>
        </div>
    </div>

    <!-- NAVBAR STICKY -->
    <nav class="navbar navbar-expand-lg sticky-top navbar-light">
        <div class="container">
            <a class="navbar-brand d-flex align-items-center gap-2" href="#">
                <span class="fw-extrabold text-success fs-4">SMART<span class="text-primary">4GREEN</span></span>
                <span class="badge bg-primary text-wrap text-start" style="font-size: 0.65rem;">2026</span>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto align-items-center gap-1">
                    <li class="nav-item"><a class="nav-link" href="#inicio">Inicio</a></li>
                    <li class="nav-item"><a class="nav-link" href="#acerca">Acerca de</a></li>
                    <li class="nav-item"><a class="nav-link" href="#ejes">Ejes Temáticos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#speakers">Speakers</a></li>
                    <li class="nav-item"><a class="nav-link" href="#callforpapers">Call for Papers</a></li>
                    <li class="nav-item"><a class="nav-link" href="#fechas">Fechas</a></li>
                    <li class="nav-item"><a class="nav-link" href="#emprendimiento">Feria Emprendimiento</a></li>
                    <li class="nav-item"><a class="nav-link" href="#programa">Programa</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
                    <li class="nav-item ms-lg-2">
                        <a href="#callforpapers" class="btn btn-custom-primary btn-sm rounded-pill px-3">Enviar Manuscrito</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- HERO SECTION FULLSCREEN -->
    <section id="inicio" class="hero-section">
        <div class="container">
            <div class="row align-items-center justify-content-center text-center">
                <div class="col-lg-10" data-aos="fade-up">
                    <span class="hero-badge">
                        <i class="fa-solid fa-globe me-2"></i> Seminario · 17 de noviembre de 2026
                    </span>
                    <h1 class="hero-title mb-3">SMART4GREEN 2026</h1>
                    <p class="fs-4 fw-semibold text-light mb-2">I Seminario Multidisciplinario de Innovación para el Desarrollo Sostenible</p>
                    <p class="text-info fw-bold mb-2">Tecnología • Producción • Economía • Sociedad • Ambiente</p>
                    <p class="text-light mb-4">Feria de emprendimientos presencial · 09h00 a 13h00 · Lugar por confirmar</p>
                    
                    <!-- Countdown Timer -->
                    <div class="countdown-container" id="countdown">
                        <div class="countdown-box">
                            <span class="countdown-num" id="days">00</span>
                            <span class="countdown-label">Días</span>
                        </div>
                        <div class="countdown-box">
                            <span class="countdown-num" id="hours">00</span>
                            <span class="countdown-label">Horas</span>
                        </div>
                        <div class="countdown-box">
                            <span class="countdown-num" id="minutes">00</span>
                            <span class="countdown-label">Minutos</span>
                        </div>
                        <div class="countdown-box">
                            <span class="countdown-num" id="seconds">00</span>
                            <span class="countdown-label">Segundos</span>
                        </div>
                    </div>

                    <div class="d-flex flex-wrap justify-content-center gap-3 mt-4">
                        <a href="https://forms.gle/oieuCepQ93R2p2tTA"
                           target="_blank"
                           rel="noopener noreferrer"
                           class="btn btn-outline-light btn-sm align-self-center">
                            <i class="fa-solid fa-ticket me-1"></i> Inscripción general
                        </a>
                        </button>
                        <a href="#callforpapers" class="btn btn-custom-primary">
                            <i class="fa-solid fa-paper-plane me-2"></i> Enviar Manuscrito
                        </a>
                        <a href="#emprendimiento" class="btn btn-custom-secondary">
                            <i class="fa-solid fa-lightbulb me-2"></i> Feria de Emprendimiento
                        </a>
                        <a href="#programa" class="btn btn-custom-outline">
                            <i class="fa-regular fa-calendar-check me-2"></i> Ver Programa
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- HIGHLIGHT FEATURES STRIP -->
    <section class="py-4 bg-white shadow-sm border-bottom">
        <div class="container">
            <div class="row text-center g-3">
                <div class="col-6 col-md-3">
                    <div class="d-flex align-items-center justify-content-center gap-2">
                        <i class="fa-solid fa-earth-americas text-primary fs-3"></i>
                        <span class="fw-bold text-dark">17 de noviembre de 2026</span>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="d-flex align-items-center justify-content-center gap-2">
                        <i class="fa-solid fa-chalkboard-user text-success fs-3"></i>
                        <span class="fw-bold text-dark">Feria Presencial</span>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="d-flex align-items-center justify-content-center gap-2">
                        <i class="fa-solid fa-microchip text-info fs-3"></i>
                        <span class="fw-bold text-dark">IA & Monitoreo IoT</span>
                    </div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="d-flex align-items-center justify-content-center gap-2">
                        <i class="fa-solid fa-people-arrows text-warning fs-3"></i>
                        <span class="fw-bold text-dark">Networking Académico</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ACERCA DEL SEMINARIO -->
    <section id="acerca" class="py-5">
        <div class="container py-4">
            <div class="row align-items-center g-5">
                <div class="col-lg-6" data-aos="fade-right">
                    <span class="section-subtitle">Sobre el Evento</span>
                    <h2 class="section-title text-start mb-4">Promoviendo la Investigación Científica y la Sostenibilidad Amazónica</h2>
                    <p class="text-muted leading-relaxed">
                        El <strong>SMART4GREEN 2026</strong> se constituye como un espacio internacional multidisciplinario diseñado para articular la investigación académica con el desarrollo sostenible en el contexto global y regional.
                    </p>
                    <p class="text-muted">
                        Organizado por la <strong>ESPOCH Sede Morona Santiago</strong>, el seminario integra proyectos estratégicos como el <em>"Sistema Inteligente de Monitoreo de la Calidad Ambiental en Ecosistemas Amazónicos mediante IoT e Inteligencia Artificial"</em> y la <em>"Hidroponía Inteligente Amazónica"</em>.
                    </p>
                    <div class="row g-3 mt-3">
                        <div class="col-sm-6">
                            <div class="p-3 border rounded bg-white border-start border-4 border-success">
                                <h6 class="fw-bold text-success mb-1">Impacto Ambiental</h6>
                                <p class="small text-muted mb-0">Protección ecosistémica mediante sensores de última generación.</p>
                            </div>
                        </div>
                        <div class="col-sm-6">
                            <div class="p-3 border rounded bg-white border-start border-4 border-primary">
                                <h6 class="fw-bold text-primary mb-1">Transformación Digital</h6>
                                <p class="small text-muted mb-0">Aplicación de modelos de Inteligencia Artificial.</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6" data-aos="fade-left">
                    <div class="row g-3">
                        <div class="col-12">
                            <h5 class="fw-bold mb-3"><i class="fa-solid fa-users text-primary me-2"></i>Público Objetivo</h5>
                        </div>
                        <div class="col-6">
                            <div class="p-3 bg-white rounded shadow-sm border text-center">
                                <i class="fa-solid fa-user-graduate text-success fs-2 mb-2"></i>
                                <h6 class="fw-bold mb-0">Investigadores y Docentes</h6>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="p-3 bg-white rounded shadow-sm border text-center">
                                <i class="fa-solid fa-book-reader text-info fs-2 mb-2"></i>
                                <h6 class="fw-bold mb-0">Estudiantes</h6>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="p-3 bg-white rounded shadow-sm border text-center">
                                <i class="fa-solid fa-briefcase text-warning fs-2 mb-2"></i>
                                <h6 class="fw-bold mb-0">Profesionales y Empresas</h6>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="p-3 bg-white rounded shadow-sm border text-center">
                                <i class="fa-solid fa-building-columns text-primary fs-2 mb-2"></i>
                                <h6 class="fw-bold mb-0">Instituciones Públicas / Privadas</h6>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- EJES TEMÁTICOS -->
    <section id="ejes" class="py-5 bg-white">
        <div class="container py-4">
            <div class="section-header" data-aos="fade-up">
                <span class="section-subtitle">Áreas de Investigación</span>
                <h2 class="section-title">Ejes Temáticos del Evento</h2>
            </div>
            <div class="row g-4">
                <!-- Eje 1 -->
                <div class="col-md-6 col-lg-4" data-aos="zoom-in" data-aos-delay="100">
                    <div class="feature-card">
                        <div class="feature-icon"><i class="fa-solid fa-robot"></i></div>
                        <h5 class="fw-bold">1. Tecnología, IA y Digitalización</h5>
                        <p class="text-muted small">Inteligencia Artificial, Internet de las Cosas (IoT), Transformación Digital y Big Data aplicados al desarrollo.</p>
                    </div>
                </div>
                <!-- Eje 2 -->
                <div class="col-md-6 col-lg-4" data-aos="zoom-in" data-aos-delay="200">
                    <div class="feature-card">
                        <div class="feature-icon"><i class="fa-solid fa-leaf"></i></div>
                        <h5 class="fw-bold">2. Ambiente y Sostenibilidad</h5>
                        <p class="text-muted small">Monitoreo ambiental, conservación de la biodiversidad, cambio climático y resiliencia ecológica.</p>
                    </div>
                </div>
                <!-- Eje 3 -->
                <div class="col-md-6 col-lg-4" data-aos="zoom-in" data-aos-delay="300">
                    <div class="feature-card">
                        <div class="feature-icon"><i class="fa-solid fa-gem"></i></div>
                        <h5 class="fw-bold">3. Recursos Naturales y Territorio</h5>
                        <p class="text-muted small">Minería responsable, gestión territorial sostenible y preservación de cuencas hidrográficas.</p>
                    </div>
                </div>
                <!-- Eje 4 -->
                <div class="col-md-6 col-lg-4" data-aos="zoom-in" data-aos-delay="400">
                    <div class="feature-card">
                        <div class="feature-icon"><i class="fa-solid fa-wheat-awn"></i></div>
                        <h5 class="fw-bold">4. Producción y Zootecnia</h5>
                        <p class="text-muted small">Agropecuaria de precisión, hidroponía inteligente y sistemas agroforestales sostenibles.</p>
                    </div>
                </div>
                <!-- Eje 5 -->
                <div class="col-md-6 col-lg-4" data-aos="zoom-in" data-aos-delay="500">
                    <div class="feature-card">
                        <div class="feature-icon"><i class="fa-solid fa-chart-line"></i></div>
                        <h5 class="fw-bold">5. Economía y Negocios Sostenibles</h5>
                        <p class="text-muted small">Economía circular, contabilidad ambiental, finanzas verdes y modelos de negocios sustentables.</p>
                    </div>
                </div>
                <!-- Eje 6 -->
                <div class="col-md-6 col-lg-4" data-aos="zoom-in" data-aos-delay="600">
                    <div class="feature-card">
                        <div class="feature-icon"><i class="fa-solid fa-scale-balanced"></i></div>
                        <h5 class="fw-bold">6. Derecho, Sociedad y Gobernanza</h5>
                        <p class="text-muted small">Políticas públicas, bioética, gobernanza territorial y legislación ambiental.</p>
                    </div>
                </div>
                <!-- Eje 7 -->
                <div class="col-md-12 col-lg-12" data-aos="zoom-in" data-aos-delay="700">
                    <div class="feature-card text-center border-success">
                        <div class="feature-icon mx-auto"><i class="fa-solid fa-rocket"></i></div>
                        <h5 class="fw-bold">7. Innovación, Emprendimiento y Desarrollo Sostenible</h5>
                        <p class="text-muted small max-w-700 mx-auto">Modelos de transferencia tecnológica, incubación de empresas sostenibles y soluciones innovadoras para comunidades amazónicas.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- KEYNOTE SPEAKERS -->
    <section id="speakers" class="py-5">
        <div class="container py-4">
            <div class="section-header" data-aos="fade-up">
                <span class="section-subtitle"></span>
                <h2 class="section-title">Keynote Speakers</h2>
            </div>
            <div class="row g-4 justify-content-center">
                <!-- Speaker 1 -->
                <div class="col-md-6 col-lg-4" data-aos="fade-up" data-aos-delay="100">
                    <div class="speaker-card">
                        <div class="speaker-img-wrapper">
                            <img src="assets/omar.jpg"
                                 alt="Fotografía del keynote speaker"
                                 class="speaker-img">
                            <span class="speaker-flag" title="Italia">🇮🇹</span>
                        </div>
                        <div class="p-4">
                            <h4 class="fw-bold mb-1">Ing. Omar Delgado, PhD.</h4>
                            <p class="text-primary fw-semibold mb-2">Università della Calabria, Italia</p>
                            <hr class="my-3">
                            <p class="small text-muted mb-2"><strong>Especialidad:</strong> Inteligencia Artificial, Sistemas Inteligentes, Transformación Digital y Tecnologías Emergentes.</p>
                            <button class="btn btn-sm btn-outline-primary rounded-pill mt-2" data-bs-toggle="modal" data-bs-target="#modalSpeaker1">Ver Bio Completa</button>
                        </div>
                    </div>
                </div>
                <!-- Speaker 2 -->
                <div class="col-md-6 col-lg-4" data-aos="fade-up" data-aos-delay="300">
                    <div class="speaker-card h-100">
                        <div class="speaker-img-wrapper">
                            <i class="fa-solid fa-user-tie text-success" style="font-size: 5rem;" aria-hidden="true"></i>
                        </div>
                        <div class="p-4">
                            <span class="badge bg-light text-success border mb-2">Por confirmar</span>
                            <h4 class="fw-bold mb-1">Keynote Speaker 3</h4>
                            <p class="text-primary fw-semibold mb-2">Afiliación por confirmar</p>
                            <hr class="my-3">
                            <p class="small text-muted mb-0"><strong>Tema:</strong> Por confirmar.</p>
                        </div>
                    </div>
                </div>
                <!-- Speaker 3: por confirmar -->
                <div class="col-md-6 col-lg-4" data-aos="fade-up" data-aos-delay="300">
                    <div class="speaker-card h-100">
                        <div class="speaker-img-wrapper">
                            <i class="fa-solid fa-user-tie text-success" style="font-size: 5rem;" aria-hidden="true"></i>
                        </div>
                        <div class="p-4">
                            <span class="badge bg-light text-success border mb-2">Por confirmar</span>
                            <h4 class="fw-bold mb-1">Keynote Speaker 3</h4>
                            <p class="text-primary fw-semibold mb-2">Afiliación por confirmar</p>
                            <hr class="my-3">
                            <p class="small text-muted mb-0"><strong>Tema:</strong> Por confirmar.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CALL FOR PAPERS -->
    <section id="callforpapers" class="py-5 bg-white">
        <div class="container py-4">
            <div class="text-center mb-5" data-aos="fade-up">
                <span class="badge bg-warning text-dark px-3 py-2 mb-3 fw-bold">Convocatoria Científica Abierta</span>
                <h2 class="fw-bold display-6 mb-3">Call for Papers</h2>
                <p class="lead text-muted mx-auto" style="max-width: 850px;">Invitamos a investigadores, académicos y profesionales a presentar trabajos originales e inéditos en las áreas temáticas de SMART4GREEN 2026.</p>
            </div>
            <div class="p-4 p-md-5 rounded-4 shadow-lg text-white mb-5" style="background: linear-gradient(135deg, #1B5E20 0%, #1565C0 100%);">
                <div class="row align-items-center">
                    <div class="col-lg-8" data-aos="fade-right">
                        <h3 class="fw-bold mb-3">Recepción de Artículos Científicos</h3>
                        <p class="mb-4">Los manuscritos presentados serán sometidos a evaluación académica. <strong></strong></p>
                        <div class="row g-3">
                            <div class="col-md-6"><i class="fa-solid fa-circle-check text-warning me-2"></i>Revisión Científica Rigurosa</div>
                            <div class="col-md-6"><i class="fa-solid fa-circle-check text-warning me-2"></i>Publicación de Trabajos Aceptados</div>
                            <div class="col-md-6"><i class="fa-solid fa-circle-check text-warning me-2"></i>Certificación Digital</div>
                            <div class="col-md-6"><i class="fa-solid fa-circle-check text-warning me-2"></i>Difusión Académica</div>
                        </div>
                    </div>
                    <div class="col-lg-4 text-center d-none d-lg-block" data-aos="fade-left">
                        <i class="fa-solid fa-file-signature" style="font-size: 8rem; opacity: .25;" aria-hidden="true"></i>
                    </div>
                </div>
            </div>
            <div class="row g-4 mb-5">
                <div class="col-lg-5" data-aos="fade-right">
                    <div class="p-4 rounded-4 border bg-light h-100">
                        <span class="badge bg-success mb-3">Revista Oficial</span>
                        <h3 class="fw-bold mb-2">INVESTIGO</h3>
                        <p class="text-muted mb-3">Revista Científica Multidisciplinaria</p>
                        <p class="fw-bold mb-4"><i class="fa-solid fa-barcode me-2"></i>ISSN 2953-6367</p>
                        <a href="http://revistainvestigo.com" target="_blank" rel="noopener noreferrer" class="btn btn-outline-primary"><i class="fa-solid fa-arrow-up-right-from-square me-2"></i>Visitar Sitio Web Revista</a>
                    </div>
                </div>
                <div class="col-lg-7" data-aos="fade-left">
                    <div class="p-4 h-100">
                        <h3 class="fw-bold mb-4">Requisitos de Presentación de Documentos</h3>
                        <ul class="list-unstyled mb-4">
                            <li class="mb-3"><i class="fa-solid fa-check text-success me-2"></i><strong>Idioma oficial:</strong> Español.</li>
                            <li class="mb-3"><i class="fa-solid fa-check text-success me-2"></i><strong>Extensión:</strong> Máximo 10 páginas utilizando la plantilla.</li>
                            <li class="mb-3"><i class="fa-solid fa-check text-success me-2"></i><strong>Formatos requeridos:</strong> PDF y editable en Word (.docx).</li>
                        </ul>
                        <div class="d-flex flex-wrap gap-2">
                            <a href="documentos/Plantilla para el desarrollo de artículos científicos InvestiGo.docx" class="btn btn-dark" download>
                                <i class="fa-solid fa-download me-2"></i>Plantilla de Artículo
                            </a>
                            <a href="documentos/Ficha de Información para autores y evaluadores InvestiGo.docx" class="btn btn-outline-dark" download>
                                <i class="fa-solid fa-download me-2"></i>Ficha de Autor
                            </a>
                            <a href="documentos/Originalidad y cesión de derechos de articulo.docx" class="btn btn-outline-dark" download>
                                <i class="fa-solid fa-download me-2"></i>Declaración de Originalidad
                            </a>
                        </div>

                    </div>
                </div>
            </div>
            <div class="text-center p-4 rounded-4 bg-light border" data-aos="fade-up">
                <h4 class="fw-bold mb-2">¿Listo para presentar tu investigación?</h4>
                <p class="text-muted mb-4">Consulta los requisitos y envía tu manuscrito para participar en SMART4GREEN 2026.</p>
                <button class="btn btn-warning btn-lg fw-bold px-5 text-dark" data-bs-toggle="modal" data-bs-target="#modalSubmitPaper"><i class="fa-solid fa-file-arrow-up me-2"></i>Enviar Manuscrito Ahora</button>
            </div>
        </div>
    </section>

    <!-- FECHAS IMPORTANTES (TIMELINE) -->
    <section id="fechas" class="py-5">
        <div class="container py-4">
            <div class="section-header" data-aos="fade-up">
                <span class="section-subtitle">Cronograma Académico</span>
                <h2 class="section-title">Fechas Importantes</h2>
            </div>
            <div class="timeline">
                <div class="timeline-item" data-aos="fade-right">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <span class="badge bg-danger mb-2">Límite de Envío</span>
                        <h5 class="fw-bold mb-1">Envío de Manuscritos</h5>
                        <p class="text-primary fw-bold mb-0"><i class="fa-regular fa-calendar me-2"></i>30 de Octubre de 2026</p>
                    </div>
                </div>
                <div class="timeline-item" data-aos="fade-left">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <span class="badge bg-primary mb-2">Evaluación</span>
                        <h5 class="fw-bold mb-1">Notificación de Aceptación</h5>
                        <p class="text-primary fw-bold mb-0"><i class="fa-regular fa-calendar me-2"></i>06 de Noviembre de 2026</p>
                    </div>
                </div>
                <div class="timeline-item" data-aos="fade-right">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <span class="badge bg-warning text-dark mb-2">Cámara Lista</span>
                        <h5 class="fw-bold mb-1">Entrega de Versión Final</h5>
                        <p class="text-primary fw-bold mb-0"><i class="fa-regular fa-calendar me-2"></i>13 de Noviembre de 2026</p>
                    </div>
                </div>
                <div class="timeline-item" data-aos="fade-left">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <span class="badge bg-success mb-2">Evento Vivo</span>
                        <h5 class="fw-bold mb-1">Desarrollo de SMART4GREEN 2026</h5>
                        <p class="text-primary fw-bold mb-0"><i class="fa-regular fa-calendar me-2"></i>17 de noviembre de 2026</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FERIA DE EMPRENDIMIENTOS -->
    <section id="emprendimiento" class="py-5">
        <div class="container py-4">
            <div class="section-header" data-aos="fade-up">
                <span class="section-subtitle">I Feria de Emprendimientos SMART4GREEN 2026</span>
                <h2 class="section-title">Convierte una idea en una solución para el futuro.</h2>
                <p class="text-muted mt-3 mb-0"><i class="fa-regular fa-calendar me-2"></i><strong>17 de noviembre de 2026 · 09h00–13h00</strong> · Modalidad presencial · Lugar por confirmar.</p>
            </div>
            <div class="row g-5">
                <div class="col-lg-5" data-aos="fade-right">
                    <div class="p-4 bg-white rounded-4 shadow-sm h-100">
                        <h4 class="fw-bold text-success mb-3"><i class="fa-solid fa-seedling me-2"></i>Feria de Emprendimientos SMART4GREEN 2026</h4>
                        <p class="text-muted mb-4">La Feria de Emprendimientos SMART4GREEN 2026 es un espacio para presentar ideas de negocio, proyectos innovadores y soluciones con potencial de impacto, vinculadas con la sostenibilidad, tecnología, producción, economía, sociedad y ambiente.</p>
                        

                        <h6 class="fw-bold text-dark"></h6>
                        <ul class="small text-muted mb-4">
                            <li><strong>¿Quiénes pueden participar?</strong> Estudiantes, docentes, investigadores y emprendedores podrán participar mediante equipos de hasta 4 integrantes.</li>
                            <li>
                                <strong>Áreas de participación:</strong> Sostenibilidad y ambiente · Tecnología e innovación · Producción y agroindustria ·  Minería sostenible · Economía y negocios · Innovación social y jurídica.
                            </li>
                        </ul>

                        <div class="p-3 bg-light rounded-3 text-center">
                            <p class="small text-muted mb-2">Descarga el formato obligatorio para la propuesta:</p>
                            <a href="documentos/Plantilla_Feria_Emprendimientos_SMART4GREEN_2026.docx"
                               class="btn btn-outline-success btn-sm"
                               download>
                                <i class="fa-solid fa-file-pdf me-1"></i> Descargar Formato
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Inscripción mediante Google Forms: allí se recopilan los datos y el PDF. -->
                <div class="col-lg-7" data-aos="fade-left">
                    <div class="bg-white p-4 p-md-5 rounded-4 shadow-sm h-100 d-flex flex-column justify-content-center">
                        <span class="badge bg-success align-self-start mb-3">Inscripciones abiertas</span>
                        <h4 class="fw-bold mb-3">Inscripción a la Feria de Emprendimientos</h4>
                        <p class="text-muted mb-3">Completa el formulario de inscripción y adjunta tu propuesta ejecutiva en PDF.</p>
                        <p class="small text-muted mb-4">La propuesta se entrega dentro del formulario. Para subir el archivo, Google puede solicitar que inicies sesión con tu cuenta.</p>
                        <a href="https://forms.gle/fv8FkEfTR3pD16yw5" target="_blank" rel="noopener noreferrer" class="btn btn-custom-primary btn-lg align-self-start">
                            <i class="fa-solid fa-arrow-up-right-from-square me-2"></i> Inscribirme en la Feria
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- PROGRAMA DEL EVENTO -->
    <section id="programa" class="py-5 bg-white">
        <div class="container py-4">
            <div class="section-header" data-aos="fade-up">
                <span class="section-subtitle">17 de noviembre de 2026 · Hora de Ecuador</span>
                <h2 class="section-title">Programa del Evento</h2>
                <p class="text-muted mt-3">Conferencias y ponencias científicas modalidad híbrida. La feria de emprendimientos se realizará en paralelo, de 09h00 a 13h00, en modalidad presencial. Lugar por confirmar.</p>
            </div>
            <div class="list-group max-w-800 mx-auto" aria-label="Programa del 17 de noviembre">
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-success">09h00–09h20</span><strong>Keynote 1</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-success">09h30–09h50</span><strong>Keynote 2</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-success">10h00–10h20</span><strong>Keynote 3</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-primary">10h30–10h50</span><strong>Paper 1</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-primary">11h00–11h20</span><strong>Paper 2</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-primary">11h30–11h50</span><strong>Paper 3</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-primary">12h00–12h20</span><strong>Paper 4</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-secondary">12h30–14h00</span><strong>Almuerzo libre</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-primary">14h00–14h20</span><strong>Paper 5</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-primary">14h30–14h50</span><strong>Paper 6</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-primary">15h00–15h20</span><strong>Paper 7</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-primary">16h30–16h50</span><strong>Paper 8</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-primary">17h00–17h20</span><strong>Paper 9</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-primary">17h30–17h50</span><strong>Paper 10</strong></div>
                    <div class="list-group-item p-3 d-flex flex-wrap align-items-center gap-2"><span class="badge bg-dark">18h00</span><strong>Cierre del evento</strong></div>
            </div>
        </div>
    </section>

    <!-- ESTADÍSTICAS ANIMADAS -->
    <section class="stats-section">
        <div class="container">
            <div class="row text-center g-4">
                <div class="col-6 col-md-3">
                    <div class="stat-number" data-target="250">0</div>
                    <div class="fw-semibold">Participantes</div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="stat-number" data-target="10">0</div>
                    <div class="fw-semibold">Instituciones Participantes</div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="stat-number" data-target="4">0</div>
                    <div class="fw-semibold">Países Representados</div>
                </div>
                <div class="col-6 col-md-3">
                    <div class="stat-number" data-target="20">0</div>
                    <div class="fw-semibold">Artículos & Emprendimientos</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ORGANIZADORES & REDES -->
    <section class="py-5">
        <div class="container py-4">
            <div class="section-header" data-aos="fade-up">
                <span class="section-subtitle">Respaldo Institucional</span>
                <h2 class="section-title">Organizadores y Redes Académicas</h2>
            </div>
            <!-- Guarde los logos en assets/logos/ con los nombres indicados en cada src. -->
            <h3 class="h4 fw-bold text-center mt-5 mb-4">Institución organizadora</h3>
            <div class="row g-4 justify-content-center">
                <div class="col-md-6 col-lg-5" data-aos="zoom-in">
                    <article class="partner-card">
                        <div class="partner-logo-box">
                            <img src="assets/logos/espoch.png" alt="Logo de Escuela Superior Politécnica de Chimborazo (ESPOCH)" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-university" aria-hidden="true"></i>
                        </div>
                        <h4 class="h5 fw-bold">Escuela Superior Politécnica de Chimborazo (ESPOCH)</h4>
                        <p class="small text-muted mb-0">Sede Morona Santiago</p>
                    </article>
                </div>
            </div>
            <h3 class="h4 fw-bold text-center mt-5 mb-4">Proyectos participantes</h3>
            <div class="row g-4 justify-content-center">
                <div class="col-md-6 col-lg-6" data-aos="zoom-in">
                    <article class="partner-card">
                        <div class="partner-logo-box">
                            <img src="assets/logos/AMAZON AIoT FINAL.png" alt="Logo de Proyecto de Investigación" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-diagram-project" aria-hidden="true"></i>
                        </div>
                        <h4 class="h5 fw-bold">Proyecto de Investigación</h4>
                        <p class="small text-muted mb-0">Desarrollo e Implementación de un Sistema Inteligente de Monitoreo de la Calidad Ambiental en Ecosistemas Amazónicos mediante Tecnologías IoT e Inteligencia Artificial.</p>
                    </article>
                </div>
                <div class="col-md-6 col-lg-6" data-aos="zoom-in">
                    <article class="partner-card">
                        <div class="partner-logo-box">
                            <img src="assets/logos/LOGO3.png" alt="Logo de Proyecto de Vinculación" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-seedling" aria-hidden="true"></i>
                        </div>
                        <h4 class="h5 fw-bold">Proyecto de Vinculación</h4>
                        <p class="small text-muted mb-0">Hidroponía Inteligente Amazónica.</p>
                    </article>
                </div>
            </div>
            <h3 class="h4 fw-bold text-center mt-5 mb-4">Redes y Grupos de Investigación</h3>
            <div class="row g-4 justify-content-center">
                <div class="col-md-6 col-lg-4" data-aos="zoom-in">
                    <article class="partner-card">
                        <div class="partner-logo-box">
                            <img src="assets/logos/ramai.jpeg" alt="Logo de Red RAMAI" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-network-wired" aria-hidden="true"></i>
                        </div>
                        <h4 class="h5 fw-bold">Red RAMAI</h4>
                        <p class="small text-muted mb-0">Red Agropecuaria, Medio Ambiente e Inteligencia Artificial</p>
                    </article>
                </div>
                <div class="col-md-6 col-lg-4" data-aos="zoom-in">
                    <article class="partner-card">
                        <div class="partner-logo-box">
                            <img src="assets/logos/iitms.png" alt="Logo de IITMS" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-microscope" aria-hidden="true"></i>
                        </div>
                        <h4 class="h5 fw-bold">IITMS</h4>
                        <p class="small text-muted mb-0">Grupo de Investigación Innovación y Tecnología Morona Santiago</p>
                    </article>
                </div>
                <div class="col-md-6 col-lg-4" data-aos="zoom-in">
                    <article class="partner-card">
                        <div class="partner-logo-box">
                            <img src="assets/logos/AMAZON AIoT FINAL.png" alt="Logo de AMAZONAIOT" onload="this.nextElementSibling.hidden=true" onerror="this.style.display='none'">
                            <i class="fa-solid fa-microchip" aria-hidden="true"></i>
                        </div>
                        <h4 class="h5 fw-bold">AMAZONAIOT</h4>

                    </article>
                </div>
            </div>
            <!-- Patrocinadores: sustituya los archivos en assets/logos/ por los logos oficiales. -->
            <!-- EMPRESAS PATROCINADORAS -->
            <div class="mt-5" data-aos="fade-up">
                <div class="text-center mb-4">
                    <span class="section-subtitle">Patrocinio</span>
                    <h3 class="h4 fw-bold">Empresas patrocinadoras</h3>
                </div>

                <div class="row g-4 justify-content-center">

                    <!-- NEOIA -->
                    <div class="col-sm-6 col-lg-3">
                        <a href="https://URL-OFICIAL-DE-NEOIA"
                           target="_blank"
                           rel="noopener noreferrer"
                           class="text-decoration-none text-reset d-block h-100">
                            <article class="partner-card">
                                <div class="partner-logo-box">
                                    <img src="assets/logos/neoia.png"
                                         alt="Logo de NEOIA"
                                         onload="this.nextElementSibling.hidden=true"
                                         onerror="this.style.display='none'">
                                    <i class="fa-solid fa-handshake" aria-hidden="true"></i>
                                </div>
                                <h4 class="h5 fw-bold mb-0">NEOIA</h4>
                            </article>
                        </a>
                    </div>

                    <!-- ELECTROSTORE -->
                    <div class="col-sm-6 col-lg-3">
                        <a href="https://www.grupoelectrostore.com/"
                           target="_blank"
                           rel="noopener noreferrer"
                           class="text-decoration-none text-reset d-block h-100">
                            <article class="partner-card">
                                <div class="partner-logo-box">
                                    <img src="assets/logos/electrostore.svg"
                                         alt="Logo de Electrostore"
                                         onload="this.nextElementSibling.hidden=true"
                                         onerror="this.style.display='none'">
                                    <i class="fa-solid fa-handshake" aria-hidden="true"></i>
                                </div>
                                <h4 class="h5 fw-bold mb-0">Electrostore</h4>
                            </article>
                        </a>
                    </div>

                    <!-- DRON -->
                    <div class="col-sm-6 col-lg-3">
                        <a href="https://URL-OFICIAL-DE-DRON"
                           target="_blank"
                           rel="noopener noreferrer"
                           class="text-decoration-none text-reset d-block h-100">
                            <article class="partner-card">
                                <div class="partner-logo-box">
                                    <img src="assets/logos/dron.png"
                                         alt="Logo de DRON"
                                         onload="this.nextElementSibling.hidden=true"
                                         onerror="this.style.display='none'">
                                    <i class="fa-solid fa-handshake" aria-hidden="true"></i>
                                </div>
                                <h4 class="h5 fw-bold mb-0">DRON</h4>
                            </article>
                        </a>
                    </div>

                    <!-- MICROCIRCUITOS -->
                    <div class="col-sm-6 col-lg-3">
                        <a href="https://www.pcbmicrocircuitos.com/en"
                           target="_blank"
                           rel="noopener noreferrer"
                           class="text-decoration-none text-reset d-block h-100">
                            <article class="partner-card">
                                <div class="partner-logo-box">
                                    <img src="assets/logos/Microcircuitos SAS.png"
                                         alt="Logo de Microcircuitos"
                                         onload="this.nextElementSibling.hidden=true"
                                         onerror="this.style.display='none'">
                                    <i class="fa-solid fa-handshake" aria-hidden="true"></i>
                                </div>
                                <h4 class="h5 fw-bold mb-0">Microcircuitos</h4>
                            </article>
                        </a>
                    </div>

                </div>
            </div>

</section>

    <!-- CONTACTO Y MAPA -->
    <section id="contacto" class="py-5">
        <div class="container py-4">
            <div class="row g-5">
                <div class="col-lg-6" data-aos="fade-right">
                    <span class="section-subtitle">Canales Oficiales</span>
                    <h2 class="section-title text-start mb-4">Contáctate con Nosotros</h2>
                    <p class="text-muted mb-4">Si tienes dudas sobre el envío de manuscritos o la postulación de emprendimientos, escríbenos a los correos institucionales.</p>
                    
                    <div class="d-flex align-items-center mb-3">
                        <i class="fa-solid fa-envelope text-primary fs-4 me-3"></i>
                        <div>
                            <strong>Correos Electrónicos:</strong><br>
                            <span class="text-muted small">macarena.flores@espoch.edu.ec | carlav.haro@espoch.edu.ec | juanpablo.haro@espoch.edu.ec</span>
                        </div>
                    </div>

                    <div class="d-flex align-items-center mb-4">
                        <i class="fa-brands fa-facebook text-primary fs-4 me-3"></i>
                        <div>
                            <strong>Facebook Oficial:</strong><br>
                            <a href="https://www.facebook.com/espochms?locale=es_LA" target="_blank" rel="noopener" class="text-decoration-none">ESPOCH Sede Morona Santiago</a>
                        </div>
                    </div>

                    <div class="p-3 bg-white rounded border">
                        <h6 class="fw-bold mb-2"><i class="fa-solid fa-location-dot me-2 text-danger"></i>Ubicación Sede</h6>
                        <p class="small text-muted mb-0">Macas, Morona Santiago, Ecuador — Escuela Superior Politécnica de Chimborazo.</p>
                    </div>
                </div>

                <div class="col-lg-6" data-aos="fade-left">
                    <div class="bg-white p-4 rounded-4 shadow-sm">
                        <h4 class="fw-bold mb-3">Enviar Mensaje Directo</h4>
                        <form id="formContacto" novalidate>
                            <div class="mb-3">
                                <label class="form-label fw-semibold">Nombre Completo</label>
                                <input type="text" class="form-control" required placeholder="Tu nombre">
                            </div>
                            <div class="mb-3">
                                <label class="form-label fw-semibold">Correo Electrónico</label>
                                <input type="email" class="form-control" required placeholder="tu@correo.com">
                            </div>
                            <div class="mb-3">
                                <label class="form-label fw-semibold">Asunto</label>
                                <input type="text" class="form-control" required placeholder="Consulta sobre manuscritos / evento">
                            </div>
                            <div class="mb-3">
                                <label class="form-label fw-semibold">Mensaje</label>
                                <textarea class="form-control" rows="4" required placeholder="Escribe tu mensaje..."></textarea>
                            </div>
                            <button type="submit" class="btn btn-custom-secondary w-100">Enviar Consulta</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-dark text-white pt-5 pb-3">
        <div class="container">
            <div class="row g-4 border-bottom border-secondary pb-4">
                <div class="col-md-6">
                    <h5 class="fw-bold text-success mb-2">SMART4GREEN 2026</h5>
                    <p class="small text-light opacity-75">I Seminario Multidisciplinario de Innovación para el Desarrollo Sostenible. ESPOCH Sede Morona Santiago.</p>
                </div>
                <div class="col-md-6 text-md-end">
                    <p class="small mb-1">Indexación e Investigación:</p>
                    <span class="badge bg-secondary me-1">ERIHPLUS</span>
                    <span class="badge bg-secondary me-1">Google Schoolar</span>
                    <span class="badge bg-secondary">ISSN 2953-6367</span>
                </div>
            </div>
            <div class="text-center pt-3 small text-light opacity-50">
                &copy; 2026 SMART4GREEN. Todos los derechos reservados. Desarrollado para la Escuela Superior Politécnica de Chimborazo.
            </div>
        </div>
    </footer>

    <!-- BOTÓN DE WHATSAPP FLOTANTE -->
    <a href="https://wa.me/593996381808?text=Hola,%20deseo%20información%20sobre%20SMART4GREEN%202026" class="whatsapp-float" target="_blank" rel="noopener" aria-label="Contacto por WhatsApp">
        <i class="fa-brands fa-whatsapp"></i>
    </a>

    <!-- VOLVER ARRIBA -->
    <a href="#inicio" class="back-to-top" id="backToTop" aria-label="Volver arriba">
        <i class="fa-solid fa-arrow-up"></i>
    </a>

    <!-- MODALES -->
    <!-- Modal Paper Submission -->
    <div class="modal fade" id="modalSubmitPaper" tabindex="-1" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-heading fw-bold">Envío de Manuscrito Científico</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body small">
                    <p>Para enviar su manuscrito, asegúrese de cumplir con la plantilla oficial y remitir los 3 documentos requeridos en formato digital a los correos oficializados:</p>
                    <div class="p-2 bg-light rounded mb-3">
                        <code>investigo@istra.edu.ec</code><br>
                        <code>macarena.flores@espoch.edu.ec</code><br>
                        <code>carlav.haro@espoch.edu.ec</code>
                    </div>
                    <p class="fw-bold mb-1">Documentos adjuntos obligatorios:</p>
                    <ol>
                        <li>Artículo Científico (Word y PDF).</li>
                        <li>Ficha de información para autores.</li>
                        <li>Declaración de originalidad y cesión de derechos.</li>
                    </ol>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary btn-sm" data-bs-dismiss="modal">Cerrar</button>
                </div>
            </div>
        </div>
    </div>

    <!-- Bootstrap 5.3 JS Bundle -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    
    <!-- AOS Library -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>

    <!-- Custom Script ES6 -->
    <script>
        // AOS Animation Initialization
        AOS.init({
            duration: 800,
            once: true
        });

        // Countdown Timer Logic
        const targetDate = new Date('2026-11-17T09:00:00-05:00').getTime();

        function updateCountdown() {
            const now = new Date().getTime();
            const difference = targetDate - now;

            if (difference > 0) {
                const days = Math.floor(difference / (1000 * 60 * 60 * 24));
                const hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                const minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((difference % (1000 * 60)) / 1000);

                document.getElementById('days').innerText = days < 10 ? '0' + days : days;
                document.getElementById('hours').innerText = hours < 10 ? '0' + hours : hours;
                document.getElementById('minutes').innerText = minutes < 10 ? '0' + minutes : minutes;
                document.getElementById('seconds').innerText = seconds < 10 ? '0' + seconds : seconds;
            }
        }
        setInterval(updateCountdown, 1000);
        updateCountdown();

        // Statistics Counter Animation
        let animated = false;
        window.addEventListener('scroll', () => {
            const statsSection = document.querySelector('.stats-section');
            if (!statsSection) return;
            const position = statsSection.getBoundingClientRect().top;
            const screenPosition = window.innerHeight / 1.3;

            if (position < screenPosition && !animated) {
                const counters = document.querySelectorAll('.stat-number');
                counters.forEach(counter => {
                    const target = +counter.getAttribute('data-target');
                    let count = 0;
                    const speed = target / 50;

                    const updateCount = () => {
                        count += speed;
                        if (count < target) {
                            counter.innerText = Math.ceil(count);
                            setTimeout(updateCount, 30);
                        } else {
                            counter.innerText = target + '+';
                        }
                    };
                    updateCount();
                });
                animated = true;
            }

            // Scroll to top button visibility
            const backToTop = document.getElementById('backToTop');
            if (window.scrollY > 300) {
                backToTop.classList.add('active');
            } else {
                backToTop.classList.remove('active');
            }
        });

        // Form Validation Handling
        document.querySelectorAll('form').forEach(form => {
            form.addEventListener('submit', function (event) {
                if (!form.checkValidity()) {
                    event.preventDefault();
                    event.stopPropagation();
                } else {
                    event.preventDefault();
                    alert('¡Formulario enviado correctamente! Nos pondremos en contacto pronto.');
                    form.reset();
                }
                form.classList.add('was-validated');
            });
        });
    </script>
</body>
</html>
