# Roadmap Bantrab × +Partners

Plataforma de seguimiento del Innovation Sprint de Ecosistema financiero digital (octubre–diciembre 2026).

## Qué incluye

- **Enfoque**: objetivo, proyectos de los dos meses, las 5 etapas del sprint y el alcance.
- **Roadmap**: cronograma editable (mover, acortar, alargar, cambiar responsable y colores) e hitos que se recalculan solos.
- **Documentos**: análisis de reuniones y documentos, cambios propuestos al cronograma y consultas sobre el proyecto.
- **Para Cristhian / Para +Partners**: pendientes de la semana y próxima sesión.

Los cambios se guardan en el navegador de cada persona (localStorage). "Restablecer datos" vuelve al estado inicial.

## Estructura

```
index.html        Página completa (HTML, CSS y JS en un solo archivo)
assets/           Logos de +Partners y Bantrab
```

## Publicar con GitHub Pages

1. Subí estos archivos a la raíz del repositorio.
2. En el repo: Settings → Pages → Source: "Deploy from a branch", rama `main`, carpeta `/ (root)`.
3. La página queda en `https://<usuario>.github.io/<repo>/`.

## Pendiente

- El análisis automático de documentos subidos y las preguntas libres a "Preguntale al proyecto" necesitan un backend con un modelo de lenguaje. Hoy las respuestas de ejemplo salen del transcript del kickoff.
- Los datos son locales a cada navegador; para compartir el estado entre Cristhian y +Partners hace falta una base de datos compartida.
