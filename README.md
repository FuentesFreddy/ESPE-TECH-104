# ESPE TECH 104 - Landing Page

## Descripción
Landing page moderna y responsiva para promocionar el evento "ESPE TECH 104: Innovación tecnológica al servicio de la seguridad y defensa del país".

## Integrantes
- Lennon Arias
- Kenai Ramirez
- Freddy Fuentes

## Tecnologías y Herramientas
- HTML5 Semántico
- CSS3 (Flexbox, Grid, Transiciones)
- Docker
- GitHub

## Estructura del proyecto
- `index.html`: Código fuente del sitio.
- `css/styles.css`: Hoja de estilos.
- `Imagenes/`: Recursos visuales institucionales.
- `Dockerfile` y `.dockerignore`: Configuración de despliegue.

## Ejecución Local
1. Construir la imagen: `docker build -t fjfuentes1/espe-tech:latest .`
2. Ejecutar el contenedor: `docker run -d -p 9090:80 espe-tech`
3. Acceder al sitio: http://localhost:9090

## 🐳 Imagen en Docker Hub
- **URL de la imagen:** https://hub.docker.com/r/usuario/espe-tech
- **Descargar imagen:** `docker pull fjfuentes1/espe-tech:latest`
- **Ejecutar imagen pública:** `docker run -d -p 9090:80 fjfuentes1/espe-tech:latest`