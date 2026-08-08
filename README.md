# RDR2 · Seguimiento de Caza y Crafteo

Rastreador de completado para **Red Dead Redemption 2** (modo historia), pensado para tener abierto en una segunda pantalla mientras jugás. Todo funciona **offline**, sin instalar nada y sin cuentas: es un único archivo HTML que guarda tu progreso en el navegador.

## Qué hace

Dos paneles con scroll independiente:

- **🐾 Animales** — sumás con `+ / −` la cantidad de cada animal cazado en calidad perfecta. Al subir de 0 queda marcado en el **compendio** (permanente, como un logro). Cada animal tiene un botón **📍** que abre el mapa del juego mostrando **dónde cazarlo** (regiones + ubicaciones puntuales + horario + arma recomendada).
- **🧵 Ítems** — todo lo que se craftea/compra: **Trapper** (116 prendas), satchels de **Pearson**, decoración de **campamento**, trinkets/talismanes del **Fence** y sets de **retos/legendarios**. Cada ítem muestra los materiales que pide; los que ya cazaste se marcan en verde y el ítem pasa a *"Listo"*. Al comprar/craftear **descuenta los materiales** del inventario, y la compra es **irreversible**.

Incluye dashboard de progreso, búsqueda, filtros, y **exportar/importar** tu progreso en JSON.

## Cómo se usa

Abrí `index.html` con doble-click. Listo. El progreso se guarda solo en ese navegador (usá **Exportar** para backup o para pasarlo a otra PC).

## Datos y fuentes

- **Datos de caza y crafteo**: recopilados de wikis y guías públicas de la comunidad (rdr2.org, Red Dead Wiki, PowerPyx, etc.). Las ubicaciones de animales fueron cruzadas contra la [Red Dead Wiki](https://reddead.fandom.com/) (solo contenido de RDR2). Son **aproximadas** — marcan la zona/región, no el spawn exacto al píxel.
- **Mapa base**: imagen de alta resolución hecha por **u/Te_Quiero_Puta**, publicada en [este post de r/reddeadredemption2](https://www.reddit.com/r/reddeadredemption2/comments/zwwcz6/i_made_a_high_res_file_of_the_rdr2_map/). Todo el crédito del mapa a su autor.
- El link opcional *"Ver zona exacta en rdr2map.com"* abre [rdr2map.com](https://rdr2map.com) (servicio de terceros) para quien quiera el detalle preciso.

## Aviso legal

Proyecto **fan, sin fines de lucro y sin monetización**, con fines informativos. *Red Dead Redemption 2*, su mapa y todo el material relacionado son **© Rockstar Games**. Este proyecto no está afiliado ni respaldado por Rockstar Games. El mapa base pertenece a su autor (ver arriba). Si algún titular de derechos quiere que se remueva algo, se remueve.

## Licencia

El **código y la compilación de datos** de este proyecto están bajo licencia **[MIT](LICENSE)** — hacé lo que quieras: usalo, modificalo, expandilo, redistribuilo (incluso con fines comerciales), solo mantené el aviso de copyright.

La MIT **no** cubre el contenido de terceros: el **mapa base** es de **u/Te_Quiero_Puta** (ver arriba) y *Red Dead Redemption 2* es **© Rockstar Games**. Si forkeás el proyecto, respetá esos derechos y mantené la atribución.

> Editá el `LICENSE` y reemplazá `<TU-NOMBRE-O-USUARIO-DE-GITHUB>` por tu nombre o usuario.

## Archivos

- `index.html` — la app (todo incluido).
- `map_med_res.jpg` — mapa base (4500×3502).
- `README.md` — este archivo.
- `LICENSE` — licencia MIT + nota de terceros.
