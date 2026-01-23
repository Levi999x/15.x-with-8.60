# 15.x-with-8.60

Hi,

I've downgraded the 15.x assets to 8.60 DAT and SPR using SpiderClientConverter. I've added all original 8.60 outfits, items, and effects.
This gives you a complete 8.60 client with content from versions up to 15.x.
I converted every single item from 8.60 by hand from asynchronous to synchronous. This means idle animations for outfits now work perfect and we don't have any bugs or visual glitches in the animation
Note: We've also imported all outfits from version 9.83 (up to ID 537), so you now have 3-frame animations and full mount support (looks like 8.60). If you prefer the original 8 frame animation for outfits you can change it by urself without problems :D

OTCv8 Features that need to be enabled in order to use this:
    
    g_game.enableFeature(GameEnhancedAnimations)
    g_game.enableFeature(GameIdleAnimations)
    g_game.enableFeature(GameSpritesU32)

    Active this only when u got mount system in your source.
    g_game.enableFeature(GamePlayerMounts)

NOTE: To avoid problems with map saving make sure to change in your rme files under data/clients.xml

from
otb client="8.60" version="3" id="20"
to
otb client="8.60" version="3" id="64"

Tibia.otfi file must be placed in OTC 860 folder and RME 860 folder

To avoid bugs and problems
Create a blank map and then import your old map on it :D
That's it.

Btw.. If you are interested to use that spr with cip client, use the 860-cip branch :)

