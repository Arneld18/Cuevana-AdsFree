# Cuevana AdsFree 🎬

Cuevana AdsFree es un wrapper de escritorio ligero y de alto rendimiento para Cuevana, diseñado para ofrecer una experiencia de streaming premium y sin interrupciones. Construido con WPF y WebView2, incluye funciones avanzadas como bloqueo de anuncios integrado, personalización de la interfaz y un motor de búsqueda integrado.

![Version](https://img.shields.io/badge/version-1.0.1-lightgreen)
![Platform](https://img.shields.io/badge/platform-Windows-blue)

![Captura de la App](https://github.com/Arneld18/Cuevana-AdsFree/blob/80529f53d909f1ae5f3b89fdedbe0099b840e8c9/Screenshot%20Cuevana-AdsFree-1.png) <!-- Enlace a actualizar por el usuario -->

## ✨ Características

- **🚫 Experiencia sin anuncios**: Filtrado avanzado de red para bloquear popups molestos y publicidad maliciosa.
- **🔍 Búsqueda integrada**: Busca tus películas y series favoritas directamente desde la barra de herramientas de la aplicación.
- **🌓 Interfaz moderna oscura**: Tema oscuro elegante y de alto contraste, inspirado en la estética de Cuevana.
- **📌 Barra inteligente con auto-ocultado**: Barra retráctil que se mantiene oculta mientras miras contenido y aparece cuando la necesitas.
- **💾 Persistencia de sesión**: Recuerda el tamaño y la posición de la ventana, así como las preferencias de anclado.
- **🚀 Instalador sin permisos de administrador**: Se instala en `LocalAppData` para una ejecución rápida sin requerir privilegios de administrador.

## 📥 Instalación

1. Descarga el instalador más reciente desde la página de [Releases](https://github.com/Arneld18/Cuevana-AdsFree/releases).
2. Ejecuta `CuevanaAdsFree_Setup.exe`.
3. La aplicación se instalará en tu carpeta LocalAppData.
4. Inicia la app desde el acceso directo del Escritorio o del Menú Inicio.

## 🛠️ Cómo funciona

La aplicación utiliza **Microsoft Edge WebView2** para renderizar el contenido, ofreciendo la mejor compatibilidad y rendimiento. Intercepta solicitudes de red en tiempo real para evitar la carga de scripts de seguimiento y publicidad, garantizando un entorno limpio y seguro.

## 🖥️ Requisitos

- **SO**: Windows 10 u 11 (64 bits).
- **Runtime**: [.NET 10.0 Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) o superior.
- **WebView2**: La aplicación utilizará automáticamente el WebView2 Runtime Evergreen instalado en tu sistema.

## ☕ Apoya el proyecto

Si esta herramienta te resulta útil, considera apoyar su desarrollo:

[**Cómprame un café ☕**](https://donate.stripe.com/eVq7sL5f75XXe5Fc8KfnO01)

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

**Aviso legal**: *Esta aplicación es un proyecto independiente y no está afiliado, autorizado ni respaldado por Cuevana. Es un wrapper de navegador diseñado para mejorar la experiencia del usuario. Los usuarios son responsables del contenido al que acceden.*
