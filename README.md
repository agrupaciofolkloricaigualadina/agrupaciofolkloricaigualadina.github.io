# Agrupació folklòrica igualadina
L'agrupació Folklòrica Igualadina és una entitat de dansa tradicional igualadina que propaga la cultura popular i tradicional des de 1940.

Aquesta pàgina web és un projecte de l'agrupació folklòrica igualadina que pretén donar a conèixer la seva història, les seves danses i les seves actuacions.

# Instal·lació i execució en local
## Windows
Per poder executar aquest projecte en local, cal tenir `git` instal·lat al sistema. Si no el tens, pots descarregar-lo des de [aquí](https://git-scm.com/downloads).

Un cop tinguis `git` instal·lat, obre una terminal i executa les següents ordres per clonar el repositori i instal·lar les dependències:

```bash
git clone https://github.com/agrupacio-folklorica-igualadina/agrupacio-folklorica-igualadina.github.io.git agrupaciofolkloricaigualadina
```

(potser cal afegir `git` al PATH si no està disponible a la terminal)

Després, accedeix al directori del projecte:

```bash
cd agrupaciofolkloricaigualadina
```

Aquest projecte utilitza `jekyll` per generar la pàgina web. Per instal·lar-lo, cal tenir instal·lats `ruby` i `bundler`. Es poden instal·lar des de [rubyinstaller.org](https://rubyinstaller.org/downloads/) o mitjançant el gestor de paquets `chocolatey`. Després, instal·lem `jekyll` i `bundler` a través de la terminal:

```bash
gem install jekyll bundler
```

Per executar el projecte, cal instal·lar les dependències i executar el servidor de desenvolupament:

```bash
bundle install
bundle exec jekyll serve
```

La web estarà disponible a `http://`127.0.0.1:4000`.

## Arch Linux
Per a Arch Linux, podem installar:

```bash
sudo pacman -S git ruby jekyll bundler
gem install jekyll bundler
```

Un cop instal·lats, podem clonar el repositori i executar el projecte de la mateixa manera que a Windows:

```bash
git clone https://github.com/agrupacio-folklorica-igualadina/agrupacio-folklorica-igualadina.github.io.git agrupaciofolkloricaigualadina
cd agrupaciofolkloricaigualadina
bundle install
bundle exec jekyll serve
```

La web estarà disponible a `http://127.0.0.1:4000`.

# Contribució
Per editar les pàgines d'aquesta web, cal editar els fitxers `.markdown` que es troben a la carpeta `_posts`. Cada fitxer representa una entrada del bloc i ha de tenir el següent format:

```markdown
---
layout: post
title: _Títol de l'entrada_
date: _Data de l'entrada (format YYYY-MM-DD)_
categories: _Categoria de l'entrada_
---

Text de l'entrada.
```

Per afegir una nova entrada, crea un nou fitxer amb el nom `YYYY-MM-DD-titol-de-lentrada.markdown` a la carpeta `_posts`, on `YYYY-MM-DD` és la data de l'entrada i `titol-de-lentrada` és el títol de l'entrada en minúscules i sense espais.

# Publicació
Per pujar els canvis al repositori, cal fer:

```bash
git add .
git commit -m "Missatge del commit"
git push origin main
```

Això pujarà els canvis al repositori i actualitzarà la pàgina web automàticament gràcies a una acció de GitHub que s'executa cada vegada que es fa un `push` al repositori. (la web pot trigar uns minuts a actualitzar-se)

