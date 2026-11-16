# Fleurs pour Tous

Mini-site produit réalisé en formation pour travailler l’accessibilité d’un parcours web. Il présente un coffret floral mensuel en HTML, CSS et JavaScript, sans framework.

## Parcours

- [Accueil](index.html) et accès à la fiche du coffret.
- [Fiche produit](produit.html) avec un carrousel contrôlable au clavier et une vidéo sous-titrée.
- [Contact](contact.html) avec aide à la saisie et retours de validation.

Le site comporte un lien d’évitement vers le contenu principal. Les dialogues se ferment avec Échap et rendent le focus au bouton qui les a ouverts.

## Vérifications documentées

- [Trois rapports Lighthouse en PDF](rapport/lighthouse/).
- [Captures des audits WAVE](rapport/wave/), dont un [relevé d’erreurs](rapport/wave/wave_p1_errors.png).

Ces pièces montrent les contrôles réalisés sur les pages et les écarts relevés. Elles ne constituent pas une évaluation complète de conformité WCAG.

## Exécution locale

Ouvrir `index.html` dans un navigateur. Pour vérifier la vidéo et ses sous-titres, servir le dossier avec un serveur HTTP local, par exemple Live Server dans VS Code.

Les images et icônes sont dans `assets/`. La vidéo et ses sous-titres sont dans `media/`.
