# Site Projects

Repositorio del sitio web estático construido con [Hugo](https://gohugo.io/) y el tema
[hugo-winston-theme](https://github.com/zerostaticthemes/hugo-winston-theme).
Este proyecto alimenta la galería de proyectos y blog alojados bajo el nombre
"Proyectos".

## Requisitos previos

- [Hugo Extended](https://gohugo.io/installation/)
- [Git](https://git-scm.com/)

## Clonar el repositorio

Incluye el tema como un submódulo de Git, por lo que es recomendable clonar
recursivamente:

```bash
git clone --recursive <url-del-repositorio>
cd projects
```

Si ya clonaste el repositorio sin submódulos ejecuta:

```bash
git submodule update --init --recursive
```

## Desarrollo local

Inicia un servidor de desarrollo con recarga en vivo:

```bash
hugo server --environment development
```

## Generar el sitio para producción

```bash
hugo --environment production
```

Los archivos generados quedarán en la carpeta `public/`.

## Estructura del proyecto

- `content/`: Entradas del blog y páginas.
- `layouts/`: Plantillas y componentes de diseño.
- `assets/`: Recursos procesados por Hugo (por ejemplo, Sass).
- `static/`: Archivos estáticos servidos tal cual (imágenes, JS, etc.).
- `config/` y `hugo.toml`: Configuración del sitio.
- `themes/`: Submódulo con el tema.

## Contribuir

1. Haz un fork del repositorio.
2. Crea una rama para tu cambio.
3. Envía un Pull Request describiendo tu contribución.

Si deseas acceso directo para contribuir, solicita permisos al mantenedor.

## Licencia

Este repositorio no incluye un archivo de licencia. Considera agregar uno si
piensas distribuir el código públicamente.
