# Bachaquero Tycoon: Economía Extrema 2D

Simulador de bodega y mercado en **pixel art**, hecho con HTML5 Canvas y JavaScript puro (un solo archivo, sin dependencias ni compilación).
Funciona en teléfono, tablet y PC. En móvil y tablet se juega en horizontal.

## Cómo se juega
1. **Prólogo:** junta $50 de capital. El hombre corta monte en el campo; la mujer trabaja una semana en la tienda china entregando pedidos.
2. **Mercado (3:00 a 5:00 AM):** camina entre 6 puestos, escucha al vendedor y abre su libro de productos para comprar bultos de 10 unidades. Cada puesto cobra distinto.
3. **Camino a la tienda:** 1 minuto manejando por la ciudad, con semáforos, elevados y alcabalas.
4. **Bodega:** agarra los bultos y suéltalos en los estantes antes de que se acabe el tiempo.
5. **Tienda (6 AM a 8 PM):** atiende a los clientes, arma la bolsa, cobra en la computadora (efectivo, divisa o punto de venta) y despacha. Gana el 30 % sobre el costo de cada bulto.
6. **Factura:** al cerrar el día ves ventas, ganancias, pérdidas y XP. El nivel sube al cerrar.
7. **Nivel 100:** se desbloquea la Tienda de Mayoreo.

## Controles
| | Teléfono / tablet | PC |
|---|---|---|
| Mover | Joystick a la izquierda o tocar el mapa | Flechas o WASD |
| Acción principal | Botones a la derecha | Espacio o E |
| Atender / despachar / soborno | Botones redondos | X / C / B |
| Manejar | Joystick + pedales | A-D dirigen, W acelera, S o espacio frena |

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `bachaquero-tycoon`) y sube todo el contenido de esta carpeta.
2. Ve a **Settings → Pages**.
3. En *Build and deployment* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y pulsa **Save**.
4. En uno o dos minutos el juego estará en `https://TU-USUARIO.github.io/bachaquero-tycoon/`.
5. En Chrome (Android) abre ese enlace y usa **Instalar app / Agregar a pantalla de inicio** para tenerlo como aplicación.

## Archivos
- `index.html`: el juego completo.
- `manifest.webmanifest` y `sw.js`: permiten instalarlo y jugar sin conexión.
- `icons/`: íconos de la aplicación.

## Notas
- El progreso se guarda en el navegador (LocalStorage) de cada dispositivo.
- Las tipografías pixel (Silkscreen y VT323) se cargan desde Google Fonts. Sin conexión se usa una tipografía de respaldo.
