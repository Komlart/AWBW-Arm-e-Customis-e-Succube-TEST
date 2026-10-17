# AWBW Lust Wars Army 💗

**AWBW Lust Wars Army** est un importeur d'armées personnalisées pour **Advance Wars By Web (AWBW)**. Il permet de charger plusieurs armées depuis des **dossiers GitHub distincts** et de les attribuer aux factions d'AWBW.

Le bouton **💗 Lust Wars** se place à côté de **End** lorsqu'il est disponible. Dans **Tampermonkey**, le script affiche aussi une petite **icône cœur “LW”** dans la liste des scripts installés. L'importeur inclut également :

- La correction des marges pour les **GIF d'unités exactement en 64×64 pixels**, affichés dans une véritable boîte de 16×16 dans le navigateur.
- Le retournement horizontal des animations `_mside.gif` lorsque l'unité se déplace vers la gauche.
- La mémorisation des armées importées et de leur attribution aux factions.

Les GIF originaux restent inchangés sur GitHub.

## Armées disponibles

| Armée | Univers / thème | Sprites et animations | Dossier de GIF |
| --- | --- | --- | --- |
| **Crimson Libido** | Succubes, magie et rose sombre | **Komlart** | [Ouvrir le dossier](CrimsonlibidoArmée/) |

<!-- POUR AJOUTER UNE NOUVELLE ARMÉE :
Copier la ligne ci-dessous juste après celle de Crimson Libido,
puis remplacer le nom, le thème, le créateur et le nom du dossier.
| **Nom de la nouvelle armée** | Son thème | Nom du créateur | [Ouvrir le dossier](Nom-du-dossier/) |
-->

*Cette liste pourra grandir au fil du projet.* Le dossier `CrimsonlibidoArmée` ci-dessus est le nom utilisé lors des premiers tests ; si tu l'as renommé, adapte uniquement son lien dans ce tableau.

**Chaque armée possède son propre dossier** avec des GIF aux noms attendus par l'importeur, par exemple `xxinfantry.gif`, `gs_xxinfantry.gif`, `xxinfantry_mside.gif`, `xxinfantry_mup.gif` ou `xxinfantry_mdown.gif`.

## Installer l'importeur

1. Installer un gestionnaire de scripts tel que **Tampermonkey**.
2. Installer le fichier [`AWBW-Lust-Wars-Army-v1.2.1.user.js`](AWBW-Lust-Wars-Army-v1.2.1.user.js), ou coller son contenu dans le script Lust Wars existant puis enregistrer.
3. **Désactiver** l'addon de Vesper d'origine et les anciens correctifs autonomes pour éviter les conflits.
4. Dans une partie AWBW, cliquer sur **💗 Lust Wars** à côté de **End**.
5. Pour chaque armée, ouvrir **son dossier de GIF** sur GitHub et copier son URL (par exemple `https://github.com/UTILISATEUR/DEPOT/tree/main/NOM-DU-DOSSIER`).
6. Cliquer sur **Importer**, puis choisir la faction AWBW à laquelle attribuer cette armée.

**Important :** importer le lien du **dossier d'une armée**, et non simplement la page d'accueil du dépôt. Une fois plusieurs armées importées, on peut choisir laquelle affecter à chaque faction. L'importeur n'ajoute pas de nouvelles factions officielles au jeu : il remplace leurs graphismes localement.

## Crédits

| Contribution | Crédit |
| --- | --- |
| **Projet, créations originales, sprites et animations de Crimson Libido** | **Komlart** |
| Adaptation et correctifs de l'importeur | **Code généré avec ChatGPT (OpenAI)**, à la demande et sous la direction de Komlart |
| Script d'origine **AWBW Custom Army Importer 2.7.1** | **Vesper / ShinyDeagle** |
| Sprites et animations d'autres armées futures | Leurs auteurs respectifs, à ajouter dans le tableau ci-dessus |

- [Code de l'importeur original de Vesper](https://greasyfork.org/en/scripts/521087-awbw-custom-army-importer-beta-2-7-1/code)
- [Exemples et documentation de Vesper](https://github.com/ShinyDeagle/My-Custom-Army)

## Licence et droits

Le **code de l'importeur** est proposé sous **licence MIT**, conformément à la licence annoncée par Vesper pour son script original. Les mentions nécessaires sont conservées dans le fichier `.user.js` et dans [`LICENSE`](LICENSE).

**Les sprites, personnages, dessins et animations de Komlart ne sont PAS placés sous licence MIT par cette documentation.** Ils restent des créations de Komlart. Chaque nouvelle armée pourra préciser ses propres conditions d'utilisation.

Projet indépendant créé par des fans, sans affiliation officielle avec AWBW, Advance Wars ou Nintendo.
