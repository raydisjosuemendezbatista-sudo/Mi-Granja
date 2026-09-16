# 🐔 Mi Granja

Aplicación web de gestión de granja avícola (huevos, gallinas, nacimientos, alimentación, finanzas e inventario). Es un **único archivo HTML autocontenido**: no necesita servidor, base de datos ni instalación.

## ⚠️ Importante sobre los datos

Los datos se guardan en el **`localStorage` del navegador**, es decir, **en el dispositivo de cada persona que la use**, no en GitHub ni en ningún servidor. Cada quien que abra la página tendrá su propio registro, separado del de los demás. Usa el botón **Exportar datos (JSON)** dentro de Configuración para respaldar tu información periódicamente, y **Importar datos** para restaurarla.

## 🚀 Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (puede ser público o privado, aunque GitHub Pages gratuito requiere que sea público, salvo plan de pago).
2. Sube el archivo `index.html` (y este `README.md` si quieres) a la raíz del repositorio.
3. Ve a **Settings → Pages**.
4. En "Source", elige la rama `main` (o `master`) y la carpeta `/ (root)`.
5. Guarda. En 1–2 minutos tu app quedará disponible en:
   `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`

No hace falta ninguna configuración adicional: al llamarse `index.html`, GitHub Pages la sirve automáticamente como página principal.

## 🛠️ Uso local

También puedes abrir `index.html` directamente haciendo doble clic, sin necesidad de subirlo a ningún lado.
