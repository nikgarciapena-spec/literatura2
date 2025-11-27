<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Recorrido por la cultura y literatura a través del tiempo">
  <meta name="author" content="Cultura y Literatura">
  <title>Cultura y Literatura a Través del Tiempo</title>

  <!-- Favicon (reemplaza por tu favicon real) -->
  <link rel="icon" href="/favicon.ico">

  <!-- Structured data básico -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "Cultura y Literatura",
    "url": "https://example.org",
    "description": "Recorrido por la cultura y literatura a través del tiempo"
  }
  </script>

  <style>
    :root{
      --primary:#007bff;
      --bg:#f6f9fc;
      --text:#343a40;
      --card-bg:#ffffff;
      --accent:#555;
      --radius:8px;
      --max-width:900px;
    }

    html,body{height:100%}
    body {
      font-family: 'Arial', sans-serif;
      line-height: 1.6;
      margin: 0;
      background-color: var(--bg);
      color: var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }

    a.skip-link{
      position:absolute;
      left:-999px;
      top:auto;
      width:1px;
      height:1px;
      overflow:hidden;
    }
    a.skip-link:focus{
      left:10px;
      top:10px;
      width:auto;
      height:auto;
      padding:8px 12px;
      background:#000;
      color:#fff;
      z-index:1000;
      border-radius:4px;
      text-decoration:none;
    }

    header {
      background-color: var(--primary);
      color: white;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }
    nav { margin-top:10px; }
    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 15px;
      margin:0;
      flex-wrap:wrap;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding:6px 10px;
      border-radius:4px;
    }
    nav a:focus, nav a:hover{
      background: rgba(255,255,255,0.12);
      outline: 2px solid rgba(255,255,255,0.15);
      outline-offset:2px;
    }

    main { padding: 20px; }
    article {
      background: var(--card-bg);
      margin: 20px auto;
      padding: 20px;
      border-radius: var(--radius);
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.06);
      max-width: var(--max-width);
    }
    h1{margin:0}
    h2 {
      color: var(--primary);
      border-bottom: 2px solid var(--primary);
      padding-bottom: 10px;
    }
    h3 { color: var(--accent); margin-top: 15px; }
    figure{margin:12px 0}
    img {
      width:100%;
      height:auto;
      border-radius:5px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.12);
      display:block;
    }
    figcaption{ font-size:0.9rem; color:#666; margin-top:6px; }
    footer {
      text-align: center;
      padding: 20px;
      background-color: var(--primary);
      color: white;
    }
    @media (max-width: 600px) {
      h1 { font-size: 1.6rem; }
      nav ul { flex-direction: column; gap:8px; align-items:center; }
      article{margin:12px;}
    }
  </style>
</head>
<body>
  <a class="skip-link" href="#main-content">Saltar al contenido</a>

  <header role="banner">
    <h1>Cultura y Literatura a Través del Tiempo</h1>
    <p>Un recorrido por las obras maestras de la humanidad</p>
    <nav aria-label="Navegación principal">
      <ul>
        <li><a href="#unidad1">Antigua</a></li>
        <li><a href="#unidad2">Griega</a></li>
        <li><a href="#unidad3">Medieval</a></li>
        <li><a href="#unidad4">Realismo</a></li>
        <li><a href="#unidad5">1900-1950 Narrativa</a></li>
        <li><a href="#unidad6">1900-1950 Poesía</a></li>
      </ul>
    </nav>
  </header>

  <main id="main-content" role="main">
    <article id="unidad1" aria-labelledby="u1-title">
      <h2 id="u1-title">Unidad 1: Literatura Antigua</h2>

      <section aria-labelledby="india-title">
        <h3 id="india-title">Literatura India</h3>
        <figure>
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/4/46/Mahabharata_artwork.jpg"
            alt="Ilustración tradicional del Mahabharata"
            loading="lazy"
            width="1200"
            height="800"
            srcset="https://upload.wikimedia.org/wikipedia/commons/4/46/Mahabharata_artwork.jpg 1200w"
            sizes="(max-width:600px) 100vw, 800px">
          <figcaption>Ilustración tradicional asociada al Mahabharata</figcaption>
        </figure>
        <p>El <strong>Mahabharata</strong> es un poema épico que narra la historia de dos familias en conflicto. Es una de las obras más extensas y relevantes de la literatura india antigua, con aportes religiosos, filosóficos y culturales que han influido en numerosas tradiciones y obras posteriores.</p>
      </section>

      <section aria-labelledby="china-title">
        <h3 id="china-title">Literatura China</h3>
        <figure>
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Li_Bai_in_Garden.jpg"
            alt="Retrato tradicional de Li Bai, poeta chino clásico"
            loading="lazy"
            width="1200"
            height="800"
            srcset="https://upload.wikimedia.org/wikipedia/commons/4/4b/Li_Bai_in_Garden.jpg 1200w"
            sizes="(max-width:600px) 100vw, 800px">
          <figcaption>Retrato tradicional de Li Bai</figcaption>
        </figure>
        <p>La poesía china clásica es rica y variada, con poetas como <strong>Li Bai</strong> y <strong>Du Fu</strong> que marcaron estilos y escuelas literarias.</p>
      </section>

      <section aria-labelledby="hebreo-title">
        <h3 id="hebreo-title">Literatura Hebrea</h3>
        <figure>
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/d/db/Bible_drawn_by_Edward_Auslander.jpg"
            alt="Ilustración antigua representando manuscritos bíblicos"
            loading="lazy"
            width="1200"
            height="800"
            srcset="https://upload.wikimedia.org/wikipedia/commons/d/db/Bible_drawn_by_Edward_Auslander.jpg 1200w"
            sizes="(max-width:600px) 100vw, 800px">
          <figcaption>Ilustración antigua de manuscritos bíblicos</figcaption>
        </figure>
        <p>La <strong>Biblia</strong> es un texto sagrado con enorme influencia cultural y literaria, tanto en tradiciones religiosas como en la literatura occidental.</p>
      </section>
    </article>

    <article id="unidad2" aria-labelledby="u2-title">
      <h2 id="u2-title">Unidad 2: Literatura Griega</h2>
      <section aria-labelledby="epica-title">
        <h3 id="epica-title">Poesía Épica</h3>
        <figure>
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/4/42/Homer_Singing_the_Iliad.jpg"
            alt="Representación de Homero recitando la Ilíada"
            loading="lazy"
            width="1200"
            height="800">
          <figcaption>Homero recitando la Ilíada (representación artística)</figcaption>
        </figure>
        <p>El poeta más importante de la literatura épica griega fue <strong>Homero</strong>, autor de la <em>Ilíada</em> y la <em>Odisea</em>, pilares de la tradición occidental.</p>
      </section>
    </article>

    <article id="unidad3" aria-labelledby="u3-title">
      <h2 id="u3-title">Unidad 3: Literatura Medieval y Prerrenacentista</h2>
      <section aria-labelledby="cid-title">
        <h3 id="cid-title">Cantar de Mío Cid</h3>
        <figure>
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/c/cb/Cantar_de_Mio_Cid.jpg"
            alt="Fragmento del manuscrito del Cantar de Mío Cid"
            loading="lazy"
            width="1200"
            height="800">
          <figcaption>Manuscrito medieval del <em>Cantar de Mío Cid</em></figcaption>
        </figure>
        <p>El <strong>Cantar de Mío Cid</strong> es la gesta épica castellana más conocida y un documento fundamental para estudiar la épica medieval en español.</p>
      </section>
    </article>

    <article id="unidad4" aria-labelledby="u4-title">
      <h2 id="u4-title">Unidad 4: Realismo y Simbolismo</h2>
      <section aria-labelledby="realismo-title">
        <h3 id="realismo-title">Realismo</h3>
        <figure>
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/1/12/Realismo_en_literatura.jpg"
            alt="Ilustración asociada al realismo literario"
            loading="lazy"
            width="1200"
            height="800">
          <figcaption>Representación artística del realismo</figcaption>
        </figure>
        <p>El realismo busca retratar la vida cotidiana con precisión y veracidad, enfocándose en los detalles sociales y psicológicos.</p>
      </section>

      <section aria-labelledby="simbolismo-title">
        <h3 id="simbolismo-title">Simbolismo</h3>
        <figure>
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/5/55/Edouard_Manet_-_Luncheon_in_the_Park_%28Le_Pique-nique%29.jpg"
            alt="Obra de Manet relacionada con el simbolismo"
            loading="lazy"
            width="1200"
            height="800">
          <figcaption>Obra relacionada por afinidad con corrientes simbólicas</figcaption>
        </figure>
        <p>El simbolismo se caracteriza por la búsqueda de significados más allá de lo visible y por el uso de imágenes sugestivas.</p>
      </section>
    </article>

    <article id="unidad5" aria-labelledby="u5-title">
      <h2 id="u5-title">Unidad 5: Literatura entre 1900 y 1950 (Narrativa)</h2>
      <figure>
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/d/d2/Marcel_Proust_1910_Benjamin_Constant_painting.jpg"
          alt="Retrato de Marcel Proust"
          loading="lazy"
          width="1200"
          height="800">
        <figcaption>Marcel Proust, figura clave en la narrativa moderna</figcaption>
      </figure>
      <p>Durante la primera mitad del siglo XX, la narrativa experimentó un extraordinario desarrollo con nuevas técnicas temporales y psicológicas.</p>
    </article>

    <article id="unidad6" aria-labelledby="u6-title">
      <h2 id="u6-title">Unidad 6: Literatura entre 1900 y 1950 (Poesía y Teatro)</h2>
      <figure>
        <img
          src="https://img.freepik.com/foto-gratis/mascara-teatro-cortina-roja_1446-280.jpg"
          alt="Máscara teatral sobre cortina roja"
          loading="lazy"
          width="1200"
          height="800">
        <figcaption>Teatro y representación escénica en el siglo XX</figcaption>
      </figure>
      <p>La vanguardia literaria desafió las normas establecidas y renovó tanto la poesía como el teatro en el siglo XX.</p>
    </article>
  </main>

  <footer role="contentinfo" aria-label="Pie de página">
    <p>&copy; 2025 Cultura y Literatura. Todos los derechos reservados.</p>
  </footer>

  <!-- SUGERENCIAS:
       - Optimizar imágenes: generar WebP/AVIF y tamaños (1200/800/480) y actualizar srcset.
       - Mover CSS a un archivo externo (styles.min.css) y servirlo con cache headers.
       - Añadir favicon real y manifest si quieres PWA básico.
       - Ejecutar Lighthouse y pruebas de accesibilidad (axe/Lighthouse).
       - Considerar internacionalización si vas a soportar más idiomas.
  -->
</body>
</html>
