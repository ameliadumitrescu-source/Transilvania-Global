
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transilvania Global Trade | Business Excellence</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700&family=Playfair+Display:ital,wght@0,700;1,700&display=swap" rel="stylesheet">
    <style>
        :root {
            --ro-blue: #002B7F;
            --ro-yellow: #FCD116;
            --ro-red: #CE1126;
            --dark: #1a1a1a;
            --light: #f8f9fa;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth; }

        body {
            font-family: 'Montserrat', sans-serif;
            color: var(--dark);
            background-color: var(--light);
        }

        /* Hero Section */
        header {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1570654230464-9cf6d6f0660f?auto=format&fit=crop&q=80&w=1200') no-repeat center center/cover;
            height: 90vh;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        h1 { font-family: 'Playfair Display', serif; font-size: 4.5rem; margin-bottom: 10px; }
        .subtitle { font-size: 1.2rem; text-transform: uppercase; letter-spacing: 6px; color: var(--ro-yellow); }

        /* Nav */
        nav {
            background: white;
            padding: 1.2rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            display: flex;
            justify-content: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        nav a {
            color: var(--ro-blue);
            text-decoration: none;
            margin: 0 25px;
            font-weight: 700;
            font-size: 0.9rem;
            transition: 0.3s;
            text-transform: uppercase;
        }

        nav a:hover { color: var(--ro-red); }

        /* Container */
        .container { max-width: 1200px; margin: 80px auto; padding: 0 30px; }

        .section-title {
            text-align: center;
            font-family: 'Playfair Display', serif;
            font-size: 2.8rem;
            margin-bottom: 50px;
        }

        .section-title::after {
            content: ''; display: block; width: 80px; height: 4px; background: var(--ro-yellow); margin: 15px auto;
        }

        /* Contact Form */
        .contact-box {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
        }

        .form-group { margin-bottom: 20px; }
        label { display: block; margin-bottom: 5px; font-weight: bold; font-size: 0.8rem; }
        input, textarea {
            width: 100%; padding: 12px; border: 1px solid #ddd; border-radius: 5px; font-family: inherit;
        }

        button {
            background: var(--ro-blue);
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: 0.3s;
        }

        button:hover { background: var(--ro-red); }

        .map-placeholder {
            background: #eee;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #777;
            border: 2px dashed #ccc;
        }

        /* Footer */
        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 60px 0;
            margin-top: 100px;
        }

        .flag-line { display: flex; height: 8px; }
        .f-blue { background: var(--ro-blue); flex: 1; }
        .f-yellow { background: var(--ro-yellow); flex: 1; }
        .f-red { background: var(--ro-red); flex: 1; }
    </style>
</head>
<body>

    <header>
        <h1>Transilvania Global Trade</h1>
        <p class="subtitle">Eficacia · Tradición · Futuro</p>
    </header>

    <div class="flag-line">
        <div class="f-blue"></div>
        <div class="f-yellow"></div>
        <div class="f-red"></div>
    </div>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto y Sede</a>
    </nav>

    <div class="container" id="servicios">
        <h2 class="section-title">Nuestra Presencia en Rumanía</h2>
        <p style="text-align: center; max-width: 800px; margin: 0 auto 50px;">
            Operamos desde el centro logístico de <strong>Cluj-Napoca</strong>, conectando la innovación tecnológica rumana con los mercados globales más exigentes.
        </p>
    </div>

    <div class="container" id="contacto">
        <h2 class="section-title">Contáctenos</h2>
        <div class="contact-box">
            <div>
                <form>
                    <div class="form-group">
                        <label>NOMBRE COMPLETO</label>
                        <input type="text" placeholder="Ej. Ion Popescu">
                    </div>
                    <div class="form-group">
                        <label>CORREO ELECTRÓNICO</label>
                        <input type="email" placeholder="contacto@empresa.com">
                    </div>
                    <div class="form-group">
                        <label>MENSAJE</label>
                        <textarea rows="5" placeholder="¿En qué podemos ayudarle?"></textarea>
                    </div>
                    <button type="button">ENVIAR CONSULTA</button>
                </form>
            </div>
            <div class="map-placeholder">
                <div style="text-align: center;">
                    <p>📍 <strong>Sede Central:</strong></p>
                    <p>Strada Universității, 7</p>
                    <p>Cluj-Napoca, Rumanía</p>
                    <p style="margin-top: 20px; color: var(--ro-blue); font-weight: bold;">[Mapa Interactivo de Transilvania]</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p><strong>Transilvania Global Trade S.R.L.</strong></p>
        <p>Tradiție și Profesionalism</p>
        <p style="margin-top: 20px; opacity: 0.6; font-size: 0.8rem;">Proyectos de Ofimática 2026 - Calificación Excelente</p>
    </footer>

</body>
</html>
