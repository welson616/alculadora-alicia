from pathlib import Path

# Updated HTML content with title, 4 headings, 2 links (dofollow), and site URL
updated_html_content = """
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="robots" content="index, follow" />
  <meta name="description" content="Descubre cómo la calculadora Alicia puede ayudarte con tus tareas matemáticas diarias con una interfaz moderna y fácil de usar." />
  <title>Calculadora Alicia - Herramienta Inteligente y Moderna para Todos</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f7f9fb;
      color: #333;
      line-height: 1.6;
      padding: 20px;
    }
    .container {
      max-width: 720px;
      margin: auto;
      background: #fff;
      border-radius: 12px;
      padding: 30px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    h1, h2 {
      color: #007bff;
    }
    .read-more {
      overflow: hidden;
      max-height: 160px;
      transition: max-height 0.5s ease;
    }
    .read-more.expanded {
      max-height: 1200px;
    }
    .toggle-btn {
      background: #007bff;
      color: white;
      border: none;
      padding: 10px 20px;
      margin-top: 15px;
      border-radius: 8px;
      cursor: pointer;
    }
    a {
      color: #007bff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Calculadora Alicia - Tu herramienta inteligente para resolver cálculos</h1>
    <p>
      ¿Buscas una forma rápida y moderna de realizar cálculos? Visita ahora 
      <a href="(https://calculadoraalicia.net/)" target="_blank" rel="dofollow"><strong>la calculadora alicia</strong></a>, 
      una herramienta intuitiva con diseño responsivo y excelentes funcionalidades.
    </p>

    <h2>1. ¿Por qué elegir la Calculadora Alicia?</h2>
    <p>
      Esta herramienta no solo resuelve cálculos matemáticos simples, sino que también facilita tareas complejas con precisión. 
      Su interfaz UX/UI es limpia, amigable y está pensada para todos los públicos.
    </p>

    <h2>2. Interfaz moderna y responsiva</h2>
    <p>
      Compatible con dispositivos móviles, tablets y PCs, la <strong>Calculadora Alicia</strong> ofrece una experiencia fluida y sin interrupciones.
    </p>

    <div class="read-more" id="more-content">
      <h2>3. Ideal para estudiantes y profesionales</h2>
      <p>
        Ya seas estudiante o profesional, esta calculadora te ahorra tiempo. Cuenta con funcionalidades avanzadas 
        y un diseño visual que minimiza la fatiga ocular.
      </p>

      <h2>4. Compatible con SEO y compartible</h2>
      <p>
        Puedes integrar fácilmente esta herramienta en tus flujos de trabajo. Está optimizada para motores de búsqueda y tiene 
        código limpio y rápido.
      </p>
      <p>
        También puedes visitar nuestro sitio principal para más herramientas como esta: 
        <a href="https://welson616.github.io/alculadora-alicia/" target="_blank" rel="dofollow">https://welson616.github.io/alculadora-alicia/</a>.
      </p>
    </div>

    <button class="toggle-btn" onclick="toggleReadMore()">Leer más</button>
  </div>

  <script>
    function toggleReadMore() {
      const content = document.getElementById('more-content');
      content.classList.toggle('expanded');
      const btn = document.querySelector('.toggle-btn');
      btn.textContent = content.classList.contains('expanded') ? 'Leer menos' : 'Leer más';
    }
  </script>
</body>
</html>
"""

# Save updated file
file_path = Path("/mnt/data/calculadora-alicia-readmore-updated.html")
file_path.write_text(updated_html_content, encoding="utf-8")

file_path.name
