🧠 Clasificador de Imágenes – Instrucciones Claras de Instalación y Ejecución

Este proyecto es una página web que ejecuta un modelo de inteligencia artificial de Teachable Machine usando la webcam del usuario.
Para ejecutarlo no necesitas instalar programas, solo seguir los pasos.

✅ ¿Cómo ejecutar este proyecto?

A continuación, los pasos explicados como si cualquier persona (sin conocimientos técnicos) fuera a ejecutarlo.

🔹 OPCIÓN 1 — Ejecutarlo directamente en tu computadora
📌 Paso 1 – Descargar los archivos del proyecto

El usuario debe:

Ir al repositorio de GitHub.

Hacer clic en el botón verde Code.

Seleccionar Download ZIP.

Guardar el archivo ZIP en su computadora.

Descomprimir el ZIP.

Al descomprimirlo verá archivos como:

finalBD.html
BDJS.js

📌 Paso 2 – Abrir la aplicación

Para abrir el clasificador:

Busque el archivo:

finalBD.html


Haga doble clic sobre él.

Esto abrirá la aplicación directamente en su navegador (Chrome recomendado).

✔ No necesita instalar nada
✔ No necesita ejecutar comandos
✔ No se requiere servidor local

📌 Paso 3 – Permitir el acceso a la webcam

Al abrir la página:

El navegador mostrará un mensaje:
"¿Permitir el acceso a la cámara?"

El usuario debe dar clic en:

👉 Permitir

Sin este permiso, la IA no podrá analizar imágenes.

📌 Paso 4 – Usar la aplicación

Una vez cargada la página:

Presione el botón Iniciar
(La IA descargará el modelo de Teachable Machine)

Aparecerá su cámara en pantalla

Debajo verá una lista de predicciones con porcentajes

Para detener la cámara, presione Detener

¡Listo! La aplicación está ejecutándose correctamente.

🔹 OPCIÓN 2 — Ejecutarlo desde GitHub Pages (Online)

Si tú (el dueño del repositorio) activas GitHub Pages, cualquier persona podrá usar tu proyecto online sin descargar nada.

📌 Paso para el dueño del repositorio:

Ir a Settings > Pages

En "Branch", seleccionar main

En carpeta, elegir root

Guardar

GitHub generará una URL como:

https://tuusuario.github.io/tu-repositorio/

📌 Para el usuario final:

Solo debe abrir esa URL en su navegador.
Nada que descargar.
Solo permitir la cámara.

🧩 ¿Qué hace cada archivo?
finalBD.html

Es la página principal.
Contiene:

Interfaz (botones, contenedores)

Diseño (CSS)

Lógica completa con TensorFlow.js

Conexión al modelo de Teachable Machine

BDJS.js (si lo usas)

Contiene la lógica separada del clasificador.
No necesita configurarse manualmente.

🔍 Requisitos técnicos mínimos

El usuario solo necesita:

✔ Un navegador moderno (Chrome recomendado)
✔ Permitir el uso de la cámara
✔ Conexión a internet (para cargar el modelo IA)

No requiere:

✘ Python
✘ Node.js
✘ Servidores
✘ Instalar librerías
✘ Consola o comandos
