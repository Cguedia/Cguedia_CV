<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Cristóbal Guerrero Díaz - CV</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;800&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    :root{
      --blue:#124872;
      --light-blue:#1b5b88;
      --muted:#6b7280;
      --card-bg:#f4f6f8;
      --accent:#0b3b5a;
    }
    *{box-sizing:border-box}
    body{font-family:'Open Sans',system-ui,Segoe UI,Arial; margin:0;background:#fff;color:#222}
    .container{max-width:920px;margin:24px auto;box-shadow:0 6px 24px rgba(2,6,23,0.12);display:grid;grid-template-columns:320px 1fr}
    /* left column */
    .left{background:linear-gradient(180deg,var(--blue),var(--light-blue));color:#fff;padding:28px}
    .photo{width:140px;height:140px;border-radius:50%;overflow:hidden;border:8px solid #fff;margin:0 auto 18px;display:block}
    .photo img{width:100%;height:100%;object-fit:cover;display:block}
    h1{font-family:'Montserrat',sans-serif;margin:6px 0 0;font-size:22px;letter-spacing:0.6px}
    h2{font-family:'Montserrat',sans-serif;margin:0;font-size:12px;opacity:0.95}
    .section{background:transparent;margin-top:22px}
    .section h3{font-size:13px;margin:0 0 8px;color:#f1f6fb}
    .icon{display:inline-block;width:34px;height:34px;border-radius:50%;background:rgba(255,255,255,0.12);text-align:center;line-height:34px;margin-right:10px}
    .about{font-size:13px;line-height:1.4;color:#e6eef8}
    .contact-list, .extra-list{list-style:none;padding:0;margin:0;font-size:13px}
    .contact-list li{margin:8px 0;display:flex;align-items:flex-start}
    .contact-list li strong{min-width:88px;display:inline-block;color:#dbeaf9}
    .left-footer{margin-top:22px;font-size:12px;color:#cfe6fb}

    /* right column */
    .right{background:#fff;padding:28px}
    .right-header{display:flex;align-items:center;justify-content:space-between}
    .badge{background:var(--blue);color:#fff;padding:8px 12px;border-radius:6px;font-weight:700}
    .section-title{display:flex;align-items:center;gap:12px;margin-bottom:12px}
    .section-title h3{margin:0;font-family:'Montserrat',sans-serif;color:var(--accent)}
    .edu-item, .job-item{margin-bottom:14px}
    .small{font-size:13px;color:var(--muted)}
    hr{border:none;border-top:1px solid #eee;margin:20px 0}

    /* responsive */
    @media(max-width:780px){
      .container{grid-template-columns:1fr;max-width:560px}
      .left{order:2}
      .right{order:1}
      .photo{margin-bottom:12px}
    }
  </style>
</head>
<body>
  <div class="container">
    <aside class="left">
      <div style="text-align:center">
        <div class="photo"><img src="photo.jpg" alt="Foto Cristóbal"></div>
        <h1>Cristóbal Guerrero Díaz</h1>
        <h2>Desarrollador de Aplicaciones Web</h2>
      </div>

      <div class="section">
        <h3>Acerca de mí</h3>
        <p class="about">Soy un chico joven, organizado y responsable, con buenas relaciones y me encanta el trabajo en equipo. Siempre tengo la mejor disposición para la resolución de mis labores y tengo ambición por aprender. Busco un puesto de trabajo donde aprender en un entorno agradable.</p>
      </div>

      <div class="section">
        <h3>Contacto</h3>
        <ul class="contact-list">
          <li><strong>Teléfono:</strong> 680191354</li>
          <li><strong>Email:</strong> cristobal@correoegmail.com</li>
          <li><strong>Dirección:</strong> Las Rozuelas Nº 20, Loja</li>
        </ul>
      </div>

      <div class="section">
        <h3>Experiencia laboral</h3>
        <ul class="extra-list">
          <li><strong>Prácticas</strong> — P.C Box 2025-2025: Instalación, configuración y mantenimiento de equipos informáticos y periféricos.</li>
        </ul>
      </div>

      <div class="left-footer">Disponible para incorporación inmediata</div>
    </aside>

    <main class="right">
      <div class="right-header">
        <div style="display:flex;flex-direction:column">
          <div style="font-size:14px;color:#374151;font-weight:700">Educación</div>
          <div class="small">Formación académica y profesional</div>
        </div>
        <div class="badge">CV - 2025</div>
      </div>

      <hr>

      <section class="section">
        <div class="section-title"><h3>Educación Secundaria Obligatoria</h3></div>
        <div class="edu-item small">IES Moraiima (Loja) — 2019-2023</div>

        <div class="section-title" style="margin-top:12px"><h3>Formación Profesional</h3></div>
        <div class="edu-item small">Técnico en Sistemas Microinformáticos y Redes — IES Francisco Ayala (Granada) • 2023-2025</div>

        <div class="section-title" style="margin-top:12px"><h3>Grado Superior</h3></div>
        <div class="edu-item small">Desarrollador de aplicaciones en Entornos Web — 2025 - Actualidad</div>
      </section>

      <section class="section">
        <div class="section-title"><h3>Información adicional</h3></div>
        <ul class="extra-list small">
          <li>Inglés básico — comprensión de textos sencillos y vocabulario técnico elemental.</li>
          <li>Carnet de conducir tipo B.</li>
          <li>Vehículo propio y disponibilidad para viajar.</li>
          <li>Incorporación inmediata.</li>
        </ul>
      </section>

      <hr>

      <section class="section">
        <div class="section-title"><h3>Habilidades</h3></div>
        <p class="small">HTML, CSS, JavaScript básico, manejo de sistemas operativos e instalación y mantenimiento de hardware.</p>
      </section>

    </main>
  </div>
</body>
</html>
