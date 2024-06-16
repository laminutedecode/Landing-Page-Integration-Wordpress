# LandingPageWordPress

Ce repository contient une intégration d'une landing page avec PHP, WordPress, et le plugin Advanced Custom Fields (ACF). Il comprend trois dossiers principaux :
1. `static` : Développement de la landing page en HTML, CSS et JavaScript.
2. `integration` : Intégration de la landing page avec WordPress en utilisant PHP et ACF.

## Contenu du Repository

### Static
Ce dossier contient tous les fichiers statiques (HTML, CSS, JavaScript) utilisés pour développer la landing page avant l'intégration avec WordPress.

### Integration
Ce dossier contient l'intégration de la landing page statique avec WordPress en utilisant PHP et le plugin ACF. Vous y trouverez les fichiers de template WordPress, les fonctions PHP, et les hooks nécessaires pour faire fonctionner la landing page avec WordPress et ACF.


## Prérequis

- WordPress installé
- Plugin Advanced Custom Fields (ACF) installé et activé

## Installation

1. Clonez ce repository :
    ```bash
    git clone https://github.com/votre-utilisateur/LandingPageWordPress.git
    ```
2. Copiez les dossiers `integration` et `childtheme` dans le répertoire `wp-content/themes` de votre installation WordPress.
3. Activez le thème parent (dossier `integration`) puis le thème enfant (dossier `childtheme`) depuis l'interface d'administration de WordPress.
4. Importez les configurations ACF incluses dans le dossier `integration/acf-json` en utilisant l'importation de champs personnalisés d'ACF.

## Utilisation

Vous pouvez maintenant utiliser et personnaliser votre landing page comme bon vous semble. Pour toute modification majeure, il est recommandé de le faire dans le thème enfant.

## Contribuer

Les contributions ne sont actuellement pas acceptées car ce repository est destiné à un usage spécifique dans le cadre de la formation "Développer une landing page avec WordPress et ACF" sur [laminutedecode.com](https://laminutedecode.com).

## Licence

Ce projet est la propriété de LaMinuteDeCode. Il est strictement interdit de copier ou de vendre cette landing page. Voir le fichier `LICENSE` pour plus de détails.
