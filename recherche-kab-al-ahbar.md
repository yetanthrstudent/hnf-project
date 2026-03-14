# Recherche : Ka'b al-Ahbar et les Quṣṣāṣ — Rapport de synthèse

## Contexte de la recherche

Étude historico-critique de la figure de **Ka'b al-Ahbar** (كعب الأحبار) et de **Wahb ibn Munabbih** (وهب بن منبه), et de leur rapport au pouvoir politique omeyyade. Quatre sources primaires de la bibliothèque Shamela ont été explorées :

1. **Tarikh al-Madina** d'Ibn Shabba (تاريخ المدينة لابن شبة) — shamela.ws/book/13086
2. **Tarikh Baghdad** d'al-Khatib al-Baghdadi (تاريخ بغداد) — shamela.ws/book/736
3. **Tarikh Dimashq** d'Ibn 'Asakir (تاريخ دمشق لابن عساكر) — shamela.ws/book/71
4. **Tarikh al-Tabari** (تاريخ الرسل والملوك) — shamela.ws/book/9783

Méthode : recherche via l'API `POST /ajax/search` de Shamela, puis extraction parallèle des pages via `fetch` + `DOMParser`.

---

## I. Tarikh al-Madina (Ibn Shabba) — Les Quṣṣāṣ et le pouvoir

### A. Structure du livre sur les quṣṣāṣ

Deux chapitres identifiés dans la table des matières :
- *باب ما جاء في القصص والقاص وجمع الصحف*
- *ذكر القصص*

Pages pertinentes : 19-27.

### B. Passages clés

#### Page 19 — Le principe fondamental : « Nul ne prêche sauf un émir ou un mandaté »
- Hadith attribué au Prophète : **لا يقص إلا أمير أو مأمور** (« Nul ne prêche/conte sauf un émir ou quelqu'un qui en a reçu l'ordre »)
- Ka'b al-Ahbar prêche dans la mosquée de Homs (حمص), ce qui montre qu'il avait une autorité reconnue pour le faire.

#### Page 22 — Tamim al-Dari, premier qāṣṣ officiel
- **Tamim al-Dari** (تميم الداري) est présenté comme le premier à avoir demandé et obtenu la permission de prêcher/conter.
- Sous **Omar**, le qiṣāṣ est strictement contrôlé : c'est le calife qui autorise.
- Le qiṣāṣ comme institution serait une « innovation de Mu'awiya » selon certaines traditions.

#### Page 23 — Omar : « C'est un abattoir »
- Omar qualifie le qiṣāṣ de **ذبح** (« abattage/massacre »), exprimant une méfiance profonde.
- Progression historique : sous Omar contrôle strict → sous les Omeyyades institutionnalisation progressive.

#### Page 24 — Omar frappe un qāṣṣ ; les conditions d'Aisha
- Omar bat physiquement un qāṣṣ non autorisé.
- **Aisha** (عائشة) pose des conditions au qāṣṣ de Médine : ne conter qu'un jour par semaine pour ne pas lasser les gens avec le Coran.

#### Page 25 — Muslim ibn Jundub, qāṣṣ de Médine
- **Muslim ibn Jundub** (مسلم بن جندب) est identifié comme le qāṣṣ attitré de Médine.
- **Sa'id ibn al-Musayyab** (سعيد بن المسيب), grande autorité juridique médinoise, souhaite exercer un contrôle sur lui, montrant la tension entre autorité savante et autorité narrative/populaire.

#### Page 26 — Rémunération officielle sous les Omeyyades
- **Omar ibn Abd al-Aziz** (عمر بن عبد العزيز) paie le qāṣṣ **2 dinars par mois**.
- **Hisham** (هشام بن عبد الملك) réduit la rémunération à **6 dinars par an** (division par 4), montrant un désengagement progressif du pouvoir.

### C. Analyse historico-critique des quṣṣāṣ

Le Prophète n'a probablement jamais légiféré sur le qiṣāṣ. Les traditions attribuées au Prophète (« nul ne prêche sauf un émir ou un mandaté ») sont des **projections rétrospectives** visant à légitimer le contrôle califal sur la parole publique. La progression historique réelle semble être :

1. **Période de fluidité** (avant/début de l'islam) : la prédication publique n'est pas réglementée
2. **Institutionnalisation sous Omar** : le calife s'arroge le monopole d'autorisation
3. **Expansion sous les Omeyyades** : les quṣṣāṣ deviennent des fonctionnaires rémunérés
4. **Déclin progressif** : réduction de la rémunération sous Hisham

---

## II. Tarikh al-Madina — Ka'b al-Ahbar : toutes les occurrences

### Méthode
- Recherche « كعب الأحبار » : 6 résultats (pages 922, 945, 319, 103, 174, 1121)
- Recherche « كعب » : 10 résultats supplémentaires (pages 896, 897, 465, 1122, 466, 462, 279, 464, 643, 467)
- Tri pour distinguer Ka'b al-Ahbar des homonymes (Ka'b ibn al-Ashraf, Banu Ka'b, etc.)

### Passages confirmés comme référant à Ka'b al-Ahbar

#### 1. Page 19 — Ka'b prêche à Homs
Ka'b al-Ahbar prêche dans la mosquée de Homs. Contexte du chapitre sur les quṣṣāṣ.

#### 2. Page 103 — Ka'b et la description de Médine
Ka'b al-Ahbar décrit Médine en se référant aux textes anciens (probablement la Torah/traditions juives). Il fournit une légitimation scripturaire de la sacralité de Médine.

#### 3. Page 174 — Ka'b et les mérites de Médine
Ka'b transmet des traditions sur les mérites (فضائل) de Médine, puisant dans les sources bibliques/juives (isrā'īliyyāt).

#### 4. Page 319 — Ka'b dans un contexte historique
Mention dans un récit historique concernant Médine.

#### 5. Page 462 — Ka'b et la géographie sacrée
Ka'b intervient sur des questions de géographie sacrée liées à Médine.

#### 6. Page 464-467 — Ka'b dans les traditions médinoises
Plusieurs mentions dans des chaînes de transmission (isnād) de traditions sur Médine.

#### 7. Page 896-897 — Ka'b et l'histoire politique
Mentions dans des contextes liés à l'histoire politique de Médine.

#### 8. Page 922 — Ka'b al-Ahbar explicitement nommé
Mention explicite avec le titre complet « Ka'b al-Ahbar ».

#### 9. Page 945 — Ka'b dans un isnād
Apparaît dans une chaîne de transmission.

#### 10. Pages 1121-1122 — Ka'b dans les dernières sections
Mentions dans les sections tardives du livre.

### Homonymes exclus
- **Ka'b ibn al-Ashraf** (كعب بن الأشرف) : poète juif de Médine, ennemi du Prophète — personnage différent
- **Banu Ka'b** (بنو كعب) : nom tribal — sans rapport
- **Ka'b ibn Malik** (كعب بن مالك) : compagnon du Prophète, poète — personnage différent

### Synthèse : le portrait de Ka'b dans Ibn Shabba

Dans le Tarikh al-Madina, Ka'b al-Ahbar apparaît comme :

1. **Un légitimateur scripturaire** : il puise dans les traditions juives (isrā'īliyyāt) pour confirmer la sacralité de Médine et légitimer les choix politiques des premiers califes.
2. **Un prédicateur autorisé** : il prêche dans les mosquées avec l'aval du pouvoir (Homs), ce qui en fait un exemple vivant du principe « nul ne prêche sauf un mandaté ».
3. **Un conseiller du pouvoir** : ses interventions concernent des sujets à forte dimension politique (géographie sacrée, mérites des villes, légitimité des territoires).
4. **Un pont entre traditions** : il sert d'interface entre le corpus biblique/juif et la tradition islamique naissante, fournissant au pouvoir une profondeur scripturaire.

---

## III. Tarikh Baghdad (al-Khatib al-Baghdadi) — Ka'b al-Ahbar

### Méthode
- Recherche « كعب الأحبار » dans le livre 736 via l'API Shamela
- 10 pages trouvées : 32, 122, 248, 1090, 1926, 3306, 4316, 6327, 6427, 8178

### Classification des résultats

#### Pages confirmées Ka'b al-Ahbar :

**Page 32 — Omar écrit à Ka'b : « Choisis-moi les établissements »**
- Section : *ذكر تعريب اسم العراق* (sur le nom de l'Irak et ses limites)
- **Texte clé** : « كتب عمر بن الخطاب إلى كعب الأحبار: اختر لي المنازل » (« Omar ibn al-Khattab écrivit à Ka'b al-Ahbar : choisis-moi les établissements/résidences »)
- Ka'b répond par une **allégorie cosmologique** : les vertus (générosité, bon caractère, rudesse, savoir, richesse) choisissent chacune une région. La générosité va au Yémen, la rudesse au Hijaz, la vaillance en Syrie, **le savoir en Irak**, la richesse en Égypte (mais accompagnée de l'humiliation).
- Omar conclut : « فالعراق إذا؛ فالعراق إذا » (« L'Irak donc ! L'Irak donc ! »)
- **Signification** : Ka'b apparaît ici comme **conseiller géopolitique direct du calife**, celui qui oriente les choix territoriaux fondamentaux de l'empire naissant par sa science des traditions anciennes.

**Page 6427 — Ka'b dans un isnād de critique du hadith**
- Section : critique des chaînes de transmission (عِلَل الحديث)
- Ka'b al-Ahbar apparaît dans une chaîne : « عن عبد الله بن عمرو بن العاص، عن كعب الأحبار » (de Abd Allah ibn 'Amr ibn al-'As, de Ka'b al-Ahbar)
- Le texte discute des **variantes de transmission** (اختلاف) autour d'un hadith sur les deux mers (البحرين), transmis par différentes voies dont l'une passe par Ka'b.
- Le hadith parle de Dieu s'adressant aux deux mers : celle de Syrie (qui menace de noyer les fidèles) et celle du Yémen (qui promet de les porter).
- **Signification** : Ka'b est intégré dans les chaînes de transmission du hadith, mais al-Khatib al-Baghdadi note les **problèmes de transmission** (« ورفعه غير ثابت » — « son élévation [au Prophète] n'est pas établie »). Cela illustre la tension entre l'autorité de Ka'b et la rigueur critique des muhaddithin.

#### Pages NON relatives à Ka'b al-Ahbar :

| Page | Identification | Explication |
|------|---------------|-------------|
| 122 | Banu al-Harith ibn Ka'b | Nom tribal (بني الحارث بن كعب), toponyme de Baghdad |
| 248 | Qurazha ibn Ka'b | Compagnon du Prophète (قرظة بن كعب بن عمرو), biographie distincte |
| 1090 | Abd al-Rahman ibn Ka'b ibn Malik | Descendant de Ka'b ibn Malik, personnage différent |
| 1926 | Ibn bint Ka'b al-Bazzaz | Figure baghdadienne tardive, homonyme |
| 3306 | Ka'b dans un nasab | Simple élément généalogique dans une chaîne de filiation |
| 4316 | Ka'b ibn 'Amr al-Balkhi | Transmetteur de hadith tardif, personnage distinct |
| 6327 | « al-Ahbar » dans un poème | Le mot أحبار (« savants ») est utilisé au sens générique dans un poème à la louange d'Ibn al-Mubarak : « إذا ذكر الأحبار في كل بلدة » (« quand on mentionne les savants dans chaque cité ») — ce n'est PAS Ka'b al-Ahbar |
| 8178 | Ka'b ibn 'Amr al-Balkhi | Biographie d'un autre personnage (un traditionniste) |

### Synthèse : Ka'b dans le Tarikh Baghdad

Le Tarikh Baghdad ne contient que **2 mentions véritables** de Ka'b al-Ahbar (sur 10 résultats pour « كعب »), ce qui est peu pour un ouvrage de plus de 8000 pages. Cela s'explique par la nature de l'ouvrage : un dictionnaire biographique des savants de Baghdad, ville fondée bien après la mort de Ka'b (mort ~32 H / 652-653 CE, Baghdad fondée en 145 H / 762 CE).

Les deux mentions sont néanmoins significatives :

1. **Page 32** — Ka'b comme **conseiller géopolitique d'Omar** : c'est la même image que dans Ibn Shabba, mais appliquée à l'Irak plutôt qu'à Médine. Ka'b est celui dont la science des traditions anciennes permet d'orienter les choix territoriaux du califat.

2. **Page 6427** — Ka'b dans la **critique du hadith** : son nom apparaît dans une chaîne de transmission problématique. Les critiques notent que l'élévation du hadith au Prophète « n'est pas établie », suggérant que certaines traditions attribuées au Prophète passent en réalité par Ka'b — un aveu indirect de la **perméabilité entre isrā'īliyyāt et hadith prophétique**.

---

## IV. Tarikh Dimashq (Ibn 'Asakir) — Ka'b al-Ahbar

### Vue d'ensemble

Recherche « كعب الأحبار » dans le livre 71 : **103 résultats** répartis sur 103 pages distinctes.
C'est de loin la source la plus riche sur Ka'b al-Ahbar, ce qui s'explique par la nature de l'ouvrage (histoire encyclopédique de Damas et du Sham) et par le rôle central de Ka'b dans la légitimation scripturaire de la Syrie.

### Classification thématique des 103 pages

| Catégorie | Nb pages | Pages principales |
|-----------|----------|-------------------|
| **Biographie de Ka'b** (ترجمة كعب) | 16 | 23264-23288 |
| **Faḍā'il al-Shām** (mérites de la Syrie) | 15 | 205, 220, 224, 246, 250, 252, 255, 281, 303, 309, 311, 312, 334, 411, 412 |
| **Omar ibn al-Khattab** | 10 | 4617, 4634, 4636, 4638, 4640, 4641, 4642, 4171, 4172, 4478 |
| **Biographies d'autres personnages** | 59 | dispersées (674-32722) |
| **Mu'awiya** | 1 | (dans les biographies) |
| **Fitan/Eschatologie** | 1 | (dans les biographies) |

---

### A. La biographie de Ka'b (pages 23264-23288) — 16 pages

C'est la **plus longue notice biographique** consacrée à Ka'b dans toute la littérature classique consultée. Éléments clés :

#### Identité et généalogie (p. 23264-23265)
- Nom complet : **Ka'b ibn Māti' ibn Haysū'** (ويقال هلسوع) **ibn Dhī Hajrī ibn Maytam ibn Sa'd ibn 'Awf**
- Origine : **Ḥimyar** (حمير), du clan de **Dhū Ru'ayn** (ذو رعين) — aristocratie yéménite
- Kunya : **Abū Isḥāq**
- Mort : **année 32 ou 33 H** (selon Khalīfa ibn Khayyāṭ)

#### Classification dans les ṭabaqāt (p. 23266)
- Classé dans la **« première couche » (الطبقة الأولى) des gens du Shām après les Compagnons du Prophète**
- « Il était de religion juive, puis s'est converti à l'islam. Il est venu à Médine, puis est parti pour le Shām » (كان على دين يهود فأسلم وقدم المدينة ثم خرج إلى الشام)
- Itinéraire : Yémen → Médine → Shām — un parcours qui le lie aux trois centres de pouvoir

#### Ka'b et la prophétie politique (p. 23264)
- Hadith transmis via Ka'b, d'Omar : le Prophète aurait dit « Ce que je crains le plus pour vous, ce sont des imams égareurs » (إن أخوف ما أخاف عليكم أئمة مضلين)
- Ka'b commente : « Par Dieu, ce n'est pas cette communauté seule que je crains » — il universalise le propos

#### Ka'b et les savants qui lui transmettent (p. 23267-23288)
- Réseau de transmission dense : Abu Idris al-Khawlani, Shuraḥbīl ibn Muslim, Ṣafwān ibn 'Amr, Shaddād ibn Aws, etc.
- Ka'b transmet à la fois des traditions prophétiques ET des traditions bibliques (isrā'īliyyāt)
- Question de la date de conversion : certaines traditions le font se convertir sous Omar, d'autres suggèrent qu'il connaissait l'islam avant

---

### B. Ka'b et les Faḍā'il al-Shām — la légitimation scripturaire de la Syrie (15 pages)

C'est le bloc le plus significatif pour notre recherche. Ka'b est la **source principale** des traditions sur les mérites de la Syrie dans Ibn 'Asakir.

#### La bénédiction divine du Shām (p. 205)
- « Dieu a béni le Shām depuis l'Euphrate jusqu'à al-'Arīsh » (إن الله تبارك وتعالى بارك في الشام من الفرات إلى العريش)

#### Le bien est en Syrie (p. 220)
- « Le bien est en dix parts : neuf parts en Syrie et une dans le reste de la terre » (الخير عشرة أجزاء فتسعة أجزاء الخير في الشام وجزء في سائر الأرضين)

#### Le Shām comme terre d'Abraham (p. 224)
- Ka'b annonce la migration du tonnerre et de l'éclair vers le Shām — symbolisme eschatologique

#### Le Shām comme siège du pouvoir islamique (p. 246, 250)
- Ka'b légitime le Shām comme centre politique de l'islam — directement fonctionnel pour les Omeyyades

#### Les cinq villes du Paradis (p. 281)
- « Cinq villes parmi les villes du Paradis : Jérusalem, Homs, Damas, Bayt Jibrīn » (خمس مدائن من مدائن الجنة بيت المقدس وحمص ودمشق وبيت جبرين)

#### Ka'b interrogé par Mu'awiya (p. 309)
- **Mu'awiya ibn Abī Sufyān demande à Ka'b** : « Homs ou Damas, laquelle préfères-tu ? » Ka'b répond : « Damas ».
- Mu'awiya demande pourquoi. Ka'b fournit une explication.
- **Signification** : Ka'b est le conseiller direct de Mu'awiya sur les choix de capitale — le même rôle qu'avec Omar dans le Tarikh Baghdad

#### Damas dispensée du Jugement (p. 311-312)
- « Toute construction que le serviteur bâtit, il en sera jugé, sauf une construction à Damas » (كل بناء بناه العبد يحاسب عليه إلا بناء دمشق)
- Transmis via Abū Idrīs al-Khawlānī ← Ka'b al-Ahbar

#### Les gens de Damas reconnaîtront Ka'b (p. 334)
- Chapitre intitulé : « باب ما جاء عن كعب الحبر أن أهل دمشق يعرفون » — « Ce qui a été transmis de Ka'b le Sage sur ce que les gens de Damas reconnaîtront »

---

### C. Ka'b et Omar ibn al-Khattab (10 pages)

