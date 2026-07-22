# Projet 8 OpenClassrooms : Portfolio de Nina Carducci (Optimisation SEO et Performance)

Ce projet consiste en l'optimisation globale du site vitrine d'une photographe professionnelle basée à Bordeaux, Nina Carducci. L'objectif principal est d'améliorer les performances techniques, l'accessibilité, le référencement naturel (SEO) local et l'impact sur les réseaux sociaux.

<img width="600" alt="Capture_site_Nina_Carducci" src="https://github.com/user-attachments/assets/2a303f48-8871-4e74-9002-3c11ce235de5" />


## 🚀 Objectifs du Projet
*   **Performance :** Augmenter la vitesse de chargement globale.
*   **SEO :** Améliorer l'indexation et la visibilité sur les moteurs de recherche.
*   **Accessibilité :** Rendre le site pleinement utilisable pour les personnes en situation de handicap.
*   **Référencement Local et Social :** Structurer les données de l'entreprise et optimiser les partages communautaires.

## 🌐 Démo en ligne
Ce projet est hébergé sur Vercel. Vous pouvez le consulter ici : [Site de Nina Carducci](https://oc-p8-optimisez-le-referencement-d.vercel.app/)

## 🛠️ Optimisations Réalisées

### 1. Performance et Vitesse de Chargement
*   **Optimisation des images :** Conversion de tous les visuels lourds (`.jpg`, `.png`) vers le format moderne **WebP**. Redimensionnement des dimensions physiques aux tailles d'affichage réelles et compression logicielle.
*   **Minification des ressources :** Allègement des fichiers locaux CSS et JavaScript (suppression des espaces, sauts de ligne et commentaires).
*   **Nettoyage des dépendances :** Remplacement de la version de développement lourde de Bootstrap (`bootstrap.css`) par sa version de production nativement minifiée (`bootstrap.min.css`).
*   **Scripts non bloquants :** Ajout de l'attribut `defer` sur les balises de scripts pour prioriser le rendu visuel de la page (HTML/CSS).

### 2. SEO & Structure Sémantique
*   **Sémantique HTML5 :** Restructuration complète du code en remplaçant les blocs génériques `<div>` par des balises sémantiques ciblées (`<header>`, `<main>`, `<section>`, `<footer>`).
*   **Hiérarchie des titres :** Réorganisation logique des balises de titre (`<h1>` à `<h6>`) pour une meilleure indexation par les robots de recherche.
*   **Métadonnées fondamentales :** Intégration des balises `<title>` et `<meta name="description">` optimisées pour le SEO.
*   **Internationalisation :** Spécification de la langue native du site via l'attribut `lang="fr"`.

### 3. Accessibilité
*   **Liaison des formulaires :** Association stricte de chaque `<label>` à son `<input>` ou `<textarea>` (via `for` et `id`) pour les lecteurs d'écran.
*   **Attributs alternatifs :** Ajout systématique d'attributs `alt` descriptifs pertinents sur toutes les images du portfolio et masquage des images purement décoratives (`alt=""`).
*   **Contraste visuel :** Ajustement des couleurs de navigation du slider (flèches et pagination passées en noir sur fond blanc solide) pour respecter les normes de contraste minimales.

### 4. Référencement Local & Social (Éléments Additionnels)
*   **Données structurées (Rich Snippets) :** Intégration d'un script **JSON-LD** au schéma `LocalBusiness` (Schema.org) validé sur l'outil officiel de Google (nom, adresse, téléphone, horaires, gamme de prix et image).
*   **Partage social (Métadonnées) :** Configuration du protocole **Open Graph (og:)** pour Facebook/LinkedIn et déploiement des **Twitter Cards** au format `summary_large_image` pour X.

---

## 📈 Résultats des Audits (Lighthouse)

| Catégorie          | Desktop - Score Initial | Desktop - Score Après Optimisation | Mobile - Score Initial | Mobile - Score Après Optimisation |
| :----------------- | :---------------------: | :--------------------------------: | :--------------------: | :-------------------------------: |
| **Performance**    |           73%           |              **99%**               |          68%           |             **82%**               |
| **Accessibilité**  |           68%           |              **100%**              |          68%           |             **96%**               |
| **Best Practices** |          100%           |              **100%**              |          100%          |             **100%**              |
| **SEO**            |           73%           |              **100%**              |          73%           |             **100%**              |

---

## 💻 Installation et Lancement en Local

1. Cloner le dépôt :

   ```bash
   git clone https://github.com/Sereta80/OC-P8_Optimisez_le_referencement_d_un_site_de_photographe.git
   ```

2. Aller dans le dossier du projet :

```bash
cd OC-P8_Optimisez_le_referencement_d_un_site_de_photographe
```

3. Ouvrir le fichier `index.html` directement dans un navigateur ou lancer un serveur local (via l'extension _Live Server_ de VS Code par exemple).

---

*Séréta THAI - Étudiante Intégratrice Web chez OpenClassrooms 2026*
