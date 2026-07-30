# Allison Bautizo — Spotify Jam

Página estática para usar un QR permanente que dirige al Spotify Jam activo del evento.

## Archivos

- `index.html`: página pública para los invitados.
- `jam.json`: contiene el enlace actual del Spotify Jam.
- `admin.html`: acceso rápido al editor de `jam.json` en GitHub.

## Configuración inicial

1. Crea un repositorio público llamado `allison-bautizo-musica`.
2. Sube estos tres archivos a la raíz del repositorio.
3. Abre `admin.html` y reemplaza:

   ```js
   const GITHUB_USERNAME = "TU-USUARIO";
   ```

   por tu usuario real de GitHub.

4. En GitHub ve a `Settings → Pages`.
5. En `Build and deployment` selecciona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`

La página será:

```text
https://TU-USUARIO.github.io/allison-bautizo-musica/
```

Usa esa URL para generar el QR permanente.

## El día del evento

1. Inicia Spotify Jam.
2. Copia el enlace de invitación.
3. Abre:

```text
https://TU-USUARIO.github.io/allison-bautizo-musica/admin.html
```

4. Pulsa `Abrir editor en GitHub`.
5. Cambia `jam.json` a:

```json
{
  "url": "https://spotify.link/EL-LINK-DEL-JAM"
}
```

6. Haz commit.

## Seguridad

GitHub Pages es público. No coloques direcciones, teléfonos ni información privada.
El enlace del Jam también será visible públicamente mientras permanezca en `jam.json`.