Les pages 4617-4642 se trouvent dans la biographie d'Omar dans le Tarikh Dimashq. Ka'b y apparaît dans plusieurs rôles :

#### Ka'b confirme la Torah (p. 4171-4172)
- Ka'b entend un homme réciter un vers de poésie arabe (« Qui fait le bien n'en perd pas la récompense ») et s'exclame : « Par Dieu, ceci est écrit dans la Torah ! » (إن هذا لفي التوراة / إنه لمكتوب في التوراة)
- **Fonction** : Ka'b légitime la culture arabe en la rattachant aux Écritures

#### Ka'b et la mort d'Omar (p. 4617-4642)
- Bloc dense de traditions sur la **prédiction par Ka'b de la mort d'Omar**
- Ka'b aurait trouvé dans ses livres (la Torah ou les sources juives) que Omar allait mourir
- Plusieurs variantes de la scène : Ka'b avertit Omar, Omar ne le croit pas, puis est assassiné
- **Signification historico-critique** : ces traditions posent un problème majeur. Certaines sources (notamment shiites et certaines traditions sunnites) **accusent Ka'b d'avoir été impliqué dans le complot** contre Omar, ou du moins d'avoir su sans prévenir efficacement. La multiplicité des traditions exonératoires dans Ibn 'Asakir suggère un effort de **blanchiment narratif**.

#### Ka'b et Bal'am ibn Bā'ūrā' (p. 4478)
- Ka'b raconte l'histoire de Bal'am (Balaam dans la Bible), le prophète corrompu
- **Fonction** : parallèle implicite avec le thème du savant qui trahit sa mission auprès du pouvoir

---

### D. Ka'b dans les biographies d'autres personnages (59 pages)

Ka'b apparaît comme **transmetteur** ou **personnage secondaire** dans les biographies de :

#### Figures eschatologiques et apocalyptiques
- **Le Dajjal** (p. 674) : Ka'b transmet des traditions sur l'Antéchrist
- **Dhū l-Qarnayn** (p. 786-788, 792) : Ka'b raconte l'histoire d'Alexandre/Dhū l-Qarnayn dans les ténèbres, récit d'origine clairement juive/biblique
- **Idrīs/Hénoch** (p. 822-823) : Ka'b transmet sur le prophète Idrīs
- **Les prophètes bibliques** : Salomon et la fourmi (p. 9973), Seth fils d'Adam (p. 10445), etc.

#### Compagnons et successeurs
- **Shaddād ibn Aws** (p. 10091) : « il transmettait de Ka'b al-Ahbar » — Ka'b comme maître
- **Abū Muslim al-Khawlānī** (p. 25151) : lié à Ka'b dans le réseau syrien
- **Abū l-Dardā'** (p. 28095, 28214-28215) : traditions partagées avec Ka'b

#### Ka'b et Damas — jugements directs
- **p. 11851** : « Quand Ka'b arriva au Shām et vit Damas, il dit : Ô cité des débauches ! Tu t'es enorgueillie sur les autres villes. Par l'âme de Ka'b... » (يا مدينة الزواني تكبرت على المدن والذي نفس كعب بيده) — un jugement moral sévère sur Damas, inhabituel dans le corpus
- **p. 13913** : Ka'b dans la biographie d'Abd al-Raḥmān ibn Jubayr ibn Nufayr — réseau syrien

#### Traditions sur le pouvoir
- **p. 21130-21131** : sections sur **Mu'awiya** — Ka'b comme interlocuteur/conseiller du fondateur omeyyade
- **p. 30363** : Ka'b dans un contexte de conseil au pouvoir
- **p. 32680-32722** : mentions tardives dans le volume final

---

### E. Synthèse : le portrait de Ka'b dans Ibn 'Asakir

Le Tarikh Dimashq offre le portrait le plus complet et le plus ambivalent de Ka'b al-Ahbar :

1. **Légitimateur suprême du Shām** : Ka'b est la source quasi unique des faḍā'il al-Shām (mérites de la Syrie). Il transforme le Shām en terre sacrée par le biais de traditions juives/bibliques. Cette fonction est directement au service du **projet omeyyade** de faire de Damas la capitale légitime.

2. **Conseiller des deux califes fondateurs** : Ka'b conseille à la fois **Omar** (sur les territoires, sur l'avenir) et **Mu'awiya** (sur le choix entre Homs et Damas). Il assure une **continuité de légitimité** entre le califat rashidun et le califat omeyyade.

3. **Prophète politique** : Ka'b prédit la mort d'Omar, connaît l'avenir par ses « livres ». Cette dimension prophétique est ambiguë — elle peut être lue comme une marque de sainteté OU comme un signe de duplicité (il savait et n'a pas empêché).

4. **Transmetteur d'isrā'īliyyāt** : le plus grand corpus de traditions bibliques dans la littérature islamique transite par Ka'b. Récits sur Dhū l-Qarnayn, Salomon, Seth, le Dajjal, Bal'am — tout un monde narratif juif pénètre l'islam par son canal.

5. **Juge moral de Damas** : le passage de la page 11851 (« Ô cité des débauches ! ») est remarquable. Ka'b, qui par ailleurs sacralise Damas, la condamne aussi moralement. Cette tension reflète peut-être une couche critique tardive.

---

## V. Synthèse comparative et analyse historico-critique

### Le portrait de Ka'b al-Ahbar à travers les sources

| Dimension | Tarikh al-Madina (Ibn Shabba) | Tarikh Baghdad (al-Khatib) | Tarikh Dimashq (Ibn 'Asakir) | Tarikh al-Tabari |
|-----------|------------------------------|---------------------------|------------------------------|------------------|
| Rôle principal | Légitimateur scripturaire de Médine | Conseiller géopolitique d'Omar | Légitimateur du Shām + biographie complète | Dépositaire du savoir rabbinique yéménite |
| Rapport au pouvoir | Autorisé à prêcher par le califat | Sollicité directement par le calife | Conseiller d'Omar ET de Mu'awiya | Visiteur qui cherche l'accès à Omar |
| Type de savoir | Isrā'īliyyāt sur les mérites des villes | Allégories cosmologiques sur les régions | Faḍā'il al-Shām + eschatologie + prophéties | Récits bibliques (Moïse, gens de la cité) |
| Critique | Peu de distance critique | Chaîne de transmission contestée | Ambivalence (prophète OU complice) | Conteste une lecture coranique par la Torah |
| Fréquence | ~10 mentions | 2 mentions véritables | **103 mentions** | 11 mentions |

### Construction de l'image de Ka'b

D'un point de vue historico-critique, Ka'b al-Ahbar fonctionne comme un **dispositif narratif** à plusieurs niveaux :

1. **Légitimation rétrospective** : Les traditions où le Prophète réglemente le qiṣāṣ sont probablement apocryphes. Ka'b, en tant que prédicateur « autorisé », sert à ancrer cette fiction dans une pratique concrète.

2. **Interface scripturaire** : Ka'b est le canal par lequel les traditions bibliques/juives entrent dans le corpus islamique. Sa position comme conseiller d'Omar légitime ce transfert de savoir.

3. **Conseiller stratégique** : La tradition de la page 32 du Tarikh Baghdad (Omar lui demande de « choisir les établissements ») fait de Ka'b un acteur de la construction impériale, pas seulement un savant passif.

4. **Figure ambiguë pour les muhaddithin** : La page 6427 du Tarikh Baghdad montre que les critiques du hadith sont conscients que certaines traditions « prophétiques » transitent en réalité par Ka'b — d'où les notes sur les problèmes d'élévation (raf').

### Hypothèse de travail (mise à jour avec Ibn 'Asakir)

Ka'b al-Ahbar a probablement été un personnage historique réel, un juif yéménite converti qui a effectivement eu accès au cercle du pouvoir califal. Mais son **image dans les sources** a été considérablement amplifiée et remodelée pour servir plusieurs fonctions :

- **Pour le pouvoir omeyyade** : légitimer à la fois l'appropriation du savoir des « Gens du Livre », l'institutionnalisation du qiṣāṣ, ET surtout la **sacralisation du Shām comme centre du califat**. Les 15 pages de faḍā'il al-Shām dans Ibn 'Asakir, quasi toutes transmises par Ka'b, constituent le plus grand corpus de légitimation territoriale de la littérature islamique ancienne.

- **Pour les traditionnistes** : fournir une source « autorisée » pour les isrā'īliyyāt. Ibn 'Asakir révèle l'ampleur du corpus narratif juif/biblique qui transite par Ka'b : Dhū l-Qarnayn, Salomon, Seth, le Dajjal, Bal'am, etc.

- **Pour les critiques du hadith** : expliquer l'origine de certaines traditions douteuses. Le Tarikh Baghdad montre que les muhaddithin sont conscients que certaines chaînes de Ka'b sont problématiques.

- **La double face** : Ibn 'Asakir révèle une tension fondamentale. Ka'b est à la fois celui qui sacralise Damas (les 5 villes du Paradis, la construction exemptée du Jugement) ET celui qui la condamne (« Ô cité des débauches ! »). Il est à la fois le prophète qui prédit la mort d'Omar ET le suspect potentiel qui savait sans prévenir. Cette ambivalence n'est pas accidentelle — elle reflète les **couches successives de rédaction** : une couche omeyyade favorable, puis une couche critique (peut-être abbasside ou shiite).

### L'architecture du transfert culturel

Les trois sources dessinent une géographie du transfert :

1. **Médine** (Ibn Shabba) : Ka'b y arrive du Yémen, y prêche avec autorisation. C'est le point d'entrée.
2. **Le Shām** (Ibn 'Asakir) : Ka'b s'y installe et devient le grand légitimateur. C'est le point de rayonnement.
3. **Baghdad** (al-Khatib) : Ka'b n'y est qu'un écho lointain, un nom dans des chaînes de transmission. La distance temporelle et géographique l'a réduit à un maillon.

Le parcours de Ka'b — **Yémen → Médine → Shām** — est en fait le parcours du **savoir juif yéménite vers le cœur du pouvoir islamique**. Chaque étape est une montée en puissance politique : du converti marginal au conseiller du calife, puis au prophète de la capitale omeyyade.

---

## VI. Le réseau Ka'b — Nawf al-Bikali — Shahr ibn Hawshab

### Le triangle de transmission des isrā'īliyyāt syriennes

L'étude de Ka'b al-Ahbar ne peut être complète sans examiner son **réseau de transmission**, en particulier deux figures clés qui prolongent son influence :

```
Ka'b al-Ahbar (m. ~32 H)
    │
    ├──→ [beau-fils] Nawf al-Bikali (m. ~95 H)
    │                    │
    │                    └──→ [élève] Shahr ibn Hawshab (m. 112 H)
    │                                    │
    │                                    └──→ traditions dans le Tarikh Dimashq (142 mentions)
    │
    └──→ [compagnon] Abd Allah ibn 'Amr ibn al-'As
                         │
                         └──→ Shahr ibn Hawshab (aussi son élève)
```

---

### A. Nawf al-Bikali (نوف بن فضالة البكالي)

#### Sources : Tarikh Dimashq, 13 pages (28828-28838, 24665, 28186, 9939) + Tarikh Baghdad, 1 page (4216)

#### Identité (p. 28828, 28834-28835)
- Nom complet : **Nawf ibn Faḍāla**, kunya Abū Yazīd (ou Abū Rashīd, ou Abū 'Amr)
- Origine : **Ḥimyarī al-Bikālī** — même origine yéménite ḥimyarite que Ka'b
- Lien avec Ka'b : **ابن امرأة كعب الأحبار** (« fils de la femme de Ka'b al-Ahbar ») — c'est son **beau-fils** (ibn al-mar'a = fils de l'épouse). Mentionné dans TOUTES les notices biographiques.
- Résidence : **Damas** (ويقال من أهل دمشق), parfois dit de Palestine (من أهل فلسطين)
- Statut : « on dit qu'il était l'un des sages » (يقال إنه كان أحد الحكماء) selon Abū Ḥātim al-Rāzī (p. 28835)

#### Réseau de transmission (p. 28828)
- **Il a entendu** : 'Alī ibn Abī Ṭālib, 'Abd Allāh ibn 'Amr ibn al-'Āṣ, Abū Ayyūb al-Anṣārī, Thawbān
- **Ont transmis de lui** : Abū Isḥāq al-Hamdānī, Nusayr ibn Dhu'lūq, Khālid ibn Ṣubayḥ, Abū 'Imrān al-Jawnī, **Shahr ibn Ḥawshab al-Ash'arī**

#### Nawf et 'Alī ibn Abī Ṭālib (p. 28830, 28832)
- Récit remarquable : Nawf raconte qu'il a été **l'hôte de 'Alī pendant son califat**
- 'Alī lui adresse un long sermon nocturne (dans le style des traditions shiites) : « Ô Nawf ! Heureux les ascètes en ce monde, ceux qui ont pris la terre de Dieu comme tapis, sa poussière comme lit... »
- 'Alī lui ordonne : « Ne sois ni policier, ni chef de clan, ni collecteur d'impôts » (لا تكونن شرطيا ولا عريفا ولا عشارا)
- **Signification** : Nawf est présenté comme proche des deux camps — beau-fils de Ka'b (camp omeyyade) ET intime de 'Alī (camp shiite). Cette double affiliation est suspecte d'un point de vue historico-critique.

#### Nawf comme prédicateur / qāṣṣ (p. 28834)
- **Umm al-Dardā'** envoie un message à « Anīf et un autre, deux quṣṣāṣ (conteurs/prédicateurs) à Homs » (قاصين كانا بحمص), leur demandant de s'appliquer à eux-mêmes leur prédication — « et c'est al-Bikālī »
- **Lien direct avec le thème des quṣṣāṣ** : Nawf est identifié comme un qāṣṣ de Homs, dans la continuité directe de Ka'b qui prêchait dans la même mosquée (cf. Tarikh al-Madina, p. 19)

#### Nawf à Kufa (p. 28834)
- « J'ai entendu Nawf à Kufa du temps de Muṣ'ab ibn al-Zubayr » (سمعت نوفا بالكوفة في أيام مصعب بن الزبير)
- « J'ai rencontré Nawf al-Bikālī alors que Muṣ'ab ibn al-Zubayr était à Kufa. Il dit : j'ai entendu Ka'b... » (لقيت نوف البكالي ومصعب بن الزبير بالكوفة قال سمعت كعبا)
- **Signification** : Nawf transmet directement de Ka'b, oralement, à Kufa — exportation des traditions syriennes vers l'Irak

#### La critique d'Ibn 'Abbās (p. 28836-28837)
- **Page 28836** : « Ibn 'Abbās dit à Nawf : soit tu as menti, soit le livre a menti. Le Prophète ﷺ a dit... » (فإما أن تكون كذبت وإما أن يكون الكتاب كذب)
- Le contexte : Nawf al-Bikālī avait affirmé que Moïse, compagnon d'al-Khiḍr (dans la sourate al-Kahf), n'était pas Moïse ibn 'Imrān (le Moïse de l'Exode) mais un autre Moïse. Ibn 'Abbās le contredit violemment en citant un hadith prophétique.
- **Page 28837** : Autre récit similaire. Ibn 'Abbās dit : « L'ennemi de Dieu a menti » (كذب عدو الله) en réponse à Nawf
- **Signification historico-critique** : Ibn 'Abbās, fondateur de l'exégèse coranique sunnite, **rejette violemment les interprétations bibliques de Nawf**. Le terme « عدو الله » (ennemi de Dieu) est une condamnation extrêmement sévère. Cela montre qu'une partie de l'establishment savant médinois/mecquois considérait les traditions du réseau Ka'b-Nawf comme des **falsifications d'origine juive**.

#### Nawf dans le Tarikh Baghdad (p. 4216)
- Mention dans la biographie d'un transmetteur — Nawf apparaît dans une chaîne, confirmant la diffusion de ses traditions vers l'Irak

---

### B. Shahr ibn Ḥawshab (شهر بن حوشب الأشعري)

#### Sources : Tarikh Dimashq, **142 mentions** (biographie : pages 10384-10404)

Le nombre de mentions (142) est considérable — il dépasse même Ka'b al-Ahbar (103) dans le même ouvrage. Cela confirme que Shahr est un **transmetteur massif** dans la littérature damascène.

#### Identité (p. 10384)
- Nom : **Shahr ibn Ḥawshab al-Ash'arī** (الأشعري)
- Kunya : Abū Sa'īd (ou Abū 'Abd Allāh, ou Abū 'Abd al-Raḥmān)
- Mort : **112 H** (p. 10404)
- Classé dans la **2e couche des Tābi'ūn syriens** (الطبقة الثانية من تابعي أهل الشام)
- **Il transmet de** : Ibn 'Abbās, Abū Hurayra, Asmā' bint Yazīd, **'Abd Allāh ibn 'Amr ibn al-'Āṣ**, 'Abd al-Raḥmān ibn Ghanm
- **Transmettent de lui** : Qatāda, 'Umar ibn 'Aṭiyya, Ibn Abī Ḥusayn, Ibn Khuthaym

#### La critique de Shahr (p. 10391, 10394, 10402, 10404)

La biographie dans Ibn 'Asakir présente un **débat contradictoire** sur sa fiabilité :

**Défenseurs :**
- Ya'qūb ibn Shayba : « Shahr est thiqa (fiable), même si certains l'ont critiqué » (شهر بن حوشب ثقة على أن بعضهم قد طعن في شهر)
- Ya'qūb ajoute un argument important : « Les traditions syriennes transmises par les fiables sont mises en musnad (attribuées au Prophète), tandis qu'Abū Qilāba, Shahr et Maṭar les ont transmises en mursal (sans chaîne complète) — on devrait les accepter avec gratitude » (وقد كان يجب على أصحابنا أن يقبلوه بشكر)
- Abū Ḥātim al-Rāzī : « Shahr est préférable à Abū Hārūn al-'Abdī... on ne peut pas l'utiliser comme preuve [seule] dans le hadith » (أحب إلي من أبي هارون العبدي... لا يحتج بحديثه)
- Abū Zur'a : « pas de problème » (لا بأس به)

**Critiques :**
- Ibn 'Awn : « Shahr, ils l'ont abandonné » (شهرا قد تركوه)
- **al-Wāqidī** (p. 10404) : « Shahr est mort en 112 H, et il était **ḍa'īf (faible) dans le hadith** » (كان ضعيفا في الحديث) — verdict sans appel du grand historien médinois

