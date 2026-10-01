# Estudio Rojo

Herramientas web para clientes del estudio. Sitio estático, se publica con GitHub Pages.

| Carpeta | Herramienta | Link |
|---|---|---|
| `edicion/` | Pedido de retoque: el cliente indica qué cambiar en cada foto, adjunta referencias y descarga un Excel con las imágenes dentro de las celdas. | `/edicion/` |

## Publicar
Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
Queda en `https://robeigles.github.io/estudio-rojo/` y la herramienta en `.../estudio-rojo/edicion/`.

## Configurar
En `edicion/index.html`, línea `const CONFIG = { contacto: "" }`: pon tu WhatsApp o correo para que aparezca al final del pedido.

## Agregar una herramienta nueva
Crear una carpeta con su `index.html` y sumarla a la lista en `index.html` de la raíz.
