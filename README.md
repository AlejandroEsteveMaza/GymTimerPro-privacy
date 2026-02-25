# GymTimerPro Privacy

Repositorio estático de la política de privacidad pública de **GymTimerPro**.

## Contenido

- `index.html`: documento completo de Privacy Policy en HTML5 (listo para producción).
- `logo.png`: logo mostrado en la cabecera del documento.
- `favicon.png`: favicon PNG principal.
- `favicon.ico`: favicon adicional para compatibilidad amplia de navegador.

## Requisitos de assets

Coloca estos archivos en la raíz del proyecto (misma carpeta que `index.html`):

- `logo.png`
- `favicon.png` (recomendado usar `favicon-32x32.png` renombrado)
- `favicon.ico`

## Vista local

Puedes abrir el archivo directamente:

- Doble clic en `index.html`

O servirlo localmente:

```bash
cd /Users/alejandroestevemaza/Code/GymTimerPro-privacy
python3 -m http.server 8000
```

Luego abre: `http://localhost:8000`

## Publicación (GitHub Pages)

1. Haz push de este repositorio a GitHub.
2. En GitHub: `Settings > Pages`.
3. Selecciona la rama principal y carpeta raíz (`/root`).
4. Guarda y espera a que se publique.

URL esperada (ejemplo):

- `https://alejandroestevemaza.github.io/GymTimerPro-privacy/`

## Checklist antes de publicar

- Verificar que el logo se vea en modo claro y oscuro.
- Verificar favicons (`favicon.png` y `favicon.ico`).
- Revisar metadatos SEO/OG/Twitter en `<head>`.
- Validar impresión (`@media print`).
- Confirmar datos de contacto legales.

## Mantenimiento

Cuando cambies el texto legal:

1. Actualiza `index.html`.
2. Cambia la **Effective Date**.
3. Revisa enlaces canónicos y metadatos sociales.
4. Publica los cambios.
