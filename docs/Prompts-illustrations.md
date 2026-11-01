# Illustrations IA de Zajko (enfants) — prompts Gemini

Une illustration par série, pour la **fiche 05** (le dialogue, le moment fort), plus une **couverture** pour l'introduction et une scène pour le **kit de survie** (fiche 03). Même méthode que pour le cours adulte (`Slovingo-sk-fr`) et les ados (`Slovingo-sk-fr-friends`), avec les **mêmes personnages, rajeunis**.

**Style** : dessin animé 2D classique (pas de 3D), animaux qui marchent debout et portent des vêtements, décors peints réalistes pour que les lieux soient reconnaissables. Les formes sont plus rondes et plus douces que dans le cours ados : ce sont des enfants de 8 à 10 ans.

## Méthode

1. **Planche des héros** : dans Gemini, joindre `esp32/zajko-quest/art/characters/fox-reference.png`, puis `andrea-reference.png`, puis `docs/illustrations/planche-heros.jpg` (tous trois dans le repo friends), et coller le prompt « Planche des héros ». Garder la meilleure : `docs/illustrations/planche-heros.jpg` (dans ce repo). Même chose pour « Planche des seconds rôles ».
2. **Chaque scène** : nouvelle conversation, joindre **la planche des héros** (et celle des seconds rôles si la scène en contient un) + **la photo de référence** du lieu (lien Commons donné : télécharger l'image depuis la page), coller le prompt de la scène. Chaque prompt est complet : rien d'autre à ajouter.
3. Si un personnage dérive (couleurs, vêtements, taille), le redemander dans la même conversation : « Keep the characters exactly as in the attached model sheet. »
4. **Format** : paysage 16/9. Déposer l'image dans `img/illus_<NN>_<lieu>.jpg` (le nom est donné pour chaque scène). Je la réduis à 1280 px de large et l'intègre.
5. **Les défauts à surveiller** : un objet qui ne tient à rien, des humains plus réalistes que les animaux, des yeux réduits à de gros points noirs, Andrea qui redevient une lapine (voir plus bas).
6. **Si Gemini refuse** : ne pas insister avec le même texte. Nouvelle conversation, et enlever la phrase qui coince (en général une précision sur l'âge ou une émotion forte). **Ne jamais citer de film, de studio ou de personnage connu** : c'est la cause de refus la plus fréquente.

## Où va l'image dans la fiche

- **L'illustration IA prend la place de l'image d'en-tête** de la fiche 05.
- **La photo Wikimedia Commons qui y était va dans le 🇸🇰 Coin slovaque** de la même fiche (ligne `@ …` insérée dans cette section), avec sa légende et son crédit. Elle reste donc visible et le coin slovaque y gagne une vraie photo du pays.
- Pour la couverture (intro 01) et le kit 03, qui n'ont pas de coin slovaque : la photo descend plus bas dans la même fiche, à un endroit à choisir au moment de l'intégration.

**Crédits** : « Illustration générée avec Google Gemini, d'après une photo de <auteur> (Wikimedia Commons, <licence>) ». Une image faite d'après une photo CC BY ou CC BY-SA en est une œuvre dérivée : elle garde le nom du photographe, et sous CC BY-SA elle reste sous CC BY-SA (voir `img/credits.md`). Je m'en occupe à l'intégration.

## Les personnages

| | Personnage | Description à garder |
|---|---|---|
| 🦊 | Le renard (toi) | renardeau roux, 10 ans, garçon ; sweat à capuche bleu roi, sac à dos aux bretelles jaunes, jean bleu marine, baskets blanches |
| 🐰 | Andrea | **hase** (un vrai lièvre, pas une lapine), 10 ans ; pelage gris-brun moucheté, fine bande claire du front au museau, très longues oreilles dressées à pointe noire à l'intérieur rose, longues pattes arrière fines ; T-shirt vert menthe, sacoche jaune en bandoulière, short en jean, baskets rouges |
| 🐻 | Maťo | ourson brun, 9 ans, grand pour son âge, doux ; chemise à carreaux vert et brun ouverte sur un T-shirt gris, short cargo |
| 🐹 | Katka | marmotte des Alpes, 8 ans, petite (à l'épaule du renard) ; pelage gris-brun, petites oreilles rondes, incisives visibles, queue courte et touffue ; sweat violet, écouteurs autour du cou |
| 🐑 | Babka Zuzana | brebis âgée, laine blanche, petites lunettes rondes ; costume traditionnel : foulard rouge à fleurs, gilet noir brodé, chemise blanche brodée, tablier blanc, jupe rouge |
| 🦔 | Pani Ježková | dame hérisson, commerçante ; tablier de magasin bleu clair, petites lunettes |
| 🦅 | Pán Orol | aigle royal, garde du parc ; chapeau de garde forestier, gilet vert kaki avec un insigne en forme de sapin |

Le renard n'a pas de prénom écrit dans les prompts : dans le cours, c'est « toi ».

**Andrea, hase et pas lapine** : c'est la correction qu'il a fallu faire sur ChatGPT (première version trop proche d'un lapin de dessin animé). Les prompts la décrivent donc dès le départ avec les oreilles longues à pointe noire, les pattes arrière longues, le pelage moucheté et le visage un peu anguleux.

---

## Planche des héros

**À joindre** : `fox-reference.png`, `andrea-reference.png`, puis `planche-heros.jpg` (celle de friends).

```
Character model sheet for a friendly animated film for children, on a plain light background. Four young animal characters standing side by side at the same scale, each shown front view and three-quarter view, full body, with a few facial expressions (smiling, surprised, shy). They are friends living in the Tatra mountains of Slovakia.

The attached images show these same characters as older teenagers. Keep the same species, colours, clothes and recognisable look, but redraw them as clearly YOUNGER children (8 to 10 years old): rounder heads, bigger eyes, shorter limbs, softer shapes, gentle friendly expressions.

1. A 10-year-old red fox boy (bright orange fur, black ear tips, white muzzle and chest, white tail tip, curious lively eyes), wearing a royal-blue hoodie, a backpack with yellow straps, navy jeans and white sneakers. Use the first attached image as the design reference.
2. Andrea, a 10-year-old hare girl — a real hare, not a rabbit (speckled grey-brown fur, a thin light blaze from forehead to muzzle, very long upright ears with pink insides and black tips, long slender hind legs, a slightly angular face, calm and slightly ironic look), wearing a mint-green T-shirt, a yellow cross-body bag, denim shorts and red sneakers. Use the second attached image as the design reference.
3. Maťo, a 9-year-old brown bear cub, taller and broader than the others, gentle and calm, wearing an open green-and-brown checked shirt over a grey T-shirt and cargo shorts.
4. Katka, an 8-year-old alpine marmot girl, small and quick (small round ears close to the head, grey-brown fur, visible front teeth, a short bushy tail), cheerful and direct, wearing a purple hoodie with earbuds around her neck.

Height: the hare's ears aside, the fox and the hare are about the same height; Maťo is a head taller than them; Katka reaches the fox's shoulder.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, expressive faces. Warm, natural light. Anthropomorphic animals walk upright, wear clothes and live among ordinary humans, who are drawn in the same 2D style and find this normal. No text, no letters, no speech bubbles, no logos, no watermark.
```

Si Andrea sort en lapine, dans la même conversation :

```
Great, keep everything but make this change: Andrea is a hare, not a rabbit — longer ears with black tips, longer hind legs, slightly speckled grey-brown fur on the back, a more angular face, so she looks less like a cartoon rabbit.
```

## Planche des seconds rôles

**À joindre** : rien (ou la planche des héros, pour garder le même style).

```
Character model sheet for a friendly animated film for children, on a plain light background. Three adult animal characters standing side by side, each shown front view and three-quarter view, full body, kind and warm:

1. Babka Zuzana, an elderly ewe (white wool, kind wrinkled eyes, small round glasses), wearing a flowered red headscarf, a white apron, a black embroidered waistcoat, a white embroidered blouse and a red skirt (traditional Slovak costume).
2. Pani Ježková, a middle-aged hedgehog lady shopkeeper (brown spines, round friendly face, small glasses), wearing a light-blue shop apron.
3. Pán Orol, a golden eagle park ranger (dark brown feathers, golden neck), wearing a ranger hat, a khaki-green vest with a small fir-tree badge, stern but kind.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, expressive faces. No text, no letters, no logos, no watermark.
```

---

## Intro — Couverture

Fiche `00_Introduction_01_comment-ca-marche.md` → `img/illus_00_couverture.jpg`

**À joindre** : la planche des héros. **Photo de référence** : [Vysoké Tatry panorama](https://commons.wikimedia.org/wiki/File:Vysok%C3%A9_Tatry_panorama.jpg) (auteur et licence à compléter dans `img/credits.md`)

```
Use the attached model sheet for the characters (keep them exactly as designed). Use the attached photo as the reference for the mountains.

Scene: Opening image of a children's animated adventure, wide landscape format. The four young friends — the fox, Andrea the hare, Maťo the bear cub and Katka the marmot — stand together on a green mountain meadow in summer, waving cheerfully towards the viewer, the fox in the middle. Behind them the jagged peaks of the High Tatras under a bright morning sky, a small mountain lake, spruce forest, wildflowers in the grass. Leave the upper third fairly calm (sky with a few clouds), as a title may be added later.

Style: Classic 2D hand-drawn animated-film style (not 3D): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark.
```

## Kit 03 — Prvé stretnutie (la première rencontre)

Fiche `10_Series_00_KitSurvie_03_dialogue.md` → `img/illus_00_kit.jpg`

**À joindre** : la planche des héros. **Photo de référence** : [le chamois de Kończysty Wierch](https://commons.wikimedia.org/wiki/File:20170401_kozica_Ko%C5%84czysty_Wierch_5522.jpg) (Jakub Hałun, CC BY-SA 4.0)

```
Use the attached model sheet for the characters (keep them exactly as designed). Use the attached photo as the reference for the chamois and the rocky slope.

Scene: A sunny mountain path in the Tatras, wide landscape format. The young fox, with his backpack, meets Andrea the hare for the first time: they stand face to face, a little shy, the fox waving, Andrea smiling with her long ears upright. A bit behind them on the rocks, a chamois watches calmly. Wildflowers along the path, rocky peaks in the background.

Style: Classic 2D hand-drawn animated-film style (not 3D): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark.
```

## 01 Rodina — U babky (chez la grand-mère)

Fiche `10_Series_01_Rodina_05_u-babky.md` → `img/illus_01_rodina.jpg`

**À joindre** : la planche des héros + la planche des seconds rôles. **Photo de référence** : [les cabanes de la clairière Podkólna](https://commons.wikimedia.org/wiki/File:SZA%C5%81ASY_NA_POLANIE_PODK%C3%93LNA_W_JURGOWIE,_fot._M._Klag_(MIK,_2001)_(3508450272).jpg) (mik Krakow, CC BY-SA 2.0)

```
Use the attached model sheets for the characters (keep them exactly as designed). Use the attached photo as the reference for the mountain pasture and the wooden huts.

Scene: A high mountain pasture in the Tatras on a summer afternoon, wide landscape format, with old wooden herders' huts and a flock of sheep grazing. Babka Zuzana, the old ewe in her traditional costume, stands in front of a hut with open arms to welcome the young fox. Katka the marmot and Maťo the bear cub stand next to her, smiling. The fox, with Andrea the hare beside him, shyly waves hello; Andrea has a small reassuring smile. A warm, welcoming family-gathering mood.

Style: Classic 2D hand-drawn animated-film style (not 3D): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark.
```

## 02 Doma — Návšteva (la visite)

Fiche `10_Series_02_Doma_05_navsteva.md` → `img/illus_02_doma.jpg`

**À joindre** : la planche des héros. **Photo de référence** : [Alpine Marmot Family](https://commons.wikimedia.org/wiki/File:Alpine_Marmot_Family.jpg) (EpsilonEridani, CC BY-SA 4.0)

```
Use the attached model sheet for the characters (keep them exactly as designed). Use the attached photo as the reference for the burrow entrance and the grass.

Scene: The entrance of a cosy marmot burrow dug into a grassy mountain slope, wide landscape format, with a small round wooden door and a tiny window. Katka the marmot stands proudly in the doorway, inviting her visitors in with a welcoming gesture. The fox, Andrea the hare and Maťo the bear cub arrive up the little path, curious, looking at the burrow. A warm glow comes from inside, a few flowers and a small lantern by the door. Late afternoon light.

Style: Classic 2D hand-drawn animated-film style (not 3D): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark.
```

## 03 Jedlo — Halušky u babky

Fiche `10_Series_03_Jedlo_05_halusky-u-babky.md` → `img/illus_03_jedlo.jpg`

**À joindre** : la planche des héros + la planche des seconds rôles. **Photo de référence** : [Bryndzové halušky so slaninou](https://commons.wikimedia.org/wiki/File:Bryndzov%C3%A9_halu%C5%A1ky_so_slaninou.jpg) (Gregory finster, CC0)

```
Use the attached model sheets for the characters (keep them exactly as designed). Use the attached photo as the reference for the dish.

Scene: Inside a cosy wooden mountain hut at lunchtime, wide landscape format. A long wooden table with a checked tablecloth. Babka Zuzana, the old ewe in her apron, proudly serves steaming plates of potato dumplings with white sheep-cheese sauce from a big pot. The fox, Andrea the hare, Katka the marmot and Maťo the bear cub sit around the table with hungry, happy faces; a bowl of wild berries is on the table for the fox. Warm light through a small window, a few embroidered curtains.

Style: Classic 2D hand-drawn animated-film style (not 3D): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out. Landscape format 16:9. No text, no letters, no logos, no watermark.
```

## 04 Dedina — V obchode (au magasin)

Fiche `10_Series_04_Dedina_05_v-obchode.md` → `img/illus_04_dedina.jpg`

**À joindre** : la planche des héros + la planche des seconds rôles. **Photo de référence** : [le magasin de Veľké Raškovce](https://commons.wikimedia.org/wiki/File:Ve%C4%BEk%C3%A9_Ra%C5%A1kovce_grocery_shop_and_village_pub_(June_2006).jpg) (ZemplinTemplar, CC BY-SA 4.0)

```
Use the attached model sheets for the characters (keep them exactly as designed). Use the attached photo as the reference for the shop building.

Scene: A small village grocery shop in Slovakia on a sunny day, wide landscape format, seen from the street with its open door and shelves visible inside, crates of fruit and vegetables on the pavement. Pani Ježková, the hedgehog lady shopkeeper in her light-blue apron, stands at the door holding a basket of berries and smiling at the fox. The fox holds a few coins, Andrea the hare points at the bread on the shelf and Katka the marmot peeks over the counter. A friendly, busy village-morning mood.

Style: Classic 2D hand-drawn animated-film style (not 3D): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Any humans are drawn in the same simple cartoon style as the animals. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark.
```

## 05 Zvieratá — Strážca parku (le garde du parc)

Fiche `10_Series_05_Zvierata_05_strazca-parku.md` → `img/illus_05_zvierata.jpg`

**À joindre** : la planche des héros + la planche des seconds rôles. **Photo de référence** : [aigle royal en vol](https://commons.wikimedia.org/wiki/File:Chrysaetos_La_Ca%C3%B1ada_20120114_1.jpg) (Juan lacruz, CC BY 3.0)

```
Use the attached model sheets for the characters (keep them exactly as designed). Use the attached photo as the reference for the eagle's plumage and posture.

Scene: A marked hiking trail in a Tatra mountain valley, wide landscape format. Pán Orol, the golden eagle park ranger in his ranger hat and green vest, stands on a wooden signpost, pointing with one wing towards a small burrow in the grass and a nest on a rock, explaining something to the children. The fox, Andrea the hare, Katka the marmot and Maťo the bear cub stand on the path, listening carefully; Maťo keeps both feet on the path. In the background a chamois on the rocks, spruce trees and high peaks. Clear morning light.

Style: Classic 2D hand-drawn animated-film style (not 3D): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark.
```

## 06 Hry — Skrývačka na lúke (cache-cache dans la prairie)

Fiche `10_Series_06_Hry_05_skryvacka-na-luke.md` → `img/illus_06_hry.jpg`

**À joindre** : la planche des héros. **Photo de référence** : [la prairie fleurie sous le Chleb](https://commons.wikimedia.org/wiki/File:Chleb_%E2%80%93_flowering_meadow_below_the_summit_in_June.jpg) (Punteador, CC BY-SA 4.0)

```
Use the attached model sheet for the characters (keep them exactly as designed). Use the attached photo as the reference for the meadow.

Scene: A flowering mountain meadow in June, wide landscape format, with a small tree in the middle. Andrea the hare stands with her eyes covered by her paws, counting, her back to the tree. Behind her, Katka the marmot peeks out from behind a bush, Maťo the bear cub tries to hide behind the too-thin trunk with his round belly showing, and the fox crouches in the tall grass, hand over his mouth to stifle a giggle. Joyful, playful mood, warm afternoon sun, wildflowers everywhere.

Style: Classic 2D hand-drawn animated-film style (not 3D): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark.
```