# Compatible Tools
- [RME v4.1.2 OTAcademy Map Editor](https://github.com/OTAcademy/RME)
- [Item Editor v.0.5.1](https://github.com/ottools/ItemEditor/releases/tag/v0.5.1)
- [Object Builder v0.5.6](https://github.com/punkice3407/ObjectBuilder/releases/tag/v0.5.6)

![alt text](img/objectbuilder-options.png)


# Mounts

Mounts ordered by name.

Missing mounts:
- Ashen Coast Predator
- Battlefrazzle
- Bright Percht Sleigh
- Cold Percht Sleigh
- Crimson Bay Predator
- Dark Percht Sleigh
- Flame Bear
- Hibernal Moth
- Lacewing Moth
- Manta Ray
- Platesaurian
- Primal Demonosaur
- Tidal Seawater Predator
- Ursagrodon
- Walker

|  ID    | clientid      | Name                           | Premium |
|--------|---------------|--------------------------------|---------|
| 1  	 | 1827	         | Alpha Demonosaur               | Yes     |
| 2  	 | 1281	         | Antelope                       | No      |
| 3  	 | 1018	         | Arctic Unicorn                 | No      |
| 4  	 | 426	         | Armoured War Horse             | No      |
| 5      |               | Ashen Coast Predator           | No      |
| 6  	 | 621	         | Azudocus                       | No      |
| 7  	 | 728	         | Batcat                         | No      |
| 8  	 | 1247	         | Battle Badger                  | No      |
| 9  	 | 1873	         | Battle Werewolf                | No      |
| 10     |               | Battlefrazzle                  | Yes     |
| 11  	 | 1310	         | Benevolent Coral Rhea          | No      |
| 12  	 | 1311	         | Benevolent Eventide Nandu      | No      |
| 13  	 | 1309	         | Benevolent Savanna Ostrich     | No      |
| 14  	 | 371	         | Black Sheep                    | Yes     |
| 15  	 | 686	         | Black Stag                     | No      |
| 16  	 | 651	         | Blackpelt                      | No      |
| 17  	 | 376	         | Blazebringer                   | Yes     |
| 18  	 | 1017	         | Blazing Unicorn                | No      |
| 19  	 | 869	         | Bloodcurl                      | No      |
| 20  	 | 1257	         | Blue Rolling Barrel            | Yes     |
| 21  	 | 1743	         | Bog Tyrant                     | No      |
| 22  	 | 1447	         | Bogwurm                        | No      |
| 23  	 | 1672	         | Boisterous Bull                | No      |
| 24  	 | 1106	         | Boreal Owl                     | No      |
| 25  	 | 1609	         | Brass Speckled Koi             | No      |
| 26     |               | Bright Percht Sleigh           | Yes     |
| 27  	 | 1230	         | Bright Percht Sleigh Variant   | Yes     |
| 28  	 | 1778	         | Bumblebee                      | No      |
| 29  	 | 1180	         | Bunny Dray                     | No      |
| 30  	 | 1169	         | Caped Snowman                  | No      |
| 31  	 | 622	         | Carpacosaurus                  | No      |
| 32  	 | 1026	         | Cave Tarantula                 | No      |
| 33  	 | 1209, 1645    | Cerberus Champion              | No      |
| 34  	 | 851	         | Cinderhoof                     | No      |
| 35  	 | 1528	         | Cinnamon Ibex                  | No      |
| 36     |               | Cold Percht Sleigh             | Yes     |
| 37  	 | 1229	         | Cold Percht Sleigh Variant     | Yes     |
| 38  	 | 1181	         | Cony Cart                      | No      |
| 39  	 | 671	         | Copper Fly                     | No      |
| 40  	 | 1325	         | Coral Rhea                     | No      |
| 41  	 | 735	         | Coralripper                    | No      |
| 42  	 | 1842	         | Corpse Phoenix                 | No      |
| 43  	 | 1687	         | Corpsefire Skull               | No      |
| 44  	 | 1025	         | Cranium Spider                 | No      |
| 45     |               | Crimson Bay Predator           | No      |
| 46  	 | 1744	         | Crimson Fang                   | No      |
| 47  	 | 521	         | Crimson Ray                    | No      |
| 48  	 | 390	         | Crystal Wolf                   | Yes     |
| 49  	 | 1334	         | Cunning Hyaena                 | No      |
| 50  	 | 1441	         | Dandelion                      | No      |
| 51     |               | Dark Percht Sleigh             | Yes     |
| 52  	 | 1231	         | Dark Percht Sleigh Variant     | Yes     |
| 53  	 | 1677	         | Darkfire Devourer              | No      |
| 54  	 | 1286	         | Dawn Strayer                   | No      |
| 55  	 | 1727	         | Dawnbringer Pegasus            | No      |
| 56  	 | 624	         | Death Crawler                  | No      |
| 57     | 1843	         | Death Phoenix                  | No      |
| 58  	 | 572	         | Desert King                    | No      |
| 59  	 | 387	         | Donkey                         | Yes     |
| 60  	 | 1685	         | Doom Skull                     | No      |
| 61  	 | 644	         | Doombringer                    | No      |
| 62  	 | 506	         | Dragonling                     | Yes     |
| 63  	 | 373	         | Draptor                        | Yes     |
| 64  	 | 906	         | Dreadhare                      | No      |
| 65  	 | 405	         | Dromedary                      | Yes     |
| 66  	 | 1285	         | Dusk Pryer                     | No      |
| 67  	 | 1091	         | Ebony Tiger                    | No      |
| 68  	 | 960	         | Ember Saurian                  | No      |
| 69  	 | 1453	         | Emerald Raven                  | No      |
| 70  	 | 951	         | Emerald Sphinx                 | No      |
| 71  	 | 693	         | Emerald Waccoon                | No      |
| 72  	 | 687	         | Emperor Deer                   | No      |
| 73  	 | 1248	         | Ether Badger                   | No      |
| 74  	 | 1326	         | Eventide Nandu                 | No      |
| 75  	 | 1092	         | Feral Tiger                    | No      |
| 76  	 | 1381	         | Festive Mammoth                | No      |
| 77  	 | 1167	         | Festive Snowman                | No      |
| 78  	 | 1233	         | Finished Bright Percht Sleigh  | Yes     |
| 79  	 | 1232	         | Finished Cold Percht Sleigh    | Yes     |
| 80  	 | 1234	         | Finished Dark Percht Sleigh    | Yes     |
| 81     |               | Flame Bear                     | No      |
| 82  	 | 626	         | Flamesteed                     | No      |
| 83  	 | 1101	         | Fleeting Knowledge             | Yes     |
| 84  	 | 726	         | Flitterkatzen                  | No      |
| 85  	 | 1266	         | Floating Augur                 | No      |
| 86  	 | 690	         | Floating Kashmir               | No      |
| 87  	 | 1264	         | Floating Sage                  | No      |
| 88  	 | 1265	         | Floating Scholar               | No      |
| 89  	 | 688	         | Flying Divan                   | No      |
| 90  	 | 1632	         | Foxmouse                       | Yes     |
| 91  	 | 1615	         | Frostbringer                   | No      |
| 92  	 | 850	         | Frostflare                     | No      |
| 93  	 | 1536	         | Giant Beaver                   | Yes     |
| 94  	 | 674	         | Glacier Vagabond               | No      |
| 95  	 | 1742	         | Glacier Wyrm                   | No      |
| 96  	 | 1866	         | Gloom Maw                      | Yes     |
| 97  	 | 1027	         | Gloom Widow                    | No      |
| 98  	 | 1448	         | Gloomwurm                      | No      |
| 99  	 | 1459	         | Gloothomotive                  | Yes     |
| 100  	 | 515	         | Gnarlhound                     | Yes     |
| 101  	 | 950	         | Gold Sphinx                    | No      |
| 102  	 | 669	         | Golden Dragonfly               | No      |
| 103  	 | 682	         | Glooth Glider                  | Yes     |
| 104  	 | 1724	         | Gorgon Hydra                   | No      |
| 105  	 | 738	         | Gorongra                       | No      |
| 106  	 | 1259	         | Green Rolling Barrel           | Yes     |
| 107  	 | 1191	         | Gryphon                        | Yes     |
| 108  	 | 648	         | Hailstorm Fury                 | No      |
| 109  	 | 1269	         | Haze                           | Yes     |
| 110  	 | 1826	         | Hell Demonosaur                | Yes     |
| 111    |               | Hibernal Moth                  | Yes     |
| 112  	 | 673	         | Highland Yak                   | No      |
| 113  	 | 1380	         | Holiday Mammoth                | No      |
| 114  	 | 421	         | Horse                          | No      |
| 115  	 | 1439	         | Hyacinth                       | No      |
| 116  	 | 1617	         | Icebreacher                    | No      |
| 117  	 | 1610	         | Ink Spotted Koi                | No      |
| 118  	 | 502	         | Ironblight                     | Yes     |
| 119  	 | 901	         | Ivory Fang                     | No      |
| 120  	 | 905	         | Jackalope                      | No      |
| 121  	 | 627	         | Jade Lion                      | No      |
| 122  	 | 628	         | Jade Pincer                    | No      |
| 123  	 | 1492	         | Jade Shrine                    | No      |
| 124  	 | 1208, 1644	 | Jousting Eagle                 | No      |
| 125  	 | 1579	         | Jousting Horse                 | No      |
| 126  	 | 959	         | Jungle Saurian                 | No      |
| 127  	 | 1093	         | Jungle Tiger                   | No      |
| 128  	 | 401	         | Kingly Deer                    | Yes     |
| 129  	 | 1363	         | Krakoloss                      | Yes     |
| 130    |               | Lacewing Moth                  | Yes     |
| 131  	 | 447	         | Ladybug                        | Yes     |
| 132  	 | 961	         | Lagoon Saurian                 | No      |
| 133  	 | 1834	         | Leaf Locust                    | No      |
| 134  	 | 870	         | Leafscuttler                   | No      |
| 135  	 | 689	         | Magic Carpet                   | No      |
| 136  	 | 503	         | Magma Crawler                  | Yes     |
| 137  	 | 1686	         | Magma Skull                    | No      |
| 138    |               | Manta Ray                      | Yes     |
| 139  	 | 1052	         | Marsh Toad                     | No      |
| 140  	 | 1379	         | Merry Mammoth                  | No      |
| 141  	 | 372	         | Midnight Panther               | Yes     |
| 142  	 | 1527	         | Mint Ibex                      | No      |
| 143  	 | 1049	         | Mole                           | Yes     |
| 144  	 | 887	         | Mould Shell                    | No      |
| 145  	 | 868	         | Mouldpincer                    | No      |
| 146  	 | 1168	         | Muffled Snowman                | No      |
| 147  	 | 1599	         | Mutated Abomination            | Yes     |
| 148  	 | 1721	         | Mystic Jaguar                  | Yes     |
| 149  	 | 1454	         | Mystic Raven                   | No      |
| 150  	 | 889	         | Neon Sparkid                   | Yes     |
| 151  	 | 629	         | Nethersteed                    | No      |
| 152  	 | 1833	         | Night Locust                   | No      |
| 153  	 | 692	         | Night Waccoon                  | No      |
| 154  	 | 849	         | Nightdweller                   | No      |
| 155  	 | 1185	         | Nightmarish Crocovile          | No      |
| 156  	 | 762	         | Nightstinger                   | No      |
| 157  	 | 571	         | Noble Lion                     | Yes     |
| 158  	 | 739	         | Noctungra                      | No      |
| 159  	 | 1493	         | Obsidian Shrine                | No      |
| 160  	 | 1674	         | Obstinate Ox                   | No      |
| 161  	 | 437	         | Old Horse                      | No      |
| 162  	 | 1813	         | Pallbearer                     | No      |
| 163  	 | 1578	         | Parade Horse                   | No      |
| 164  	 | 1835	         | Pearl Locust                   | No      |
| 165  	 | 1730	         | Pegasus                        | Yes     |
| 166  	 | 1440	         | Peony                          | No      |
| 167  	 | 1417	         | Phant                          | No      |
| 168  	 | 1321	         | Phantasmal Jade                | Yes     |
| 169    |               | Platesaurian                   | No      |
| 170  	 | 736	         | Plumfish                       | No      |
| 171  	 | 650	         | Poisonbane                     | No      |
| 172  	 | 1526	         | Poppy Ibex                     | No      |
| 173    |               | Primal Demonosaur              | Yes     |
| 174  	 | 1019	         | Prismatic Unicorn              | No      |
| 175  	 | 1179	         | Rabbit Rickshaw                | No      |
| 176  	 | 369	         | Racing Bird                    | Yes     |
| 177  	 | 1455	         | Radiant Raven                  | No      |
| 178  	 | 377	         | Rapid Boar                     | Yes     |
| 179  	 | 763	         | Razorcreep                     | No      |
| 180  	 | 1258	         | Red Rolling Barrel             | Yes     |
| 181  	 | 888	         | Reed Lurker                    | No      |
| 182  	 | 438	         | Rented Horse                   | No      |
| 183  	 | 848	         | Rift Runner                    | Yes     |
| 184  	 | 1391	         | Rift Watcher                   | No      |
| 185  	 | 691	         | Ringtail Waccoon               | No      |
| 186  	 | 1577	         | Ripptor                        | Yes     |
| 187  	 | 1183	         | River Crocovile                | No      |
| 188  	 | 1390	         | Rune Watcher                   | No      |
| 189  	 | 1446	         | Rustwurm                       | No      |
| 190  	 | 1053	         | Sanguine Frog                  | No      |
| 191  	 | 1836	         | Satin Moth                     | No      |
| 192  	 | 1324	         | Savanna Ostrich                | No      |
| 193  	 | 406	         | Scorpion King                  | Yes     |
| 194  	 | 1335	         | Scruffy Hyaena                 | No      |
| 195  	 | 734	         | Sea Devil                      | No      |
| 196  	 | 902	         | Shadow Claw                    | No      |
| 197  	 | 427	         | Shadow Draptor                 | No      |
| 198  	 | 685	         | Shadow Hart                    | No      |
| 199  	 | 952	         | Shadow Sphinx                  | No      |
| 200  	 | 1430	         | Shellodon                      | Yes     |
| 201  	 | 580	         | Shock Head                     | Yes     |
| 202  	 | 649	         | Siegebreaker                   | No      |
| 203  	 | 740	         | Silverneck                     | No      |
| 204  	 | 1431	         | Singeing Steed                 | Yes     |
| 205  	 | 1729	         | Skybreaker Pegasus             | No      |
| 206  	 | 761	         | Slagsnare                      | No      |
| 207  	 | 903	         | Snow Pelt                      | No      |
| 208  	 | 1284	         | Snow Strider                   | No      |
| 209  	 | 1105	         | Snowy Owl                      | No      |
| 210  	 | 1844	         | Soul Phoenix                   | No      |
| 211  	 | 883	         | Sparkion                       | Yes     |
| 212  	 | 1682	         | Spirit of Purity               | Yes     |
| 213  	 | 378	         | Stampor                        | Yes     |
| 214  	 | 670	         | Steel Bee                      | No      |
| 215  	 | 522	         | Steelbeak                      | No      |
| 216  	 | 937	         | Stone Rhino                    | Yes     |
| 217  	 | 1673	         | Surly Steer                    | No      |
| 218  	 | 1184	         | Swamp Crocovile                | No      |
| 219  	 | 886	         | Swamp Snapper                  | No      |
| 220  	 | 402	         | Tamed Panda                    | Yes     |
| 221  	 | 1608	         | Tangerine Flecked Koi          | No      |
| 222  	 | 1104	         | Tawny Owl                      | No      |
| 223  	 | 630	         | Tempest                        | No      |
| 224  	 | 559	         | The Hellgrip                   | Yes     |
| 225    |               | Tidal Seawater Predator        | No      |
| 226  	 | 388	         | Tiger Slug                     | Yes     |
| 227  	 | 375	         | Tin Lizzard                    | Yes     |
| 228  	 | 374	         | Titanica                       | Yes     |
| 229  	 | 546	         | Tombstinger                    | No      |
| 230    | 1491	         | Topaz Shrine                   | No      |
| 231  	 | 1580	         | Tourney Horse                  | No      |
| 232    | 1054	         | Toxic Toad                     | No      |
| 233  	 | 672	         | Tundra Rambler                 | No      |
| 234  	 | 379	         | Undead Cavebear                | Yes     |
| 235  	 | 389	         | Uniwheel                       | Yes     |
| 236    |               | Ursagrodon                     | Yes     |
| 237  	 | 727	         | Venompaw                       | No      |
| 238  	 | 1389	         | Void Watcher                   | No      |
| 239  	 | 1333	         | Voracious Hyaena               | No      |
| 240  	 | 890	         | Vortexion                      | Yes     |
| 241    |               | Walker                         | Yes     |
| 242  	 | 370	         | War Bear                       | Yes     |
| 243  	 | 392	         | War Horse                      | Yes     |
| 244  	 | 526	         | Water Buffalo                  | Yes     |
| 245  	 | 1336	         | White Lion                     | Yes     |
| 246  	 | 368	         | Widow Queen                    | Yes     |
| 247  	 | 393	         | Wild Horse                     | No      |
| 248  	 | 631	         | Winter King                    | No      |
| 249  	 | 1616	         | Winterstride                   | No      |
| 250  	 | 907	         | Wolpertinger                   | No      |
| 251  	 | 647	         | Woodland Prince                | No      |
| 252  	 | 1728	         | Wrathfire Pegasus              | No      |
| 253  	 | 1249	         | Zaoan Badger                   | No      |

> **Note:** Outfits table from: https://tibia.fandom.com/wiki/Mounts and https://www.tibiawiki.com.br/wiki/Montarias

---
# Outfits

Outfits ordered by name.

Missing outfits:
- Feral Trapper 
- Fiend Slayer 
- Percht Raider
- Phoenix Evoker
- Revenant


| Name                   | Male Looktype | Addons  | Female Looktype | Addons  | Type    | Premium |
|------------------------|---------------|---------|-----------------|---------|---------|---------|
| Unidentified 1         |               |         | 1068            | Yes     |         |         |
| Unidentified 2         | 1072          | Yes     | 1071, 1316, 1317| Yes     |         |         |
| Unidentified 3         | 1137          | Yes     | 1136            | Yes     |         |         |
| Unidentified 4         |               |         | 1747            | Yes     |         |         |
| Afflicted              | 430           | Yes     | 431             | Yes     | Quest   | Yes     |
| Ancient Aucar          | 1597          | Yes     | 1598            | Yes     | Quest   | Yes     |
| Arbalester             | 1449          | Yes     | 1450            | Yes     | Special | No      |
| Arena Champion         | 884           | Yes     | 885             | Yes     | Special | No      |
| Armoured Archer        | 1618          | Yes     | 1619            | Yes     | Special | No      |
| Assassin               | 152           | Yes     | 156             | Yes     | Quest   | Yes     |
| Barbarian              | 143           | Yes     | 147             | Yes     | Premium | Yes     |
| Bat Knight             | 1874          | Yes     | 1875            | Yes     | Special | No      |
| Battle Mage            | 1069          | Yes     | 1070            | Yes     | Quest   | Yes     |
| Beastmaster            | 637           | Yes     | 636             | Yes     | Special | No      |
| Beekeeper              | 1776          | Yes     | 1777            | Yes     | Special | No      |
| Beggar                 | 153           | Yes     | 157             | Yes     | Quest   | Yes     |
| Blade Dancer           | 1745          | Yes     | 1746            | Yes     | Special | No      |
| Breezy Garb            | 1245          | Yes     | 1246            | Yes     | Special | No      |
| Brotherhood            | 278           | Yes     | 279             | Yes     | Quest   | Yes     |
| Cave Explorer          | 574           | Yes     | 575             | Yes     | Quest   | Yes     |
| Celestial Avenger      | 1725          | Yes     | 1726            | Yes     | Special | No      |
| Ceremonial Garb        | 695           | Yes     | 694             | Yes     | Special | No      |
| Champion               | 633           | Yes     | 632             | Yes     | Special | No      |
| Chaos Acolyte          | 665           | Yes     | 664             | Yes     | Special | No      |
| Citizen                | 128           | Yes     | 136             | Yes     | Basic   | No      |
| Citizen of Issavi      | 1200, 1386    | Yes     | 1199, 1387      | Yes     | Quest   | Yes     |
| Conjurer               | 634           | Yes     | 635             | Yes     | Special | No      |
| Crystal Warlord        | 512           | Yes     | 513             | Yes     | Quest   | Yes     |
| Darklight Evoker       | 1675          | Yes     | 1676            | Yes     | Special | No      |
| Death Herald           | 667           | Yes     | 666             | Yes     | Special | No      |
| Decaying Defender      | 1662          | Yes     | 1663            | Yes     | Quest   | Yes     |
| Deepling               | 463           | Yes     | 464             | Yes     | Quest   | Yes     |
| Demon Hunter           | 289           | Yes     | 288             | Yes     | Quest   | Yes     |
| Demon                  | 542           | Yes     | 541             | Yes     | Quest   | Yes     |
| Discoverer             | 1094          | Yes     | 1095            | Yes     | Quest   | Yes     |
| Doom Knight            | 1713          | Yes     | 1714            | Yes     | Special | No      |
| Draccoon Herald        | 1722          | Yes     | 1723            | Yes     | Quest   | Yes     |
| Dragon Knight          | 1444          | Yes     | 1445            | Yes     | Special | No      |
| Dragon Slayer          | 1288, 1688    | Yes     | 1289, 1689      | Yes     | Quest   | Yes     |
| Dream Warden           | 577           | Yes     | 578             | Yes     | Quest   | Yes     |
| Dream Warrior          | 1146          | Yes     | 1147            | Yes     | Quest   | Yes     |
| Druid                  | 144           | Yes     | 148             | Yes     | Premium | Yes     |
| Elementalist           | 432           | Yes     | 433             | Yes     | Quest   | Yes     |
| Entrepreneur           | 472           | Yes     | 471             | Yes     | Special | No      |
| Evoker                 | 725           | Yes     | 724             | Yes     | Special | No      |
| Falconer               | 1282          | Yes     | 1283            | Yes     | Special | No      |
| Fencer                 | 1575          | Yes     | 1576            | Yes     | Special | No      |
| Feral Trapper          |               | Yes     |                 | Yes     | Special | No      |
| Festive                | 931           | Yes     | 929             | Yes     | Quest   | Yes     |
| Field Surgeon          | 1814          | Yes     | 1815            | Yes     | Special | No      |
| Fiend Slayer           |               | Yes     |                 | Yes     | Quest   | Yes     |
| Fire-Fighter           | 1568          | Yes     | 1569            | Yes     | Quest   | Yes     |
| Flamefury Mage         | 1680          | Yes     | 1681            | Yes     | Special | No      |
| Forest Warden          | 1415          | Yes     | 1416            | Yes     | Special | No      |
| Formal Dress           | 1460          | Yes     | 1461            | Yes     | Quest   | Yes     |
| Frost Tracer           | 1612          | Yes     | 1613            | Yes     | Special | No      |
| Ghost Blade            | 1489          | Yes     | 1490            | Yes     | Special | No      |
| Glooth Engineer        | 618           | Yes     |                 | Yes     | Quest   | Yes     |
| Golden                 | 1210          | Yes     | 1211            | Yes     | Quest   | No      |
| Grove Keeper           | 908           | Yes     | 909             | Yes     | Special | No      |
| Guidon Bearer          | 1186          | Yes     | 1187            | Yes     | Special | No      |
| Hand of the Inquisition| 1243          | Yes     | 1244            | Yes     | Quest   | Yes     |
| Herbalist              | 1021          | Yes     | 1020            | Yes     | Special | No      |
| Herder                 | 1279          | Yes     | 1280            | Yes     | Special | No      |
| Hunter                 | 129           | Yes     | 137             | Yes     | Basic   | No      |
| Illuminator            | 1860          | Yes     | 1861            | Yes     | Quest   | Yes     |
| Insectoid              | 465           | Yes     | 466             | Yes     | Quest   | Yes     |
| Jersey                 | 619           | No      | 620             | No      | Special | Yes     |
| Jester                 | 273           | Yes     | 270             | Yes     | Quest   | Yes     |
| Jouster                | 1331          | Yes     | 1332            | Yes     | Special | No      |
| Knight                 | 131           | Yes     | 139             | Yes     | Basic   | No      |
| Lion of War            | 1206          | Yes     | 1207            | Yes     | Special | No      |
| Lupine Warden          | 899           | Yes     | 900             | Yes     | Special | No      |
| Mage                   | 130           | Yes     | 138             | Yes     | Basic   | No      |
| Makeshift Warrior      | 1042          | Yes     | 1043            | Yes     | Quest   | Yes     |
| Martial Artist         | 1837          | Yes     | 1838            | Yes     | Special | No      |
| Mercenary              | 1056          | Yes     | 1057            | Yes     | Special | No      |
| Merry Garb             | 1382          | Yes     | 1383            | Yes     | Special | No      |
| Monk                   | 1824          | Yes     | 1825            | Yes     | Basic   | No      |
| Moth Cape              | 1338          | Yes     | 1339            | Yes     | Special | No      |
| Necromancer            | 1845          | Yes     | 1846            | Yes     | Special | No      |
| Newly Wed              | 328           | No      | 329             | No      | Quest   | No      |
| Nightmare              | 268           | Yes     | 269             | Yes     | Quest   | Yes     |
| Nobleman / Noblewoman  | 132           | Yes     | 140             | Yes     | Premium | Yes     |
| Nordic Chieftain       | 1500          | Yes     | 1501            | Yes     | Special | No      |
| Norseman               | 251           | Yes     | 252             | Yes     | Quest   | Yes     |
| Orcsoberfest Garb      | 1251          | Yes     | 1252            | Yes     | Quest   | Yes     |
| Oriental               | 146           | Yes     | 150             | Yes     | Premium | Yes     |
| Owl Keeper             | 1173          | Yes     | 1174            | Yes     | Special | No      |
| Percht Raider          |               | Yes     |                 | Yes     | Quest   | Yes     |
| Pharaoh                | 955           | Yes     | 956             | Yes     | Special | No      |
| Philosopher            | 873           | Yes     | 874             | Yes     | Special | No      |
| Phoenix Evoker         |               | Yes     |                 | Yes     | Special | No      |
| Pirate                 | 151           | Yes     | 155             | Yes     | Quest   | Yes     |
| Poltergeist            | 1270          | Yes     | 1271            | Yes     | Quest   | Yes     |
| Pumpkin Mummy          | 1127          | Yes     | 1128            | Yes     | Special | No      |
| Puppeteer              | 697           | Yes     | 696             | Yes     | Special | No      |
| Ranger                 | 684           | Yes     | 683             | Yes     | Special | No      |
| Rascoohan              | 1371          | Yes     | 1372            | Yes     | Quest   | Yes     |
| Recruiter              | 746           | Yes     | 745             | Yes     | Special | No      |
| Retro Citizen          | 974           | No      | 975             | No      | Special | No      |
| Retro Hunter           | 972           | No      | 973             | No      | Special | No      |
| Retro Knight           | 970           | No      | 971             | No      | Special | No      |
| Retro Mage             | 968           | No      | 969             | No      | Special | No      |
| Retro Nobleman / woman | 966           | No      | 967             | No      | Special | No      |
| Retro Summoner         | 964           | No      | 965             | No      | Special | No      |
| Retro Warrior          | 962           | No      | 963             | No      | Special | No      |
| Revenant               |               | Yes     |                 | Yes     | Quest   | Yes     |
| Rift Warrior           | 846           | Yes     | 845             | Yes     | Quest   | Yes     |
| Rootwalker             | 1774          | Yes     | 1775            | Yes     | Quest   | Yes     |
| Royal Bounacean Advisor| 1436          | Yes     | 1437            | Yes     | Quest   | Yes     |
| Royal Costume          | 1457          | Yes     | 1456            | Yes     | Quest   | No      |
| Royal Pumpkin          | 760           | Yes     | 759             | Yes     | Special | No      |
| Rune Master            | 1384          | Yes     | 1385            | Yes     | Special | No      |
| Sea Dog                | 750           | Yes     | 749             | Yes     | Special | No      |
| Seaweaver              | 733           | Yes     | 732             | Yes     | Special | No      |
| Shadowlotus Disciple   | 1581          | Yes     | 1582            | Yes     | Special | No      |
| Shaman                 | 154           | Yes     | 158             | Yes     | Quest   | Yes     |
| Siege Master           | 1051          | Yes     | 1050            | Yes     | Special | No      |
| Sinister Archer        | 1102          | Yes     | 1103            | Yes     | Special | No      |
| Soil Guardian          | 516           | Yes     | 514             | Yes     | Quest   | Yes     |
| Spirit Caller          | 699           | Yes     | 698             | Yes     | Special | No      |
| Summoner               | 133           | Yes     | 141             | Yes     | Premium | Yes     |
| Sun Priest             | 1023          | Yes     | 1024            | Yes     | Special | No      |
| Trailblazer            | 1292          | Yes     | 1293            | Yes     | Special | No      |
| Trophy Hunter          | 957           | Yes     | 958             | Yes     | Special | No      |
| Veteran Paladin        | 1204          | Yes     | 1205            | Yes     | Special | No      |
| Void Master            | 1202          | Yes     | 1203            | Yes     | Special | No      |
| Warmaster              | 335           | Yes     | 336             | Yes     | Quest   | Yes     |
| Warrior                | 134           | Yes     | 142             | Yes     | Premium | Yes     |
| Wayfarer               | 367           | Yes     | 366             | Yes     | Quest   | Yes     |
| Winged Druid           | 1831          | Yes     | 1832            | Yes     | Special | No      |
| Winter Warden          | 853           | Yes     | 852             | Yes     | Special | No      |
| Wizard                 | 145           | Yes     | 149             | Yes     | Premium | Yes     |
| Yalaharian             | 325           | Yes     | 324             | Yes     | Quest   | Yes     |

> **Note:** Outfits table from: https://tibia.fandom.com/wiki/Outfits and https://www.tibiawiki.com.br/wiki/Outfits

---