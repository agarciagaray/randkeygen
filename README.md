# Generador de Contraseñas Seguras 🔒

![Generador de Contraseñas](https://via.placeholder.com/800x400.png?text=Captura+de+Pantalla+del+Generador "Captura de pantalla de la aplicación")

Una aplicación web moderna para generar contraseñas seguras con indicador visual de fortaleza, diseñada con HTML, CSS y JavaScript.

## Características ✨

- 📏 Control deslizante para longitud de contraseña (8-20 caracteres)
- ☑️ Opciones personalizables:
  - Letras mayúsculas (A-Z)
  - Letras minúsculas (a-z)
  - Números (0-9)
  - Símbolos (!@#$%^&*)
- ⚡ Generación instantánea de contraseñas seguras
- 📋 Botón para copiar al portapapeles con notificación visual
- 📊 Indicador visual de fortaleza con tres niveles:
  - 🔴 Débil
  - 🟡 Media
  - 🟢 Fuerte
- 📱 Diseño completamente responsive (funciona en móviles y escritorio)
- 🎨 Interfaz de usuario moderna y atractiva

## Cómo Usar 🚀

1. Selecciona la longitud deseada con el control deslizante
2. Marca los tipos de caracteres que deseas incluir
3. Haz clic en "Generar Contraseña"
4. Revisa la fortaleza de tu contraseña en el indicador
5. Usa el botón "Copiar Contraseña" para llevarla al portapapeles

## Instalación 💻

No se requiere instalación! Simplemente abre el archivo HTML en cualquier navegador moderno:

```bash
# Clona el repositorio (opcional)
git clone https://github.com/agarciagaray/randkeygen.git

# Abre el archivo en tu navegador
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

## Tecnologías Utilizadas 🛠️

- **HTML5**: Estructura de la aplicación
- **CSS3**: Estilos y diseño responsive
- **JavaScript**: Lógica de generación de contraseñas
- **Gradientes CSS**: Para el fondo atractivo
- **Flexbox y Grid**: Diseño de componentes
- **Transiciones CSS**: Efectos visuales suaves

## Requisitos del Sistema 🌐

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexión a Internet no requerida (funciona offline)

## Personalización 🎨

Puedes modificar los siguientes aspectos fácilmente:

```css
:root {
  --primary: #4361ee;       /* Color principal */
  --primary-dark: #3a56d4;  /* Color principal oscuro */
  --secondary: #7209b7;    /* Color secundario */
  --success: #06d6a0;      /* Color para fortaleza fuerte */
  --warning: #ffd166;      /* Color para fortaleza media */
  --danger: #ef476f;       /* Color para fortaleza débil */
  --border-radius: 8px;    /* Radio de bordes */
}
```

## Licencia 📄

Este proyecto está bajo la licencia [MIT](LICENSE). Eres libre de usarlo, modificarlo y distribuirlo según tus necesidades.

---

**Nota**: Para una experiencia óptima, se recomienda usar la última versión de tu navegador preferido.