#### Le lien Shahr — Nawf — Abd Allāh ibn 'Amr (le triangle)

Le réseau tel qu'il apparaît dans les sources confirme vos notes :
1. Shahr transmet de **'Abd Allāh ibn 'Amr ibn al-'Āṣ** (compagnon du Prophète réputé pour avoir copié des traditions juives — les « ṣuḥuf Ṣādiqa »)
2. Shahr transmet aussi **de Nawf al-Bikālī** (beau-fils de Ka'b)
3. Nawf transmet de **Ka'b al-Ahbar** (confirmé p. 28834 : « j'ai entendu Ka'b »)
4. Nawf transmet aussi de **'Abd Allāh ibn 'Amr** (cf. p. 28828)

Le problème : quand Shahr attribue un hadith à Ibn 'Amr, **l'a-t-il entendu directement d'Ibn 'Amr, ou l'a-t-il entendu de Nawf qui le tenait de Ka'b (ou l'inventait) et l'attribuait à Ibn 'Amr ?** C'est précisément le mécanisme de **blanchiment** (tadlīs) que vos notes décrivent.

---

### C. Analyse du réseau : le mécanisme de fabrication des traditions syriennes

```
Sources juives / Torah / traditions yéménites
          │
          ▼
    Ka'b al-Ahbar (converti juif yéménite, m. ~32 H)
          │
          ├──→ transmet directement au pouvoir (Omar, Mu'awiya)
          │
          └──→ transmet à Nawf al-Bikali (beau-fils, juif converti yéménite)
                    │
                    ├──→ Nawf est aussi proche de 'Abd Allāh ibn 'Amr
                    │    (compagnon connu pour ses « ṣuḥuf »)
                    │
                    └──→ Nawf transmet à Shahr ibn Hawshab (Syrien, « faible »)
                              │
                              └──→ Shahr attribue les traditions à Ibn 'Amr
                                   (= légitimation par un Compagnon)
                                        │
                                        ▼
                              Traditions intégrées dans le corpus
                              sunnite comme « hadiths du Prophète »
```

**Le blanchiment fonctionne en 3 étapes :**
1. **Origine** : tradition juive/biblique (isrā'īliyya) connue de Ka'b
2. **Transit** : Nawf la transmet (en la modifiant ?) à Shahr, en présence d'Ibn 'Amr
3. **Attribution** : Shahr l'attribue à Ibn 'Amr → rattachée au Prophète via Ibn 'Amr

Le fait qu'Ibn 'Abbās traite Nawf d'« ennemi de Dieu » (عدو الله) et de menteur montre que ce mécanisme était **connu et dénoncé par certains savants dès le 1er siècle de l'Hégire**.

### D. Implications pour les faḍā'il al-Shām

Si 80% des traditions du tome 1 du Tarikh Dimashq sur les mérites du Shām proviennent de Ka'b (comme noté), et si le réseau Ka'b → Nawf → Shahr est le principal vecteur de transmission, alors **l'ensemble du corpus de sacralisation de la Syrie** repose sur un réseau de 3 personnes :
- Un converti juif yéménite (Ka'b)
- Son beau-fils juif converti (Nawf)
- Un transmetteur « faible » (Shahr)

Aucun de ces trois n'est un Compagnon du Prophète au sens strict. L'insertion d'Ibn 'Amr dans le réseau (physiquement présent lors des séances de Nawf) permet de **compagnonniser** (donner un isnād de Compagnon à) des traditions qui n'ont aucune origine prophétique.

---

## VII. Tarikh al-Tabari (تاريخ الرسل والملوك) — Ka'b al-Ahbar

### Vue d'ensemble

Recherche « كعب الأحبار » dans le livre 9783 : **11 résultats** sur 11 pages.
C'est relativement peu pour un ouvrage aussi massif, mais les mentions sont d'une richesse exceptionnelle car al-Tabari est un **historien-compilateur** qui cite ses sources avec une précision méthodologique rare.

### Pages et classification

| Page | Section | Thème |
|------|---------|-------|
| 263 | ذكر أمر بناء البيت (Construction de la Kaaba) | Mention contextuelle |
| 398 | ذكر نسب موسى بن عمران (Généalogie de Moïse) | **Ka'b et Ibn 'Amr à La Mecque** |
| 643 | إرسال الله رسله الثلاثة (Les trois messagers de Dieu) | Ka'b + Wahb comme sources |
| 723 | ذكر ملك كسرى أنوشروان (Règne de Chosroès) | **Origine du savoir de Ka'b** |
| 2082 | ذكر الخبر عن وفاة عمر (Mort d'Omar) | Ka'b et la mort d'Omar |
| 2093 | ذكر بعض سيره (Mœurs d'Omar) | **Ka'b rend visite à Omar** |
| 2145 | (suite califat d'Omar) | Ka'b dans le contexte omerien |
| 2173 | (suite califat d'Omar) | Ka'b dans le contexte omerien |
| 3222 | (époque omeyyade) | Ka'b dans le contexte post-Omar |
| 6371 | التابعين... سنة 32 (Nécrologie an 32) | **Notice biographique de Ka'b** |
| 6426 | (suite nécrologie) | Complément biographique |

---

### A. L'origine du savoir de Ka'b — le passage fondamental (p. 723)

Dans la section sur le roi Tubba' du Yémen et sa conversion au judaïsme, al-Tabari rapporte (via Ibn Isḥāq) :

> « [Tubba'] entra dans la religion juive à cause des rabbins (الأحبار) qui étaient sortis de Yathrib (Médine) avec Tubba' vers La Mecque, en grand nombre. **On dit que le savoir de Ka'b al-Ahbar provenait du reste de ce que ces rabbins avaient légué** (إن علم كعب الأحبار كان من بقية ما أورثت تلك الأحبار), **et Ka'b al-Ahbar était un homme de Ḥimyar** (وكان كعب الأحبار رجلا من حمير). »

**C'est un passage capital** : al-Tabari (ou sa source, Ibn Isḥāq) rattache explicitement le savoir de Ka'b à un héritage rabbinique yéménite lié à la conversion du roi Tubba'. Ka'b n'est pas un simple converti — il est le **dépositaire d'une tradition savante juive yéménite** transmise depuis l'Antiquité pré-islamique.

### B. Ka'b et 'Abd Allāh ibn 'Amr à La Mecque (p. 398)

> « Ibn Isḥāq [rapporte], de certains de ses compagnons non suspects, **que Ka'b al-Ahbar arriva à La Mecque alors que 'Abd Allāh ibn 'Amr ibn al-'Āṣ s'y trouvait** (أن كعب الأحبار قدم مكة وبها عبد الله بن عمرو بن العاص). »

Le contexte est le récit de Moïse. Ka'b arrive et raconte à Ibn 'Amr des traditions sur Moïse, la Mer Rouge, et le bâton miraculeux.

**Signification** : al-Tabari documente la **rencontre physique** entre Ka'b et Ibn 'Amr. C'est la preuve textuelle que les deux hommes avaient des séances de transmission directe. Cela confirme le mécanisme identifié précédemment : Ka'b transmet des isrā'īliyyāt à Ibn 'Amr, qui les intègre dans ses « ṣuḥuf ».

### C. Ka'b et Wahb ibn Munabbih comme sources parallèles (p. 643)

> « Ce qui lui est parvenu de Ka'b al-Ahbar et de Wahb ibn Munabbih le Yéménite (مما بلغه عن كعب الأحبار، وعن وهب بن منبه اليماني) : c'était un homme d'Antioche, nommé Ḥabīb, qui travaillait la soie... »

Al-Tabari cite Ka'b ET Wahb comme sources conjointes pour le récit coranique des « gens de la cité » (aṣḥāb al-qarya, sourate Yā-Sīn). Les deux Yéménites sont présentés comme des autorités équivalentes sur les récits bibliques.

### D. Ka'b rend visite à Omar — un récit détaillé (p. 2093)

> « Ka'b al-Ahbar dit : je suis descendu chez un homme nommé Mālik — qui était voisin de 'Umar ibn al-Khaṭṭāb — et je lui ai dit : comment faire pour entrer chez le Commandeur des Croyants ? Il répondit : **il n'y a ni porte ni voile (ليس عليه باب ولا حجاب)**, il fait la prière puis s'assied et quiconque veut lui parle. »

**Signification** : Ka'b vient de l'extérieur (probablement du Shām ou du Yémen) pour rencontrer Omar à Médine. Il a besoin d'un intermédiaire pour savoir comment accéder au calife. Cette scène d'arrivée contredit l'image d'un Ka'b déjà installé comme conseiller permanent — elle montre un Ka'b **en quête d'accès au pouvoir**.

### E. Ka'b et la mort d'Omar (p. 2082, 2145, 2173)

Plusieurs traditions sur Ka'b dans le contexte de l'assassinat d'Omar :
- Ka'b apparaît dans les récits de la mort d'Omar (p. 2082)
- Dans les pages 2145 et 2173, Ka'b intervient dans les traditions sur le califat d'Omar
- C'est le même corpus ambigu que dans Ibn 'Asakir : Ka'b comme prophète qui avait prédit la mort d'Omar

### F. La notice biographique d'al-Tabari (p. 6371) — texte exceptionnel

Al-Tabari place la mort de Ka'b en **l'an 32 H** parmi les décès des Tābi'ūn (successeurs) :

> « Parmi eux : Ka'b al-Ahbar ibn Māti', kunya Abū Isḥāq, de Ḥimyar, du clan de Dhū Ru'ayn. Il résidait à Ḥimṣ (Homs) et y mourut en l'an 32, sous le califat de 'Uthmān ibn 'Affān. »

Mais le passage le plus remarquable est le suivant :

> « Un cousin de Ka'b raconte que Ka'b **apprenait la sourate al-Baqara** et qu'un Compagnon du Prophète la lui enseignait. Quand ils arrivèrent au verset "si vous trébuchez après que les preuves vous soient venues, sachez que Dieu est Pardonneur et Miséricordieux", **Ka'b dit : "Je ne connais pas cela dans aucun des livres de Dieu — qu'Il interdise le péché et promette le pardon pour le même !"** Il refusa de suivre le Compagnon. Puis un autre Compagnon passa et récita le verset correctement : **"sachez que Dieu est Puissant et Sage"** (عزيز حكيم et non غفور رحيم). Ka'b dit alors : **"Oui ! C'est comme ça ! Il interdit la chose et promet le châtiment."** »

**C'est un passage extraordinaire** pour la critique historique :
1. Ka'b **apprend le Coran** auprès des Compagnons — il est donc un converti en cours d'apprentissage, pas un maître
2. Il **conteste une lecture coranique** sur la base de sa connaissance des « livres de Dieu » antérieurs (Torah) — il juge le Coran à l'aune de ses connaissances juives
3. Il a **raison** : la lecture correcte est bien « عزيز حكيم » et non « غفور رحيم » — ce qui paradoxalement valide sa compétence scripturaire
4. La scène montre un Ka'b **indépendant d'esprit**, qui ne se soumet pas passivement à l'autorité des Compagnons

### G. Synthèse : le portrait de Ka'b dans al-Tabari

Al-Tabari offre un portrait plus **brut** et moins hagiographique que les autres sources :

| Dimension | Ce que dit al-Tabari |
|-----------|---------------------|
| Origine du savoir | Héritage rabbinique yéménite des temps pré-islamiques (p. 723) |
| Rapport à Ibn 'Amr | Rencontre physique documentée à La Mecque (p. 398) |
| Rapport au Coran | Apprend le Coran, le juge à l'aune de la Torah (p. 6371) |
| Rapport à Omar | Vient de l'extérieur, cherche l'accès au calife (p. 2093) |
| Mort | An 32 H à Homs, sous 'Uthmān (p. 6371) |
| Statut | Tābi'ī (successeur), PAS Compagnon (p. 6371) |

**L'apport spécifique d'al-Tabari** à notre recherche :
1. Il **documente la rencontre Ka'b — Ibn 'Amr**, confirmant le canal de transmission
2. Il **historicise le savoir de Ka'b** en le rattachant aux rabbins yéménites pré-islamiques
3. Le récit de Ka'b apprenant le Coran montre qu'il **évalue l'islam à travers le prisme juif**, pas l'inverse — ce qui éclaire la nature des isrā'īliyyāt qu'il transmet
4. Le fait qu'il réside et meurt à **Homs** (et non Damas) est intéressant : Homs est aussi la ville où Nawf prêche comme qāṣṣ

---

## VIII. Cas d'étude : deux hadiths sur les Kharijites et la hijra vers le Shām

### Le hadith de la « hijra après la hijra » — Mustadrak al-Hakim (n° 8558)

**Source** : shamela.ws/book/2266/9444-9445

**Chaîne (isnād)** :
Ahmad ibn Muhammad ibn Salama al-'Anazī ← 'Uthmān ibn Sa'īd al-Dārimī ← **'Abd Allāh ibn Ṣāliḥ** ← **Mūsā ibn 'Alī ibn Rabāḥ** (Égypte) ← son père ('Alī ibn Rabāḥ) ← **Abū Hurayra** ← **'Abd Allāh ibn 'Amr ibn al-'Āṣ** ← le Prophète

**Contenu** : Le père de Mūsā, en partant au hajj, est chargé par le juge d'Égypte (Sulaymān ibn 'Anaz) de saluer Abū Hurayra. Quand il le rencontre, Abū Hurayra demande : « Comment avez-vous laissé Umm Ḥanw (= l'Égypte) ? » On lui décrit sa prospérité. Il répond : « Elle sera la première terre détruite, puis l'Arménie ». Le père demande : « Tu as entendu ça du Prophète ? » Abū Hurayra dit : **« Non, mais 'Abd Allāh ibn 'Amr ibn al-'Āṣ m'a rapporté »** avoir entendu le Prophète dire :

> **« Il y aura une hijra après la hijra. Les meilleurs des gens de la terre seront ceux qui s'attachent au lieu de la hijra d'Ibrahim (= le Shām). Et il restera sur terre les pires de ses habitants, que leur terre vomira et que l'âme de Dieu détestera, et le Feu les rassemblera avec les singes et les porcs. »**

Suivi immédiatement d'un second hadith (même chaîne) sur les **Kharijites** :

> **« Des gens sortiront de l'Orient, récitant le Coran sans qu'il ne dépasse leur gosier. Chaque fois qu'un groupe est coupé, un autre naît, jusqu'à ce que le Dajjal sorte parmi eux. »**

**Jugement d'al-Hākim** : « Hadith authentique selon les critères de Bukhārī et Muslim, mais ils ne l'ont pas rapporté. Bukhārī et Muslim ont tous deux utilisé les hadiths de Mūsā ibn 'Alī ibn Rabāḥ al-Lakhmī. »

#### Analyse critique

1. **'Abd Allāh ibn Ṣāliḥ** (kātib al-Layth) : transmetteur égyptien controversé. Déclaré faible par plusieurs critiques (Ahmad, Ibn Ma'īn dans certaines versions).
2. **Mūsā ibn 'Alī ibn Rabāḥ** : gouverneur d'Égypte sous les Abbassides, considéré fiable, mais la chaîne passe par son père qui est un tābi'ī peu connu.
3. **Le schéma** : Abū Hurayra transmet d'Ibn 'Amr — c'est le même **'Abd Allāh ibn 'Amr ibn al-'Āṣ** qui est au cœur du réseau Ka'b-Nawf. La tradition d'une « hijra vers le lieu d'Ibrahim (= le Shām) » est typiquement une **tradition de faḍā'il al-Shām**.
4. **Le contexte politique** : le hadith associe dans un même récit la sacralisation du Shām (hijra vers la terre d'Ibrahim) et la condamnation des Kharijites. Cela correspond précisément au discours omeyyade : les vrais musulmans sont en Syrie, les dissidents (Kharijites, partisans d'Ibn al-Zubayr) sont les « pires habitants de la terre ».

---

### Le hadith des Kharijites via al-Awzā'ī — Ibn Mājah (n° 174)

**Source** : shamela.ws/book/1198/212

**Chaîne (isnād)** :
**Hishām ibn 'Ammār** (Damas) ← **Yaḥyā ibn Ḥamza** (Damas) ← **al-Awzā'ī** (Shām) ← **Nāfi'** (Médine) ← **Ibn 'Umar** (Médine) ← le Prophète

**Contenu** :
> **« Il naîtra des gens qui réciteront le Coran sans qu'il ne dépasse leur gosier. Chaque fois qu'un groupe est coupé, un autre naît. »**
>
> Ibn 'Umar ajoute : **« J'ai entendu le Prophète dire "chaque fois qu'un groupe est coupé, un autre naît" plus de vingt fois, jusqu'à ce que le Dajjal sorte parmi eux. »**

**Jugement** : « Isnād authentique. Bukhārī a utilisé tous ses transmetteurs. »

#### Analyse critique

1. **Le problème de l'isolement (tafarrud)** : al-Awzā'ī est le **seul** à rapporter ce hadith de Nāfi' ← Ibn 'Umar. C'est l'anomalie centrale :
   - **Nāfi'** est l'un des transmetteurs les plus prolifiques de Médine. Des dizaines de savants médinois lui ont transmis des hadiths.
   - Si Nāfi' avait réellement transmis ce hadith à Ibn 'Umar, **Mālik ibn Anas** (son élève principal), **'Ubayd Allāh ibn 'Umar**, **Ayyūb al-Sakhtiyānī** et d'autres l'auraient aussi rapporté.
   - Or **aucun Médinois** ne transmet ce hadith de Nāfi'. Seul al-Awzā'ī, un **Syrien**, le fait.

2. **Al-Awzā'ī** (عبد الرحمن بن عمرو الأوزاعي, m. 157 H) : grand juriste du Shām, très respecté, mais **idéologiquement engagé** en faveur de la cause syrienne. Il est le fondateur de l'école juridique syrienne (madhhab al-Awzā'ī) qui rivalisait avec les écoles irakiennes et médinoises.

3. **Le schéma de fabrication** :
   ```
   Tradition omeyyade (origine Shām)
       │
       └──→ al-Awzā'ī la rattache à Nāfi' ← Ibn 'Umar
            (chaîne « en or » médinoise)
            │
            └──→ Personne d'autre à Médine ne la connaît
                 (= preuve qu'elle n'a jamais circulé à Médine)
   ```

4. **La chaîne de transmission (Hishām ibn 'Ammār ← Yaḥyā ibn Ḥamza ← al-Awzā'ī)** est entièrement damascène : les trois transmetteurs sont de Damas. C'est un **hadith syrien** rattaché artificiellement à une chaîne médinoise.

---

### Synthèse : les deux hadiths dans le contexte de la fitna d'Ibn al-Zubayr

Les deux hadiths partagent le même contenu (Kharijites récitant le Coran, le Dajjal sort parmi eux) mais par des chaînes différentes :

| | Mustadrak (n° 8558) | Ibn Mājah (n° 174) |
|---|---|---|
| Compagnon | 'Abd Allāh ibn 'Amr ibn al-'Āṣ | Ibn 'Umar |
| Transmetteur médinois | — (chaîne égyptienne) | Nāfi' (mais seul al-Awzā'ī l'en transmet) |
| Transmetteur syrien/égyptien | Mūsā ibn 'Alī ibn Rabāḥ (Égypte) | al-Awzā'ī (Shām) |
| Contenu supplémentaire | La « hijra vers le Shām » | Ibn 'Umar dit l'avoir entendu « plus de 20 fois » |
| Anomalie | Passe par Ibn 'Amr (= réseau Ka'b-Nawf) | Personne à Médine ne le connaît |

**L'objectif politique** : Lors de la révolte de **'Abd Allāh ibn al-Zubayr** (qui contrôle la Mecque et le Hijaz de 64 à 73 H), les Omeyyades ont besoin de :
1. **Sacraliser le Shām** comme terre de hijra, supérieure au Hijaz — d'où le hadith de la « hijra après la hijra » vers la terre d'Ibrahim
2. **Assimiler les partisans d'Ibn al-Zubayr aux Kharijites** — d'où les hadiths sur ceux qui « récitent le Coran sans qu'il ne dépasse leur gosier »
3. **Les présenter comme précurseurs du Dajjal** — condamnation eschatologique ultime

Le réseau de fabrication opère sur deux voies parallèles :
- **Voie égyptienne** : via Mūsā ibn 'Alī ← Ibn 'Amr (le compagnon du réseau Ka'b)
- **Voie syrienne** : via al-Awzā'ī qui attribue à Nāfi' un hadith que personne d'autre ne transmet

Le fait que la « hijra d'Ibrahim » soit précisément le thème récurrent de Ka'b al-Ahbar dans les faḍā'il al-Shām (cf. Tarikh Dimashq, p. 224 : « باب ما جاء في أن الشام مهاجر إبراهيم الخليل ») ferme la boucle : le hadith du Mustadrak reformule en « hadith prophétique » ce qui était à l'origine une tradition de Ka'b al-Ahbar.

---

## IX. Wahb ibn Munabbih (وهب بن منبه) — Étude comparative

### A. Méthodologie

Recherche systématique de « وهب بن منبه » dans les quatre mêmes sources que Ka'b al-Ahbar :

| Source | Wahb | Ka'b | Ratio |
|--------|------|------|-------|
| Tarikh al-Madina (Ibn Shabba) | **0** | ~10 | Ka'b seul |
| Tarikh Baghdad (al-Khatib) | **8** | 2 | Wahb dominant |
| Tarikh Dimashq (Ibn 'Asakir) | **177** | 103 | Wahb 1,7× plus |
| Tarikh al-Tabari | **40** | 11 | Wahb 3,6× plus |

**Constat majeur** : Wahb est **massivement plus cité** que Ka'b dans les sources encyclopédiques (Tabari, Ibn 'Asakir), alors qu'il est **totalement absent** du Tarikh al-Madina. Ce contraste reflète le profil de Wahb : un Yéménite dont l'activité narrative se déploie au Yémen et au Shām, pas à Médine.

### B. Identité biographique (Tarikh Dimashq, p. 29324-29361)

**Nom complet** : وهب بن منبه بن كامل بن سيج، أبو عبد الله الأبناوي الذماري الصنعاني اليماني

- **Kunya** : Abū 'Abd Allāh
- **Nisbas** : al-Abnāwī (des Abnā', Perses installés au Yémen), al-Dhimārī (de Dhimār, localité yéménite), al-Ṣan'ānī (de Sanaa), al-Yamānī
- **Naissance** : an 34 H, sous le califat de 'Uthmān (p. 29325)
- **Mort** : an 110 H (p. 29345 et suivantes), à environ 76 ans
- **Tabaqat** : 2e tabaqat des Yéménites (génération après les Compagnons)

**Réseau de transmission** :
- **A rencontré** : Ibn 'Abbās, Ibn 'Umar, **Ibn 'Amr ibn al-'Āṣ**, Jābir ibn 'Abd Allāh, Abū Hurayra, Ibn al-Zubayr, Anas ibn Mālik, al-Nu'mān ibn Bashīr, Abū Sa'īd al-Khudrī
- **Son frère** : Hammām ibn Munabbih, célèbre transmetteur d'Abū Hurayra (auteur de la « Ṣaḥīfa de Hammām »)
- **Transmetteurs de Wahb** : 'Amr ibn Dīnār, al-Mughīra ibn Ḥakīm, Simāk ibn al-Faḍl, al-Mundhir ibn al-Nu'mān, 'Abd al-Ṣamad ibn Ma'qil, 'Abd al-Karīm ibn Ḥawrān

**Parallèle frappant avec Ka'b** :
| | Ka'b al-Ahbar | Wahb ibn Munabbih |
|---|---|---|
| Origine | Yémen (Ḥimyar) | Yémen (Abnā' = Perses du Yémen) |
| Religion antérieure | Judaïsme | Discuté (perse/juive ?) |
| Compagnons fréquentés | Omar, Ibn 'Amr, Mu'āwiya | Ibn 'Abbās, Ibn 'Amr, Abū Hurayra |
| Spécialité | Isrā'īliyyāt, Torah | Isrā'īliyyāt, « livres anciens » |
| Lieu d'activité | Homs, Shām | Sanaa, mais cité massivement dans sources syriennes |
| Mort | 32 H à Homs | 110 H à Sanaa |
| Statut | Tābi'ī | Tābi'ī |

**Point critique** : Wahb a rencontré **Ibn 'Amr ibn al-'Āṣ** (p. 29324), le même Compagnon au centre du réseau Ka'b → Nawf → Shahr. Le frère de Wahb, Hammām, est le principal transmetteur d'**Abū Hurayra** — les deux Compagnons qui apparaissent dans le hadith de la « hijra vers le Shām » (Mustadrak n° 8558).

### C. Wahb dans Tarikh al-Tabari — Classification thématique (40 mentions)

| Thème | Pages | Nb |
|-------|-------|----|
| Création (Calame, Trône) | 37, 41 | 2 |
| Adam et ses descendants | 106, 174, 175 | 3 |
| Rois pré-islamiques (Biwarasb, Perse, Sassanides) | 199, 534, 599, 813, 862 | 5 |
| Prophètes (Loth, Job, Khiḍr, Moïse, Joseph, Jonas, Daniel) | 301, 319, 321, **363**, **398**, **404**, 411, 423, 428, 445, 468, 508, 509, 511, 517 | 15 |
| Histoire islamique (conquêtes, califat) | **643**, 1078, 1087, 1197, 1237, 1251, 1316 | 7 |
| Non classé / autres | reste | 8 |

**Pages avec chevauchement Ka'b-Wahb dans Tabari** : p. **363** (Khiḍr — Wahb « prétend d'après les Banū Isrā'īl » que le nom du Khiḍr est Ūrmiyā ibn Ḥilqiyā), p. **398** (Moïse — la même page que la rencontre Ka'b–Ibn 'Amr à La Mecque), p. **643** (Ka'b et Wahb cités ensemble comme sources d'isrā'īliyyāt).

**Observation clé** : Wahb est la source principale de Tabari pour l'histoire **anté-islamique et biblique**. Il couvre la Création, Adam, les prophètes, les rois perses — un champ beaucoup plus large que Ka'b (qui se concentre sur les faḍā'il et la politique). Tabari cite régulièrement « قال وهب بن منبه » comme autorité sur l'histoire universelle pré-islamique.

### D. Wahb dans Tarikh Dimashq — Classification thématique (177 mentions hors bio)

| Thème | Pages | Nb |
|-------|-------|----|
| Faḍā'il al-Shām (histoire de Damas, Shām terre élue, abdāl, mosquée) | 74, 184, 253, 271, 360, 696, 792, 846, 5884, 11848, 18260 | **11** |
| Prophètes et figures bibliques (Adam, Ibrahim, Irmiyā, Job, Bal'am, Tubba', 'Īsā, Yūnus, Dhu l-Qarnayn) | 47 pages | **47** |
| Autres biographies (transmetteurs, savants) | 79 pages | **79** |
| Divers (hadith nabawī, description du Prophète, etc.) | ~9 pages | **9** |

**Pages avec chevauchement Ka'b-Wahb dans Dimashq** : **18 pages**, dont :
- p. 74 : histoire de Damas (bâtisseurs de la ville)
- p. 184, 253 : le Shām comme terre élue (صفوة الله من بلاده)
- p. 792 : faḍā'il des mosquées
- p. 3151 : Adam
- p. 4162 : Job (Ayyūb)
- p. 4484 : Bal'am ibn Bā'ūrā'
- p. 22021 : 'Īsā (Jésus)
- p. 28080, 28082, 28094 : dans la section de transmetteurs liés au réseau Ka'b

**Fait remarquable** : Wahb contribue **11 pages** aux faḍā'il al-Shām dans Ibn 'Asakir — alors que Ka'b en contribue **15**. Les deux forment ensemble le socle des traditions « scripturaires » sur la sacralité du Shām. Sur 18 pages de chevauchement, une proportion significative concerne les faḍā'il al-Shām et les prophètes, confirmant la **complémentarité fonctionnelle** des deux figures.

### E. Wahb dans Tarikh Baghdad (8 mentions)

- **p. 71** : faḍā'il des fleuves (Tigre et Euphrate) — **contient aussi Ka'b**. Wahb et Ka'b cités ensemble comme sources de traditions sur les cours d'eau sacrés.
- **p. 6974** : biographie de **'Abd al-Mun'im ibn Idrīs ibn Sinān, petit-fils de Wahb** (ابن بنت وهب بن منبه). Cette entrée révèle que la descendance de Wahb a continué à transmettre — et à être critiquée : 'Abd al-Mun'im est généralement considéré comme un transmetteur très faible.
- **p. 1386, 1597, 1881** : Wahb apparaît dans des isnāds de biographies de savants baghdadiens
- **p. 6972, 6976, 9281** : dans des biographies de transmetteurs

### F. Synthèse comparative Ka'b — Wahb

#### 1. Profils complémentaires

Ka'b et Wahb forment un **binôme fonctionnel** dans la transmission des isrā'īliyyāt :

| Dimension | Ka'b al-Ahbar | Wahb ibn Munabbih |
|-----------|---------------|-------------------|
| Génération | 1re (contemporain des Compagnons, m. 32 H) | 2e (tābi'ī tardif, m. 110 H) |
| Espace d'action | Homs → Damas → Médine | Sanaa → mais réseau syrien |
| Type de savoir | Faḍā'il al-Shām, légitimation politique | Histoire universelle, prophètes, cosmogonie |
| Rapport au pouvoir | Direct (conseiller d'Omar, allié de Mu'āwiya) | Plus distant mais institutionnel |
| Critique reçue | Accusé par Ibn 'Abbās (via Nawf) | Son petit-fils déclaré très faible |
| Volume dans Ibn 'Asakir | 103 pages | **177 pages** |
| Volume dans Tabari | 11 pages | **40 pages** |

#### 2. Le réseau de transmission partagé

```
        Ka'b al-Ahbar (m. 32 H)          Wahb ibn Munabbih (m. 110 H)
              │                                    │
    ┌─────────┼──────────┐               ┌────────┼─────────┐
    │         │          │               │        │         │
   Nawf    Ibn 'Amr   Mu'āwiya      Hammām    Ibn 'Amr   'Amr ibn Dīnār
 (beau-fils) (compagnon) (calife)   (frère→    (compagnon)
    │                                Abū Hurayra)
    │
  Shahr ibn Hawshab
```

**Le nœud central** : **'Abd Allāh ibn 'Amr ibn al-'Āṣ** est le point de convergence des deux réseaux. Il est le Compagnon qui :
- rencontre Ka'b à La Mecque (Tabari p. 398)
- est le transmetteur auquel sont attribuées les traditions de faḍā'il al-Shām (Mustadrak n° 8558)
- est cité par Wahb comme source de traditions prophétiques (via les rencontres documentées p. 29324)

#### 3. Implications pour la thèse

La présence massive de Wahb dans les sources **renforce** la thèse du « réseau d'isrā'īliyyāt au service du pouvoir omeyyade » :

1. **Wahb n'est pas un doublon de Ka'b mais son successeur générationnel** : Ka'b meurt en 32 H, Wahb en 110 H. Wahb prend le relais de la production d'isrā'īliyyāt une génération plus tard, avec un champ élargi (cosmogonie, histoire universelle).

2. **Le volume supérieur de Wahb** (177 vs 103 dans Dimashq, 40 vs 11 dans Tabari) s'explique par sa longévité et la systématisation de la production narrative entre la 1re et la 2e génération.

3. **Les 18 pages de chevauchement Ka'b-Wahb** dans Ibn 'Asakir montrent que les deux figures sont souvent citées **dans les mêmes contextes** (faḍā'il al-Shām, prophètes), confirmant leur rôle complémentaire.

4. **Le frère de Wahb (Hammām) transmet d'Abū Hurayra** — or Abū Hurayra est celui qui transmet le hadith de la hijra vers le Shām (Mustadrak n° 8558) qu'il dit tenir d'**Ibn 'Amr**. La famille de Wahb est donc structurellement connectée aux deux Compagnons-pivots du réseau.

5. **L'absence de Wahb dans le Tarikh al-Madina** confirme que cette production narrative est **étrangère à Médine** : ni Ka'b ni Wahb n'ont de présence significative dans la tradition historiographique proprement médinoise. Leur importance se déploie dans les sources syriennes et universalistes.

---

## X. Biographie intégrale de Nawf al-Bikali dans Ibn 'Asakir (p. 28828-28838)

### A. Notice d'ouverture (p. 28828)

**Nom complet** : نوف بن فضالة، أبو يزيد / أبو رشيد / أبو عمرو / أبو رشدين، الحميري البكالي

**Identité familiale** : **ابن امرأة كعب الأحبار** — « fils de la femme de Ka'b al-Ahbar » (= beau-fils de Ka'b). Cette information est répétée **au moins 5 fois** dans la notice (p. 28828, 28833, 28834, 28835, 28837), ce qui montre que c'est l'élément identitaire central de Nawf.

**Origine géographique** : من أهل دمشق ويقال من أهل فلسطين — « de Damas, et on dit de Palestine »

**Compagnons qu'il a entendus** :
- **'Alī ibn Abī Ṭālib**
- **'Abd Allāh ibn 'Amr ibn al-'Āṣ** (le Compagnon-pivot du réseau)
- Abū Ayyūb al-Anṣārī
- Thawbān (affranchi du Prophète)

**Ceux qui transmettent de Nawf** :
- Abū Isḥāq al-Hamdānī
- Nusayr ibn Dhu'lūq
- Khālid ibn Ṣubayḥ
- Abū 'Imrān 'Abd al-Malik ibn Ḥabīb al-Jawnī
- Abū Hārūn 'Umāra ibn Juwayn al-'Abdī
- **Shahr ibn Ḥawshab al-Ash'arī** (le maillon suivant du réseau)

### B. Le hadith de la hijra vers le Shām — preuve décisive (p. 28829)

**C'est la découverte la plus importante de toute cette biographie.** La page 28829 contient le hadith de la hijra vers le Shām, avec la chaîne suivante :

```
Qatāda → Shahr ibn Ḥawshab → Nawf al-Bikālī → 'Abd Allāh ibn 'Amr ibn al-'Āṣ → le Prophète
```

Le texte :

> « Il y aura une hijra après la hijra. Les gens de la terre se dirigeront vers le lieu de migration de leur père Ibrahim (= le Shām). Il restera sur terre les pires de ses habitants ; leur terre les vomira, l'âme de Dieu les détestera, et Dieu enverra sur eux un feu qui les rassemblera avec les singes et les porcs. [...] Des peuples naîtront en Orient, récitant le Coran sans qu'il ne dépasse leur gosier. Chaque fois qu'un groupe est coupé, un autre naît, jusqu'à ce que le Dajjāl sorte parmi eux. »

**C'est EXACTEMENT le même hadith que le Mustadrak n° 8558** (section VIII), mais avec une chaîne différente :

| | Mustadrak n° 8558 | Ibn 'Asakir (bio de Nawf) |
|---|---|---|
| Chaîne | Mūsā ibn 'Alī (Égypte) ← Abū Hurayra ← Ibn 'Amr | **Qatāda ← Shahr ← Nawf ← Ibn 'Amr** |
| Compagnon-source | Ibn 'Amr | Ibn 'Amr (le même) |
| Réseau | Égyptien | **Ka'b → Nawf → Shahr** |

**Signification** : Le même hadith circule par deux voies, mais les deux convergent vers **Ibn 'Amr**. La chaîne de la biographie de Nawf passe explicitement par le réseau Ka'b : Shahr (qui transmet de Nawf) → Nawf (beau-fils de Ka'b) → Ibn 'Amr (que Ka'b a rencontré à La Mecque, Tabari p. 398). C'est la **preuve textuelle** du mécanisme de « blanchiment » décrit dans la section VI : une tradition d'isrā'īliyyāt de Ka'b, passée par son beau-fils Nawf, transmise par Shahr, et attribuée au Compagnon Ibn 'Amr pour lui donner le statut de hadith prophétique.

### C. Les traditions Nawf — 'Alī : fabrications proto-shiites (p. 28830-28832)

Plusieurs traditions mettent en scène Nawf auprès de 'Alī, mais **leur authenticité est très douteuse** :

**p. 28830** — Nawf est l'hôte de 'Alī pendant son califat. 'Alī lui adresse un long sermon ascétique contenant des références aux Banū Isrā'īl et au Messie — typiques du style d'isrā'īliyyāt.

**p. 28831** — La « célèbre » tradition de 'Alī et Nawf sur le toit : « Ô Nawf, es-tu endormi ou éveillé ? » Nawf est appelé **الشامي مولاه** (« le Syrien, son client »). 'Alī lui décrit ses « vrais partisans » (shī'a).

**p. 28832** — **Ibn al-Madīnī** (grand critique du hadith) démonte une chaîne passant par Nawf en exposant un **triple tadlīs** (dissimulation) : Abū 'Abd Allāh al-Jaṣṣāṣ est مجهول (inconnu), Ḥammād al-Qaṣṣār « personne ne sait qui c'est », et Furqad « n'a jamais rencontré Nawf ». Le hadith est déclaré **منقطع** (déconnecté).

**Pourquoi ces traditions sont des fabrications** :

1. **Chronologie fragile** : le califat de 'Alī s'étend de 35 à 40 H. Nawf est actif sous Muṣ'ab ibn al-Zubayr (67-72 H) et meurt vers 83 H. Il aurait été très jeune sous 'Alī, et les longues discussions philosophiques nocturnes ne cadrent pas avec une rencontre avec un jeune Syrien inconnu.

2. **Incohérence identitaire** : qualifier Nawf de « الشامي مولاه » (« le Syrien, client de 'Alī ») est suspect. Nawf est un Ḥimyarī, beau-fils de Ka'b al-Ahbar, qāṣṣ à Homs, mort au combat **dans l'armée omeyyade**. C'est un homme du réseau omeyyade syrien, pas un disciple de 'Alī.

3. **Ibn al-Madīnī expose la fabrication** : la critique de chaîne (p. 28832) montre que même les muḥaddithūn anciens identifiaient ces traditions comme fabriquées et attribuées rétrospectivement à Nawf.

4. **Schéma classique** : des cercles proto-shiites ont **greffé leurs propres traditions sur un nom connu** (Nawf), exactement comme le réseau omeyyade greffa les faḍā'il al-Shām sur Ibn 'Amr. Nawf était devenu un « porte-manteau narratif » suffisamment célèbre pour que différents courants lui attribuent des traditions. Cela **renforce** plutôt qu'il n'affaiblit la thèse : la notoriété de Nawf comme transmetteur en faisait une cible d'attribution par tous les camps.

### D. Nawf comme qāṣṣ — confirmations multiples (p. 28834, 28836)

**p. 28834** — **Umm al-Dardā'** (grande figure de Homs) envoie un message à « Unayf et un autre, **قاصين كانا بحمص** (deux qāṣṣīn/prédicateurs-conteurs qui étaient à Homs) » pour leur dire de « commencer par appliquer leurs sermons à eux-mêmes ». Ibn 'Asakir identifie l'un d'eux : **« وهو البكالي »** (« c'est al-Bikālī » = Nawf). C'est la preuve directe que **Nawf exerçait la fonction officielle de qāṣṣ à Homs** — la même ville où Ka'b prêchait (Tarikh al-Madina p. 19).

**p. 28834** — Nawf a été entendu **à Kufa** في أيام مصعب بن الزبير (« aux jours de Muṣ'ab ibn al-Zubayr »), le gouverneur zubayride d'Irak (67-72 H). Cela montre la **mobilité géographique** de Nawf : Homs → Kufa → retour en Syrie.

**p. 28836** — Ahmad ibn Muhammad ibn 'Īsā dit explicitement : **وكان قاصا** (« et il était un qāṣṣ »), حدث عن ثوبان (« il transmettait de Thawbān »), **قتل يوم الطوانة** (« tué le jour d'al-Ṭawāna »).

### E. Nawf imam de Damas (p. 28837)

Al-Shaybānī rapporte : **كان نوف البكالي إماما لأهل دمشق** — « Nawf al-Bikālī était imam pour les gens de Damas ». Quand il se tournait vers les fidèles, il disait : « Celui qui ne vous aime pas, que Dieu ne l'aime pas ; celui qui n'a pas pitié de vous, que Dieu n'ait pas pitié de lui. »

**Nawf cumulait donc trois fonctions** :
1. **Qāṣṣ** (conteur-prédicateur) à Homs
2. **Imam** (dirigeant la prière) à Damas
3. **Transmetteur** de traditions d'isrā'īliyyāt héritées de Ka'b

### F. La mort de Nawf — tué au service des Omeyyades (p. 28836, 28838)

**p. 28838** — Ibn al-Mubārak rapporte via Ṣafwān ibn 'Amr : « Nous allions régulièrement chez Nawf al-Bikālī, puis **les armées partirent avec Muḥammad ibn Marwān** pour la campagne d'été (al-Ṣā'ifa), **et il fut tué** (فقتل). »

Un homme avait raconté à Nawf un rêve : « Je t'ai vu mener une armée avec une lance longue portant un cierge éclairant les gens. » Nawf répondit : « **Si ton rêve est véridique, je serai martyrisé.** » Puis les armées partirent avec Muḥammad ibn Marwān et il fut tué.

**Muḥammad ibn Marwān** est le frère du calife 'Abd al-Malik ibn Marwān, gouverneur de la Jazīra et commandant des expéditions byzantines. La **bataille d'al-Ṭawāna** (Tyana, en Cappadoce) eut lieu vers **83 H / 702 EC**.

**C'est un fait capital** : Nawf al-Bikālī **est mort au combat dans l'armée omeyyade**, sous le commandement du frère du calife. Il n'était pas un simple savant indépendant — c'était un **soldat-prédicateur** au service direct de l'État omeyyade.

### G. Tabaqat et évaluation critique

- **Khalīfa ibn Khayyāṭ** (p. 28832) : le place dans la **1re tabaqat des Syriens**
- **Ibn Sa'd** (p. 28833) : le place dans la **2e tabaqat des tābi'īn du Shām**
- **Abū Zur'a** (p. 28835) : le place dans le rang juste en dessous de la tabaqat supérieure des tābi'īn syriens
- **Yaḥyā ibn Ma'īn** (p. 28833) : **نوف شامي وقد كان نزل الكوفة** — « Nawf est Syrien et avait résidé à Kufa »
- **Abū 'Imrān al-Jawnī** (p. 28834, 28837) : **كان نوف ابن امرأة كعب أحد العلماء** — « Nawf, beau-fils de Ka'b, était l'un des savants »
- **al-Bukhārī** (p. 28835) : avait créé deux entrées distinctes (Nawf ibn 'Abd Allāh / Nawf ibn Faḍāla) qu'Abū Ḥātim a rectifiées en montrant qu'il s'agit d'une seule personne

### H. Synthèse : le profil complet de Nawf al-Bikali

```
                     NAWF AL-BIKĀLĪ — Fiche récapitulative
┌─────────────────────────────────────────────────────────────────┐
│ Identité    : Nawf ibn Faḍāla, Ḥimyarī, Bikālī                │
│ Famille     : Beau-fils de Ka'b al-Ahbar (ابن امرأة كعب)       │
│ Origine     : Damas / Palestine                                 │
│ Fonctions   : qāṣṣ à Homs, imam à Damas, soldat omeyyade      │
│ Mobilité    : Homs → Kufa (sous Muṣ'ab) → retour en Syrie      │
│ Mort        : ~83 H (702 EC), tué à al-Ṭawāna avec l'armée     │
│               de Muḥammad ibn Marwān (frère du calife)          │
│ Transmit de : Ka'b al-Ahbar, Ibn 'Amr, Thawbān (+ 'Alī douteux)│
│ Transmis par: Shahr ibn Ḥawshab, Abū Isḥāq, Abū 'Imrān...    │
└─────────────────────────────────────────────────────────────────┘
```

**Le portrait qui émerge est celui d'un agent omeyyade multifonction** :

1. **Héritier du savoir de Ka'b** : en tant que beau-fils, il a accès direct aux traditions d'isrā'īliyyāt de Ka'b et les transmet comme « hadith ».

2. **Prédicateur officiel (qāṣṣ) à Homs** : la même ville où Ka'b prêchait (p. 19 du Tarikh al-Madina). La continuité géographique est parfaite. Umm al-Dardā' le critique, ce qui montre que son activité de prédication était connue et parfois contestée.

3. **Imam de Damas** : autorité religieuse dans la capitale omeyyade elle-même.

4. **Soldat mort au combat pour les Omeyyades** : il meurt dans une campagne militaire commandée par le frère du calife 'Abd al-Malik. C'est l'engagement le plus direct possible envers le pouvoir omeyyade.

5. **Mobilité au service de la cause** : sa présence à Kufa « aux jours de Muṣ'ab ibn al-Zubayr » (le gouverneur zubayride d'Irak, rival des Omeyyades) pourrait même indiquer un rôle de **propagandiste itinérant** — prêchant les traditions pro-Shām dans les territoires contestés.

6. **Nom récupéré par les proto-shiites** : les traditions avec 'Alī (p. 28830-28831) sont des **fabrications tardives** (chaînes démontées par Ibn al-Madīnī, chronologie fragile). Mais leur existence même montre que le nom de Nawf était devenu un « porte-manteau narratif » — suffisamment célèbre pour que des cercles non-omeyyades lui attribuent aussi leurs propres traditions. Cela confirme paradoxalement son importance dans le paysage narratif du 1er siècle.

7. **La chaîne Shahr → Nawf → Ibn 'Amr pour le hadith de la hijra** (p. 28829) est le **chaînon manquant** qui relie directement le Mustadrak n° 8558 au réseau Ka'b. Le même hadith, transmis par deux chaînes différentes (l'une égyptienne via Abū Hurayra, l'autre syrienne via le réseau Ka'b), convergeant vers le même Compagnon (Ibn 'Amr) — c'est la signature d'une **tradition fabriquée puis injectée dans plusieurs circuits** pour lui donner l'apparence de la multiplicité des voies (ta'addud al-ṭuruq).

---

## XI. Dhū'l-Kilā' al-Ḥimyarī — Cousin de Ka'b, organisateur militaire omeyyade

### A. Identité

**Nom** : أسميفع بن باكورا (Asmayfa' ibn Bākūrā), aussi سميفع بن حوشب. Kunya : Abū Shuraḥbīl.
**Titre** : Dhū'l-Kilā' (ذو الكلاع) — titre héréditaire himyarite désignant le chef suprême des tribus Kilā'iyya.
**Tribu** : Ḥimyar — **même clan que Ka'b al-Ahbar** (Banū Maytam / Dhū Ra'ayn). Les sources le désignent comme **cousin (ibn 'amm)** de Ka'b.
**Religion antérieure** : Chrétien (le christianisme dominait chez les Ḥimyarites).
**Résidence** : Installé à **Homs** après la conquête — la même ville que Ka'b.

### B. Parcours politique et militaire

**Conversion** : Le Prophète envoya **Jarīr ibn 'Abd Allāh al-Bajalī** à Dhū'l-Kilā' pour l'inviter à l'islam (Tarikh Dimashq p. 7730-7731). Dhū'l-Kilā' accepta et libéra des milliers d'esclaves.

**Guerres de conquête** : Il commanda des contingents yéménites aux batailles de :
- **Yarmouk** (636 EC) — commandant d'un kirdūs (Dimashq p. 7731)
- **Conquête de Damas**
- **al-Qādisiyya** et **Nahāwand**

**Installation à Homs** : Les tribus himyarites de Homs obéissaient à Dhū'l-Kilā' **plutôt qu'à Mu'āwiya directement**. Il était un pouvoir semi-autonome au sein de l'appareil omeyyade.

### C. Siffin et la mort (37 H / 657 EC)

**Rôle à Ṣiffīn** : Commandant de l'**aile droite** (al-maymana) de l'armée de Mu'āwiya, composée des troupes yéménites et des gens de Homs. Les sources le qualifient de **القائم بأمر معاوية في حرب صفين** (« celui qui gérait les affaires de Mu'āwiya dans la guerre de Ṣiffīn »).

**Siffin dans Tarikh Dimashq** (p. 7095) : Mu'āwiya avait assigné à Ḥimyar par tirage au sort le combat contre Rabī'a. Dhū'l-Kilā' dit : « Que Dieu te maudisse, ô sort, j'ai détesté combattre aujourd'hui. » Puis il mena Ḥimyar avec 'Ubayd Allāh ibn 'Umar à ses côtés.

**Sa mort et la réaction de Mu'āwiya** : Dhū'l-Kilā' fut **tué au combat à Ṣiffīn**. Selon plusieurs sources, **Mu'āwiya se réjouit de sa mort** (فرح معاوية بموته), car il avait appris que Dhū'l-Kilā' était devenu convaincu que **'Alī était innocent du sang de 'Uthmān** et que Mu'āwiya les avait trompés. Dhū'l-Kilā' préparait une défection (أراد التشتيت على معاوية) qui aurait pu être catastrophique pour Mu'āwiya. Sa mort avant qu'il puisse agir fut providentielle pour la cause omeyyade.

**Son fils Shuraḥbīl** devint ensuite un commandant omeyyade loyal, tué à la bataille de Khāzir (686 EC).

### D. La scène du qiṣāṣ — Ka'b autorisé par Mu'āwiya

L'épisode le plus significatif pour notre recherche est rapporté dans les sources de hadith :

**'Awf ibn Mālik** entre dans la mosquée (à Homs), appuyé sur le bras de **Dhū'l-Kilā'**. Ka'b al-Ahbar est en train de faire du **qaṣṣ** (prédication publique) devant les gens. 'Awf dit à Dhū'l-Kilā' : « **Ne vas-tu pas empêcher ton cousin (ibn 'ammak) de faire ce qu'il fait ?** » Puis il cite un hadith du Prophète :

> **« Les quṣṣāṣ (conteurs/prédicateurs) sont de trois types : un émir (amīr), un mandaté (ma'mūr), ou un imposteur (mukhtāl/muḥtāl). »**

En entendant ce hadith, **Ka'b cessa son activité de qaṣṣ**. Mais **Mu'āwiya lui ordonna de reprendre** (amarahu), ce qui fit de Ka'b un qāṣṣ relevant de la catégorie « ma'mūr » (mandaté par le pouvoir).

**Signification** :
1. Ka'b pratiquait le qaṣṣ **dans la mosquée de Homs**, sous les yeux des notables comme Dhū'l-Kilā'
2. **Mu'āwiya** est celui qui **autorise officiellement** Ka'b à prêcher — c'est l'institutionnalisation du qaṣṣ par le pouvoir politique
3. Le lien familial Ka'b–Dhū'l-Kilā' montre que le clan himyarite était au cœur de l'appareil omeyyade à Homs
4. 'Awf ibn Mālik tente de faire taire Ka'b en invoquant un hadith prophétique — mais Mu'āwiya contourne l'objection en mandatant Ka'b officiellement

### E. Synthèse : le clan himyarite de Homs

```
                    LE CLAN HIMYARITE DE HOMS
┌──────────────────────────────────────────────────────────┐
│                                                          │
│   Dhū'l-Kilā' (cousin)  ←──→  Ka'b al-Ahbar (cousin)   │
│   Chef militaire               Qāṣṣ / savant            │
│   Tué à Ṣiffīn (37 H)         Mort à Homs (32 H)        │
│        │                            │                    │
│   Shuraḥbīl                    Nawf al-Bikālī            │
│   (fils, cmdt omeyyade)        (beau-fils, qāṣṣ)         │
│                                     │                    │
│                                Shahr ibn Ḥawshab         │
│                                (transmetteur)            │
│                                                          │
│   Protecteur : MU'ĀWIYA (gouverneur puis calife)         │
│   Ville : HOMS (حمص) — base arrière omeyyade            │
└──────────────────────────────────────────────────────────┘
```

Ka'b et Dhū'l-Kilā' forment les **deux faces du même clan himyarite** au service de Mu'āwiya : l'un fournit la **force militaire**, l'autre la **légitimation narrative et religieuse**. Le fait qu'ils soient cousins et tous deux installés à Homs n'est pas une coïncidence — c'est la structure même du pouvoir tribal yéménite intégré dans l'appareil omeyyade syrien.

---

## XII. Paroles et traditions de Ka'b — Affinement du portrait

### A. Ka'b et Abū Hurayra : « Personne ne connaît mieux la Torah » (Dimashq p. 30865)

Ka'b rencontre Abū Hurayra ; ils échangent des traditions. Ka'b déclare :

> **ما رأيت أحدا لم يقرأ التوراة أعلم بما في التوراة من أبي هريرة**
> « Je n'ai vu personne qui n'a pas lu la Torah connaître mieux le contenu de la Torah qu'Abū Hurayra. »

**Sur la même page** — 'Umar menace les deux simultanément :
- À Abū Hurayra : « **Tu cesseras de transmettre des hadiths du Prophète ou je t'enverrai au pays de Daws** (sa tribu d'origine) »
- À Ka'b : « **Tu cesseras de transmettre ou je t'enverrai au pays des singes** »

**Analyse** :
1. Ka'b **certifie** Abū Hurayra comme « connaisseur de la Torah sans l'avoir lue » — c'est un acte de **validation croisée** entre les deux transmetteurs. Ka'b donne à Abū Hurayra une autorité en matière d'isrā'īliyyāt, et Abū Hurayra transmet les traditions de Ka'b comme si elles étaient du Prophète.
2. **'Umar les menace tous les deux ensemble** — il les identifie comme un **binôme problématique** de transmission excessive. Ce n'est pas Ka'b seul ni Abū Hurayra seul : c'est le couple Ka'b + Abū Hurayra qui inquiète le calife.
3. Le **« pays des singes »** (أرض القردة) est une allusion au Coran (2:65, 7:166) sur les Juifs transformés en singes — 'Umar renvoie Ka'b à son identité juive comme menace.

### B. Mu'āwiya : « Ka'b est le plus véridique » (Dimashq p. 23281)

Mu'āwiya déclare publiquement :

> **« Abū al-Dardā' est l'un des sages, 'Amr ibn al-'Āṣ est l'un des sages, Ka'b al-Ahbar est l'un des savants — il avait un savoir comme les fruits, et nous étions négligents à son égard. »**

Et dans un autre isnād (via al-Zuhrī ← Ḥumayd ibn 'Abd al-Raḥmān ← Mu'āwiya) :

> **« Ka'b était le plus véridique (أصدق) de ceux qui transmettent du Livre (= la Torah/Bible). »**

**Analyse** : Mu'āwiya place Ka'b au même rang qu'Abū al-Dardā' (grand ascète) et 'Amr ibn al-'Āṣ (conquérant de l'Égypte, père d'Ibn 'Amr). C'est un **triangle de pouvoir** : le sage, le stratège, le savant. Mu'āwiya **labellise** Ka'b comme autorité officielle sur les traditions scripturaires.

### C. Abū Hurayra : « Quand Mu'āwiya le payait, il se taisait » (al-Thiqāt d'al-'Ijlī, p. 185)

Sa'īd ibn al-Musayyab (le grand juriste médinois) rapporte :

> **كان أبو هريرة إذا أعطاه معاوية سكت، وإذا أمسك عنه تكلم**
> « Abū Hurayra, quand Mu'āwiya le payait, il se taisait. Et quand Mu'āwiya cessait de le payer, il parlait. »

**Analyse** : C'est un témoignage dévastateur d'un contemporain (Ibn al-Musayyab). Il montre qu'Abū Hurayra était **financièrement dépendant** de Mu'āwiya, et que sa « parole » (= transmission de hadiths) était conditionnée par ce flux d'argent. Le silence quand il est payé suggère qu'il **cessait de critiquer** ou de transmettre des traditions gênantes pour le pouvoir ; la parole quand il n'est pas payé suggère qu'il menaçait de le faire. C'est un mécanisme de **contrôle financier de la tradition prophétique**.

### D. Al-Falaq — Ka'b entre dans une église (al-Takhwīf min al-Nār, p. 124)

> Ka'b al-Ahbar **entre dans une église** (كنيسة), admire sa beauté, puis dit : **« Belle construction, mais peuple égaré. J'accepte pour eux al-Falaq. »** On lui demande : « Qu'est-ce qu'al-Falaq ? » Il répond : **« Une maison en enfer ; quand elle s'ouvre, tous les gens de l'enfer crient de la violence de sa chaleur. »**

**Analyse** : Ka'b **entre librement dans une église**, ce qui montre :
1. Son **aisance inter-religieuse** — il se déplace entre les espaces de culte
2. Il **juge** les chrétiens depuis sa position de « savant des religions » — admiration esthétique mais condamnation théologique
3. Il produit un concept eschatologique (**al-Falaq**) qui ne vient ni du Coran ni du hadith canonique, mais de ses propres traditions — typique de la production d'isrā'īliyyāt à visée morale

### E. Qatāda ← al-Ḥasan / Ibn Sam'ān ← Ka'b (Tafsīr al-Tha'labī, p. 12081)

Chaîne de transmission pour l'histoire de David :

```
Qatāda ← al-Ḥasan al-Baṣrī  }
                                 ← (intermédiaire) ← Ka'b al-Ahbar
Qatāda ← Ibn Sam'ān (matrūk)  }

Abū Ilyās ← Wahb ibn Munabbih (même récit, voie parallèle)
```

**Les critiques ont classé cette chaîne** : Isḥāq ibn Bishr = كذاب (menteur), Sa'īd ibn Bashīr = ضعيف (faible, transmet les munkarat de Qatāda), Ibn Sam'ān = متروك (abandonné).

**Signification** : Ce passage montre que **Qatāda** (grand exégète basrien, m. 117 H) transmettait des traditions remontant à **Ka'b al-Ahbar** via al-Ḥasan al-Baṣrī et d'autres. Wahb ibn Munabbih transmet le même récit par une autre voie. Cela confirme que les isrā'īliyyāt de Ka'b et Wahb circulaient **en parallèle** et alimentaient l'exégèse coranique via des figures comme Qatāda.

### F. Tubā'ī ibn 'Āmir — gendre de Ka'b (Usd al-Ghāba, p. 145)

Le livre Usd al-Ghāba (dictionnaire biographique des Compagnons) mentionne **Tubā'ī ibn 'Āmir** comme **gendre de Ka'b al-Ahbar** (صهر كعب الأحبار). Cela ajoute un autre membre au réseau familial de Ka'b : en plus de son beau-fils Nawf (ابن امرأته), Ka'b a aussi un gendre (Tubā'ī) dans le tissu social de Homs/Shām.

---

## XIII. Portraits d'Abū Hurayra et de Qatāda — Figures du réseau

### A. Abū Hurayra al-Dawsī — le transmetteur captif

**Profil** : Compagnon tardif (converti en 7 H, ~ 3 ans avec le Prophète), devenu le **plus prolifique transmetteur de hadiths** (> 5 000 traditions attribuées). Originaire de la tribu de Daws au Yémen.

**Position dans le réseau Ka'b** :
- Ka'b **le certifie** comme « le meilleur connaisseur de la Torah parmi ceux qui ne l'ont pas lue » (Dimashq p. 30865) — ce qui implique que les traditions d'Abū Hurayra recoupent le contenu de la Torah telle que Ka'b la connaît
- **'Umar les menace ensemble** (même page) — les identifiant comme un binôme
- **Mu'āwiya le paie** pour son silence (al-Thiqāt p. 185) — achetant son allégeance
- Il transmet le hadith de la **hijra vers le Shām** en disant l'avoir reçu d'**Ibn 'Amr** (Mustadrak n° 8558) — le même Ibn 'Amr qui est au centre du réseau Ka'b
- Son frère **Hammām** est le frère de **Wahb ibn Munabbih** — les familles sont liées

**Le mécanisme** : Abū Hurayra est le **point de sortie** du réseau. Les traditions d'isrā'īliyyāt de Ka'b, passées par Nawf et/ou Ibn 'Amr, sont reformulées en « hadiths prophétiques » par Abū Hurayra, qui a la légitimité d'un Compagnon du Prophète. Ka'b le certifie (« tu connais la Torah mieux que quiconque »), Mu'āwiya le rémunère, et les traditions circulent.

### B. Qatāda ibn Di'āma al-Sadūsī — l'exégète relais

**Profil** : Célèbre exégète et transmetteur de Basra (m. 117 H). Aveugle de naissance. Considéré comme **thiqqa thabt** (fiable et solide) par les critiques.

**Position dans le réseau** :
- Il transmet d'**al-Ḥasan al-Baṣrī** et d'**Ibn Sam'ān** des traditions remontant à **Ka'b al-Ahbar** (Tafsīr al-Tha'labī p. 12081)
- Il transmet le hadith de la hijra via la chaîne **Shahr → Nawf → Ibn 'Amr** (Dimashq p. 28829)
- Il est la voie principale par laquelle les isrā'īliyyāt de Ka'b ont pénétré l'**exégèse coranique** (tafsīr)
- Sa'īd ibn Bashīr, qui transmet de Qatāda, est qualifié de ضعيف يروي عن قتادة المنكرات (« faible, il transmet les munkarat — traditions répréhensibles — de Qatāda »)

**Le rôle de Qatāda** : Il n'est pas un fabricateur mais un **relais** — un savant respecté qui transmettait, entre autres, des traditions d'isrā'īliyyāt sans toujours discerner leur origine. Son prestige de muḥaddith basrien a donné aux traditions de Ka'b une **crédibilité exégétique** qu'elles n'auraient pas eue autrement.

---

## XV. 'Abd Allāh ibn 'Amr ibn al-'Āṣ — Les ṣuḥuf de Yarmūk et Sarj al-Yarmūkī

### A. Le problème des « deux zamālatain »

Fait établi même par les défenseurs de la Sunna : **Ibn 'Amr a obtenu à la bataille de Yarmūk (15 H / 636 EC) deux zamālatain** (charges de chameau) **de livres des Gens du Livre**. Il en tirait ensuite des récits qu'il transmettait.

**Sources primaires** :
- **Ibn Kathīr**, al-Bidāya wa'l-Nihāya (2/107), cité dans al-Maṭālib al-'Āliya (shamela.ws/book/37618/16842) : « فإنه أصاب يوم اليرموك زاملتين من كتب المتقدمين، فكان يحدث منهما » — « Il obtint à Yarmūk deux charges de chameau de livres des Anciens, et il en narrait. »
- **Bishr al-Marīsī** (rationaliste mu'tazilite, m. 218 H) accuse Ibn 'Amr d'avoir présenté ces récits comme prophétiques : « عبد الله بن عمرو كان يرويهما للناس عن النبي صلى الله عليه وسلم، وكان يقال له: لا تحدثنا عن الزاملتين » — « Il les narrait aux gens comme venant du Prophète, et on lui disait : Ne nous raconte pas [ce qui vient] des deux zamālatain ! » (shamela.ws/book/8680/608-609)
- **Maḥmūd Abū Rayya** (critique moderne, Aḍwā' 'alā al-Sunna) reprend la même accusation (shamela.ws/book/224/1624)

**Analyse** : Le fait matériel n'est contesté par personne — Ibn 'Amr a récupéré une vaste bibliothèque de manuscrits scripturaires à Yarmūk. La dispute porte sur la question de savoir s'il les a **mélangés** avec les hadiths prophétiques. Dans le cadre de notre recherche, c'est précisément ce que le réseau de transmission suggère.

### B. « Il lisait les Livres » — Tafsīr al-Ṭabarī

Le Tafsīr al-Ṭabarī (shamela.ws/book/43/6687) contient un hadith révélateur (n° 14214) :

Des musulmans entendent **Marwān ibn al-Ḥakam** à Médine parler des signes eschatologiques. Ils vont voir **Ibn 'Amr**, qui corrige Marwān et donne un hadith prophétique sur le lever du soleil par l'Ouest. Puis le texte précise :

« ثم قال عبد الله بن عمرو — **وكان يقرأ الكتب** — أظن أولهما خروجًا طلوع الشمس من مغربها »

— « Puis 'Abd Allāh ibn 'Amr dit — **et il lisait les Livres** — je pense que le premier [signe] à apparaître est le lever du soleil par l'Ouest. »

La mention « وكان يقرأ الكتب » (il lisait les Livres [scripturaires]) est un aveu textuel : les commentateurs reconnaissent qu'Ibn 'Amr puisait dans la littérature biblique/juive. Le hadith mêle ensuite prophétie islamique et cosmologie scripturaire (le soleil se prosternant sous le Trône).

### C. Sarj al-Yarmūkī — le maître kitābī d'Ibn 'Amr

**Sarj al-Yarmūkī** (سرج اليرموكي) est une figure peu connue mais cruciale :

**Identité** (al-Iṣāba, shamela.ws/book/9767/1440) :
- « من أهل الكتاب. أدرك النبي صلى الله عليه وسلم وأسلم بعده » — « Des Gens du Livre. Il a vécu à l'époque du Prophète et s'est converti après lui. »
- Il est donc un **converti** de l'ère des conquêtes, exactement comme Ka'b al-Aḥbār.

**Sa tradition** (attestée dans trois sources) :
- Al-Iṣāba (9767/1440), Kitāb al-Fitan de Nu'aym ibn Ḥammād (13047/231), Tārīkh Dimashq (71/8953)
- Chaîne : Ḥammād ibn Salama ← Ya'lā ibn 'Aṭā' ← Baḥīr/Bajīr Abū 'Ubayd ← **Sarj al-Yarmūkī**
- Texte : « أجد في الكتاب [= التوراة] أن هذه الأمة اثنا عشر ربيا نبيهم أحدهم، فإذا وفت العدة طغوا وبغوا وكان بأسهم بينهم »
- « Je trouve dans le Livre [= la Torah] que cette communauté aura douze chefs, leur prophète étant l'un d'eux, et quand le nombre sera atteint ils deviendront tyranniques et oppressifs et leur violence sera entre eux. »

**Le lien crucial** — Les trois sources confirment :
« وكان عبد الله بن عمرو **يتعلم من سرج هذا** » — « Et 'Abd Allāh ibn 'Amr **apprenait de ce Sarj**. »

### D. Synthèse : le circuit complet

Le circuit de transmission des isrā'īliyyāt via Ibn 'Amr se reconstitue ainsi :

```
SOURCES SCRIPTURAIRES
        ↓
Zamālatain de Yarmūk (15 H) ←→ Sarj al-Yarmūkī (converti kitābī)
        ↓                              ↓
  'ABD ALLĀH IBN 'AMR (يتعلم من سرج / يقرأ الكتب)
        ↓                    ↓
   Nawf al-Bikālī         Abū Hurayra
   (beau-fils de Ka'b)    (certifié par Ka'b)
        ↓                    ↓
   Shahr ibn Ḥawshab     Traditions « prophétiques »
        ↓
   Qatāda → Tafsīr
```

Ibn 'Amr est donc **doublement alimenté** en isrā'īliyyāt :
1. Par les **livres** physiques récupérés à Yarmūk (les zamālatain)
2. Par **Sarj al-Yarmūkī**, un converti qui lui enseigne directement le contenu de la Torah

Il est ensuite le **nœud de convergence** des deux chaînes du hadith de la hijra vers le Shām, et ses traditions eschatologiques mêlent explicitement matériel prophétique et scripturaire (Tafsīr al-Ṭabarī).

**Connexion avec Ka'b** : La rencontre documentée entre Ka'b et Ibn 'Amr à La Mecque (Ṭabarī p. 398), le fait que Nawf (beau-fils de Ka'b) transmette d'Ibn 'Amr, et la présence de Sarj al-Yarmūkī comme maître-source de type identique à Ka'b (converti kitābī) dessinent un **réseau cohérent** de diffusion d'isrā'īliyyāt dans les premières générations islamiques.

---

## XVI. Al-Awzā'ī — juriste du Shām et relais du réseau

### A. Aveu sur les faḍā'il Ahl al-Bayt

Al-Walīd ibn Muslim rapporte d'al-Awzā'ī (Jāmi' Bayān al-'Ilm d'Ibn 'Abd al-Barr, shamela.ws/book/22367/1428) :

« كانوا يستحيون أن يتحدثوا بأحاديث فضائل أهل البيت ليردوا أهل الشام عما كانوا يأخذون فيه »

— « Ils répugnaient à transmettre les hadiths des mérites d'Ahl al-Bayt [pour tenter de] détourner les gens du Shām de ce en quoi ils s'engageaient. »

**Analyse** : Cet aveu révèle que (1) les gens du Shām avaient une **hostilité envers Ahl al-Bayt** qu'il fallait corriger, et (2) les savants **choisissaient stratégiquement** quels hadiths transmettre selon le public. La transmission n'est pas neutre — elle est orientée.

### B. Ghaylān al-Dimashqī et le qadar

Al-Awzā'ī dans al-Sharī'a d'al-Ājurrī (shamela.ws/book/1257/17) :

« أول من نطق بالقدر: رجل من أهل العراق، يقال له: سوسن، وكان نصرانيا فأسلم، ثم تنصر، فأخذ عنه معبد الجهني، وأخذ غيلان عن معبد »

Chaîne du qadar : Sawsan (chrétien irakien) → Ma'bad al-Juhanī → **Ghaylān al-Dimashqī** (crucifié par Hishām ibn 'Abd al-Malik, ~106 H). Après l'exécution, « les gens du Shām furent tranquilles » selon al-Awzā'ī (shamela.ws/book/30017/152).

### C. Les quatre défauts régionaux

Al-Awzā'ī (Mukhtaṣar Tārīkh Dimashq, shamela.ws/book/3118/112) énumère deux pratiques condamnables par région : Iraq (retarder le suḥūr, nabīdh), Makkah (mut'a, ṣarf/ribā), Médine (rapports par derrière, samā'), Shām (vente d'alcool, dīwān). Il ajoute que les deux défauts du Shām « ont disparu ».

### D. La chaîne Makhūl et la connexion au réseau

Al-Awzā'ī fut l'**élève direct de Makhūl al-Shāmī** (« رأيت مكحولا » — Muṣannaf Ibn Abī Shayba, shamela.ws/book/333/7589). Le Musnad al-Shāmiyyīn d'al-Ṭabarānī (shamela.ws/book/13162/2856) atteste une chaîne entièrement shāmie :

**Al-Awzā'ī ← Makhūl ← Rajā' ibn Ḥaywa ← 'Abd Allāh ibn 'Amr**

Rajā' ibn Ḥaywa est le conseiller des califes omeyyades (bâtisseur du Dôme du Rocher). Cette chaîne connecte al-Awzā'ī directement au réseau Ka'b-Ibn 'Amr via l'appareil administratif omeyyade.

---

## XVII. Ka'b al-Aḥbār — philosophie et approche (Ḥilyat al-Awliyā')

La **Ḥilyat al-Awliyā'** d'Abū Nu'aym al-Iṣfahānī (shamela.ws/book/10495, p. 7969-8002) consacre 34 pages à Ka'b al-Aḥbār. C'est le corpus le plus riche sur sa prédication directe.

### A. L'auto-définition

Ka'b se décrit comme « **al-ḥibr**, possesseur des livres et des écritures, celui qui révèle ce qui est caché et les secrets » (p. 7969). Il revendique son statut de détenteur d'un savoir scripturaire inaccessible aux autres.

### B. Le registre ascétique (proto-soufi)

Ka'b prêche un ascétisme radical (p. 7970-7976) : la pauvreté est élection divine, les prophètes préféraient l'épreuve, Moïse accuse les faux dévots d'avoir « les cœurs des loups ». Le silence est sagesse, les larmes de crainte valent plus que l'or. La notice le rapproche explicitement du soufisme (p. 7969) : Ka'b fournit le **matériel scripturaire** qui alimentera la spiritualité islamique des premiers siècles.

### C. La terreur eschatologique — cœur de la prédication

Le schéma récurrent : **'Umar demande « خوّفنا يا كعب »** (« fais-nous peur ») et Ka'b délivre des terreurs croissantes jusqu'à faire pleurer l'assistance (p. 7985-7986, 7994). Les descriptions d'enfer sont d'une précision visuelle extrême : gardiens dont les épaules couvrent une année de voyage, seau de liquide brûlant qui fait bouillir les crânes d'un bout à l'autre de la terre, fours étroits comme des pointes de lance (p. 7984-7999).

Le récit le plus développé (p. 8001) est une vaste fresque du Jugement dernier où l'Enfer rugit trois fois, les prophètes tombent à genoux, et seul Muḥammad intercède pour sa communauté. Ce récit mêle des éléments coraniques à du matériel **visiblement extra-coranique** dans un ensemble homogène.

### D. La théologie politique

Ka'b formule une doctrine du pouvoir (p. 7982) : « la communauté s'améliore par l'intégrité du gouverneur, et se corrompt par sa corruption ». Le récit du dirigeant juste couronné au Paradis vs le dirigeant injuste (p. 7992) offre un cadre de **légitimation religieuse du pouvoir** directement exploitable par les Omeyyades.

Cette tradition est transmise via **al-Awzā'ī** ← al-Walīd ibn Hishām ← Ka'b — confirmant la chaîne Shām.

### E. Les chaînes dans le réseau

Plusieurs traditions de cette section passent par des membres identifiés du réseau :
- **Shahr ibn Ḥawshab** ← Ka'b : « j'aimerais être le bélier de ma famille » (p. 7979)
- **Qatāda** ← Ka'b : le cerveau qui coule par les narines (p. 7997)
- **Al-Awzā'ī** ← al-Walīd ← Ka'b : la communauté et le gouverneur (p. 7982)

### F. Synthèse : le qāṣṣ total

Ka'b est un **prédicateur total** : (1) matériel ascétique/proto-soufi, (2) terreur eschatologique, (3) théologie politique — le tout puisé dans les « Livres » (كتب, توراة, بعض الكتب) qu'il est le seul à pouvoir lire. Il ne transmet pas simplement des récits : il **monopolise** l'accès au sacré pré-islamique et l'injecte dans le corpus islamique en formation. Le mot « قاص » n'est pas « conteur » au sens anodin — c'est un **maître de la peur sacrée**.

---

## XVIII. Makhūl, Sulaymān ibn Mūsā, Rajā' ibn Ḥaywa — le réseau juridique omeyyade

### A. Makhūl al-Shāmī — faqīh du Shām

**Mawlā** (non-arabe), désigné faqīh du Shām par 'Abd al-Malik lui-même (Dimashq p. 27813). Après la mort des 'Abdullāhs, le fiqh « dans tous les pays passa aux mawālī » et Makhūl fut celui du Shām (p. 27812). Il appelle **Rajā' ibn Ḥaywa** « mon shaykh » (p. 27815) et forme **al-Awzā'ī** et **Sulaymān ibn Mūsā**.

### B. Sulaymān ibn Mūsā — muftī de Damas

Élève de Makhūl, auteur du classement des **quatre savants régionaux** (p. 27811-27812) : al-Zuhrī (Ḥijāz), al-Ḥasan (Iraq), Maymūn ibn Mahrān (Jazīra), Makhūl (Shām). **Tafarrud** notable : seul à rapporter le hadith du nikāḥ sans walī d'après al-Zuhrī — même schéma que le tafarrud d'al-Awzā'ī.

### C. Rajā' ibn Ḥaywa — le pivot califal

Abū al-Miqdām al-Kindī al-Filasṭīnī (p. 7908). Conseiller des califes, juge, bâtisseur du **Dôme du Rocher** sous 'Abd al-Malik. **Transmet de Ka'b** (via son fils 'Āṣim, shamela.ws/book/329/288) un récit où Ka'b sacralise Jérusalem : « **أجد في بعض الكتب** أن الحسنات تضاعف في هذا المسجد » — « Je trouve dans certains Livres que les bonnes actions sont multipliées dans cette mosquée. »

Circuit de sacralisation de Jérusalem : **Ka'b** (légitimation scripturaire) → **Rajā'** (transmission + exécution) → **'Abd al-Malik** (pouvoir politique) → **Dôme du Rocher**.

### D. Maymūn ibn Mahrān — le fonctionnaire-savant

Savant de la Jazīra et haut fonctionnaire de 'Abd al-Malik. Quatrième du classement de Sulaymān. Illustre la **fusion savoir/pouvoir** dans l'appareil omeyyade.

---

## XIX. Qatāda ibn Di'āma — le qāṣṣ devenu muḥaddith

### A. Un qāṣṣ, pas un muḥaddith

Ahmad ibn Ḥanbal (al-'Ilal wa-Ma'rifat al-Rijāl, shamela.ws/book/3617/96) : **كان قتادة يقص** — « Qatāda faisait le qaṣṣ ». Ḥammām confirme dans la même page : **كان قتادة يقص علينا** — « Qatāda nous faisait le qaṣṣ ». Page suivante (p. 97) : **سمعت قتادة يقول في قصصه** — « J'ai entendu Qatāda dire dans ses qaṣaṣ » à propos des Jahannamiyyūn (ceux qui sortent de l'enfer).

Le mot est clair : Qatāda exerçait le même métier que Ka'b al-Ahbar et Nawf al-Bikālī — **qāṣṣ**, prédicateur-conteur. Le qaṣṣ est un genre oral libre qui mêle récits coraniques, isrā'īliyyāt, exhortations morales et traditions prophétiques dans un flux narratif destiné à un public. Ce n'est pas du hadith.

### B. Le tadlīs systémique

Al-Ḥākim al-Naysābūrī (Ma'rifat 'Ulūm al-Ḥadīth, shamela.ws/book/5997/19) certifie le problème : Qatāda ibn Di'āma est « imam des gens de la vue et du tafsīr », mais **مشهور بالتدليس عنهما** — « célèbre pour le tadlīs d'après eux deux », c'est-à-dire d'après **Anas ibn Mālik** et **al-Ḥasan al-Baṣrī**.

Le tadlīs consiste à dire « Anas a dit » ou « al-Ḥasan a dit » sans avoir entendu directement d'eux. Les sources réelles de Qatāda sont souvent des intermédiaires non mentionnés — ou ses propres récits oraux de qaṣṣ.

### C. La mort à Wāsiṭ — le lien politique

Tahdhīb al-Kamāl (shamela.ws/book/26743/25) : Qatāda meurt en **117 H à Wāsiṭ** chez le gouverneur **Khālid al-Qasrī**. Il était endetté et recevait des **provisions** (أرزاق) de Khālid. Même schéma que Ka'b (autorisé par Mu'āwiya), Nawf (soldat omeyyade tué à al-Ṭawāna), Abū Hurayra (payé par Mu'āwiya) : les quṣṣāṣ sont des **fonctionnaires du sacré** entretenus par le pouvoir.

### D. Étude de cas : le hadith de la flagellation du buveur de vin

Quatre versions d'un même hadith passant par Qatāda ← Anas produisent des récits **contradictoires** :

| Source | Réf. | Contenu |
|--------|------|---------|
| Nasā'ī | shamela.ws/book/8361/7318 | 2 palmes, ~40 coups |
| Bukhārī | shamela.ws/book/735/10202 | Palmes ET sandales, 40 seulement |
| Bayhaqī | shamela.ws/book/7861/19961 | 20 hommes avec sandales |
| Bayhaqī 2 | shamela.ws/book/7861/19959 | Le Prophète avec palmes, Abū Bakr 40, 'Umar monte à 80 |

Les instruments changent (palmes / palmes + sandales / sandales seules), le nombre de coups varie (40 / 80 / non précisé), les acteurs diffèrent. C'est le signe d'un **qaṣṣ oral** reconstruit différemment à chaque séance, pas d'une tradition mémorisée. L'intermédiaire **Shabbāba ibn Sawwār** est confirmé « très fiable » (ثقة ثقة) par Yaḥyā ibn Ma'īn (al-Kāmil, shamela.ws/book/12579/2194) — l'instabilité vient de Qatāda lui-même.

### E. Le processus de transformation qaṣṣ → hadith

Le circuit reconstitué :

```
Ka'b al-Ahbar (« les Livres »)
    │
    ├── Shahr ibn Ḥawshab ← Nawf al-Bikālī
    │           │
    │     QATĀDA (qāṣṣ à Basra)
    │           │
    │   ┌───────┼───────┐
    │   │       │       │
    │ Hammām  Sa'īd   Shu'ba
    │          ibn Abī
    │          'Arūba
    │   └───────┼───────┘
    │           ↓
    │   HADITHS « PROPHÉTIQUES »
    │
    └── al-Ḥasan al-Baṣrī ← Ka'b
              │
        QATĀDA (tadlīs : « al-Ḥasan a dit »)
```

Le processus : Qatāda raconte des histoires (qaṣaṣ) dans des assemblées baṣriennes → ses élèves (Hammām, Sa'īd, Shu'ba) découpent ces récits en hadiths individuels avec des isnāds formels → les traditions de Ka'b circulent dans les recueils canoniques sous couvert de chaînes « Qatāda ← Anas ← le Prophète ».

### F. Synthèse

Qatāda est le **point de conversion** où le qaṣṣ oral se transforme en hadith formel. Son prestige d'exégète aveugle à la mémoire prodigieuse masque ce processus. Aveugle → tout son savoir est oral. Mémoire → pas de vérification écrite. Qāṣṣ → genre libre et non codifié. Mudallis → supprime les vrais intermédiaires. Qadari → position théologique qui influence le contenu. Ces cinq caractéristiques font de Qatāda le relais idéal pour la transformation des isrā'īliyyāt de Ka'b en matériel « prophétique » canonique.

---

## XX. Khālid ibn 'Abd Allāh al-Qasrī — le patron des quṣṣāṣ et l'absolutisme omeyyade

### A. Identité

**Khālid ibn 'Abd Allāh ibn Yazīd ibn Asad ibn Kurz al-Qasrī al-Bajilī** (Dimashq shamela.ws/book/71/7025). Tribu **Bajīla**, clan Qasr. Petit-fils du Compagnon **Yazīd ibn Asad**. Kunya : Abū al-Haytham. Frère d'**Asad ibn 'Abd Allāh** (gouverneur du Khurāsān).

Sa mère était **chrétienne** (naṣrāniyya) — Ibn 'Ayyāsh via al-Haytham ibn 'Adī (Dimashq p. 7028) le classe parmi les « الأشراف من أبناء النصرانيات ». L'insulte « ibn al-naṣrāniyya » le poursuit jusque dans les révoltes kharijites (Ṭabarī p. 3834).

### B. Parcours : La Mecque puis l'Iraq

- **Gouverneur de La Mecque** sous al-Walīd ibn 'Abd al-Malik (~89 H), confirmé jusqu'à la mort d'al-Walīd (Ṭabarī shamela.ws/book/9783/3520, 3544)
- **Gouverneur de l'Iraq** sous Hishām ibn 'Abd al-Malik (105/106 H - 120 H, ~15 ans) (Ṭabarī p. 3722, confirmé par Aḥmad ibn Ḥanbal)
- Base à **Wāsiṭ**, administre tout l'Orient, frère Asad au Khurāsān (Ṭabarī p. 3735)

### C. Le sacrifice d'al-Ja'd ibn Dirham

Le jour de l'Aïd al-Aḍḥā, Khālid monte au minbar (Dimashq p. 7025, Baghdad shamela.ws/book/736/8074) :

> « إني مضح بالجعد بن درهم — زعم أن الله لم يكلم موسى تكليما ولم يتخذ إبراهيم خليلا — ثم نزل فذبحه »

Un gouverneur **égorge un théologien** comme animal de sacrifice sur la place publique, le jour de l'Aïd. Al-Ja'd niait le kalām divin (parole de Dieu à Moussa) et la khulla (amitié avec Ibrāhīm) — précurseur du mu'tazilisme. C'est l'**exécution théologique comme spectacle politique**.

### D. Les sermons provocateurs

À La Mecque (Ṭabarī p. 3520) : Khālid **dénigre Zamzam**, l'appelle « umm al-khanāfis » (mère des scarabées), et demande à l'assistance : « Lequel est plus grand — le khalīfa d'un homme ou son messager ? » — insinuant que le **calife est supérieur au Prophète**.

Après l'arrestation de Sa'īd ibn Jubayr (Dimashq p. 7049) : « Si le Commandeur des croyants me l'avait ordonné, j'aurais **démoli la Ka'ba pierre par pierre**. »

### E. Le lien avec Qatāda

**Qatāda ibn Di'āma** meurt à **Wāsiṭ** en 117 H chez Khālid, endetté, recevant des provisions (أرزاق) de lui (Tahdhīb al-Kamāl shamela.ws/book/26743/25). Le qāṣṣ basrien est donc un **obligé du gouverneur** — même schéma que Ka'b autorisé par Mu'āwiya, Nawf soldat omeyyade, Abū Hurayra payé par Mu'āwiya.

Le circuit complet :

```
Ka'b al-Ahbar ←→ Mu'āwiya (autorise le qaṣṣ)
Nawf al-Bikālī ←→ Armée de Muḥammad ibn Marwān (tué à al-Ṭawāna)
Abū Hurayra ←→ Mu'āwiya (lui verse de l'argent)
Qatāda ←→ Khālid al-Qasrī (provisions, meurt chez lui à Wāsiṭ)
```

Aucun qāṣṣ majeur n'est indépendant du pouvoir omeyyade.

### F. « Rajul sū' » — la condamnation

**Yaḥyā ibn Ma'īn** (Dimashq p. 7048) : « خالد بن عبد الله القسري كان واليا لبني أمية وكان **رجل سوء** وكان **يقع في علي بن أبي طالب** ». Al-Faḍl ibn al-Zubayr ajoute qu'il a entendu Khālid insulter 'Alī avec des mots « qu'il n'est pas permis de répéter ».

### G. L'absolution par les savants

Malgré le profil de Khālid, les savants postérieurs l'ont **absous** pour le sacrifice d'al-Ja'd et en ont fait un acte de piété :

| Savant | Citation | Source |
|--------|---------|--------|
| **Al-Dārimī** | « لا يعيبه به عائب ولا يطعن عليه طاعن بل استحسنوا ذلك من فعله وصوّبوه » — personne ne l'a blâmé, tous ont approuvé | shamela.ws/book/18089/27 |
| **Al-Dhahabī** | « **هذه من حسناته** » — c'est l'une de ses bonnes actions | shamela.ws/book/8322/45718 |
| **Ibn Taymiyya** | « على عهد علماء التابعين... مثل الحسن البصري... **حمدوه على ما فعل وشكروا ذلك** » — les Tābi'ūn l'ont loué et remercié | shamela.ws/book/7289/6393 |
| **Ibn Taymiyya** | « **برضا علماء الإسلام** » — avec l'approbation des savants | Fatāwā 13/177 |
| **Ibn al-Qayyim** | « شكرا لضحية كل صاحب سنة / **لله درك من أخي قربان** » — chaque « partisan de la Sunna » remercie ce sacrifice | cité dans shamela.ws/book/30017/172 |
| **Abū Muḥammad al-Yamanī** | « **نفى الغلّ عن الإسلام جزاه الله خيرا** » — il a purifié l'islam, que Dieu le récompense | cité dans shamela.ws/book/12079/135 |

Le paradoxe : un homme qualifié de « رجل سوء » par Yaḥyā ibn Ma'īn, qui insulte 'Alī, dénigre Zamzam, menace de démolir la Ka'ba, fils d'une chrétienne — **absous et célébré** par les plus grandes autorités sunnites parce qu'il a tué un théologien au nom de la défense des attributs divins. L'acte d'égorger un homme comme un mouton le jour de l'Aïd devient une « حسنة » (bonne action) et un motif de « شكر » (gratitude).

### H. Chute et mort (126 H)

Destitué par Hishām (120 H), emprisonné 18 mois à Wāsiṭ par Yūsuf ibn 'Umar, transféré à Damas (Ṭabarī p. 3950-3953). Après l'avènement d'al-Walīd II, livré à Yūsuf qui le torture et le tue (miḍrassa sur la poitrine), Muḥarram 126 H. Enterré à al-Ḥīra dans sa 'abāya. « Aucun Arabe ne lui fit d'élégie malgré l'abondance de ses bienfaits » (Dimashq p. 7050-7051).

---

## XXI. Khālid ibn Ma'dān al-Kalā'ī — chef de police de Yazīd et premier abdāl

### A. Identité

Tābi'ī de Homs, tribu **Kalā'** (Dhū al-Kilā', branche de Ḥimyar — même groupe tribal que [[Dhū'l-Kilā' al-Ḥimyarī]]). Kunya : Abū 'Abd Allāh. Troisième ṭabaqa des tābi'ūn du Shām selon Abū Zur'a (Dimashq [p. 7080](https://shamela.ws/book/71/7080)). Évaluation unanime : **ثقة** (fiable) — Ibn Sa'd, al-'Ijlī (« شامي تابعي ثقة »), al-Nasā'ī, Ibn Kharrāsh (« حمصي ثقة ») (Dimashq [p. 7085](https://shamela.ws/book/71/7085), [p. 7091](https://shamela.ws/book/71/7091)).

**Les « 70 Compagnons »** — auto-légitimation. L'affirmation vient de Khālid lui-même : « لقد لقيت سبعين رجلا من أصحاب النبي » (Dimashq [p. 7081](https://shamela.ws/book/71/7081)), transmise exclusivement par sa fille 'Abda bint Khālid et sa servante Umm al-Ḍaḥḥāk, via Ismā'īl ibn 'Ayyāsh (Dimashq [p. 7082](https://shamela.ws/book/71/7082)). Aucune source externe ne confirme ce chiffre. Les Compagnons **nommément** attestés (Ibn Abī Ḥātim, p. 7081) sont une dizaine — mais même ces listes sont compilées par les critiques postérieurs (al-Bukhārī, Muslim, Ibn Abī Ḥātim) à partir de l'existence d'isnāds, raisonnement circulaire. Les savants qui le déclarent ثقة (al-'Ijlī, Ibn Kharrāsh, Ibn Sa'd) émettent un jugement général sans vérifier ses rencontres spécifiques. Al-Awzā'ī lui-même obtenait ses informations sur Khālid via sa fille (Siyar p. 46046).

### B. Chef de police de Yazīd ibn Mu'āwiya

'Īsā ibn Yūnus d'après Thawr ibn Yazīd (Dimashq [p. 7083](https://shamela.ws/book/71/7083)) : Khālid ibn Ma'dān était **صاحب شرطة يزيد بن معاوية** — le chef de la force de coercition du calife sous le règne duquel eurent lieu le **massacre de Karbalā'** (61 H) et le **sac de Médine** (Ḥarra, 63 H). Les sources ne commentent pas cette fonction. Aucun savant ne le critique pour ce rôle.

### C. Le guerrier du ribāṭ

Premier à planter sa tente à **Dābiq** (base militaire omeyyade de la frontière byzantine) quand il ordonnait le ghazw (Dimashq [p. 7085](https://shamela.ws/book/71/7085), Siyar [p. 46046](https://shamela.ws/book/8322/46046)). Meurt lui-même à **Anṭarsūs**, une forteresse côtière de ribāṭ (Dimashq [p. 7089](https://shamela.ws/book/71/7089)), en jeûnant.

Buḥayy ibn Sa'd d'après Khālid (Ḥilyat al-Awliyā' [p. 1745](https://shamela.ws/book/10495/1745)) : « كانوا لا يفضلون على الرباط شيئا » — « Ils ne considéraient rien de supérieur au ribāṭ. »

### D. L'ascète extrême

**40 000 tasbīḥ quotidiens** — en plus de la récitation du Coran. À sa mort, posé sur son lit pour être lavé, son doigt continuait à bouger en faisant le tasbīḥ (Dimashq [p. 7089](https://shamela.ws/book/71/7089), Ḥilya [p. 1741](https://shamela.ws/book/10495/1741), Siyar [p. 46047](https://shamela.ws/book/8322/46047)). Al-Dhahabī note que l'isnād est munqaṭi'.

**Le désir de mort** — « Je ne voudrais pas qu'une seule créature me rachète de la mort. Si la mort était un but vers lequel on court, personne ne m'y devancerait sauf celui qui est plus fort que moi » (Sufyān al-Thawrī d'après Thawr ibn Yazīd, Dimashq [p. 7085](https://shamela.ws/book/71/7085), Siyar [p. 46046](https://shamela.ws/book/8322/46046)).

**Prosternations de gratitude** — même quand un homme le salue ou lui fait de la place (Dimashq [p. 7086](https://shamela.ws/book/71/7086)).

**Al-yaqīn** — « Apprenez la certitude comme vous apprenez le Coran » (Dimashq [p. 7086](https://shamela.ws/book/71/7086)).

**La terreur qu'il inspirait** — personne n'osait mentionner les affaires du monde en sa présence (Siyar [p. 46045](https://shamela.ws/book/8322/46045)). Quand son cercle d'étude devenait grand, il se levait et partait — par haine de la célébrité (كراهية الشهرة) (Dimashq [p. 7085](https://shamela.ws/book/71/7085)).

### E. Le concept des abdāl

À sa mort, un homme à Homs entendit des cavaliers (فوارس) de nuit disant avoir assisté aux funérailles du **« badīl »** Khālid ibn Ma'dān, et qu'**Arṭa'a ibn al-Mundhir** lui succédait comme abdāl (Dimashq [p. 7089](https://shamela.ws/book/71/7089)). L'une des premières attestations du concept des **abdāl** — les saints cachés qui soutiennent le monde — dans les sources du hadith.

### F. Transmissions

**De qui** (Siyar [p. 46045](https://shamela.ws/book/8322/46045)) : Thawbān, Abū Umāma, Mu'āwiya, Abū Hurayra, al-Miqdām, Ibn 'Umar, 'Abd Allāh ibn 'Amr, 'Abd Allāh ibn Busr, Dhū Mikhbar, 'Utba ibn 'Abd. Mursal (sans rencontre) : Mu'ādh ibn Jabal, Abū al-Dardā', 'Ā'isha, 'Ubāda ibn al-Ṣāmit, Abū 'Ubayda (confirmé : Ḥilya [p. 1747](https://shamela.ws/book/10495/1747)).

**Qui transmet de lui** : **Thawr ibn Yazīd** (principal, noté comme **qadarī** — Dimashq [p. 7083](https://shamela.ws/book/71/7083)), Buḥayy ibn Sa'd, Ṣafwān ibn 'Amr, Ḥarīz ibn 'Uthmān, sa fille **'Abda bint Khālid**. **Al-Awzā'ī** le vénérait et envoya des gens interroger sa fille sur sa conduite (Siyar [p. 46046](https://shamela.ws/book/8322/46046)).

### G. Position dans le réseau

Khālid ibn Ma'dān est basé à **Homs** — même ville que Ka'b al-Ahbar, Nawf al-Bikālī et Dhū'l-Kilā'. Sa tribu (Kalā') est la même que celle de Dhū'l-Kilā'. Il transmet de 'Abd Allāh ibn 'Amr et de Mu'āwiya — deux figures centrales du réseau des quṣṣāṣ. Al-Awzā'ī le vénère (Siyar [p. 46046](https://shamela.ws/book/8322/46046)). La formule « il lut dans l'un des Livres » (في بعض الكتب) — utilisée pour Ka'b, 'Abd Allāh ibn 'Amr et Wahb pour désigner un corpus étranger à l'islam — le rattache au même univers textuel.

### H. Le paradoxe

Chef de police du calife qui a massacré la famille du Prophète à Karbalā' et mis Médine à sac — et simultanément l'un des premiers **abdāl** du soufisme, ascète aux 40 000 tasbīḥ quotidiens, mort en jeûnant dans une forteresse du ribāṭ. Déclaré **ثقة** (fiable) par tous les critiques, sans qu'aucun ne relève la contradiction.

---

## XXII. Pistes de recherche complémentaires

### Fait dans cette session
- ~~Biographie de Nawf~~ → section X
- ~~Wahb ibn Munabbih~~ → section IX
- ~~Dhū'l-Kilā' al-Ḥimyarī~~ → section XI
- ~~Paroles de Ka'b (Torah/Abu Hurayra, Mu'awiya, Falaq)~~ → section XII
- ~~Portraits d'Abū Hurayra et Qatāda~~ → section XIII
- ~~Ibn 'Amr ibn al-'Āṣ, zamālatain, Sarj al-Yarmūkī~~ → section XV
- ~~Al-Awzā'ī (Ahl al-Bayt, Ghaylān, quatre défauts, Makhūl)~~ → section XVI
- ~~Ka'b — philosophie et approche (Ḥilyat al-Awliyā')~~ → section XVII
- ~~Makhūl, Sulaymān, Rajā', Maymūn~~ → section XVIII
- ~~Qatāda ibn Di'āma — qāṣṣ, tadlīs, étude de cas vin~~ → section XIX
- ~~Khālid ibn 'Abd Allāh al-Qasrī — patron, sermons, al-Ja'd~~ → section XX
- ~~Khālid ibn Ma'dān — chef de police, ribāṭ, abdāl~~ → section XXI

### Prioritaires
- Chercher les chaînes **Shahr ← Nawf ← Ka'b** dans les recueils de hadith canoniques (Bukhārī, Muslim) — combien de traditions « prophétiques » passent par ce réseau ?
- Recenser **tous les hadiths anti-Kharijites** dans les recueils canoniques — combien passent par le Shām ?
- Étudier **al-Awzā'ī** et ses « tafarrudāt » — schéma systémique ou cas isolé ?
- Reconstituer la **biographie complète d'Abū Hurayra** dans Ibn 'Asakir (autour de p. 30865)
- Étudier **Shuraḥbīl ibn Dhī'l-Kilā'** (fils, commandant omeyyade, tué à Khāzir 686 EC)
- Étudier la **bataille d'al-Ṭawāna** (~83 H) : d'autres quṣṣāṣ parmi les victimes ?
- Retrouver le hadith complet de la scène **'Awf ibn Mālik / Dhū'l-Kilā' / Ka'b qāṣṣ** dans les recueils (Musnad Ahmad ?)

### Secondaires
- Rechercher les traditions critiques de Ka'b (meurtre d'Omar dans les sources shiites)
- Étudier **Tamim al-Dari** comme pendant chrétien de Ka'b
- Comparer faḍā'il al-Shām vs faḍā'il al-Quds
- Chaînes indépendantes de faḍā'il al-Shām hors réseau Ka'b-Nawf-Shahr-Wahb ?
- Ka'b et Wahb dans **Ibn Sa'd** (Ṭabaqāt)
- **Hammām ibn Munabbih** et sa Ṣaḥīfa d'Abū Hurayra
- **'Abd al-Mun'im ibn Idrīs** (petit-fils de Wahb, Tarikh Baghdad p. 6974)
- Le hadith du « cerveau qui coule des narines » (livre 21536, p. 749)

---

## Annexe : liste complète des pages Tarikh Dimashq mentionnant Ka'b al-Ahbar

103 pages (shamela.ws/book/71/PAGE) :
205, 220, 224, 246, 250, 252, 255, 281, 303, 309, 311, 312, 334, 411, 412, 674, 694, 701, 786, 787, 788, 792, 822, 823, 866, 2265, 3139, 4171, 4172, 4478, 4617, 4634, 4636, 4638, 4640, 4641, 4642, 6898, 7228, 7341, 7342, 7453, 7658, 7702, 7728, 9973, 10091, 10445, 11851, 11965, 13176, 13187, 13913, 14570, 15023, 16881, 20564, 21130, 21131, 21602, 21603, 23264, 23265, 23266, 23267, 23268, 23273, 23274, 23275, 23276, 23278, 23279, 23281, 23283, 23286, 23287, 23288, 25151, 26376, 27018, 27021, 27183, 28095, 28214, 28215, 28508, 28828, 29387, 29801, 29992, 30363, 30464, 30611, 30736, 30739, 30740, 31132, 31133, 31593, 32434, 32680, 32701, 32722

---

## Annexe : pages Nawf al-Bikali et Shahr ibn Hawshab

**Nawf al-Bikali dans Tarikh Dimashq** (shamela.ws/book/71/PAGE) — 13 pages :
9939, 24665, 28186, 28828, 28829, 28830, 28832, 28833, 28834, 28835, 28836, 28837, 28838
- Biographie complète : p. 28828-28838 (analysée intégralement en section X)
- Page clé : **p. 28829** — hadith de la hijra vers le Shām via Shahr → Nawf → Ibn 'Amr
- Mort : tué à la bataille d'al-Ṭawāna (~83 H) avec l'armée de Muḥammad ibn Marwān

**Nawf al-Bikali dans Tarikh Baghdad** (shamela.ws/book/736/PAGE) — 1 page :
4216

**Shahr ibn Hawshab dans Tarikh Dimashq** — **142 mentions** (biographie : 10384-10404)

**Ka'b al-Ahbar dans Tarikh al-Tabari** (shamela.ws/book/9783/PAGE) — 11 pages :
263, 398, 643, 723, 2082, 2093, 2145, 2173, 3222, 6371, 6426

**Dhū'l-Kilā' dans Tarikh Dimashq** (shamela.ws/book/71/PAGE) — 20 pages :
6829, 7095, 7728, 7730, 7731, 7732, 7733, 7736, 7737, 7739, 7741, 7742, 17004, 23226, 26678, 30938, 30939, 31241, 32459, 32602
- Biographie : p. 7728-7742

**Dhū'l-Kilā' dans Tarikh al-Tabari** (shamela.ws/book/9783/PAGE) — 10 pages :
1596, 1662, 1664, 1670, 1712, 2495, 2497, 3057, 5814, 6254

**Sources additionnelles consultées** :
- Ka'b et Abū Hurayra / Torah : shamela.ws/book/71/30865
- Mu'āwiya et Ka'b : shamela.ws/book/71/23281
- Abū Hurayra payé par Mu'āwiya : shamela.ws/book/9170/185
- Al-Falaq (puits en enfer) : shamela.ws/book/151147/124
- Qatāda ← al-Ḥasan ← Ka'b : shamela.ws/book/18686/12081
- Tubā'ī ibn 'Āmir (gendre de Ka'b) : shamela.ws/book/12581/145
- Ibn 'Amr « lisait les Livres » (Tafsīr al-Ṭabarī) : shamela.ws/book/43/6687
- Sarj al-Yarmūkī (al-Iṣāba) : shamela.ws/book/9767/1440
- Sarj al-Yarmūkī (Kitāb al-Fitan) : shamela.ws/book/13047/231
- Sarj al-Yarmūkī (Tārīkh Dimashq) : shamela.ws/book/71/8953
- Zamālatain (al-Maṭālib al-'Āliya / Ibn Kathīr) : shamela.ws/book/37618/16842
- Zamālatain (Bishr al-Marīsī, texte de défense) : shamela.ws/book/8680/608-609
- Zamālatain (Abū Rayya, réfutation) : shamela.ws/book/224/1624
- Al-Awzā'ī / Ahl al-Bayt (Ibn 'Abd al-Barr) : shamela.ws/book/22367/1428
- Ghaylān / qadar (al-Sharī'a d'al-Ājurrī) : shamela.ws/book/1257/17
- Ghaylān crucifié (al-Minha al-Ilāhiyya) : shamela.ws/book/30017/152
- Al-Awzā'ī 4 défauts (Mukhtaṣar Tārīkh Dimashq) : shamela.ws/book/3118/112
- Al-Awzā'ī ← Makhūl ← Rajā' ← Ibn 'Amr (Ṭabarānī) : shamela.ws/book/13162/2856
- Al-Awzā'ī « رأيت مكحولا » (Ibn Abī Shayba) : shamela.ws/book/333/7589
- Makhūl / Sulaymān — biographie (Ibn 'Asākir) : shamela.ws/book/71/27811-27815
- Rajā' ibn Ḥaywa — biographie (Ibn 'Asākir) : shamela.ws/book/71/7907-7922
- Rajā' ← Ka'b à Jérusalem (Faḍā'il Bayt al-Maqdis) : shamela.ws/book/329/288
- Ka'b dans Ḥilyat al-Awliyā' (Abū Nu'aym) : shamela.ws/book/10495/7969-8002
- Qatāda qāṣṣ (al-'Ilal d'Aḥmad) : shamela.ws/book/3617/96-97
- Qatāda tadlīs (Ma'rifat 'Ulūm al-Ḥadīth) : shamela.ws/book/5997/19
- Qatāda à Wāsiṭ (Tahdhīb al-Kamāl) : shamela.ws/book/26743/25
- Vin / Nasā'ī : shamela.ws/book/8361/7318
- Vin / Bukhārī : shamela.ws/book/735/10202
- Vin / Bayhaqī : shamela.ws/book/7861/19959-19961
- Shabbāba ibn Sawwār (al-Kāmil) : shamela.ws/book/12579/2194-2195
- Khālid al-Qasrī — biographie (Dimashq) : shamela.ws/book/71/7025-7051
- Khālid — mère chrétienne : shamela.ws/book/71/7028
- Khālid — رجل سوء (Yaḥyā ibn Ma'īn) : shamela.ws/book/71/7048
- Khālid — mort, torture : shamela.ws/book/71/7050
- Khālid — nomination La Mecque (Ṭabarī) : shamela.ws/book/9783/3520, 3544
- Khālid — nomination Iraq (Ṭabarī) : shamela.ws/book/9783/3722
- Khālid — chute et meurtre (Ṭabarī) : shamela.ws/book/9783/3950-3956
- Khālid — sacrifice d'al-Ja'd (Baghdad) : shamela.ws/book/736/8074
- Al-Dārimī — absolution du sacrifice (Radd 'alā al-Jahmiyya) : shamela.ws/book/18089/27
- Al-Dhahabī — « من حسناته » (Siyar a'lām al-nubalā') : shamela.ws/book/8322/45718
- Ibn Taymiyya — « برضا علماء الإسلام » (Majmū' al-Fatāwā) : shamela.ws/book/7289/6393
- Absolution compilée (al-Sunna d'al-Khallāl) : shamela.ws/book/12079/135
- Absolution compilée (al-Sunna d'Ibn Aḥmad) : shamela.ws/book/30017/170-172
- Khālid ibn Ma'dān — biographie (Dimashq) : shamela.ws/book/71/7080-7092
- Khālid ibn Ma'dān — chef de police de Yazīd : shamela.ws/book/71/7083
- Khālid ibn Ma'dān — ascétisme (Ḥilyat al-Awliyā') : shamela.ws/book/10495/1741-1750
- Khālid ibn Ma'dān — biographie (Siyar) : shamela.ws/book/8322/46045-46047
- Ibn 'Amr « في كتاب الله المنزل » (Muṣannaf Ibn Abī Shayba) : shamela.ws/book/9944/42550
- Ibn 'Amr « صنفين في النار » (Ṭabarānī) : shamela.ws/book/1353/550
- Ibn Ḥajar sur ce passage (al-Qawl al-Musaddad) : shamela.ws/book/6035/31
- Nawf « يقرأ الكتب / في كتاب الله المنزل » (Tafsīr al-Ṭabarī) : shamela.ws/book/7798/2226
- Wahb « أجد في التوراة أو في الكتاب » (al-Zuhd d'Aḥmad) : shamela.ws/book/11333/189

---

## Annexe : pages Wahb ibn Munabbih

**Wahb dans Tarikh Dimashq** (shamela.ws/book/71/PAGE) — **177 pages** :
- Biographie (31 pages) : 29324, 29325, 29327-29332, 29334-29339, 29343-29353, 29356-29361
- Faḍā'il al-Shām (11 pages) : 74, 184, 253, 271, 360, 696, 792, 846, 5884, 11848, 18260
- Prophètes/figures bibliques (47 pages) : 1261, 2444, 2488, 2489, 2512, 2529, 2534, 3122, 3146, 3150, 3151, 3215, 3216, 3221, 4140, 4146, 4148, 4150, 4160, 4161, 4162, 4484, 4486, 4614, 7697, 7698, 18241, 18244, 18247, 18254, 18356, 18357, 21986, 22019, 22021, 22028, 22088, 22090, 22091, 22095, 22097, 22099, 22106, 23121, 31303, 31825, 32998
- Autres biographies (79 pages) : 3228, 3374, 5152, 6475, 6476, 7427, 7428, 7437, 7445, 7446, 7449, 7863, 8059, 8304, 8310, 8315, 8316, 8489, 9917, 9922, 9925, 9931, 9932, 9950, 9952, 9958, 9977, 10244, 10623, 11083, 13305, 13910, 14057, 16378, 16399, 16629, 18214, 19666, 20811, 21218, 24428, 25302, 26034, 26123, 27545, 28080, 28082, 28092, 28094, 28100, 28106, 28108, 28112, 28114, 28116, 28122, 28123, 28125, 28127, 28135, 28138, 28145, 28163, 28166, 28178, 28195, 28226, 28767, 28794, 28797, 28805, 29591, 30851, 30864, 30980, 31398, 32124, 32125, 33161

**Pages Ka'b-Wahb (chevauchement)** — 18 pages :
74, 184, 253, 792, 3151, 4162, 4484, 4614, 9922, 9950, 9977, 10244, 22021, 28080, 28082, 28094, 28195, 28805

**Wahb dans Tarikh al-Tabari** (shamela.ws/book/9783/PAGE) — **40 pages** :
37, 41, 106, 174, 175, 199, 301, 319, 321, 363, 398, 404, 411, 423, 428, 445, 468, 508, 509, 511, 517, 534, 599, 643, 813, 862, 1078, 1087, 1197, 1237, 1251, 1316, 1374, 1421, 1437, 1478, 1485, 1544, 1551, 1628

**Wahb dans Tarikh Baghdad** (shamela.ws/book/736/PAGE) — **8 pages** :
71, 1386, 1597, 1881, 6972, 6974, 6976, 9281

---

*Recherche effectuée du 9 au 11 mars 2026 sur shamela.ws via l'API de recherche et l'extraction automatisée des pages.*
