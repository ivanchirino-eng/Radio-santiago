[README.md](https://github.com/user-attachments/files/31283194/README.md)
# 📻 Dial Santiago

Aplicación web gratuita para escuchar radios chilenas en vivo, con foco en emisoras de Santiago. Sin anuncios, sin instalación, sin cuentas — solo abrir el link y darle play.

🔗 **[Escuchar ahora](https://ivanchirino-eng.github.io/Radio-santiago/)**

## ¿Qué es esto?

Dial Santiago reúne en un solo lugar las principales radios de Santiago y Chile, con reproducción directa dentro de la misma página. Nació como un proyecto simple para escuchar radio chilena desde cualquier navegador, sin depender de apps de terceros.

## Características

- 🎧 Reproducción directa de emisoras (sin salir de la página)
- 🔍 Buscador para encontrar radios por nombre o género
- 📱 Funciona en celular y computador, sin instalar nada
- 🌐 Hosteado gratis en GitHub Pages
- ⚡ Sin frameworks ni dependencias pesadas — HTML, CSS y JavaScript puro

## Emisoras disponibles

Incluye radios como Radio Bío-Bío, Cooperativa, ADN Radio, Radio Agricultura, Radio Concierto, Radio Futuro, Radioactiva, Los 40 Chile, Radio Pudahuel, Corazón FM, Radio Carolina, Radio Duna y Radio Carabineros, entre otras. Las emisoras sin transmisión directa disponible enlazan a su sitio oficial para escuchar ahí.

## Cómo agregar una nueva radio

1. Abre `index.html` en el editor de GitHub
2. Busca el bloque `const STATIONS = [ ... ]`
3. Agrega una línea nueva con este formato:
   ```js
   { name: "Nombre de la radio", tags: "género · categoría", stream: "URL_DEL_STREAM_O_null", site: "https://sitio-oficial.cl" },
   ```
4. Guarda los cambios ("Commit changes") — el sitio se actualiza solo en 1-2 minutos

Si no tienes la URL de transmisión directa, deja `stream: null` y la emisora funcionará igual, abriendo su sitio oficial en una pestaña nueva.

## Tecnología

Proyecto 100% estático: un solo archivo `index.html` con HTML, CSS y JavaScript vanilla. No requiere build, servidor backend, ni base de datos. Desplegado con [GitHub Pages](https://pages.github.com/).

## Créditos

Fuentes de transmisión obtenidas de los sitios oficiales de cada radio y de [myradioonline.cl](https://myradioonline.cl).

---

Proyecto personal, sin fines comerciales. Todas las marcas y transmisiones pertenecen a sus respectivas radios.
