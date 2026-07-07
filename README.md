# EROS · Elegí tu RRPP

Sitio listo para subir a GitHub Pages sin modificaciones adicionales.

## Cómo agregar el logo
Coloca el archivo del logo en `img/logo-eros.png` (idealmente con fondo
transparente). Si el archivo no existe, la página muestra automáticamente
el texto "EROS" con un estilo cromado similar.

## Cómo agregar/editar RRPP
Abrí `script.js` y sumá un objeto al array `RRPP_LIST`:

```js
{
  nombre: "Nombre Apellido",
  ciudad: "Ciudad",
  instagram: "@usuario",
  foto: "img/nombre.jpg",
  whatsapp: "598XXXXXXXX", // solo dígitos, con código de país
  instagramUrl: "https://instagram.com/usuario",
}
```

Las fotos van en la carpeta `img/`. Si una foto no existe o no carga,
se muestra automáticamente un ícono de reemplazo.

## Cómo cambiar el link de "Comprar entradas online"
En `index.html`, buscá el elemento con `id="onlineTicketsLink"` y
reemplazá el valor de `href` por el link real de venta de entradas.

## Publicar en GitHub Pages
1. Subí estos 3 archivos (`index.html`, `style.css`, `script.js`) y la
   carpeta `img/` a un repositorio de GitHub.
2. Andá a Settings → Pages → Source → seleccioná la rama principal.
3. Listo, la página va a estar disponible en `https://tuusuario.github.io/turepo/`.
