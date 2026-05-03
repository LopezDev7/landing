# San Andreas Roleplay - Landing Page

Rediseño de la web principal para el servidor de **San Andreas RolePlay**. El enfoque fue limpiar la interfaz, arreglar los bugs de los contenedores y darle una atmósfera más "chill" acorde al servidor.

## 🛠 Cambios realizados

*   **Rediseño de UI:** Se cambió el estilo plano por uno de profundidad con *Glassmorphism* y luces ambientales naranja.
*   **Fix de Maquetación:** Se eliminaron los bloques negros laterales. Ahora las secciones usan contenedores fluidos que aprovechan todo el ancho de pantalla.
*   **Jugadores en vivo:** El contador conecta vía `fetch` a la IP `play.sarp.es:7777` para mostrar el número real de ciudadanos online y detectar eventos (Doble EXP).
*   **Galería Visual:** Se añadió una sección de características con imágenes reales del servidor (Casino, Downtown, etc.) usando efectos de zoom y degradados.

## 📂 Estructura

*   `src/components/`: Componentes modulares (Navbar, Hero, Stats, Features).
*   `src/layouts/`: Template base con la iluminación de fondo y tipografía.
*   `public/images/`: Assets, logos y capturas del juego.

## 🚀 Instalación y uso

```bash
# Instalar dependencias
npm install

# Correr en local
npm run dev

# Generar build para producción
npm run build
```

## ⚙️ Notas técnicas

*   **IP del servidor:** Se configura en el componente `Stats.astro`.
*   **Responsive:** Diseñado con Tailwind para que no se rompa en móviles o monitores ultra-wide.
*   **Rendimiento:** Optimizado con Astro para una carga instantánea.

---
**SARP.es** - *Escribe tu propia historia.*
