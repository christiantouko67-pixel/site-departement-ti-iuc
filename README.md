# Site web du département TI Expert – IUC Cameroun

Site vitrine (HTML / CSS / JavaScript) présentant le département Technologies de l'Information (TI) de l'IUC, Douala, Cameroun : Master TI en partenariat avec le CCNB (Canada), spécialités, programme, débouchés, partenaires (Huawei, CCNB, Cisco, Microsoft) et poursuite d'études.

## Équipe

| Membre | Branche | Rôle |
|---|---|---|
| FOGO TOUKO Christian Yannick | `christian-fogo` | Création du projet, structure de la page, en-tête, présentation, README |
| WELADJI HAPPI Loïc Trésor | `loic-weladji` | Sections « Spécialités » et « Programme / Débouchés » |
| NJONFA Gautier Valère | `gautier-njonfa` | Sections « Partenaires », « Poursuite d'études », « Contact » et pied de page |

## Structure du projet

```
index.html        Page principale
assets/css/       Styles (main.css, fontawesome)
assets/js/        Scripts (jQuery et plugins du template)
assets/webfonts/  Polices d'icônes
images/           Images et logo
```

## Lancer le site en local

Ouvrir `index.html` dans un navigateur (double-clic), aucune installation nécessaire.

## Organisation Git

- `main` : version stable, mise à jour uniquement par fusion de branches validées.
- Une branche par membre, créée depuis `main`.
- Messages de commit en français, à l'impératif, préfixés : `feat:`, `fix:`, `style:`, `docs:`.
  Exemple : `feat: ajout de la section Partenaires`.
- Fusion dans `main` via Pull Request relue par un autre membre.

## Crédits

Template « Stellar » par [HTML5 UP](https://html5up.net) (licence CCA 3.0). Icônes : Font Awesome. Images de démonstration : Unsplash.
