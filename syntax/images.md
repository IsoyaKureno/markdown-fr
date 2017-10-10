# Images

```markdown
# Inline
![Alternative text](/path/to/img.jpg "Optional title")

# Reference
![Alternative text][id]
[id]: url/to/image  "Optional title"
```
Comme vous avez dû le remarquer, les images en Markdown sont très semblables aux liens.  
La différence est la suivante :
* les crochets doivent être précédés par un point d'exclamation ;
* ils peuvent contenir un texte alternatif, qui s'affiche quand l'image ne peut être chargée.

---

Voici un quiz sur les markdown images.

Sélectionne les images valides:
- [ ] `[Google logo](https://www.google.ru/logo.png)`
- [x] `![](https://www.google.ru/logo.png)`

> Les images doivent être précédées d'un point d'exclamation.
Le texte alternatif et le titre sont optionnels.

Ce qui est juste parmis les lignes suivantes: ```![Funny cat](http://cats.ru/funny.png "Share this")```
- [x] Si l'url est 404, "Funny cat" sera affiché
- [ ] Le point d'exclamation peut être ommis dans ce cas
- [ ] Si l'url est 404, "Share this" sera affiché
- [x] Au passage de la souris sur l'image "Share this" sera affiché

> Comme les liens, les images peuvent avoir 3 parties: un texte alternatif, un lien et un titre. Un point d'exclamation est nécessaire.

---
