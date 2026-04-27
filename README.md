# Torneig de Batalles de Calbs

Mini-joc web inspirat en el *53.º Torneo de Batallas de Calvos*: dos calbs asseguts cara a cara amb una ventosa al cap, unides per un fil. Guanya qui aconsegueix que la ventosa del rival cedeixi.

**Juga-hi:** https://xavier-lc.github.io/combat-de-calbs/

## Com es juga

Cada jugador masteguen la seva tecla per estirar el fil; com més fort estiris, més erosiones l'adherència de la ventosa del rival. Si tu també estires alhora, contrarestes part de la força que rep la teva ventosa. La primera ventosa que cedeix fa **PLOC!** i el seu jugador perd.

| Acció | Tecla |
|---|---|
| Començar (1 jugador vs CPU) | `Espai` o clic |
| Mode 2 jugadors locals | `V` |
| Tibar — Jugador 1 (el bigotut) | `A` (també `Z` o `←`) |
| Tibar — Jugador 2 (el cicatriu) | `L` (també `M` o `→`) |

En mòbil/tauleta apareixen dos botons grans als laterals.

## Estructura

Tot el joc viu en un únic fitxer: `index.html` (HTML + CSS + JavaScript canvas, sense dependències externes). Les imatges `IMG_*.jpg` són les pàgines del còmic original que van inspirar el joc.
