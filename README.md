# Inkoma — site public

Présentation, politique de confidentialité, mentions légales et contact de
l'application iPad **Inkoma** (dessiner et animer), gratuite.

Publiée via GitHub Pages : https://jeromehouix.github.io/inkoma-site/

Ce dépôt ne contient que la page web publique. Le code source de
l'application est hébergé séparément. Les questions, problèmes, idées et
demandes sur la confidentialité passent par les
[formulaires](https://github.com/jeromehouix/inkoma-site/issues/new/choose)
(`.github/ISSUE_TEMPLATE`, en français et en anglais).

## Contenu

| Fichier | Rôle |
| --- | --- |
| `index.html` | La page complète en français (présentation, confidentialité, œuvres, conditions, mentions légales, contact) |
| `<langue>/index.html` | La même page en anglais, espagnol, allemand, italien, portugais (Brésil), néerlandais, japonais, chinois simplifié et coréen |
| `inkoma.png` | L'icône de l'app |
| `.github/ISSUE_TEMPLATE/` | Les formulaires de contact : question, problème, idée, confidentialité |

## À tenir à jour

Les pages sont générées par `Scripts/site.py` (dépôt de l'app) : le texte
reprend mot pour mot la page « À propos » de l'app dans chaque langue (la
présentation et le contact, propres au site, sont dans
`Scripts/site-textes.json`). On ne
modifie pas ces fichiers à la main : on change le texte dans l'app, puis on
relance le script.

---

© 2026 Jérôme Houix
