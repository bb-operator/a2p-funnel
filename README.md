# BBP A2P SMS Opt-In Funnel

Landing page de opt-in SMS para registro A2P 10DLC de Blackbook Properties.

**URL:** https://messages.blackbookproperties.com

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | Página principal de opt-in SMS (formulario con consentimiento) |
| `terms.html` | Términos y condiciones (`/terms`) |
| `privacy.html` | Política de privacidad (`/privacy` y `/privacy-policy`) |
| `default.conf` | Configuración de nginx (rutas limpias sin `.html`) |
| `docker-compose.yml` | Contenedor nginx + labels de Traefik (SSL automático) |

## Deploy en el VPS

1. Copiar esta carpeta al VPS (donde corre Traefik).
2. Dentro de la carpeta, correr:

```bash
docker compose up -d
```

3. Traefik detecta el contenedor y genera el certificado SSL solo.

## Actualizar contenido

Los HTML están montados como volúmenes de solo lectura. Editar el archivo y recargar la página — no hace falta reiniciar el contenedor (si nginx cachea, `docker compose restart`).
