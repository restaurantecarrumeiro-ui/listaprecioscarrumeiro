# Lista de Precios — Carrumeiro
Club Marítimo · Corcubión · Costa da Morte · v-co-015074

Lista de precios oficial publicada mediante GitHub Pages y accesible desde cualquier dispositivo a través de un código QR.

---

## Cómo publicar en GitHub Pages

### 1. Crear el repositorio

1. Ve a [github.com/new](https://github.com/new)
2. Nombre: `carrumeiro-precios` (o el que prefieras)
3. Déjalo **público**
4. Haz clic en **Create repository**

### 2. Subir el archivo

**Desde GitHub web (sin instalar nada):**

1. Dentro del repositorio, pulsa **Add file → Upload files**
2. Arrastra el archivo `index.html`
3. Escribe un mensaje de commit, por ejemplo: `Lista de precios v1`
4. Pulsa **Commit changes**

**Desde terminal:**

```bash
git init
git add index.html
git commit -m "Lista de precios v1"
git remote add origin https://github.com/TU_USUARIO/carrumeiro-precios.git
git push -u origin main
```

### 3. Activar GitHub Pages

1. Ve a **Settings → Pages**
2. En **Source**, selecciona la rama `main` y carpeta `/ (root)`
3. Pulsa **Save**

La URL pública quedará así:

```
https://TU_USUARIO.github.io/carrumeiro-precios/
```

---

## Generar el código QR

Con la URL publicada, genera el QR en cualquiera de estas webs gratuitas:

- [goqr.me](https://goqr.me)
- [qr-code-generator.com](https://www.qr-code-generator.com)
- [qrcodemonkey.com](https://www.qrcodemonkey.com) — permite personalizar colores y añadir logo

Descarga el QR en **SVG o PNG a 300 dpi** para impresión de calidad. Tamaño mínimo recomendado en papel: **3 × 3 cm**.

---

## Actualizar precios

Edita `index.html` directamente en GitHub (botón ✏️) o con cualquier editor de texto, y haz commit. Los cambios son visibles en menos de un minuto.
