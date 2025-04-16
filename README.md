# Formulario de Registro - Liga Nacional de Robótica

Este proyecto es un formulario interactivo y dinámico para registrar equipos en el campeonato de la **Liga Nacional de Robótica (LNR)**. Incluye validaciones en tiempo real, soporte para temas claro/oscuro, y una experiencia de usuario moderna y atractiva.

## Características

- **Validaciones en tiempo real**: Cada campo del formulario es validado dinámicamente para garantizar que los datos ingresados sean correctos.
- **Modo claro/oscuro**: Los usuarios pueden alternar entre temas claro y oscuro, con la configuración guardada en `localStorage`.
- **Previsualización de archivos**: Los usuarios pueden cargar imágenes y documentos, con previsualización en tiempo real.
- **Contador de equipos registrados**: Se muestra un contador dinámico de equipos registrados, persistente gracias a `localStorage`.
- **Categorías de competencia**: Los usuarios pueden seleccionar entre múltiples categorías, con descripciones detalladas mediante tooltips.
- **Campos condicionales**: Algunos campos, como el certificado de seguridad, se muestran dinámicamente según las selecciones del usuario.
- **Diseño responsivo**: El formulario se adapta a diferentes tamaños de pantalla, ofreciendo una experiencia óptima en dispositivos móviles y de escritorio.

## Estructura del Proyecto
Formulario/ ├── index.html # Archivo principal del formulario ├── style.css # Estilos del formulario └── indexviejo.html # Versión anterior del formulario (no utilizada)


## Tecnologías Utilizadas

- **HTML5**: Estructura del formulario.
- **CSS3**: Estilos modernos con animaciones y diseño responsivo.
- **JavaScript**: Validaciones, interactividad y manejo de eventos.

## Cómo Usar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/formulario-lnr.git

2. Abre el archivo index.html en tu navegador.
3. Completa el formulario y disfruta de la experiencia interactiva.

Funcionalidades Clave
Validaciones
El formulario valida automáticamente los siguientes campos:

Nombre del equipo (máximo 30 caracteres).
Selección de institución o ingreso de una institución personalizada.
Email del responsable.
Datos de los estudiantes (uno por línea).
Foto de perfil del equipo (JPG/PNG, máximo 2MB).
Selección de al menos una categoría de competencia.
Diseño del robot (PDF/JPG/PNG, máximo 5MB).
Certificado de seguridad (si aplica).
Contacto de emergencia (10 dígitos).
Fecha preferida para la competencia.
Aceptación de las reglas del campeonato.
Modo Claro/Oscuro
El usuario puede alternar entre temas claro y oscuro mediante un interruptor. La preferencia se guarda en localStorage para futuras visitas.

Contador de Equipos Registrados
El contador de equipos registrados se actualiza dinámicamente y persiste entre sesiones gracias a localStorage.
