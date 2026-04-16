# Création du site "JASMIN CAFé"

L'objectif de cette tâche est de créer un site vitrine à partir du squelette et des styles du fichier `model.html`. Le site comprendra deux pages : `index.html` (Accueil) et `experience.html` (L'expérience café).

## Proposed Changes

### Fichiers HTML
Création des deux fichiers HTML reprenant la charte graphique et la structure CSS de `model.html`.

#### [NEW] [index.html](file:///c:/Users/HP/Documents/My%20Work/Vibe%20coding/businesscraper%20sites/Jasmincafe/index.html)
- **Menu (Navbar) :** Fixe (sticky), avec les liens vers les différentes sections et la page "L'expérience café".
- **Héros :** Intègre la vidéo `images/hero_video_2_cprsd.mp4` en arrière-plan.
- **Sections :**
  1. Héro (Accueil)
  2. À propos de nous
  3. Nos produits
  4. La preuve sociale
  5. Nos contacts (intégrant les informations de `contacts.txt`)
- **Pied de page (Footer) :** Informations de contact et liens utiles.

#### [NEW] [experience.html](file:///c:/Users/HP/Documents/My%20Work/Vibe%20coding/businesscraper%20sites/Jasmincafe/experience.html)
- **Menu (Navbar) :** Identique à l'accueil pour cohérence.
- **Héros :** Reprend les titres de `Page - L'expérience café.txt` avec un design engageant.
- **Sections "Bien plus qu'un café, une expérience" :**
  1. Salons & événements
  2. Formations
  3. Services café
  4. Visites & immersion

### Adaptation CSS
- Les balises `<style>` du modèle seront conservées, en incluant quelques ajouts spécifiques au besoin (ex: vidéo en arrière-plan `object-fit: cover`).

## User Review Required
- Le modèle de couleurs (basé sur le modèle "Le Charbon", avec des tons noirs, bruns, et ors) convient-il à l'image de JASMIN CAFé ?
- Validez-vous ce plan avant que je ne génère les fichiers ?

## Open Questions
- Avez-vous des textes détaillés pour "À propos de nous", "Nos produits" et "La preuve sociale" (pour la page Accueil) ou est-ce que j'utilise du faux-texte (Lorem Ipsum) pour la structure attendue ?

## Verification Plan
1. Vérification que la vidéo s'affiche correctement en fond du héros.
2. Vérification que la navigation sticky fonctionne sur les deux pages.
3. Vérification que les informations de contact correspondent bien au fichier fourni.
