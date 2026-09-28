# Coach de entrenamiento V2 — instalación en GitHub Pages

Sube estos archivos a la raíz del repositorio, manteniendo exactamente estos nombres:

- `index.html`
- `exercises.json`
- `manifest.webmanifest`
- `service-worker.js`
- `icon.png`

## Publicar

1. En GitHub abre el repositorio.
2. Sustituye el `index.html` anterior por este.
3. Añade los otros archivos si no existen. Conserva `exercises.json` en la misma carpeta que `index.html`.
4. Ve a **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**.
6. Selecciona la rama `main` y la carpeta `/ (root)` y guarda.
7. Abre la URL de GitHub Pages en Safari del iPhone.
8. En Safari: **Compartir → Añadir a pantalla de inicio**.

## Datos y copias de seguridad

Los datos continúan guardándose localmente en el navegador del dispositivo. En **Plan → Datos** puedes usar **Copia completa** para exportar todo a JSON y **Restaurar copia** para volver a cargarlo. Haz una copia periódicamente.

La V2 migra automáticamente los datos de la versión anterior. Las sesiones antiguas se conservan; como no tenían RIR registrado, ese campo aparecerá vacío en su historial.

## Novedades V2

- RIR real por serie.
- Las series sólo se guardan como realizadas cuando marcas `✓`.
- Series de aproximación separadas del volumen efectivo.
- Recomendaciones de carga con peso + repeticiones + RIR + historial reciente.
- Detección básica de estancamiento.
- Preparación diaria: energía, sueño, fatiga, agujetas y estrés.
- Registro diario de calorías, proteína, hidratos y grasas.
- Medidas de pecho, brazo, muslo y cadera.
- Métricas de e1RM y volumen por ejercicio.
- Exportación CSV enriquecida y restauración JSON.
- PWA instalable y caché offline del núcleo de la aplicación.