# Silver Devs Labs - App Configs & House Ads

Repositorio centralizado de configuraciones remotas, parámetros dinámicos y banners de House Ads (autopromoción) para las aplicaciones móviles de **Silver Devs Labs**.

## Archivos
- `house_ads.json`: Configuración principal de campañas de banners y anuncios recompensados de respaldo.
- `assets/`: Imágenes de banners promocionales en formato `.webp`.

## Cómo agregar una app nueva a House Ads
1. Sube la imagen del banner (formato `.webp`) a la carpeta `assets/`.
2. Edita `house_ads.json` y agrega la app en la lista `"banners"`, con `"active": true` y el enlace hacia la ficha de Google Play Store.
3. Guarda el commit. La actualización se propagará automáticamente a todos los usuarios.
