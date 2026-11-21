# La aventura de Link — Hyrule (43 niveles)

Videojuego de plataformas en español, estilo retro, con **43 niveles**, **6 mundos**, **11 jefes**, tienda de mejoras, mapa gráfico de islas y el rescate final de Zelda.

> **Proyecto de fans, no oficial.** Link, Zelda, Ganon, Hyrule y otros personajes pertenecen a sus respectivos titulares. Este repositorio no está afiliado ni patrocinado por Nintendo. No se concede licencia sobre personajes ni marcas de terceros.

![Planisferio de mundos](assets/mapa-mundos.png)

## ▶️ Cómo jugar

- **En línea con GitHub Pages:** una vez activado GitHub Pages, abre la dirección publicada del sitio.
- **En tu computador:** descarga el repositorio y abre `index.html` con Chrome, Edge o Firefox.
- **No requiere instalar dependencias, Node.js ni un servidor.** El juego está incluido dentro de `index.html` (HTML, CSS, JavaScript e ilustraciones integradas).

### Controles

| Tecla | Acción |
|---|---|
| Flechas ← → | Caminar |
| Flecha ↑ | Saltar |
| **S** | Atacar con el arma equipada |
| **A** | Levantar el escudo |
| **SHIFT** | Cambiar de arma |
| **ENTER** | Alternar flechas normal, fuego y hielo (si están disponibles) |
| **U** | Abrir tienda de mejoras |
| **M** | Abrir mapa de mundos |
| **T** | Abrir portal secreto |
| **0** | Reiniciar toda la partida y borrar el progreso |

### Características

- Mundos 1–5: 8 niveles por mundo, con jefes en los niveles 4 y 8.
- Mundo 6: 3 niveles y Ganon como jefe final.
- Tienda con espada, escudo, arco, bumerán, martillo, lanza, bastón mágico, hacha y flechas de fuego y hielo.
- Compras, rupias y progreso guardados automáticamente en el navegador.
- Controles táctiles para dispositivos móviles.
- Escena final con Zelda y la Trifuerza.

![Tienda de mejoras](assets/tienda-mejoras.png)

## 🌐 Publicarlo gratis con GitHub Pages

1. Entra a [github.com](https://github.com) y crea un repositorio (por ejemplo, `aventura-link-hyrule`).
2. Selecciona **Add file → Upload files** y sube **el contenido de esta carpeta**, especialmente `index.html`, `README.md`, `.nojekyll` y `assets/`.
3. Guarda con **Commit changes**.
4. Abre **Settings → Pages** en el repositorio.
5. En **Build and deployment**, selecciona **Deploy from a branch**, la rama **main** y la carpeta **/(root)**, y guarda.
6. Abre el enlace que GitHub Pages mostrará al publicar el sitio. Habitualmente tiene el formato `https://USUARIO.github.io/NOMBRE-REPOSITORIO/`.

**Importante:** `index.html` debe estar en la **raíz** del repositorio, no dentro de otra carpeta. Si prefieres, también puedes subir los archivos con Git desde tu computador.

## 💾 Guardado y contraseña

- El progreso se almacena con `localStorage`: funciona en ese mismo navegador y origen web, pero **no se sincroniza automáticamente** entre dispositivos.
- Si cambias desde un archivo local a GitHub Pages, es posible que tengas que empezar de nuevo, porque la dirección del juego cambia.
- La tecla **0** elimina el progreso del juego en ese navegador; úsala solo si quieres reiniciar.
- **El portal secreto no constituye un mecanismo de seguridad.** Aunque la clave no se muestre en pantalla, la lógica del juego está en código público y puede examinarse. No uses allí contraseñas personales o importantes.

## Nota sobre derechos

Este juego es un proyecto de entretenimiento creado por fans. Los nombres, personajes y elementos de las franquicias de Nintendo siguen siendo de sus titulares. Publicar el código en GitHub no implica obtener autorización para usar esos elementos; respeta las políticas aplicables de los titulares.
