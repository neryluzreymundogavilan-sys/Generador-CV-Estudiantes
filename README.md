# GENERADOR WEB DE CURRÍCULUM (CV) — Dossier Documental

![Generador Web de CV](https://img.shields.io/badge/Versi%C3%B3n-2.1-indigo?style=for-the-badge)
![Licencia](https://img.shields.io/badge/Licencia-MIT-emerald?style=for-the-badge)
![HTML5 / Tailwind CSS](https://img.shields.io/badge/Frontend-Tailwind_CSS_&_Vanilla_JS-blue?style=for-the-badge)

Sistema web interactivo y profesional para la creación, personalización y exportación en formato **A4** de **Currículum Vitae (CV)** y **Dossier de Certificados / Constancias** (admitiendo imágenes y documentos Word `.docx`).

---

## 🌟 Características Principales

- **Hoja A4 exacta (210mm x 297mm)**: Diseño profesional milimétrico adaptado a estándares internacionales de impresión y exportación.
- **Importación de Certificados en Word (.docx) e Imágenes**:
  - Lectura de archivos `.docx` directamente en el navegador con `Mammoth.js`.
  - Soporta constancias en texto y diplomas/certificados escaneados pegados en Word.
  - Soporta formatos de imagen clásicos (`.png`, `.jpg`, `.jpeg`, `.webp`).
- **Catálogo de Carreras Profesionales y Técnicas**:
  - Ingeniería de Sistemas e Informática
  - Arquitectura de Plataformas y Servicios TI
  - Enfermería Técnica / Licenciatura
  - Administración de Empresas
  - Ingeniería Civil
  - Y muchas más con autocompletado inteligente de perfiles, cargos, logros y habilidades.
- **Doble Rol con Control de Acceso**:
  - **Portal Estudiantil**: Registro, inicio de sesión y llenado de datos guiado.
  - **Panel de Administradora (Ingeniera)**: Aprobación de cuentas y revisión de solicitudes con PIN de seguridad.
- **Exportación en un Clic**:
  - Generación directa de PDF con `html2pdf.js` y `html2canvas`.
  - Envío automático de solicitud a WhatsApp de la Administradora.
- **Diseño 100% Responsivo**: Funciona en computadoras de escritorio, laptops, tablets y celulares con selector de vista (Editor / Vista Previa A4).

---

## 📁 Estructura del Proyecto

```text
cvstudio-pro/
├── index.html       # Aplicación web completa (HTML5, Tailwind, JS, Mammoth, html2pdf)
├── README.md        # Documentación oficial del proyecto
├── .gitignore       # Archivos ignorados por Git
└── LICENSE          # Licencia libre MIT
```

---

## 🚀 Cómo Usar y Publicar en GitHub

### 1. Despliegue gratuito en GitHub Pages:
1. Crea un repositorio en GitHub (por ejemplo: `cvstudio-pro`).
2. Sube estos archivos a la rama `main`.
3. Ve a **Settings (Configuración)** > **Pages** en tu repositorio de GitHub.
4. En **Branch**, selecciona `main` y la carpeta `/(root)`. Haz clic en **Save**.
5. ¡Listo! En un minuto tu aplicación estará disponible en una URL pública (ejemplo: `https://tuusuario.github.io/cvstudio-pro/`).

### 2. Uso local en tu computadora:
No necesitas instalar Node.js ni configurar servidores:
1. Descomprime los archivos en cualquier carpeta.
2. Haz doble clic en `index.html` para abrirlo en cualquier navegador web moderno (Chrome, Edge, Firefox, Brave, Safari).

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & CSS3**
- [Tailwind CSS](https://tailwindcss.com/) vía CDN
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js/) para decodificar documentos `.docx` a HTML
- [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/) para exportar a PDF
- [FontAwesome 6](https://fontawesome.com/) para iconografía profesional
- [Google Fonts](https://fonts.google.com/) (Inter, Plus Jakarta Sans, Playfair Display)

---

## 📝 Licencia

Este proyecto está bajo la Licencia [MIT](LICENSE). Puedes usarlo, modificarlo y distribuirlo libremente.
