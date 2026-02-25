<!DOCTYPE html>
<html lang="ca">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laia Artés — Portafoli</title>
    <style>
        body {
            font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
            margin: 0;
            display: flex;
            color: #333;
            line-height: 1.4;
        }
        /* Panell Lateral Fix */
        nav {
            width: 25%;
            padding: 2rem;
            position: fixed;
            height: 100vh;
            border-right: 1px solid #eee;
        }
        nav a { text-decoration: none; color: black; display: block; margin-bottom: 0.5rem; }
        
        /* Contingut Principal */
        main {
            margin-left: 25%;
            width: 75%;
            padding: 2rem;
        }
        .project {
            display: flex;
            gap: 2rem;
            margin-bottom: 5rem;
            align-items: flex-start;
        }
        .project-info { flex: 1; }
        .project-media { flex: 2; }
        
        img, video { width: 100%; height: auto; display: block; margin-bottom: 1rem; }
        
        @media (max-width: 768px) {
            body { flex-direction: column; }
            nav { position: relative; width: 100%; height: auto; border-right: none; border-bottom: 1px solid #eee; }
            main { margin-left: 0; width: 100%; }
            .project { flex-direction: column; }
        }
    </style>
</head>
<body>

    <nav>
        <strong>Laia Artés</strong>
        <br><br>
        <a href="#sobre-mi">Sobre mi</a>
        <a href="mailto:laiaartseb@gmail.com">Email</a>
    </nav>

    <main>
        <section class="project">
            <div class="project-info">
                <h3>Vertigo Vida</h3>
                <p>Disseny de gràfica i estratègia de XXSS, campanya Meta Ads, disseny web i shooting.</p>
                <span>02/2026</span>
            </div>
            <div class="project-media">
                <video autoplay loop muted playsinline src="mockup-redes.mp4"></video>
            </div>
        </section>

        <section class="project">
            <div class="project-info">
                <h3>Protocol Consell Joventut Barcelona</h3>
                <p>Disseny i maquetació</p>
                <span>09/2025</span>
            </div>
            <div class="project-media">
                <img src="portada-fontana.png" alt="Protocol CJB">
            </div>
        </section>

        </main>

</body>
</html>
