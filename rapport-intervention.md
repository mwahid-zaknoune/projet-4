# Rapport d’intervention – Projet Nina Carducci

## 1. Présentation du projet

Optimisation du site de Nina Carducci, photographe professionnelle à Bordeaux.

Objectifs du projet :

* améliorer les performances du site ;
* améliorer le référencement SEO ;
* améliorer l’accessibilité ;
* corriger les bugs présents dans la galerie ;
* mettre en place le référencement local ;
* optimiser les images du site.

---

# 2. Audit Lighthouse

## Scores avant optimisation

* Performance : 58
* Accessibility : 67
* Best Practices : 100
* SEO : 73

Problèmes détectés :

* images très lourdes ;
* absence de balises meta SEO ;
* absence de balises alt sur les images ;
* problèmes d’accessibilité ;
* absence de référencement local ;
* erreurs dans la galerie ;
* chargement lent du site.

---

## Scores après optimisation

* Performance : 75
* Accessibility : 96
* Best Practices : 96
* SEO : 100

Améliorations constatées :

* réduction importante du temps de chargement ;
* amélioration du Largest Contentful Paint ;
* disparition des erreurs SEO ;
* amélioration importante de l’accessibilité ;
* réduction du poids des images.

---

# 3. Optimisations réalisées

## Optimisation des images

Actions réalisées :

* conversion des images principales en format WebP ;
* compression des images avec Squoosh ;
* réduction du poids des images ;
* ajout du lazy loading ;
* ajout des dimensions width et height.

Résultats :

* amélioration du chargement ;
* réduction du poids total de la page ;
* amélioration du score Lighthouse.

---

## Optimisation SEO

Actions réalisées :

* ajout de la balise title ;
* ajout de la meta description ;
* ajout des balises Open Graph ;
* amélioration de la structure HTML ;
* ajout des attributs alt ;
* ajout du référencement local avec Schema.org.

Résultats :

* score SEO Lighthouse à 100 ;
* meilleure compréhension du site par les moteurs de recherche.

---

## Accessibilité

Actions réalisées :

* ajout des labels sur les formulaires ;
* ajout des textes alternatifs ;
* correction de la hiérarchie des titres ;
* ajout de lang="fr" ;
* amélioration de la structure sémantique.

Résultats :

* score Accessibilité à 96 ;
* validation WAVE sans erreur rouge.

---

## Débogage JavaScript

Bugs corrigés :

* navigation précédente/suivante dans la modale ;
* filtre actif non visible dans la galerie.

Résultats :

* galerie totalement fonctionnelle ;
* affichage correct du filtre actif.

---

# 4. Référencement local

Ajout des données locales :

* adresse ;
* téléphone ;
* horaires ;
* données structurées Schema.org LocalBusiness.

Informations ajoutées :

* 68 avenue Alsace-Lorraine, 33200 Bordeaux ;
* 05 56 67 78 89 ;
* du lundi au vendredi de 10h à 19h.

---

# 5. Cahier de recette

| Action                          | Résultat attendu                 | Résultat obtenu            | Statut |
| ------------------------------- | -------------------------------- | -------------------------- | ------ |
| Cliquer sur les filtres galerie | Filtrer les images correctement  | Fonctionne correctement    | Validé |
| Changer de filtre               | Afficher le filtre actif en doré | Fonctionne correctement    | Validé |
| Ouvrir une image                | Ouvrir la modale                 | Fonctionne correctement    | Validé |
| Cliquer sur suivant/précédent   | Naviguer entre les images        | Fonctionne correctement    | Validé |
| Charger le site                 | Affichage rapide du contenu      | Temps de chargement réduit | Validé |
| Vérifier le référencement       | SEO optimisé                     | Score SEO 100              | Validé |
| Vérifier l’accessibilité        | Aucune erreur critique           | 0 erreur WAVE              | Validé |

---

# 6. Conclusion

Le site de Nina Carducci a été optimisé afin d’améliorer :

* les performances ;
* le référencement naturel ;
* l’accessibilité ;
* l’expérience utilisateur.

Les bugs présents dans la galerie ont été corrigés et le référencement local a été mis en place.
