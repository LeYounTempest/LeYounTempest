# LeYounTempest

Portafolio personal de LeYounTempest: sitio estático de una sola página (`index.html`), sin build ni dependencias.

© 2026 LeYounTempest. Todos los derechos reservados (ver [LICENSE](LICENSE)).

## Cómo agregar cosas

- **Imágenes de modelos:** copia un `<article class="mcard">` en la sección *Modelos 3D* de `index.html` y cambia imagen, nombre y rol.
- **Capturas de Alice o del juego:** guarda la imagen en `assets/` y cámbiala en la galería correspondiente.
- **Avances del RTS:** copia un `<li>` de la lista `.log` (bitácora), ponlo arriba y cambia la fecha.
- **Donadores de Ko-fi:** copia un `<li>` de la lista `.donors` con el nombre (con su permiso) y borra el `<li class="vacio">`.
- **Recortes de Aurelia:** `python3 herramientas/recortes.py` los regenera a partir de las hojas de `assets/`; `herramientas/promo.py` hace lo mismo con las imágenes de Monster Siege.
