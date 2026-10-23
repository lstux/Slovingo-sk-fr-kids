# Crédits des images

Toutes les images viennent de [Wikimedia Commons](https://commons.wikimedia.org/).
Pour l'instant, les fiches pointent vers les fichiers Commons (adresses `Special:FilePath`).
Une fois les images des fiches téléchargées dans `img/` (`src/fetch_images.py` du moteur), les références deviennent locales : ce fichier reste la source des crédits. Les images de style se téléchargent avec `tools/fetch_style_images.sh`.

**À compléter pour chaque image : auteur et licence**, tels qu'ils sont écrits sur la page Commons. Les licences CC BY et CC BY-SA demandent de citer l'auteur (CC BY-SA : la même licence pour les versions modifiées).

## Images utilisées

| Fiche | Fichier Commons | Auteur | Licence |
|---|---|---|---|
| Intro 01 · Comment ça marche (le renard) | [European red fox (Vulpes vulpes).jpg](https://commons.wikimedia.org/wiki/File:European_red_fox_(Vulpes_vulpes).jpg) | à compléter | à compléter |
| Intro 02 · Le pays (les Tatras) | [Vysoké Tatry panorama.jpg](https://commons.wikimedia.org/wiki/File:Vysok%C3%A9_Tatry_panorama.jpg) | à compléter | à compléter |
| Intro 03 · La langue (Andrea, la hase) | [European Hare(js)02.jpg](https://commons.wikimedia.org/wiki/File:European_Hare(js)02.jpg) | à compléter | à compléter |
| Intro 04 · Prononciation (la marmotte) | [M. marmota latirostris in front of the burrow (Tatra).jpg](https://commons.wikimedia.org/wiki/File:M._marmota_latirostris_in_front_of_the_burrow_(Tatra).jpg) | à compléter | à compléter |
| Intro 05 · Comptage (les moutons) | [Amoo click.jpg](https://commons.wikimedia.org/wiki/File:Amoo_click.jpg) | à compléter | à compléter |
| Kit 01 · Salutations (le sentier) | [Biele pleso, NPR Belianske Tatry 727.jpg](https://commons.wikimedia.org/wiki/File:Biele_pleso,_NPR_Belianske_Tatry_727.jpg) | à compléter | à compléter |
| Kit 02 · Politesse (Babka Zuzana, les prés fleuris) | [Flowers Štrbské Pleso 25 Slovakia 4.jpg](https://commons.wikimedia.org/wiki/File:Flowers_%C5%A0trbsk%C3%A9_Pleso_25_Slovakia_4.jpg) | à compléter | à compléter |
| Kit 03 · Dialogue (le chamois) | [20170401 kozica Kończysty Wierch 5522.jpg](https://commons.wikimedia.org/wiki/File:20170401_kozica_Ko%C5%84czysty_Wierch_5522.jpg) | à compléter | à compléter |
| Kit 04 · Extra (le lac) | [Nové Štrbské pleso 25 Slovakia 1.jpg](https://commons.wikimedia.org/wiki/File:Nov%C3%A9_%C5%A0trbsk%C3%A9_pleso_25_Slovakia_1.jpg) | à compléter | à compléter |

## Images de style (bandeaux de thème)

Fichiers `img/style_<clé>.jpg`, téléchargés et réduits à 1200 px de large avec `tools/fetch_style_images.sh`. Dans l'application, ces images sont de plus **passées en demi-gris et teintées** aux couleurs du thème, et rognées en bandeau : ce sont des versions modifiées des photos d'origine (à indiquer pour les licences CC BY-SA).

Pour remplir les colonnes auteur et licence : `./tools/fetch_style_images.sh --credits` affiche des lignes prêtes à coller ici.

| Thème (utilisé pour) | Fichier Commons | Auteur | Licence |
|---|---|---|---|
| `default` (Intro, hors séries) | [On the way to Biele pleso - panoramio (2).jpg](https://commons.wikimedia.org/wiki/File:On_the_way_to_Biele_pleso_-_panoramio_(2).jpg) | à compléter | à compléter |
| `basics` (Kit de survie) | [Belianske Tatry oct 2022.jpg](https://commons.wikimedia.org/wiki/File:Belianske_Tatry_oct_2022.jpg) | à compléter | à compléter |
| `family` (Rodina) | [Marmota marmota in Vanoise National Park 2023 (1).jpg](https://commons.wikimedia.org/wiki/File:Marmota_marmota_in_Vanoise_National_Park_2023_(1).jpg) (Alpes françaises, pas Tatras) | à compléter | à compléter |
| `house` (Doma) | [Tanap schronisko Zamkovskiego 2.jpg](https://commons.wikimedia.org/wiki/File:Tanap_schronisko_Zamkovskiego_2.jpg) | à compléter | à compléter |
| `food` (Jedlo) | [Bohemian waxwing tosses a mountain ash berry (50829531677).jpg](https://commons.wikimedia.org/wiki/File:Bohemian_waxwing_tosses_a_mountain_ash_berry_(50829531677).jpg) | à compléter | à compléter |
| `city` (Dedina) | [Banská Štiavnica, 2018 (20).jpg](https://commons.wikimedia.org/wiki/File:Bansk%C3%A1_%C5%A0tiavnica,_2018_(20).jpg) | à compléter | à compléter |
| `animals` (Zvieratá) | [Gämse In Der Hohen Tatra (224466327).jpeg](https://commons.wikimedia.org/wiki/File:G%C3%A4mse_In_Der_Hohen_Tatra_(224466327).jpeg) | à compléter | à compléter |
| `games` (Hry) | [Lupina mnoholistá (Lupinus polyphyllus) - Cesta slobody.jpg](https://commons.wikimedia.org/wiki/File:Lupina_mnoholist%C3%A1_(Lupinus_polyphyllus)_-_Cesta_slobody.jpg) | à compléter | à compléter |

## En réserve (pas encore utilisées)

| Sujet | Fichier Commons |
|---|---|
| Renard | [Líška hrdzavá Vulpes vulpes, NPR Dolina Bielej vody 733.jpg](https://commons.wikimedia.org/wiki/File:L%C3%AD%C5%A1ka_hrdzav%C3%A1_Vulpes_vulpes,_NPR_Dolina_Bielej_vody_733.jpg) |
| Hase | [European hare (Lepus europaeus) Marken 2.jpg](https://commons.wikimedia.org/wiki/File:European_hare_(Lepus_europaeus)_Marken_2.jpg) |

## Images des fiches (première passe)

| Fiche | Fichier Commons | Auteur | Licence |
|---|---|---|---|
| 01_Rodina_01_moja-rodina | [Alpenmurmeltier 2.jpg](https://commons.wikimedia.org/wiki/File:Alpenmurmeltier_2.jpg) | Bernard Landgraf | CC BY-SA 4.0 |
| 01_Rodina_02_kolko-mas-rokov | [Red fox kits (40215214874).jpg](https://commons.wikimedia.org/wiki/File:Red_fox_kits_(40215214874).jpg) | USFWS Headquarters | Public domain |
| 01_Rodina_03_mam-brata | [M.marmota latirostris in Veľká Studená dolina 2.jpg](https://commons.wikimedia.org/wiki/File:M.marmota_latirostris_in_Ve%C4%BEk%C3%A1_Studen%C3%A1_dolina_2.jpg) | Krzysztof Górecki | CC BY-SA 3.0 |
| 01_Rodina_04_aka-je-tvoja-rodina | [Eurasian brown bear (Ursus arctos arctos) mother and cub.jpg](https://commons.wikimedia.org/wiki/File:Eurasian_brown_bear_(Ursus_arctos_arctos)_mother_and_cub.jpg) | Charles J. Sharp | CC BY-SA 4.0 |
| 01_Rodina_05_u-babky | [SZAŁASY NA POLANIE PODKÓLNA W JURGOWIE, fot. M. Klag (MIK, 2001) (3508450272).jpg](https://commons.wikimedia.org/wiki/File:SZA%C5%81ASY_NA_POLANIE_PODK%C3%93LNA_W_JURGOWIE,_fot._M._Klag_(MIK,_2001)_(3508450272).jpg) | mik Krakow | CC BY-SA 2.0 |
| 01_Rodina_06_extra | [Mlade lisice u rupi.jpg](https://commons.wikimedia.org/wiki/File:Mlade_lisice_u_rupi.jpg) | Divlja Srbija | CC BY-SA 4.0 |
| 02_Doma_01_kde-byvas | [Alpine marmot (Marmota marmota) in the mountains at the entrance to its burrow.JPG](https://commons.wikimedia.org/wiki/File:Alpine_marmot_(Marmota_marmota)_in_the_mountains_at_the_entrance_to_its_burrow.JPG) | trldp | CC BY-SA 4.0 |
| 02_Doma_05_navsteva | [Alpine Marmot Family.jpg](https://commons.wikimedia.org/wiki/File:Alpine_Marmot_Family.jpg) | EpsilonEridani | CC BY-SA 4.0 |
| 02_Doma_06_extra | [Belianske Tatry.jpg](https://commons.wikimedia.org/wiki/File:Belianske_Tatry.jpg) | Michalsmr | CC BY-SA 4.0 |
| 03_Jedlo_02_chcem-jablko | [DFC 2197 A colorful assortment of fresh fruits and vegetables - apples mango dragon fruit kiwis limes bananas and more - arranged on a wooden crate.jpg](https://commons.wikimedia.org/wiki/File:DFC_2197_A_colorful_assortment_of_fresh_fruits_and_vegetables_-_apples_mango_dragon_fruit_kiwis_limes_bananas_and_more_-_arranged_on_a_wooden_crate.jpg) | PattayaPatrol | CC BY-SA 4.0 |
| 03_Jedlo_03_chuti-mi | [Fresh bilberries picked in Tuntorp 4.jpg](https://commons.wikimedia.org/wiki/File:Fresh_bilberries_picked_in_Tuntorp_4.jpg) | W.carter | CC BY-SA 4.0 |
| 03_Jedlo_04_co-je-na-obed | [DFC 3982 A steaming bowl of homemade vegetable soup garnished with chopped parsley served with a slice of rustic brown bread.jpg](https://commons.wikimedia.org/wiki/File:DFC_3982_A_steaming_bowl_of_homemade_vegetable_soup_garnished_with_chopped_parsley_served_with_a_slice_of_rustic_brown_bread.jpg) | PattayaPatrol | CC BY-SA 4.0 |
| 03_Jedlo_05_halusky-u-babky | [Bryndzové halušky so slaninou.jpg](https://commons.wikimedia.org/wiki/File:Bryndzov%C3%A9_halu%C5%A1ky_so_slaninou.jpg) | Gregory finster | CC0 |
| 02_Doma_02_kde-je-postel | [Koliba Žerucha, Tatranská Štrba, Štrba, okres Poprad, Prešovský kraj 01.jpg](https://commons.wikimedia.org/wiki/File:Koliba_%C5%BDerucha,_Tatransk%C3%A1_%C5%A0trba,_%C5%A0trba,_okres_Poprad,_Pre%C5%A1ovsk%C3%BD_kraj_01.jpg) | Fry72 (Karel Frydrýšek) | CC BY-SA 4.0 |
| 02_Doma_03_co-je-na-stole | [Lamp at Dubay Creek, Al Seef.jpg](https://commons.wikimedia.org/wiki/File:Lamp_at_Dubay_Creek,_Al_Seef.jpg) | KpokeJlJla | CC BY-SA 4.0 |
| 02_Doma_04_su-tu-dve-stolicky | [Wooden table and chairs on a balcony over the Mekong at sunrise in Don Det Si Phan Don Laos.jpg](https://commons.wikimedia.org/wiki/File:Wooden_table_and_chairs_on_a_balcony_over_the_Mekong_at_sunrise_in_Don_Det_Si_Phan_Don_Laos.jpg) | Basile Morin | CC BY-SA 4.0 |
| 03_Jedlo_01_mam-hlad | [Picnic basket 01.jpg](https://commons.wikimedia.org/wiki/File:Picnic_basket_01.jpg) | Jeremy Noble | CC BY 2.0 |
| 03_Jedlo_06_extra | [Sery góralskie.jpg](https://commons.wikimedia.org/wiki/File:Sery_g%C3%B3ralskie.jpg) | Pawel Swiegoda (Paberu) | CC BY-SA 2.5 |
| 04_Dedina_01_idem-do-dediny | [Zdiar 2 Tatry.jpg](https://commons.wikimedia.org/wiki/File:Zdiar_2_Tatry.jpg) | Ing.Mgr.Jozef Kotulič | CC BY-SA 3.0 |
| 04_Dedina_03_pod-sem | [01 005a Ždiar, Blockhaus.jpg](https://commons.wikimedia.org/wiki/File:01_005a_%C5%BDdiar,_Blockhaus.jpg) | Falk2 | CC BY-SA 4.0 |
| 04_Dedina_02_kolko-to-stoji | [Slovak euro coins.jpg](https://commons.wikimedia.org/wiki/File:Slovak_euro_coins.jpg) | Wizzard | Public domain |
| 04_Dedina_04_dobry-den-pani | [Hedgehog in grass.jpg](https://commons.wikimedia.org/wiki/File:Hedgehog_in_grass.jpg) | Mikejamesshaw | CC BY-SA 4.0 |
| 04_Dedina_05_v-obchode | [Veľké Raškovce grocery shop and village pub (June 2006).jpg](https://commons.wikimedia.org/wiki/File:Ve%C4%BEk%C3%A9_Ra%C5%A1kovce_grocery_shop_and_village_pub_(June_2006).jpg) | ZemplinTemplar | CC BY-SA 4.0 |
| 04_Dedina_06_extra | [Belianske Tatry oct 2022.jpg](https://commons.wikimedia.org/wiki/File:Belianske_Tatry_oct_2022.jpg) | Michalsmr | CC BY-SA 4.0 |
| 05_Zvierata_01_zvierata-v-tatrach | [20181006 Lis rudy Tatrzański Park Narodowy 1437 7472 DxO.jpg](https://commons.wikimedia.org/wiki/File:20181006_Lis_rudy_Tatrza%C5%84ski_Park_Narodowy_1437_7472_DxO.jpg) | Jakub Hałun | CC BY-SA 4.0 |
| 05_Zvierata_02_veverky-a-sovy | [Squirrel posing.jpg](https://commons.wikimedia.org/wiki/File:Squirrel_posing.jpg) | Peter Trimming | CC BY 2.0 |
| 05_Zvierata_03_ake-je-zviera | [Rupicapra rupicapra - Jahňaci štít.jpg](https://commons.wikimedia.org/wiki/File:Rupicapra_rupicapra_-_Jah%C5%88aci_%C5%A1t%C3%ADt.jpg) | Marcin Białek | CC BY-SA 4.0 |
| 05_Zvierata_04_kto-je-vacsi | [Bear (28392685756).jpg](https://commons.wikimedia.org/wiki/File:Bear_(28392685756).jpg) | Susanne Nilsson | CC BY-SA 2.0 |
| 05_Zvierata_05_strazca-parku | [Chrysaetos La Cañada 20120114 1.jpg](https://commons.wikimedia.org/wiki/File:Chrysaetos_La_Ca%C3%B1ada_20120114_1.jpg) | Juan lacruz | CC BY 3.0 |
| 05_Zvierata_06_extra | [Kościeliski Potok Dolina Kościeliska 2023-08-22 03.jpg](https://commons.wikimedia.org/wiki/File:Ko%C5%9Bcieliski_Potok_Dolina_Ko%C5%9Bcieliska_2023-08-22_03.jpg) | Agnieszka Kwiecień, Nova | CC BY-SA 4.0 |
| 06_Hry_01_hrame-sa | [Young Foxes (50015799956).jpg](https://commons.wikimedia.org/wiki/File:Young_Foxes_(50015799956).jpg) | Zebralongwing | CC BY 2.0 |
| 06_Hry_06_extra | [Belianske Tatry.jpg](https://commons.wikimedia.org/wiki/File:Belianske_Tatry.jpg) | Michalsmr | CC BY-SA 4.0 |
| 06_Hry_02_mozem | [Slovak hiking signpost - intersection just above Tery's Hut in High tatras.jpg](https://commons.wikimedia.org/wiki/File:Slovak_hiking_signpost_-_intersection_just_above_Tery%27s_Hut_in_High_tatras.jpg) | User: (WT-shared) Scharla at wts wikivoyage | Public domain |
| 06_Hry_03_kto-je-na-rade | [Acacia heterophylla 1.JPG](https://commons.wikimedia.org/wiki/File:Acacia_heterophylla_1.JPG) | B.navez | CC BY-SA 3.0 |
| 06_Hry_04_vyhravam | [Игры черношапочных сурков.jpg](https://commons.wikimedia.org/wiki/File:%D0%98%D0%B3%D1%80%D1%8B_%D1%87%D0%B5%D1%80%D0%BD%D0%BE%D1%88%D0%B0%D0%BF%D0%BE%D1%87%D0%BD%D1%8B%D1%85_%D1%81%D1%83%D1%80%D0%BA%D0%BE%D0%B2.jpg) | NadezhdaKhaustova | CC BY-SA 4.0 |
| 06_Hry_05_skryvacka-na-luke | [Chleb – flowering meadow below the summit in June.jpg](https://commons.wikimedia.org/wiki/File:Chleb_%E2%80%93_flowering_meadow_below_the_summit_in_June.jpg) | Punteador | CC BY-SA 4.0 |
