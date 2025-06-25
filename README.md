<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>J&M | Educación e Ingeniería</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --azul-oscuro: #002244;
      --azul: #0059b3;
      --amarillo: #ffcc00;
      --blanco: #ffffff;
      --gris: #f4f4f4;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--gris);
      color: #333;
    }

    header {
      background: var(--azul-oscuro);
      padding: 15px 30px;
      color: var(--blanco);
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    header img {
      height: 50px;
    }

    nav a {
      color: var(--blanco);
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: var(--amarillo);
    }

    .hero {
      background: linear-gradient(to right, var(--azul-oscuro), var(--azul));
      color: var(--blanco);
      text-align: center;
      padding: 80px 20px;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .btn {
      background: var(--amarillo);
      color: var(--azul-oscuro);
      padding: 12px 25px;
      border-radius: 30px;
      font-weight: bold;
      text-decoration: none;
    }

    .section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }

    .section h2 {
      text-align: center;
      color: var(--azul);
      font-size: 2.4rem;
      margin-bottom: 40px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: var(--blanco);
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    .card h3 {
      color: var(--azul);
      margin-bottom: 10px;
    }

    .card p {
      font-size: 0.95rem;
    }

    .card ul {
      list-style: none;
      padding-left: 0;
    }

    .footer {
      background: var(--azul-oscuro);
      color: var(--blanco);
      text-align: center;
      padding: 50px 20px;
    }

    .footer a {
      color: var(--amarillo);
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo-jym-sac-white.png" alt="Logo J&M">
    <nav>
      <a href="#servicios">Servicios</a>
      <a href="#capacitaciones">Capacitaciones</a>
      <a href="#proyectos">Proyectos</a>
      <a href="#equipo">Nosotros</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Conoce nuestros Servicios y Capacitaciones</h1>
    <p>Brindamos los mejores servicios a nivel nacional con ingeniería, capacitación y compromiso.</p>
    <a href="#servicios" class="btn">Descubrir más</a>
  </section>

  <section class="section" id="servicios">
    <h2>Nuestros Servicios</h2>
    <div class="grid">
      <div class="card">
        <h3>Proyectos Eléctricos</h3>
        <p>Diseño y ejecución de proyectos eléctricos de baja tensión.</p>
      </div>
      <div class="card">
        <h3>Sistema de Energía Renovable</h3>
        <p>Instalación y mantenimiento de sistemas fotovoltaicos modernos.</p>
      </div>
      <div class="card">
        <h3>Digitalización de Documentos</h3>
        <p>Transformación de archivos físicos a formatos digitales seguros.</p>
      </div>
      <div class="card">
        <h3>Capacitaciones Especializadas</h3>
        <p>Programas técnicos adaptados a cada industria.</p>
      </div>
    </div>
  </section>

  <section class="section" id="capacitaciones">
    <h2>Capacitaciones Técnicas</h2>
    <div class="grid">
      <div class="card">
        <h3>Sistemas Fotovoltaicos</h3>
        <p>Curso de 40 horas desde la teoría a la instalación práctica.</p>
      </div>
      <div class="card">
        <h3>Interconexión y Almacenamiento</h3>
        <p>Especialízate en baterías y conexión a red en 32 horas.</p>
      </div>
      <div class="card">
        <h3>Diseño de Cerco Eléctrico</h3>
        <p>Capacitación de 24 horas sobre sistemas de protección.</p>
      </div>
      <div class="card">
        <h3>Electricidad Básica</h3>
        <p>Formación esencial en normativas y seguridad eléctrica.</p>
      </div>
    </div>
  </section>

  <section class="section" id="equipo">
    <h2>Todo en una solución</h2>
    <p style="text-align:center; max-width:800px; margin:auto; font-size:1.1rem;">¿Tienes algún proyecto en mente? <strong>J&M</strong> brinda servicios de óptima calidad satisfaciendo todas las necesidades y expectativas del cliente.</p>
    <br><br>
    <div class="grid">
      <div class="card">
        <h3>Misión</h3>
        <p>Brindar servicios de instalación, mantenimiento y reparación en el sector eléctrico, y capacitación en energías renovables. Promovemos tecnologías sostenibles para beneficio ambiental y social.</p>
      </div>
      <div class="card">
        <h3>Visión</h3>
        <p>Ser líderes nacionales en formación técnica y servicios eléctricos, promoviendo prácticas sostenibles y tecnologías limpias.</p>
      </div>
      <div class="card">
        <h3>Nuestro Equipo</h3>
        <p>Compuesto por profesionales altamente capacitados, con experiencia en proyectos y capacitaciones técnicas. Comprometidos con la calidad, seguridad y sostenibilidad.</p>
      </div>
    </div>
  </section>

  <section class="footer" id="contacto">
    <h2>Contáctanos</h2>
    <p>¿Deseas más información? Envíanos un mensaje, estaremos gustosos de atenderte.</p>
    <p><strong>Email:</strong> capacitate@asociadosjym.com | ventas@asociadosjym.com</p>
    <p><strong>Teléfono:</strong> +51 925665530</p>
    <p><strong>Dirección:</strong> Horacio Zevallos Mz C Lt 5 Grp L - Ate Vitarte, Lima</p>
    <p style="margin-top:30px; font-size:0.9rem;">© 2025 J&M. Todos los derechos reservados.</p>
  </section>
</body>
</html>
