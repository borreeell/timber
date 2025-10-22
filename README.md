# Timber

Un clon simple del popular joc **Timberman**, desenvolupat durant les classes de programacio utilitzant C++ i la llibreria SFML per a grafics, sons i interaccio amb l'usuari. 

## Contingut del repositori
- ``timber.cpp`` - Codi del joc
- ``graphics/`` - Carpeta amb els grafics del joc
- ``fonts/`` - Carpeta amb la font utilitzada per els textos del joc
- ``sound/`` - Arxius de so del joc (S'implementara en els proxims dies)

## Caracteristiques:
- Jugador que ha de tallar un arbre amb una destral canviant de costat segons on baixin els obstacles.
- Temps limitat amb barra de temps.
- Obstacle (branques) que poden matar al jugador.
- Entitats mobils decoratives (nuvols i abella).
- Tronc volant visualment quan el jugador talla.
- Marcador amb la puntuacio en temps real.

## Controls
- **Enter** - Començar o reinciar el joc.
- **Fletxes dreta/esquerra** - Tallar l'arbre per la dreta o l'esquerra.
- **Esc** - Sortir del joc

## Estructura del joc
- **Player** – Sprite que es mou a l’esquerra o dreta per tallar arbres.
- **Branch** – Obstacles que poden fer perdre el joc si col·lisionen amb el jugador.
- **NPC** – Entitats mòbils com núvols i abella.
- **Log** – Tronc volant visual que apareix al tallar arbres.
- **Time Bar** – Barra que mostra el temps restant per cada acció.
- **Score Text** – Mostra la puntuació actual.

## Millores properes
- [x] Afegir sons al morir el jugador, acabar-se el temps, etc..
- [ ] Properament mes 



