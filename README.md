# macoju-web
Sitio web de MACOJU Asesoría en Prevención
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MACOJU Asesoría en Prevención</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Roboto', sans-serif; }
  </style>
</head>
<body class="bg-gray-100 text-gray-800">

  <header class="bg-blue-900 text-white p-6 text-center">
    <img src="logo-macoju.png" alt="Logo MACOJU" class="mx-auto w-32 mb-4">
    <h1 class="text-3xl font-bold">MACOJU Asesoría en Prevención</h1>
    <p class="text-lg">Comprometidos con tu seguridad laboral</p>
  </header>

  <nav class="bg-blue-700 text-white p-4 flex justify-center gap-8 font-semibold">
    <a href="#servicios" class="hover:underline">Servicios</a>
    <a href="#contacto" class="hover:underline">Contacto</a>
  </nav>

  <main class="max-w-4xl mx-auto p-6">
    <section id="servicios" class="mb-12">
      <h2 class="text-2xl font-bold text-blue-900 mb-4">Servicios Ofrecidos</h2>
      <ul class="list-disc pl-6 space-y-2">
        <li>Asesoría técnica permanente</li>
        <li>Visitas en terreno para verificar condiciones de seguridad y salud</li>
        <li>Capacitaciones y charlas preventivas</li>
        <li>Coordinación con organismos administradores (ACHS, Mutual, IST, ISL)</li>
        <li>Gestión de cursos y solicitud de diplomas</li>
        <li>Gestión de higiene ambiental y protocolos MINSAL</li>
        <li>Implementación de programas preventivos</li>
        <li>Documentación legal: Reglamento Interno, IPER, planes de emergencia, procedimientos, capacitaciones, entrega de EPP</li>
        <li>Investigación de accidentes e incidentes</li>
        <li>Gestión de señalética, extintores y servicios sanitarios</li>
        <li>Levantamiento de hallazgos para mejoras</li>
        <li>Detección de necesidades de Elementos de Protección Personal (EPP)</li>
      </ul>
    </section>

    <section id="contacto">
      <h2 class="text-2xl font-bold text-blue-900 mb-4">Contacto</h2>
      <p class="mb-4">¿Tienes dudas o necesitas una propuesta personalizada? Escríbenos:</p>
      <form action="mailto:macojuasesorias@gmail.com" method="post" enctype="text/plain" class="bg-white p-6 rounded-lg shadow-md space-y-4">
        <div>
          <label for="nombre" class="block font-semibold">Nombre:</label>
          <input type="text" id="nombre" name="Nombre" required class="w-full p-2 border rounded">
        </div>
        <div>
          <label for="correo" class="block font-semibold">Correo Electrónico:</label>
          <input type="email" id="correo" name="Correo" required class="w-full p-2 border rounded">
        </div>
        <div>
          <label for="mensaje" class="block font-semibold">Mensaje:</label>
          <textarea id="mensaje" name="Mensaje" rows="5" required class="w-full p-2 border rounded"></textarea>
        </div>
        <button type="submit" class="bg-blue-900 text-white px-6 py-2 rounded hover:bg-blue-800">Enviar</button>
      </form>
    </section>
  </main>

  <footer class="bg-blue-800 text-white text-center p-6 mt-12">
    <p class="text-sm">&copy; 2025 MACOJU Asesoría en Prevención | Carolina Mendoza Veneros</p>
    <p class="text-sm">📧 macojuasesorias@gmail.com | 📞 +56 9 4680 9187</p>
  </footer>

</body>
</html>
