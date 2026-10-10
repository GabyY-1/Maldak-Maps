# Maldak Maps 🗺️

Carte interactive fictive de la **République de Maldak**, archipel de la planète imaginaire **M7B3**.

## Version initiale V0.1

Le site est une application web statique autonome : aucun serveur, compte, API, abonnement ou base de données n'est nécessaire.

### Fonctions opérationnelles
- Carte SVG interactive utilisable à la souris et au tactile (déplacement / zoom).
- Cinq grandes îles : Maldak, Valdorie, Solmera, Azurane et Néris.
- Recherche instantanée de quartiers, villes et lieux.
- Sélection des repères et fiches descriptives.
- Modes **Plan**, **Satellite fictif stylisé**, **Relief stylisé**.
- Interface responsive pour Chromebook, ordinateur et téléphone.
- Réinitialisation et zoom avec boutons.
- Trait de liaison indicatif vers les lieux (⚠️ ne constitue pas un itinéraire calculé).

### Données connues et limites

| Élément | Statut |
| --- | --- |
| Maldak : cinq grandes îles, 35 000 km², 20 M d'habitants | Validé pour l'univers fictif |
| Capitale : Maldak-City au fond d'une grande baie | Validé |
| Huit arrondissements et leurs populations | Propositions, non définitives |
| Gratte-ciel centraux atteignant environ 400 m | Orientation validée |
| Littoral naturel protégé et parcs vastes | Orientation validée |
| Routes et limites cartographiées dans l'interface | **Illustration conceptuelle**, ni levé ni réseau navigable |
| Satellite | **Rendu stylisé fictif**, pas une photographie |
| Relief | **Illustration**, pas un modèle numérique d'altitude |
| Itinéraires | Non calculés à ce stade |

Les dimensions et la topologie des îles sont **non à l'échelle**. Les tracés antérieurs V0.1–V0.3 élaborés en conversation n'ont pas été importés sous forme de GeoJSON authentifié dans ce dépôt ; il faut reconstruire, vérifier et géoréférencer ces données avant de les traiter comme la carte géographique officielle. Aucune donnée n'est extraite de Google Maps.

## Utiliser

Ouvrir `index.html` directement dans un navigateur moderne ou servir le dossier via n'importe quel hébergement statique.

Pour publier via GitHub Pages : **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save** (si disponible sur le dépôt).

## Améliorations V0.2

- Couches Routes et Noms activables séparément.
- Favoris enregistrés dans le navigateur (stockage local).
- Liens de partage contenant le lieu choisi et le mode de carte.
- Boutons de recentrage sur Maldak-City, favoris et partage.
- Centrage corrigé lors de la sélection d'un lieu.
- Coordonnées de zoom recalculées à partir de la transformation SVG.
- Recherche rapide avec la touche `/`, légende et retours visuels.
- Toujours aucune API ou compte requis.

## Netteté V0.3

- Typographie, contrastes et lisibilité des libellés renforcés.
- Icônes Lucide et boutons uniformisés.
- Panneaux, recherche et commandes plus nets sur ordinateur et mobile.
- Zoom centré plus précisément sur la position du pointeur.
- Toujours une carte SVG conceptuelle : la V0.3 n'est pas encore une cartographie haute définition du réseau routier.

## Cartographie V0.4

- Fond de carte de l'archipel enrichi : reliefs stylisés, parcelles agricoles, textures forestières, voies locales et petits ensembles bâtis.
- Les détails restent conceptuels, non à l'échelle : aucune photographie satellite réelle de M7B3.
- Prochaine évolution : géométrie géographique validée, rues réellement connectées et données vectorielles par zoom.

## Suite envisagée

1. Choisir le référentiel géographique fictif de M7B3 et des unités de distance.
2. Ajouter des GeoJSON versionnés (îles, régions, arrondissements, voies, bâtiments).
3. Définir intersections, sens de circulation et graphe routier connecté.
4. Remplacer le SVG initial par un moteur vectoriel type MapLibre avec fonds de carte propres.
5. Générer des tuiles de relief et textures aériennes fictives.
6. Préparer des données cohérentes avec un futur monde 3D.

## Propriété et attribution

Univers, lieux et noms fictifs de Maldak. Interface inspirée des conventions ergonomiques des services cartographiques, sans marque, données ni imagerie Google. Pas de clé Google Maps requise.
