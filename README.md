# Proyecto Integrador — Almacenes y Minería de Datos

Facultad de Ciencias, UNAM. Proyecto Integrador construido de forma incremental sobre la metodología
**CRISP-DM**, entregado como sitio web con [Quarto](https://quarto.org/) y desplegado con GitHub
Pages.

**Sitio publicado:** [PENDIENTE — pegar aquí la URL de GitHub Pages, p. ej.
`https://<usuario>.github.io/<repositorio>/`]

## Integrantes

- [Nombre completo 1]
- [Nombre completo 2]
- [Nombre completo 3]
- [Nombre completo 4]

## Estructura del repositorio

```
.
├── entregas/
│   └── E0_comprension_negocio/
│       ├── bitacora.qmd          # bitácora de la reunión con el stakeholder
│       ├── canvas.qmd            # Business Understanding Canvas
│       ├── preguntas.qmd         # preguntas de investigación priorizadas
│       ├── criterio_exito.qmd    # criterio de éxito en términos de negocio
│       ├── riesgos_supuestos.qmd # supuestos y riesgos
│       ├── uso_ia.qmd            # documentación de uso de LLMs
│       └── fuentes/              # opcional: evidencia citada si el stakeholder fue simulado
├── _quarto.yml                   # configuración del sitio (output-dir: docs)
├── index.qmd                     # página de inicio del sitio
├── styles.css                    # estilos del sitio
├── docs/                         # sitio compilado (servido por GitHub Pages)
└── README.md
```

Este repositorio y su sitio Quarto se reutilizan durante todo el semestre: cada entrega agrega una
nueva carpeta en `entregas/` y sus páginas correspondientes al sitio, en lugar de crear un
repositorio nuevo.

## Cómo previsualizar el sitio localmente

Requiere tener [Quarto](https://quarto.org/docs/get-started/) instalado.

```bash
quarto preview
```

## Cómo compilar el sitio

```bash
quarto render
```

Esto genera el sitio estático en `docs/`, que es la carpeta que sirve GitHub Pages.

## Despliegue en GitHub Pages

1. Hacer `quarto render` y confirmar que `docs/` se generó correctamente.
2. Subir el repositorio a GitHub (`main` como rama por defecto).
3. En GitHub: **Settings → Pages → Branch: `main` / `docs`**.
4. Pegar la URL pública resultante en este README, en la sección "Sitio publicado" de arriba.

## Licencia

[Pendiente de definir por el equipo, si aplica.]
