# ESPE TECH 104 - Landing Page

## Descripción
Landing page moderna y responsiva para promocionar el evento "ESPE TECH 104: Innovación tecnológica al servicio de la seguridad y defensa del país".

## Integrantes
- Persona 1
- Persona 2
- Persona 3

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
1. Construir la imagen: `docker build -t espe-tech .`
2. Ejecutar el contenedor: `docker run -d -p 8080:80 espe-tech`
3. Acceder al sitio: http://localhost:8080

## 🐳 Imagen en Docker Hub
- **URL de la imagen:** https://hub.docker.com/r/usuario/espe-tech
- **Descargar imagen:** `docker pull usuario/espe-tech:latest`
- **Ejecutar imagen pública:** `docker run -d -p 8080:80 usuario/espe-tech:latest`