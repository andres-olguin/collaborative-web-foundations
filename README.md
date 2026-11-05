# Collaborative Web Foundations — UNAB Devs

**Proyecto académico grupal de Desarrollo Web y Móvil** construido con HTML5 y CSS3 para practicar diseño, estructura semántica, trabajo colaborativo y versionado en Git.

**Integrantes identificados en el código HTML:** Andrés Olguín, Maximiliano Valdés y Miguel Margas. La referencia a UNAB es parte del contexto educativo; **este repositorio no acredita ningún patrocinio institucional ni autorización de uso comercial de su marca**.

## Qué contiene

La página [`html/index.html`](html/index.html) presenta una tarjeta de equipo, sección de avance y tarjetas de interfaz con estilos propios y referencias a iconos Font Awesome.

```text
collaborative-web-foundations/
├── html/index.html       # Interfaz web del trabajo grupal
├── css/styles.css        # Estilos y diseño responsive
└── docs/                 # Evaluación técnica y hoja de ruta
```

## Ejecución local

No requiere Node.js, npm ni servidor backend. Puedes abrir `html/index.html` en el navegador o iniciar un servidor de archivos:

```bash
python -m http.server 8000
```

Abrir `http://localhost:8000/html/index.html`. Algunos iconos dependen de una CDN y requieren conexión a Internet.

## Alcance real

- Maqueta estática académica, no un sistema de gestión de proyectos.
- El texto de la página puede sugerir despliegue continuo, pero el repositorio no demuestra una plataforma CI/CD de aplicación.
- El botón de acción necesita comprobarse en navegador: su presencia visual no acredita una funcionalidad completa.
- No hay backend, autenticación, base de datos ni API.

## Evolución técnica

1. Revisar semántica HTML, etiquetas, contrastes y navegación por teclado.
2. Probar tamaños de pantalla móvil, tablet y escritorio.
3. Incorporar validación de rutas y enlaces; documentar resultados y capturas reales.
4. Añadir ejemplos de interactividad sencilla, sin desviar el objetivo educativo.
5. Conservar los créditos grupales y comprobar las licencias de iconos y recursos externos.

Documentación: [roadmap de ingeniería](docs/ENGINEERING_ROADMAP_2026-11-04.md) y [escalabilidad apropiada a un sitio estático](docs/ARCHITECTURE_SCALABILITY_2026-11-04.md).

**Licencia:** verificar con todos los integrantes antes de reutilizar o distribuir el trabajo como producto comercial.
