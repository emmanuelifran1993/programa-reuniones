# Programa mensual de reuniones

Página única (`index.html`) para armar el programa de reuniones de la congregación:
Sonido, Micrófono, Plataforma y Acomodadores.

## Uso

Abrir la página y usar los botones del panel «Compartir y respaldar»:

- **Compartir app + mis datos** / **Descargar app + mis datos**: genera un archivo con el
  programa y los datos cargados. Al abrirlo, pregunta si se quieren reemplazar los datos
  del dispositivo.
- **Descargar app (sin datos)**: el programa con la lista de publicadores y ancianos,
  sin asignaciones.
- **Guardar copia** / **Restaurar copia**: respaldo en `.json` de los datos.

Los datos se guardan en el navegador de cada dispositivo (`localStorage`); no se
sincronizan entre personas ni se envían a ningún servidor.

## Estructura

```
index.html   Programa completo (HTML + CSS + JS en un solo archivo)
```

## Actualizar el sitio

1. Reemplazar `index.html` por la versión nueva.
2. Subir el cambio al repositorio (rama `main`).

GitHub Pages publica automáticamente la versión nueva en 1–2 minutos.
