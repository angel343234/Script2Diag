# ◈ Script2Diag — Arquitectura de Sistemas

Script2Diag es un diseñador moderno y robusto basado en texto para diagramas y arquitectura de sistemas, impulsado en tiempo real por **Mermaid.js**. Está diseñado para ofrecer una experiencia fluida, rápida y amigable a través del navegador, ideal para estudiantes, desarrolladores y arquitectos de software.

## Características Principales

- **Renderizado en Tiempo Real:** Visualiza tu código Mermaid al instante mientras lo escribes.
- **Plantillas Pre-integradas:** Inicia rápidamente diagramas de flujo, secuencia, clases, estado, entidad-relación (ER), Gantt, gráficos de pastel (Pie) y mapas mentales (Mindmap).
- **Exportación en Alta Calidad a PDF:** Nombra tu diagrama y expórtalo a PDF instantáneamente con solo un clic (o usando Ctrl+S). La exportación reconoce automáticamente la orientación adecuada (Vertical u Horizontal) y añade encabezados referenciales.
- **Personalización Visual:**
    - Ajuste de **temas nativos de Mermaid** (Default, Dark, Forest, Neutral, Base).
    - Modo claro / oscuro para la interfaz de la aplicación.
    - Personalización ilimitada del color de **fondo del diagrama**, con renderizado impecable durante el export normal de PDF.
- **Modo Pantalla Completa:** Enfócate al 100% en tu lienzo haciendo clic en el botón expansivo superior; sal de este con un rápido toque en el widget de salida en pantalla, o con la tecla <kbd>Escape</kbd>.
- **Seguridad y Accesibilidad:** Prevención contra el borrado accidental de código gracias al modal personalizado seguro, y numeración precisa de líneas en el editor integrado.

---

## 🛠️ Cómo Iniciar el Proyecto (Instrucciones de Ejecución)

**IMPORTANTE:** Debido a las fuertes políticas de seguridad de los navegadores web modernos (CORS Restrictions - "Tainted Canvas"), la funcionalidad crítica de la aplicación, como la creación y conversión del documento SVG al PDF desde el propio navegador, se bloqueará si abres el archivo localmente como `file:///.../index.html`.

Para que el programa tenga todos los permisos necesarios y funcione de forma impecable incluyendo la captura/exportación local, es absolutamente necesario correrlo desde un **Servidor Local**.

### Requisitos

Necesitas tener instalado **Node.js** en tu computadora (esto incluye el comando `npx`). Si no lo tienes, descárgalo e instálalo desde [nodejs.org](https://nodejs.org/).

### Pasos para Ejecutar

1. Abre tu terminal de comandos (CMD, PowerShell, Git Bash, etc.).
2. Navega con el comando `cd` hasta la ubicación u origen del directorio de esta carpeta, o bien si estás en Visual Studio Code, simplemente abre la terminal integrada.
3. Ejecuta el siguiente comando rápido:
   ```bash
   npx serve . -p 3000
   ```
4. Abre tu navegador moderno preferido (Chrome, Edge, Firefox, Brave) y navega a la siguiente dirección web:
   ```
   http://localhost:3000
   ```

*(Nota: Solo debes permitir que la terminal se quede minimizada y corriendo en segundo plano, tu aplicación ahora es totalmente operativa).*

---

## Componentes Técnicos
- HTML5 y Vanilla CSS (Aesthetic Glassmorphism & Mesh effects).
- **Mermaid.js v10:** Motor principal de renderizado de texto a SVG.
- **jsPDF:** Generador de documentos PDF.
- Editor de código personalizado y responsivo con paneles auto-ajustables (Resize handlers).

## Créditos
- Desarrollado por **Ángel Muñoz**.
- Licencia MIT (Ver archivo `LICENSE` para los detalles completos del software libre).
- Powered by Mermaid.js.
