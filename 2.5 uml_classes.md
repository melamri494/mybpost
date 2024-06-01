# Diagramme de Classes #

## Notifications ##
- `id_notification`: int
- `id_utilisateur`: int
- `id_expedition`: int
- `message`: string
- `date_notification`: date

## Utilisateurs ##
- `id_utilisateur`: int
- `nom_utilisateur`: string
- `email`: string
- `mot_de_passe`: string
- `role_utilisateur`: string
- `date_creation`: date

## Colis ##
- `id_colis`: int
- `id_utilisateur`: int
- `statut_livraison`: string
- `poids`: int
- `dimensions`: int
- `adresse`: string

## Expeditions ##
- `id_expedition`: int
- `id_colis`: int
- `localisation_actuelle`: string
- `date_livraison_estimee`: date
- `date_creation`: date
- `mise_a_jour_statut`: string
- `date_mise_a_jour`: date

## Problemes_Livraison ##
- `id_probleme`: int
- `id_expedition`: int
- `type_probleme`: string
- `date_creation`: date
- `statut_resolution`: bool
- `date_mise_a_jour`: date

## Communications ##
- `id_communication`: int
- `id_expedition`: int
- `id_utilisateur`: int
- `date_communication`: date
- `message`: string

## Confirmation_livraison ##
- `id_confirmation`: int
- `id_expedition`: int
- `date_confirmation`: date
- `signature_electronique`: string

  
![Class Diagram1](https://github.com/melamri494/mybpost/assets/120380659/484cdf93-2715-4491-9102-593307e63544)


