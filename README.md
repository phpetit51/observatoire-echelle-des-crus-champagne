# Communes « grand cru » et « premier cru » de l'AOC Champagne (cahier des charges 2025) et code officiel géographique

Jeu de données de l'**Observatoire VITACEAE** (Reims, France). Liste sourcée des 59 communes de la Marne dont les vins peuvent porter les mentions « grand cru » (17 communes) ou « premier cru » seul (42 communes), selon le cahier des charges de l'AOC Champagne homologué par l'arrêté du 31 juillet 2025, rapprochée du code officiel géographique.

*English summary below.*

## Contenu

| Fichier | Lignes | Description |
|---|---|---|
| `VITACEAE_communes_grand_cru_premier_cru_Champagne_2026.csv` | 59 | Une ligne par commune citée au cahier des charges (chapitre Ier, point II, b et c), avec code INSEE actuel, ancien code pour les communes devenues déléguées et écarts de graphie. |

### Colonnes

| Colonne | Contenu |
|---|---|
| `commune_cahier_des_charges` | Nom de la commune tel qu'il figure au cahier des charges |
| `mention_grand_cru` | `oui` si la commune peut porter la mention « grand cru » |
| `mention_premier_cru` | `oui` si la commune peut porter la mention « premier cru » |
| `departement` | Département (51, Marne) |
| `code_insee_commune_actuelle` | Code INSEE de la commune actuelle |
| `commune_actuelle` | Nom de la commune actuelle |
| `ancien_code_insee` | Ancien code INSEE lorsque la commune est devenue commune déléguée d'une commune nouvelle |
| `observation` | Commune nouvelle de rattachement, écart de graphie |
| `source_mentions` | Source des mentions |
| `source_code_geographique` | Source du code géographique et dates de consultation |

Format : CSV, séparateur virgule, encodage UTF-8.

## Limites

- Trois communes nouvelles regroupent des communes de rang différent (Aÿ-Champagne, Blancs-Coteaux, Val de Livre). Le cahier des charges continue de viser les anciennes communes par leur nom ; aucun avis de l'INAO consacré à ce point n'a été trouvé.
- Le projet de modification du cahier des charges approuvé par le comité national de l'INAO le 18 juin 2026 conserve les mêmes listes sous les mêmes noms.

## Étude associée

Philippe Petit, *L'échelle des crus de Champagne, de 1911 à 2026 : du barème de prix du raisin aux mentions Grand Cru et Premier Cru*, Observatoire VITACEAE, 2026 (version 1.0).
DOI : [10.5281/zenodo.24056579](https://doi.org/10.5281/zenodo.24056579)

Présentation et mises à jour : [page Observatoire VITACEAE](https://vitaceae.fr/observatoire/droit-rural-du-foncier-viticole/echelle-des-crus-champagne/)

## Autres dépôts du même jeu

- data.gouv.fr : [Communes grand cru et premier cru de l'AOC Champagne](https://www.data.gouv.fr/datasets/communes-grand-cru-et-premier-cru-de-laoc-champagne-cahier-des-charges-2025-et-correspondance-au-code-officiel-geographique/)
- Figshare : DOI [10.6084/m9.figshare.34948810](https://doi.org/10.6084/m9.figshare.34948810)

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Réutilisation libre avec mention de la source : « Observatoire VITACEAE, d'après le cahier des charges de l'AOC Champagne ».

## Auteur

Philippe Petit, VITACEAE, Reims. ORCID [0009-0000-9388-6370](https://orcid.org/0009-0000-9388-6370)
Site : [www.vitaceae.fr](https://www.vitaceae.fr)

---

## English summary

List of the 59 communes of the Marne (France) whose wines may bear the terms "grand cru" (17 communes, which may also use "premier cru") or "premier cru" only (42 communes), under the product specification of the Champagne controlled designation of origin (AOC) approved by the order of 31 July 2025. Each commune is matched with the French official geographic code: current INSEE code and name, former INSEE code where the commune has become a delegated commune of a new commune (Aÿ-Champagne, Blancs-Coteaux, Val de Livre), and spelling differences. Published by the **VITACEAE Observatory** (Reims, France).

Column names are in French (see table above). CSV, comma-separated, UTF-8. License CC BY 4.0.

Related study: DOI [10.5281/zenodo.24056579](https://doi.org/10.5281/zenodo.24056579). Project page in English: [The Champagne cru ladder](https://vitaceae.fr/en/vineyard-market-data/champagne-cru-ladder/).
