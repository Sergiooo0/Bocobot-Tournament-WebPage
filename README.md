# Bocobot Tournament - Página Web

Sitio web oficial del Torneo de Robótica Bocobot de la [ESEI](https://esei.uvigo.es/), construido con [MkDocs](https://www.mkdocs.org/) y el tema [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Ver la página

**[https://sergiooo0.github.io/Bocobot-Tournament-WebPage/](https://sergiooo0.github.io/Bocobot-Tournament-WebPage/)**

## Contenido

- **Inicio**: Información general del torneo y patrocinadores
- **Normas del Torneo**: Reglas detalladas de las 5 pruebas de competición
- **Guía del Robot**: Tutorial completo de montaje y programación del BocoBot
- **Inscripción**: Formulario para registrar equipos

## Desarrollo local

Para ejecutar el sitio localmente:

```bash
# Instalar dependencias
pip install -r requirements.txt

# Ejecutar servidor de desarrollo
mkdocs serve
```

El sitio estará disponible en `http://localhost:8000`

## Despliegue

El sitio se despliega automáticamente en GitHub Pages mediante GitHub Actions al hacer push a la rama `main`.
