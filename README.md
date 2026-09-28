# MendiBideak

## Euskal Herriko Mendi eta Bidezidorrak

Mendi-ibilbideak bilatzeko, kargatzeko eta deskargatzeko ataria, zailtasunaren, klimaren eta iraupenaren arabera antolatuta.

*Ezaugarri nagusiak:* mapa-interfaze zabala, altuera-profilak, erabiltzaileen balorazioak eta eguraldiaren widget-a.

---

## AURKIBIDEA

* ( 1. ) [Sarrera](#1-sarrera)
* ( 2. ) [Benchmark](#2-benchmark)

  * ( 2.1 ) [Ondorioak](#21-ondorioak)
* ( 3. ) [User Profila](#3-user-profila)
* ( 4. ) [Krokisa](#4-krokisa)

  * ( 4.1 ) [Mobila](#41-mobila)
  * ( 4.2 ) [Ordenagailua](#42-ordenagailua)
* ( 5. ) [Nabigazio Mapa](#5-nabigazio-mapa)
* ( 6. ) [Estilo gida](#6-estilo-gida)

  * ( 6.1 ) [Koloreak](#61-koloreak)
  * ( 6.2 ) [Tipografia](#62-tipografia)
  * ( 6.3 ) [Ikonoak](#63-ikonoak)
  * ( 6.4 ) [Botoiak](#64-botoiak)
  * ( 6.5 ) [Irudiak](#65-irudiak)

---

# 1. Sarrera

MendiBideak Euskal Herriko mendi eta bidezidorrei buruzko informazioa eskaintzeko diseinatutako web-ataria da. Webgunearen helburu nagusia erabiltzaileei mendi-ibilbideak modu erraz, argi eta bisualean aurkitzeko aukera eskaintzea da.

Webguneak ibilbideak hainbat irizpideren arabera antolatzea eta bilatzea ahalbidetuko du, besteak beste, zailtasunaren, klimaren eta ibilbidearen iraupenaren arabera. Horrez gain, ibilbide bakoitzari buruzko informazio osagarria eskaintzea aurreikusten da, hala nola distantzia, desnibela, zailtasun-maila, eguraldia, argazkiak eta deskribapenak.

Webgunearen beste ezaugarri nagusietako bat Euskal Herriko lurraldeen araberako nabigazioa izango da. Euskal Herriko mapa interaktibo baten bidez, erabiltzaileak zazpi lurraldeetako bat hautatu ahal izango du, eta hautatutako lurraldean dauden mendi eta bidezidorrei buruzko informazioa eskuratuko du.

Diseinuaren helburua informazio ugari eskaintzea da, baina informazioa modu bisual eta ulerterrazean aurkeztea, erabiltzaileak behar duen informazioa azkar aurkitu ahal izan dezan.

---

# 2. Benchmark

MendiBideak proiektuaren diseinu eta funtzionalitate nagusiak definitzeko, antzeko zerbitzuak eskaintzen dituzten hainbat webgune eta aplikazio aztertu dira. Azterketa horretan, batez ere, WikiLoc, Outdooractive eta Google Maps hartu dira erreferentziatzat.

## WikiLoc

![WikiLoc](https://viendoosdesdearriba.wordpress.com/wp-content/uploads/2018/10/wikiloc2.png?w=256)

* **Erabilera nagusia:** aire zabaleko kirol-ibilbideak aurkitzea eta partekatzea.
* **Funtzioak:** mundu osoko erabiltzaileek igotako senderismo, txirrindularitza eta beste hainbat diziplinatako ibilbideak eskaintzen ditu.
* **Abantailak:** GPS bidezko nabigazioa ahalbidetzen du, erabiltzaileari ibilbidean zehar orientatzen laguntzeko.

[WikiLoc](https://eu.wikiloc.com/)

WikiLoc aztertuta, MendiBideak proiekturako hainbat ideia hartu dira erreferentziatzat.

Ibilbide bakoitza `div` baten barruan antolatzea aurreikusten da. Ibilbide bakoitzean informazio nagusia modu argian erakutsiko da, besteak beste:

* Distantzia.
* Desnibela.
* Zailtasun-maila.
* Klimari edo eguraldiari buruzko informazioa.
* Ibilbidearen argazkiak.
* Deskribapen bat.

Zailtasun-maila koloreen bidez ere bereiztea aurreikusten da, erabiltzaileak informazioa begirada batean identifikatu ahal izan dezan.

Horrez gain, ibilbidearekin lotutako Google Maps-eko esteka botoi baten bidez eskaintzea aztertzen da.

---

## Outdooractive

![Outdooractive](https://play-lh.googleusercontent.com/dDv0dOUwvl8aWd7BzTq1PxG2QOBmshEi37HHvUneuVelfLL_8yXUa9qfDG2exhovHsqmU0Sy_IjFfifMz4_kCw=s0-br30)

* **Erabilera nagusia:** mendi eta outdoor jardueren plangintza egitea.
* **Funtzioak:** mapa topografikoak eta ibilbide gidatuak eskaintzen ditu.
* **Abantailak:** segurtasunari eta eguraldiari buruzko informazioa eskaintzen du, mendiko jarduerak hobeto prestatzeko.

[Outdooractive](https://www.outdooractive.com)

Outdooractive aztertzean, elementuen antolaketa bisuala hartu da erreferentziatzat. Informazioa modu txukunean eta ordenatuan aurkezteak erabiltzailearen esperientzia hobetzen du.

Horregatik, MendiBideak proiektuan elementuen arteko marjinak, tarteak eta banaketa zaintzea aurreikusten da. Xehetasun txikiek interfaze garbiagoa eta erabilerrazagoa sortzen lagun dezakete.

---

## Google Maps

![Maps](https://cdn-icons-png.magnific.com/256/2642/2642502.png?semt=ais_white_label)

* **Erabilera nagusia:** kokapenak bilatzea eta leku batetik bestera nabigatzea.
* **Funtzioak:** garraiobide desberdinetarako ibilbideak kalkulatzea.
* **Abantailak:** mapak, satelite bidezko irudiak, kokapenen informazioa eta bestelako datuak eskaintzen ditu.

[Google Maps](https://maps.google.com/?authuser=0)

Google Maps proiektuan erabiltzea aurreikusten da ibilbideen kokapena eta sarbidea osatzeko. Ibilbide jakin batekin lotutako mapa edo ibilbide bat sortu ahal izango litzateke, eta MendiBideak webgunetik botoi baten bidez bertara sartzeko aukera eskaini.

Funtzionalitate hau oraindik proposamen gisa dago, eta proiektuaren garapenean zehar erabakiko da azkenean ezarriko den ala ez.

---

## 2.1 Ondorioak

Benchmarkean aztertutako webguneetatik hainbat ideia eta diseinu-irizpide hartu dira MendiBideak proiekturako.

Alde batetik, WikiLoc-en ibilbide bakoitzean informazio garrantzitsua modu argian erakusteko modua hartu da erreferentziatzat. Horren ondorioz, MendiBideak webgunean distantzia, desnibela, zailtasuna, klima, argazkiak eta deskribapena bezalako datuak modu ikusgarrian aurkeztea aurreikusten da.

Bestetik, Outdooractive-ren interfazearen antolaketa eta garbitasuna hartu dira kontuan. Elementuen arteko espazioak eta informazioaren banaketa zaintzea izango da helburuetako bat.

Azkenik, Google Maps ibilbideen kokapena eta nabigazioa osatzeko tresna gisa erabiltzea aztertzen da.

Benchmarkaren ondorioz, MendiBideak proiektuak erreferentziazko webguneen hainbat ezaugarri erabilgarri hartu eta berezko proposamenekin konbinatuko ditu.

---

# 3. User Profila

MendiBideak 16 urtetik gorako erabiltzaileentzat diseinatutako webgunea izango da. Bereziki, mendizaleei, oinez ibiltzea gustuko duten pertsonei eta naturan irteerak egin nahi dituzten erabiltzaileei zuzenduta egongo da.

Webgunearen erabiltzaile-profilak ez du zertan mendizale esperientziaduna izan. Ibilbideak bilatu nahi dituen edo naturan jardueraren bat egin nahi duen edozein erabiltzailek informazioa modu erraz eta ulergarrian kontsultatu ahal izatea izango da helburua.

Horregatik, interfazeak bisualki erakargarria eta garbia izan beharko du. Koloreek, testuek, irudiek eta bestelako elementu grafikoek elkarrekin funtzionatu beharko dute, informazioa gehiegi kargatu gabe.

Webgunearen diseinuan hainbat kolore bizi erabiltzea aurreikusten da. Naturak, paisaiek eta kanpoko inguruneek kolore ugari dituztenez, kolore horiek proiektuaren izaerarekin lotzea bilatzen da.

MendiBideak teknologiaren erabilera kanpoko jarduerekin lotzea bilatuko du. Helburua ez da erabiltzailea pantailaren aurrean denbora gehiago mantentzea, baizik eta teknologia erabiliz erabiltzaileari naturara ateratzen eta toki berriak ezagutzen laguntzea.

Edukiari dagokionez, informazio ugari eskaintzea aurreikusten da, baina informazio hori modu laburtu eta bisualean aurkeztuko da. Zailtasun-maila testuaren eta koloreen bidez identifikatu ahal izango da, eta klimari edo eguraldiari buruzko informazioa ere modu argian erakutsiko da.

---

# 4. Krokisa

MendiBideak proiektuaren lehen diseinu-proposamena krokis baten bidez definitu da. Krokisaren bidez, webgunearen egitura, elementuen kokapena eta erabiltzaileak izango duen nabigazioa aurrez planifikatu dira.

[Nabigazio Mapa](https://docs.google.com/drawings/d/1OUfY4_jM1pxkjEbJxuTI4xyYYifPQxmAPcIDMIUSWr0/edit?usp=sharing)
> 42 flecha jarri beharrean, taula bat sortu da adierazteko lurralde batetik bestera jun ahal izango dela adierazteko.

## 4.1 Mobila
[Krokisa Mugikorrean](https://docs.google.com/drawings/d/1qMkfNliMRks5AamFbIr413-2wxRBGYIDWapbWcTSmX8/edit?usp=sharing)

Webgunearen diseinua gailu mugikorretara egokituko da. Pantaila txikiagoetan elementuen banaketa eta tamaina egokitzea aurreikusten da, erabiltzaileak edukia modu erosoan kontsultatu ahal izateko.

## 4.2 Ordenagailua
[Krokisa Ordenagailuan](https://docs.google.com/drawings/d/1dgZIePFi3mph7Dz_nphQp8CRNpzIbIc-Nk11I64pzEM/edit?usp=sharing)

Ordenagailuko bertsioan pantaila-zabalera handiagoa aprobetxatuko da. Mapek, ibilbideen informazioak eta bestelako elementuek erabilgarri dagoen espazioa aprobetxatuko dute, baina interfazearen ordena eta irakurgarritasuna mantenduz.

---

# 5. Nabigazio Mapa

MendiBideak webgunearen nabigazioa Euskal Herriko zazpi lurraldeen mapa interaktibo baten inguruan antolatzea aurreikusten da.

Mapa webgunearen elementu nagusietako bat izango da, eta zazpi lurraldeak modu independentean hautatu ahal izango dira. Lurralde bakoitzak bere kolorea izango du.

Adibidez, erabiltzaileak Gipuzkoa hautatzen badu, Gipuzkoako mendi eta bidezidorrei buruzko informazioa erakutsiko da. Era berean, Bizkaia hautatuz gero, Bizkaiko ibilbideak erakutsiko dira, eta gauza bera gainerako lurraldeekin.

Sistema honek ibilbideak modu antolatuagoan aurkeztea ahalbidetuko du, erabiltzaileak bilaketa lurralde jakin batera mugatu ahal izango baitu.

Lurralde bat hautatzen denean, aukeratutako lurraldea berezko kolorearekin nabarmenduko da, eta gainerako lurraldeak gris kolorez erakutsiko dira. Horrela, erabiltzaileak modu bisualean identifikatu ahal izango du zein lurralde hautatu duen.

Lurraldeen arteko distantzia ez da nabigazioaren muga izango. Erabiltzaileak beste lurralde bateko ibilbide bat bilatu nahi badu, mapa eta kanpoko nabigazio-tresnak erabiliz ibilbide horretara iristeko informazioa kontsultatu ahal izango du.

---

# 6. Estilo gida

MendiBideak webgunearen estiloa definitzeko, koloreak, tipografia, ikonoak, botoiak eta irudiak zehaztuko dira.

Diseinuaren helburu nagusia interfaze garbi, bisualki erakargarri eta erabilerraza sortzea izango da.

Webgunearen izaerarekin bat egiteko, estiloak naturarekin, kirolarekin eta kanpoko jarduerekin lotutako elementu bisualak erabiliko ditu.

Tipografiari dagokionez, letra biribilduak erabiltzea aurreikusten da. Aukeratutako tipografiak irakurgarria izan beharko du eta, aldi berean, webguneari izaera moderno eta atsegina eman beharko dio.

Diseinuak ez du ez itxura gehiegi serioa ezta infantilizatua ere izan nahi. Bi muturren arteko oreka bilatuko da, webgunea adin eta esperientzia desberdinetako erabiltzaileentzat egokia izan dadin.

---

## 6.1 Koloreak

Webgunearen kolore-paletan hainbat kolore bizi erabiltzea aurreikusten da, naturarekin eta kanpoko jarduerekin lotura sortzeko.

Gainera, 7 probintzietako orriak, kolore desberdinak izango dute, beraien artean desberdintzeko.

Menu zabalgarrirako gradienteak erabiliko dira. Menuaren atzeko edukia zilar koloreko gradiente baten bidez definituko da, eta haren barruan Euskal Herriko mapa interaktibo bat egongo da.

Euskal Herriko mapa interaktiboan zazpi lurraldeek kolore desberdinak izango dituzte. Kolore horiek lurralde bakoitza identifikatzeko erabiliko dira.

Lurralde bat hautatzen denean, hautatutako lurraldeak berezko kolorea mantenduko du eta gainerako lurraldeak gris kolorez erakutsiko dira.

---

## 6.2 Tipografia

Webgunearen tipografiak irakurgarria, modernoa eta atsegina izan beharko du.

Letra biribilduak erabiltzea aurreikusten da, diseinuaren izaera hurbila eta dinamikoa indartzeko.

Tipografiaren tamaina eta pisua elementuaren garrantziaren arabera egokituko dira. Izenburuak, azpitituluak eta testu arrunta hierarkia bisual argi baten bidez bereiziko dira.

---

## 6.3 Ikonoak

Ikonoak informazioa azkar identifikatzeko erabiliko dira. Ikonoen diseinuak webgunearen estilo orokorrarekin bat egin beharko du.

Adibidez, ibilbideen kategorietan mendiekin, eguraldiarekin, denborarekin edo bestelako informazioarekin lotutako ikonoak erabil daitezke.

---

## 6.4 Botoiak

Botoiek forma biribildua izango dute, webgunearen estilo atsegin eta modernoarekin bat egiteko.

Botoietan testua eta ikono adierazgarriak konbinatzea aurreikusten da. Adibidez:

* ⛰️ Mendiak
* 🥾 Bidezidorrak

Botoi nagusiak erabiltzailearen eskura erraz egongo dira eta haien arteko banaketa argia izango da.

Menu zabalgarria irekitzeko botoiak egoera bisual desberdina izango du kurtsorea haren gainean dagoenean. Horrela, erabiltzaileak botoia aktibatu daitekeela identifikatu ahal izango du.

Menua zabaltzen denean, atzean dagoen webgunearen edukia geruza beltz erdi-gardenez estaliko da, erabiltzailearen arreta menuan kokatzeko.

Menu zabalgarria ezkutatzeko, botoi biribil bat erabiliko da.

---

## 6.5 Irudiak

Irudiak ibilbideak eta ingurune naturalak erakusteko erabiliko dira. Irudiek webgunearen izaera bisuala indartu eta erabiltzaileari ibilbide bakoitzaren ingurunea hobeto ezagutzeko aukera emango diote.

Ibilbideen barruan argazkiak erabiltzea aurreikusten da, erabiltzaileak bisitatu aurretik ingurunea modu bisualean ezagutu ahal izateko.

Irudien erabilerak ez du informazioa gainkargatu beharko; testuarekin eta gainerako elementuekin orekatuta egon beharko du.

![Euskal Herria](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjUzL2L2BBwB-fL4MoWnjoDWsqFEH-JfWuiBnVroKglEybvmGjo5r3Hw9Iw1GVOF95LiRB4hNK6c4bFHfXIDdE8iHeXuKAIkMnMpDs6sxZaazYdbn60MnF8Ashr7p8GjX8-UutEMSeFdSSq/s2000/Euskal_Herriko_kolore_mapa.png)

![Vizcaya](https://upload.wikimedia.org/wikipedia/commons/0/00/Bandera_de_Vizcaya.svg?utm_source=es.wikipedia.org&utm_campaign=index&utm_content=original)
![Bizkaia](https://upload.wikimedia.org/wikipedia/commons/e/e8/Bizkaia_Euskal_Herrian.png?utm_source=commons.wikimedia.org&utm_campaign=index&utm_content=original)

![Gipuzcoa](https://thumb.wikimedia.org/wikipedia/commons/thumb/f/f5/Flag_of_Guip%C3%BAzcoa.svg/3840px-Flag_of_Guip%C3%BAzcoa.svg.png?utm_source=es.wikipedia.org&utm_campaign=index&utm_content=thumbnail)
![Gipuzkoa](https://upload.wikimedia.org/wikipedia/commons/0/0a/Gipuzkoa_Euskal_Herrian.png?utm_source=commons.wikimedia.org&utm_campaign=index&utm_content=original)

![Álava](https://upload.wikimedia.org/wikipedia/commons/1/1f/Flag_of_%C3%81lava.svg?utm_source=es.wikipedia.org&utm_campaign=index&utm_content=original)
![Araba](https://thumb.wikimedia.org/wikipedia/commons/thumb/b/b2/Araba.svg/1920px-Araba.svg.png?utm_source=commons.wikimedia.org&utm_campaign=index&utm_content=thumbnail&_=20181123091430)

![Navarra](https://upload.wikimedia.org/wikipedia/commons/3/36/Bandera_de_Navarra.svg?utm_source=es.wikipedia.org&utm_campaign=index&utm_content=original)
![Nafarroa](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Nafarroa_Euskal_Herrian.svg/3840px-Nafarroa_Euskal_Herrian.svg.png?utm_source=es.wikipedia.org&utm_campaign=index&utm_content=thumbnail)

![Labort](https://thumb.wikimedia.org/wikipedia/commons/thumb/3/3a/Flag_of_Lapurdi.svg/3840px-Flag_of_Lapurdi.svg.png?utm_source=es.wikipedia.org&utm_campaign=index&utm_content=thumbnail)
![Lapurdi](https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/Lapurdi_Euskal_Herrian.svg/1280px-Lapurdi_Euskal_Herrian.svg.png?utm_source=an.wikipedia.org&utm_campaign=index&utm_content=thumbnail)

![Baja Navarra](https://thumb.wikimedia.org/wikipedia/commons/thumb/e/e2/Bandera_Navarra.svg/3840px-Bandera_Navarra.svg.png?utm_source=es.wikipedia.org&utm_campaign=index&utm_content=thumbnail)
![Nafarroa Behera](https://thumb.wikimedia.org/wikipedia/commons/thumb/e/e3/Nafarroa_Beherea.svg/330px-Nafarroa_Beherea.svg.png?utm_source=eu.wikipedia.org&utm_campaign=parser&utm_content=thumbnail)

![Zuberoa](https://upload.wikimedia.org/wikipedia/commons/5/5f/Flag_of_Zuberoa.svg?utm_source=es.wikipedia.org&utm_campaign=index&utm_content=original)
![Zuberoa](https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Zuberoa_Euskal_Herrian.svg/330px-Zuberoa_Euskal_Herrian.svg.png)
