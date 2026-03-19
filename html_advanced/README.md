# HTML Advanced — Récap du travail (version humaine)

Franchement, ce projet m’a surtout appris une chose : en HTML, **la rigueur bat la vitesse**.

J’ai construit toute la série d’exercices pas à pas (de `0-index.html` jusqu’aux fichiers finaux `index.html` et `styleguide.html`) en respectant la logique demandée :

- partir du fichier précédent ;
- ne changer que ce qui est demandé à l’étape suivante ;
- garder une structure sémantique propre ;
- éviter d’ajouter du “bonus” qui n’est pas demandé.

---

## Ce que j’ai fait concrètement

J’ai généré et vérifié tous les fichiers demandés dans ce dossier :

- les étapes `0` à `37` pour la partie homepage ;
- les étapes `11`, `13`, `26`, `28`, `30`, `32`, `33`, `34`, `38`, `39` et finale pour le styleguide ;
- les pages intermédiaires `article.html`, `about.html`, `latest_news.html`, `contact.html`.

Chaque fichier suit la progression pédagogique (headings, sections, wrappers, liens, listes, blockquotes, médias, iframe, etc.).

---

## Ma méthode de travail

J’ai avancé exactement comme un reviewer strict :

1. **Base propre** (doctype, `html`, `lang`, `dir`, `head`, `body`).
2. **Structure globale** (`header`, `main`, `footer`).
3. **Structure interne** (sections, `article`, niveaux de titres).
4. **Sémantique avancée** (`address`, `blockquote`, `details`, `pre`, `mark`, `table`, `video`, `audio`, `iframe`).
5. **Finalisation** (images, SVG, liens internes, cohérence des wrappers et des IDs).

Objectif : que chaque fichier soit lisible, logique, et fidèle à l’énoncé.

---

## Corrections importantes faites en cours de route

J’ai aussi corrigé des points qui cassent souvent les validations :

- `dir="ltr"` et `lang="en"` bien présents ;
- titres de page exacts (`Homepage - Techium`, `Styleguide - Techium`, etc.) ;
- sections avec les bons IDs (`services`, `works`, `about`, `latest_news`, `testimonials`, `contact`) ;
- listes de navigation/socials bien en `ul > li > a` ;
- liens de policy valides (pas de `li href` invalide) ;
- usage correct des balises sémantiques (`address`, `blockquote`, `cite`, `details`, etc.) ;
- attributs d’images (`alt`, `width`, `height`) respectés selon l’étape ;
- SVG finaux présents avec `width="25"` et `height="25"`.

---

## Ce que je retiens

Ce projet est “simple” en apparence, mais il force à être méthodique.

Le vrai piège, ce n’est pas HTML lui-même :
**c’est de perdre la progression entre les étapes**.

En restant strict sur la copie du fichier précédent + modifications minimales, on évite 90% des erreurs.

---

## Vérification rapide recommandée

Avant rendu, refaire un check ciblé :

- niveaux de titres (`h1`, `h2`, `h3`) ;
- wrappers `div` de l’étape 15/16 ;
- commentaires de l’étape 17 ;
- structure des listes nav/footer ;
- position des auteurs en `small` ;
- balises médias et fallback text.

Si tout ça est bon, le projet est solide.

