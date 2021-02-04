# istruzioni per aggiungere un post

Per creare un nuovo post:
* creare un nuovo file nella directory `_post`: https://github.com/boringandsad/stefanoboring/tree/main/_posts;
* selezionare dal menu in alto a destra _Add file_ e poi _Create new file_;
* dare un nome al file (*molto importante*: il nome del file deve avere la forma `YYYY-MM-DD-titolo.md` altrimenti non verra' considerato).
* popolare il contenuto del file utilizzando questo come template:

```
---
layout: post
title: Titolo
date: YYYY-MM-DD
description: Boring&Sad
img: projectdir/banner.jpg # Add image post (optional)
tags: [tag1, tag2, tagN]
category: art
---

Descrizione del lavoro
```

* creare una directory all'interno di `assets/img` nominandola con il nome del progetto (es. _projectdir_): https://github.com/boringandsad/stefanoboring/tree/main/assets/img 
* caricare all'interno della directory un file nominato `banner.jpg`. Il file verra' utilizzato nella preview dell'articolo;
* e' possibile aggiungere altre immagini che poi potranno essere utilizzate all'interno del corpo dell'articolo.
