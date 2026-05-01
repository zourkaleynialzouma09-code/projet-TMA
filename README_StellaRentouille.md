# StellaRentouille

Application React simulant une plateforme de location d’astres (planètes, astéroïdes et étoiles).  
Le projet consiste à corriger des bugs existants et à améliorer l’expérience utilisateur sur une base déjà fournie.

## Équipe

- Abdoul  
- Hawa  
- Rassoulou  

## Installation

git clone https://github.com/Atsuko-lab/StellaRentouille.git  
cd StellaRentouille/StellaRentouille-main/StellaRentouille  
npm install  
npm run dev  

## Travail réalisé

Le projet repose sur :
- la correction de bugs identifiés dans l’application
- l’analyse de leur origine
- la mise en place de corrections propres
- l’ajout d’améliorations fonctionnelles et visuelles

## Corrections des bugs

### Abdoul

Bug 1 — Formulaire de contact (saisie)  
Correction : suppression des handlers bloquants et retour à une gestion standard des inputs.

Bug 4 — Présence de la Terre  
Correction : filtrage des données au chargement.

Bug 7 — Bouton “Louer cet astre”  
Correction : ajout d’un handler permettant de fermer la popup.

Bug 10 — Fond coupé (Accueil)  
Correction : ajustement CSS (viewport dynamique, répétition du fond, correction du body).

### Rassoulou

Bug 3 — Soleils non affichés  
Correction : correction du fetch et mise en place d’un état de chargement global.

Bug 6 — Dropdown inactif  
Correction : ajout d’un état React et filtrage dynamique.

Bug 9 — Redirection des astéroïdes  
Correction : suppression du Link et ajout d’un onClick.

### Hawa

Bug 2 — Bouton envoyer  
Correction : activation du submit.

Bug 5 — Mars cliquable  
Correction : condition sur l’état.

Bug 8 — Images manquantes  
Correction : correction des chemins + fallback.

## Améliorations

### Abdoul

- recherche par nom en temps réel  
- refonte visuelle (Accueil et Marché)

### Rassoulou

- message si aucun résultat  
- meilleure visibilité des astres indisponibles  

### Hawa

- menu hamburger responsive  

## Structure

src/  
 ├── components/  
 ├── services/  
 └── main.jsx  

## Conclusion

Le projet a permis de stabiliser l’application et d’améliorer l’expérience utilisateur, avec une interface plus claire et cohérente.
