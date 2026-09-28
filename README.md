# Krokante — web de muestra

Web de una sola página (HTML + CSS + JS, sin frameworks) para el restaurante Krokante. Pensada como base de trabajo: se puede seguir editando directamente o migrar a WordPress u otra plataforma más adelante.

## Estructura

```
index.html
assets/
  css/style.css   -> todos los estilos, colores y tipografías
  js/main.js      -> menú móvil y animaciones al hacer scroll
  img/            -> fotos del restaurante
```

## Ver la web en local

Abre `index.html` directamente en el navegador, o sirve la carpeta con cualquier servidor estático, por ejemplo:

```bash
npx serve .
```

## Pendiente de confirmar

Estos datos están como placeholder en `index.html` (sección de contacto y carta) y hay que sustituirlos por los reales:

- Dirección, teléfono, email y horario (sección "Contacto")
- Precios de cada plato (sección "La carta")
- Número de WhatsApp en los botones de reserva (`https://wa.me/34000000000` y `tel:+34000000000`)

## Personalizar el color de acento

El color naranja principal está centralizado en `assets/css/style.css`, en la variable `--accent` dentro de `:root`. Cambiarlo ahí actualiza toda la web.
