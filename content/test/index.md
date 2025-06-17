+++
template = "article.html"
title = "Titre de niveau 1"
description = "Description. Lorem ipsum dolor sit amet, consectetur adipiscing elit."
[taxonomies]
tags = ["tag"]
[extra]
toc = true
katex = true
subtitle = "Sous-titre. Lorem ipsum dolor sit amet, consectetur adipiscing elit."
bibliography = "references.bib"
+++

## Titre de niveau 2

### Titre de niveau 3

#### Titre de niveau 4

##### Titre de niveau 5

###### Titre de niveau 6

---

## Texte

Ceci est un paragraphe de texte. Markdown permet de formater facilement du texte.

- **Texte en gras**
- *Texte en italique*
- ~~Texte barré~~
- `Code en ligne`

---

## Listes

### Liste non ordonnée

- Élément 1
- Élément 2
  - Sous-élément 2.1
  - Sous-élément 2.2
- Élément 3

### Liste ordonnée

1. Premier élément
2. Deuxième élément
   1. Sous-élément 2.1
   2. Sous-élément 2.2
3. Troisième élément

---

## Liens et Images

### Lien

[Texte du lien](https://www.example.com)

### Image

<figure>
    {{ image(url = "img/low-res-pup.png", alt="Une image de très basse résolution d'un chiot de face.", no_hover=true) }}
    <figcaption>Figure 1 : Une image de très basse résolution d'un chiot de face.</figcaption>
</figure>

---

## Code

### Code en ligne

Utilisez `print("Hello, World!")` pour afficher du texte.

### Bloc de code

```python
def hello_world():
    print("Hello, World!")
```
## Réferences

Lucien est l'homme le plus beau du monde {{ reference(key="einstein") }}
