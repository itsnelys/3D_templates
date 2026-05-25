# 3D Templates / Assets Library

## FR

Bibliotheque d'assets 3D, textures et templates utilises dans plusieurs projets de modding et creations personnelles.

Le dossier sert de base commune pour les projets *Arma 3*, Minecraft et autres integrations, avec une organisation par type d'usage.

### Organisation

| Dossier | Description |
| --- | --- |
| `items props` | Props, objets decoratifs, mobilier et elements d'environnement. |
| `items weapons` | Modeles d'armes, outils, munitions et equipements offensifs. |
| `items_clothes` | Vetements, accessoires, protections et elements de personnalisation. |
| `mapping_buildings` | Structures, batiments et elements de mapping. |
| `vehicle_airplane` | Assets lies aux avions et appareils aeriens. |
| `vehicle_helico` | Helicopteres et assets de transport aerien. |
| `vehicle_cars` | Vehicules terrestres motorises. |
| `vehicle_bicycle` | Velos et cycles. |
| `vehicle_ships` | Bateaux et vehicules nautiques. |
| `vehicle_surfing` | Assets nautiques recreatifs. |
| `vehicle_props` | Pieces, accessoires, vitres, plaques, remorques et props vehicules. |

### Integrations

| Projet | Utilisation |
| --- | --- |
| `OPA_` | Contenu milsim, vehicules, armes, equipements et props tactiques. |
| `sundae_` | Contenu roleplay, vehicules civils et props immersifs. |
| `eden_` / `irisV_` | Assets pour environnements voxel, blocs custom et world-building. |

### Types d'assets

| Type | Exemples |
| --- | --- |
| Vehicules | Voitures, camions, helicos, avions, bateaux, velos. |
| Equipements | Armes, caisses, accessoires, vetements, protections. |
| Props | Panneaux, mobilier, objets logistiques, elements decoratifs. |
| Mapping | Batiments, stations, helipads, arrets et elements de scene. |
| Textures | Templates PNG pour livrees, vitres, accessoires et variantes. |

### Utilisation

1. Choisis le dossier correspondant au type d'asset.
2. Recupere le template ou la texture voulue.
3. Adapte le fichier au projet cible.
4. Exporte ou integre l'asset selon le pipeline du moteur utilise.
5. Garde les noms coherents avec la convention du projet cible.

### Notes techniques

- Les assets sont organises pour rester reutilisables entre plusieurs moteurs.
- Les textures servent souvent de base pour variantes, livrees ou skins.
- Certains dossiers contiennent des sous-categories par marque, modele ou type de piece.
- Les assets peuvent necessiter une optimisation specifique selon la plateforme cible.

### Depannage

| Probleme | Solution |
| --- | --- |
| Impossible de retrouver un asset | Cherche d'abord par type : vehicule, prop, arme, vetement ou mapping. |
| Une texture semble etre une variante | Verifie le dossier parent et le nom du modele associe. |
| Un asset ne correspond pas au moteur cible | Adapte le format, les LODs ou la resolution avant integration. |
| Plusieurs fichiers se ressemblent | Compare le nom complet, la marque, le modele et le suffixe. |

### Note de patch 0.1

- Premiere version documentee.
- Organisation bilingue au format commun.
- Description des categories principales d'assets.
- Ajout des usages Arma 3, roleplay, Minecraft et projets voxel.

---

## EN

Library of 3D assets, textures, and templates used across several modding projects and personal creations.

The folder acts as a shared base for *Arma 3*, Minecraft, and other integrations, organized by usage type.

### Organization

| Folder | Description |
| --- | --- |
| `items props` | Props, decorative objects, furniture, and environment pieces. |
| `items weapons` | Weapon models, tools, ammunition, and offensive equipment. |
| `items_clothes` | Clothing, accessories, protective gear, and customization pieces. |
| `mapping_buildings` | Structures, buildings, and mapping elements. |
| `vehicle_airplane` | Airplane and aviation-related assets. |
| `vehicle_helico` | Helicopters and air transport assets. |
| `vehicle_cars` | Motorized ground vehicles. |
| `vehicle_bicycle` | Bicycles and cycles. |
| `vehicle_ships` | Boats and nautical vehicles. |
| `vehicle_surfing` | Recreational water assets. |
| `vehicle_props` | Vehicle parts, accessories, glass, plates, trailers, and props. |

### Integrations

| Project | Usage |
| --- | --- |
| `OPA_` | Milsim content, vehicles, weapons, equipment, and tactical props. |
| `sundae_` | Roleplay content, civilian vehicles, and immersive props. |
| `eden_` / `irisV_` | Assets for voxel environments, custom blocks, and world-building. |

### Asset Types

| Type | Examples |
| --- | --- |
| Vehicles | Cars, trucks, helicopters, airplanes, boats, bicycles. |
| Equipment | Weapons, crates, accessories, clothing, protective gear. |
| Props | Signs, furniture, logistics objects, decorative elements. |
| Mapping | Buildings, stations, helipads, stops, and scene elements. |
| Textures | PNG templates for liveries, glass, accessories, and variants. |

### Usage

1. Choose the folder matching the asset type.
2. Pick the needed template or texture.
3. Adapt the file to the target project.
4. Export or integrate the asset through the target engine pipeline.
5. Keep names consistent with the target project convention.

### Technical Notes

- Assets are organized to remain reusable across multiple engines.
- Textures often serve as a base for variants, liveries, or skins.
- Some folders contain subcategories by brand, model, or part type.
- Assets may require platform-specific optimization before integration.

### Troubleshooting

| Problem | Fix |
| --- | --- |
| Cannot find an asset | Search first by type: vehicle, prop, weapon, clothing, or mapping. |
| A texture looks like a variant | Check the parent folder and associated model name. |
| An asset does not fit the target engine | Adapt format, LODs, or resolution before integration. |
| Several files look similar | Compare the full name, brand, model, and suffix. |

### Patch Note 0.1

- First documented release.
- Bilingual organization using the shared README format.
- Description of the main asset categories.
- Added Arma 3, roleplay, Minecraft, and voxel project usage notes.

---

## License & Author

Provided by **soraanoir/sundae https://github.com/soraanoir**.  
Free to use and modify, provided that credit is given to the author.
