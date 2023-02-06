# Nomenclature des usages de l'infogeo

## Préambule

A partir des thèmes métiers (se rapprochant des thèmes ign) + usages identifiés par IGN et autres récupérés pas appel à contribution national, il a été choisi de définir des verbes d'action liés pour simplifier la démarche.

Ce résultat est le fruit du travail du sous-groupe du GT.

Certains usages étant trop génériques, ils n’ont volontairement pas été traités.

D'autres sont transversaux à toutes les thématiques et c'est bien là la complexité dans la nomenclature des usages, il n'y a pas de résultat optimal.

Cela peut paraître subjectif mais c'est aussi à l’appréciation.

Il a été décidé d’arrêter certains verbes d'action, liés à ces usages pour faire une première version de la nomenclature, permettant la reprise par un autre groupe.

Quand cela a été possible/facile des exemples de données représentatives aux usages listés ont été listés.

Pour information, les données "*pivots*" font parties des données génériques que l'ont peut utiliser globalement. Cela peut concerner des référentiels, ou des données à sources vérifiées.

Nous avons ainsi identifié sept actions d'usages en plus de l'état *être base de référence*  pour les données *pivot*

## Définir les usages génériques

### Etre base de référence 

Comme dit ci-dessus, ce sont les données « pivot »

### Visualiser / cartographier

Fournir une représentation cartographique (spatiale) de la donnée

### Inventorier/recenser

Dénombrer représenter un effectif de...

### Localiser/situer

Positionner des éléments de données dans un référentiel géographique

Ex : base adresse

### Suivre/observer

Pouvoir visualiser une évolution dans le temps ; composante temporelle en plus des coordonnées.

Ex : données d’OCSOL sur plusieurs années

### Analyser

Faire un « état des lieux »

Ex : cadastre solaire

### Gérer

Administrer un territoire, une zone à des fins réglementaires, techniques, commerciales.
Données textuelles complétant les données géographiques

Ex : PLU pour administrer les autorisations d’urbanisme

### Planifier

Cela inclut des données dérivées (ex : isochrones Mnx) permettant de modéliser/simuler un phénomène ou en tout cas de se projeter sur une situation à venir

Ex : données DFCI pour l’organisation des secours

## Voici quelques exemples « métier »permettant la lecture :

- l’usage « *Positionner les réseaux sur un même référentiel* » consiste finalement à visualiser/cartographier les données, quelque soit la thématique. Dans ce cas présent, on s’attend à des coordonnées géographique permettant à minima ce positionnement. Par conséquent, la donnée liée devra contenir ces coordonnées et éventuellement contrôlée sur ces aspect

- l’usage « *Évaluer la ressource en bois-énergie disponible sur un territoire* » est en fn de compte de la visualisation/cartographie, de l’inventaire et de la localisation. Ces 3 aspect doivent être présents dans la données afin de répondre à cet usage. C’est le cas pour la BD Forêt

- l’usage « *Optimiser la planification et l'organisation des secours* » est transversal. Il permet la visualisation, le recensement, la gestion, localisation, l’analyse et la planification. La données liée à cet usage doit donc être optimale et exhaustive. Exemple, DFCI, isochrones calculés sur base routières « propre »

## Réflexions sur l’établissement de cette nomenclature

Dans le cadre de la mission du GT QuaDoGéo sur la qualification des données géographiques, il est  assez rapidement apparu la nécessité de qualifier également les usages potentiels d’une donnée.

Le sous-groupe (@jerbou, @stephanerolle, @jmarsac) s’est donc attelé à la tâche avec enthousiasme sans se douter de sa difficulté.

Après avoir essayé différentes approches sur la question et consulté les nomenclatures ou listes d’usages à notre disposition, nous nous sommes rendus compte qu’une simple classification par thème n’était pas satisfaisante et qu’un usage était défini par un couple thème/action.

Le tableau ci-dessous traduit et fournit des exemples de ces couples.

On notera que très peu d’usages (colonne 2) ne sont concernés que par un seul verbe, ce qui traduit la difficulté de notre tâche.

Ce tableau est loin d’être parfait ni même définitif.  Nous pensons cependant être arrivés au bout de notre mission menée avec la limite de moyens du bénévolat.


