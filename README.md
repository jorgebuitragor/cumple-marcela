# Cumpleaños de Marcela

Tarjeta de cumpleaños en 3D para Marcela, que cumple 30 años el 6 de noviembre de 2026.

Se siente como una tarjeta de papel: se puede girar, abrir y cerrar, el dorado brilla según el ángulo y por dentro hay una foto de Marcela y un pastel con velas de número 30 para soplar.

## Cómo se usa

- **Arrastrar** la tarjeta: la gira y deja ver el reverso.
- **Tocarla** o pulsar *Abrir la tarjeta*: se abre con confeti.
- **Tocar las velas**: se apagan. Al apagar las dos aparece "¡Deseo concedido!".
- En el celular la tarjeta abierta muestra una página a la vez: se desliza o se usa el botón para pasar del pastel al mensaje.
- Teclado: `Enter` abre o cierra, las flechas la giran.

## Publicarla con GitHub Pages

1. En el repositorio: *Settings → Pages*.
2. En *Source* elige *Deploy from a branch*, rama `main`, carpeta `/ (root)`, y guarda.
3. En uno o dos minutos queda en https://jorgebuitragor.github.io/cumple-marcela/

## Editar

Todo está en `index.html`, sin dependencias ni instalación.

- **Mensaje y firma:** el bloque `<div class="note">`.
- **Nombre:** la constante `DEFAULT_NAME` en el script. También se puede cambiar desde el enlace con `#Nombre`.
