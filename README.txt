======================================================
  VENEZUELA SOLIDARIA — Instrucciones de despliegue
======================================================

TIEMPO ESTIMADO: 5-10 minutos para tener el sitio live.

──────────────────────────────────────────
PASO 1 — Subir el sitio a internet (GRATIS)
──────────────────────────────────────────

1. Abre tu navegador y ve a:
   https://app.netlify.com/drop

2. Arrastra la carpeta "venezuela-solidaria" completa
   (esta carpeta, con todos sus archivos adentro)
   al área que dice "Drag and drop your site output folder here".

3. ¡Listo! En segundos tendrás una URL como:
   https://nombre-aleatorio.netlify.app

4. Puedes cambiar ese nombre yendo a:
   Site settings → General → Site name → Rename
   Por ejemplo: venezuela-solidaria.netlify.app


──────────────────────────────────────────
PASO 2 — Recibir formularios por correo
──────────────────────────────────────────

Para que Netlify te avise cada vez que alguien envíe
un comentario o sugiera un recurso:

1. Inicia sesión en https://app.netlify.com
   (si no tienes cuenta, créala gratis con tu correo)

2. Ve a tu sitio → Site settings → Forms

3. En "Form notifications" → "Add notification"
   → Email notification

4. Ingresa: jeannetteafuentesr@gmail.com

5. Guarda. A partir de ahí recibirás un correo
   por cada envío nuevo.


──────────────────────────────────────────
PASO 3 — Acceder al panel de administración
──────────────────────────────────────────

URL: tu-sitio.netlify.app/admin.html

Contraseña por defecto: Venezuela2025!

IMPORTANTE: Cambia la contraseña antes de compartir
el sitio públicamente. Para hacerlo:

1. Abre admin.html con cualquier editor de texto
   (Bloc de notas en Windows, TextEdit en Mac)

2. Busca esta línea:
   const ADMIN_PASSWORD = "Venezuela2025!";

3. Cambia "Venezuela2025!" por tu nueva contraseña

4. Guarda y re-sube la carpeta a Netlify (Paso 1)


──────────────────────────────────────────
PASO 4 — Añadir nuevos recursos al sitio
──────────────────────────────────────────

Cuando apruebes una sugerencia recibida por correo:

1. Abre index.html con un editor de texto

2. Busca el bloque de la tarjeta que quieres reemplazar
   o añadir nueva. Ejemplo de tarjeta:

   <div class="tarjeta">
     <span class="tarjeta-icon">🔍</span>
     <span class="tarjeta-cat">Personas</span>
     <h3>Nombre del recurso</h3>
     <p>Descripción breve de qué hace y a quién ayuda.</p>
     <a href="https://URL-aqui.com" target="_blank"
        rel="noopener noreferrer" class="btn-ir">
       Ir al recurso →
     </a>
   </div>

3. Cambia el icono (emoji), categoría, nombre,
   descripción y URL.

4. Guarda el archivo y vuelve a arrastrar la carpeta
   a app.netlify.com/drop para actualizar el sitio.


──────────────────────────────────────────
PASO 5 — Analítica de visitas (opcional)
──────────────────────────────────────────

Para ver cuántas personas visitan el sitio:

1. Ve a https://www.goatcounter.com y crea una cuenta
   gratis (sin tarjeta de crédito)

2. Elige un nombre de sitio (ej. venezuela-solidaria)

3. GoatCounter te dará un fragmento de código como:
   <script data-goatcounter="https://TU-NOMBRE.goatcounter.com/count"
           async src="//gc.zgo.at/count.js"></script>

4. Pégalo justo antes de </body> en index.html

5. Re-sube la carpeta a Netlify

6. Las visitas aparecen en tu panel de GoatCounter


──────────────────────────────────────────
PREGUNTAS O PROBLEMAS
──────────────────────────────────────────

Si tienes dudas sobre cómo actualizar el sitio,
escribe a: jeannetteafuentesr@gmail.com

======================================================
  Archivos incluidos en esta carpeta:
  - index.html    → Página principal del directorio
  - admin.html    → Panel de administración (privado)
  - gracias.html  → Página de confirmación de formularios
  - README.txt    → Este archivo de instrucciones
======================================================