| **Thèmes (métier)**                                         | **Usages**                                                                               | **Exemple de données**                                                    | **Url**                                                                                  | **Visualiser<br>Cartographier** | **Inventorier<br>(Recenser)** | **Gérer** | **Localiser** | **Analyser** | **Planifier** | **Suivre<br>Observer** |
| ----------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | --------------------------- | ------------------------- | ----- | --------- | -------- | --------- | ------------------ |
| **Agriculture**                                             | Visualiser et analyser rapidement les systèmes de cultures                               | RPG                                                                       | https://geoservices.ign.fr/rpg                                                           | X                           |                           |       |           |          |           |                    |
| Simplifier la gestion de son exploitation agricole          | référentiels pédologiques                                                                |                                                                           |                                                                                          |                             | X                         |       |           |          |           |
| Interroger des données géolocalisées                        | (usage trés, trop générique ?)                                                           |                                                                           |                                                                                          |                             |                           |       |           |          |           |
| **Aménagement du territoire**                               | Favoriser la dématérialisation de l’application du droit des sols                        |                                                                           |                                                                                          |                             |                           | X     |           |          |           |                    |
| Analyser et connaitre les territoires                       | (usage trés, trop générique ?)                                                           |                                                                           |                                                                                          |                             |                           |       | X         | X        |           |
| Lutter contre l’artificialisation des sols                  | OCSOL, MOS                                                                               |                                                                           |                                                                                          |                             |                           |       | X         | X        |           |
| **Biodiversité**                                            | Cartographier les habitats naturels                                                      |                                                                           |                                                                                          | X                           |                           |       |           |          |           |                    |
| Lutter contre l'artificialisation des sols                  |                                                                                          |                                                                           |                                                                                          |                             |                           |       | X         | X        |           |
| **Chasse**                                                  | Suivre les effectifs d'animaux                                                           |                                                                           |                                                                                          | X                           | X                         | X     | X         |          |           |                    |
| Quantifier les dégâts agricoles                             |                                                                                          |                                                                           |                                                                                          | X                           |                           | X     |           |          |           |
| Cartographier les emprises chassées                         |                                                                                          |                                                                           | X                                                                                        |                             |                           |       |           |          |           |
| **Climat**                                                  | Surveiller le changement climatique                                                      | trop métier                                                               |                                                                                          | X                           | X                         | X     | X         |          |           |                    |
| Visualiser les modèles climatiques pour étudier les impacts | trop métier                                                                              |                                                                           | X                                                                                        |                             |                           |       |           |          |           |
| Fournir des données de référence sur la forêt               | bd foret                                                                                 |                                                                           | X                                                                                        | X                           |                           |       |           |          |           |
| Prévenir les risques d'incendie                             | spécifique au métier                                                                     |                                                                           |                                                                                          |                             |                           |       |           |          |           |
| **Thèmes (métier)**                                         | **Usages**                                                                               | **Exemple de données**                                                    | **Url**                                                                                  | **Visualiser<br>Cartographier** | **Inventorier<br>(Recenser)** | **Gérer** | **Localiser** | **Analyser** | **Planifier** | **Suivre<br>Observer** |
| **Culture**                                                 | Valoriser les lieux culturels et patrimoniaux                                            |                                                                           |                                                                                          | X                           | X                         |       | X         |          |           |                    |
| Contribuer à la description des territoires                 | trop vague                                                                               |                                                                           |                                                                                          |                             |                           |       |           |          |           |
| Géolocaliser des événements culturels                       |                                                                                          |                                                                           | X                                                                                        |                             |                           | X     |           |          |           |
| **Défense**                                                 | Produire des images satellitaires adaptées aux besoins militaires                        | images satellitaires (données pivot)                                      |                                                                                          | X                           |                           |       |           |          |           |                    |
| **Eau**                                                     | Disposer de connaissances sur les cours d'eau                                            | données pivot (Sandre, Carthage, Topage)                                  | https://www.sandre.eaufrance.fr/actualite/la-bd-carthage-en-licence-ouverte-open-licence | X                           | X                         | X     | X         |          |           |                    |
| Positionner les réseaux sur un même référentiel             |                                                                                          |                                                                           | X                                                                                        |                             |                           |       |           |          |           |
| Réaliser des études d'impact et de modélisation             |                                                                                          |                                                                           | X                                                                                        |                             |                           |       | X         | X        | X         |
| **Éducation**                                               | Proposer des ressources pédagogiques                                                     | edugeo ?                                                                  |                                                                                          | X                           |                           |       |           |          |           |                    |
| Utiliser un service dédié à l'enseignement de la géographie | edugeo ?                                                                                 |                                                                           |                                                                                          |                             |                           |       |           |          |           |
| **Énergie**                                                 | Fournir des données pour la rénovation énergétique des bâtiments                         | Base de données nationales des batiments (CSTB)                           | https://www.data.gouv.fr/fr/datasets/base-de-donnees-nationale-des-batiments/            | X                           | X                         | X     |           | X        |           |                    |
| Contribuer à la création d'un portail de l'énergie          |                                                                                          |                                                                           |                                                                                          | X                           |                           |       |           |          |           |
| **Espace**                                                  | Suivre l'occupation des sols                                                             | données pivot (OCS, MOS)                                                  | https://geoservices.ign.fr/ocsge                                                         | X                           |                           |       |           |          |           | X                  |
| Appuyer les contrôles de la PAC                             | (données Pivot) RPG                                                                      |                                                                           | X                                                                                        | X                           |                           | X     |           |          |           |
| Suivre un territoire après une catastrophe naturelle        | (ortho, photo sat, nuage de point)                                                       |                                                                           | X                                                                                        | X                           |                           | X     |           |          |           |
| **Europe**                                                  | Définir une ligne de frontière unique partagée                                           | (ldonnées pivot : limite de commune, territoires administratifs...)       |                                                                                          | X                           |                           |       | X         |          |           |                    |
| **Thèmes (métier)**                                         | **Usages**                                                                               | **Exemple de données**                                                    | **Url**                                                                                  | **Visualiser<br>Cartographier** | **Inventorier<br>(Recenser)** | **Gérer** | **Localiser** | **Analyser** | **Planifier** | **Suivre<br>Observer** |
| **Forêt**                                                   | Evaluer la ressource en bois-énergie disponible sur un territoire                        | BD Foret                                                                  |                                                                                          | X                           | X                         | X ?   |           |          |           |                    |
| **Mer et littoral**                                         | Surveiller et prévenir les risques naturels et les conséquences du changement climatique | (données pivot, trait de cote, litto3d, bathymetrie, LIDAR, SHOM like...) |                                                                                          | X                           | X                         | X     | X         | X        | X         | X                  |
| **Prévention des risques**                                  | Mesurer et observer pour mieux connaître les phénomènes                                  | (couches sicentifiques BRGM, Couches reglementaires DDTs...)              |                                                                                          | X                           | X                         | X     | X         |          | X         |                    |
| **Santé**                                                   | Visualiser l'offre et la consommation de soins                                           |                                                                           |                                                                                          | X                           | X                         |       |           |          |           |                    |
| **Sécurité**                                                | Optimiser la planification et l'organisation des secours                                 | (DFCI, isochrones temps intervention)                                     |                                                                                          | X                           | X                         | X     | X         | X        | X         |                    |
| Développer la connaissance de son environnement             | (données pivot SEVESO, )                                                                 |                                                                           | X                                                                                        | X                           | X                         |       |           |          |           |
| **Social**                                                  | Organiser la coopération entre acteurs multisectoriels                                   | (Données pivot, FINESS)                                                   | https://www.data.gouv.fr/fr/datasets/finess-extraction-du-fichier-des-etablissements/    | X                           | X                         |       | X         |          |           |                    |
| **Télécoms**                                                | Localiser les antennes radioélectriques                                                  |                                                                           |                                                                                          | X                           | X                         | X     |           |          |           |                    |
| Etablir une cartographie des zones blanches                 | (données pivot, ARCEP)                                                                   |                                                                           | X                                                                                        | X                           |                           | X     |           |          |           |
| **Tourisme**                                                | Valoriser les territoires                                                                | (datatourisme, autres...POI, hébergements, Zones touristiques)            |                                                                                          | X                           |                           | X     |           | X        |           |                    |
| **Transports et mobilité, Accéssibilité**                   | Contribuer à la stratégie nationale pour le véhicule autonome                            | (données pivot, Routing,)                                                 |                                                                                          |                             |                           |       |           |          |           |                    |
| **Réseaux**                                                 | Gérer les réseaux secs                                                                   | (hors IGN) Données pivot, ENEDIS                                          |                                                                                          | X                           | X                         |       | X         |          | X         |                    |
| Gérer les réseaux humides                                   | (hors IGN) Données pivot, ENEDIS                                                         |                                                                           | X                                                                                        | X                           |                           | X     |           | X        |           |
