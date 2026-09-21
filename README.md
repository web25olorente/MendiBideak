# MendiBideak
Euskal Herriko Mendi eta Bidezidorrak.

## **1. IKERKETA:**
**WikiLoc**, **Outdooractive: Senderismo** eta noski, **Google Maps** dira gaur egunean diren sektore honetako web edo aplikaziorik erabilienetarikoenak eta oso ezagunak. Eta azkenean, asko laguntzen dute gure egunean zehar.

Kirola egitea oso garrantzitzua da. Mendiko irteerak edo edozein bidezidorretik jutea, oinezien, korrikan, bizikletarekin edo nahi denarekin, dibertigarria izateaz gain, osasuntzua da.
Web orri hau pentsatuta egongo da nagusiki 16 urte gorako duten pertsonendako, nagusiki mendizaleak diren pertsonei, ibiltzea gustoko duten pertsonek edo irteeraren bat egitea nahi duten jendearentzat sortuko da.

Horretarako idei hugari bilatzen egon gara emaitz bikain bat lortu ahal izateko. Zentratuko gara ointxe sektore honetan dauden produkturik ezagunenetarikoenak.


### **WikiLoc**
![WikiLoc](https://viendoosdesdearriba.wordpress.com/wp-content/uploads/2018/10/wikiloc2.png?w=256)
- **Erabilera nagusia:** Aire zabaleko kirol-ibilbideak aurkitu eta partekatzea.
- **Funtzioak:** Mundu osoko erabiltzaileek igotako senderismo, txirrindularitza eta beste hainbat diziplinatako mapak eskaintzen ditu.
- **Abantailak:** GPS bidezko nabigazioa ahalbidetzen du, bidean galdu gabe jarraitu ahal izateko.

[WikiLoc](https://eu.wikiloc.com/)

🧠 Web orri honetan oinarrituz idei asko okurritu zaigu.
💡 *Adibidez:* Ibilbide bakoitza `div` baten barruan sartzea.
- Distantzia, Desnibel -a eta zailtasuna sartzea argi eta garbi.
  - Hemen klima ere agertzea pentsatu da.
- Zailtasuna 3 kolore desberdinetan bisualki lagungarria izateko.
- Argazki batzuk ipini.
- Deskripzioren bat.
  - Eta agian Google Maps -en ibilbidearen `esteka` ipiniko da `botoi` baten barruan.

### **Outdooractive: Senderismo**
![Outdooractive](https://play-lh.googleusercontent.com/dDv0dOUwvl8aWd7BzTq1PxG2QOBmshEi37HHvUneuVelfLL_8yXUa9qfDG2exhovHsqmU0Sy_IjFfifMz4_kCw=s0-br30)
- **Erabilera nagusia:** Mendi eta outdoor jardueren plangintza zehatza egitea.
- **Funtzioak:** Kalitate handiko mapa topografikoak eta ibilbide gidatuak eskaintzen ditu.
- **Abantailak:** Segurtasunari eta eguraldiari buruzko informazio eguneratua ematen du, mendiko esperientziak profesionaltasunez prestatzeko.
[Outdooractive](https://www.outdooractive.com)
Bisualki elementuak oso txukun antolatuta daude, eta hori gure gustukoa izan da. Horregatik sahiatuko gara txukuntazun garbi eta erakargarri bat mantentzea.
Elementuen arteko marginak, tarteak, banaketak, ... detaile txikiekin ere emaitz handiak izan daiteke.

### **Google Maps**
![Maps](https://cdn-icons-png.magnific.com/256/2642/2642502.png?semt=ais_white_label)
- **Erabilera nagusia:** Munduko edozein lekutan nabigatzea eta lokalizazioak bilatzea.
- **Funtzioak:** Garraiobide desberdinetarako (autoa, oinezkoak, garraio publikoa) ibilbiderik azkarrenak kalkulatzen ditu.
- **Abantailak:** Negozioen informazioa, satelite bidezko irudiak eta denbora errealeko trafikoaren egoera erakusten ditu.
[Maps](https://maps.google.com/?authuser=0)

Hemen izan den idea izan da erabiltzea aplikazio hau ibilbidea markatzea, ondoren ibilbidearen esteka sortzeko eta gure aplikazioan `botoi` bati sakatuz gero eramateko zuzenean eta ikusi ahal izateko ze ibilbide, nundik pasatu behar den eta ... ikusteko erabiltzaileak.
> Ideia bezala dago, agian ez da implementatzen.



---
# Estilo Gida
- **Koloreak.**
- **Tipografia.**
- **Ikonoak.**
- **Botoiak.**
- **Irudiak.**

## Koloreak:
Erabakita dago ze kolore erabili nahi den zabalgarri-menuan (Menú Desplegable). Botoi bat egongo da zabalgarri - menua erakutsiko duena. **Botoi hori kolorez aldatuko da bisualki esateko kurtsorea (El cursor) zabalgarri-menuaren botoiaren gainean dagoela.**
Zabalgarri-menua agertzen denean, zabalgarri-menu atzeko edukia; web orria, hau da, atzeko alde guztia, nun orria ikusi jarraitu ahal izango den, **itzal beltz-garden bat eukiko du** (Sombra negra semi-transparente).
> Gazteleraz esplikatuko dut hobeto ulertzeko: El menú desplegable utilizará colores gradientes. La página o lo que se pueda apreciar de ella de fondo, que quedará atrás del menú desplegable, contendrá una sombra negra semi transparente.

Behin azalduta zabalgarri-menuko atzeko aldea nola izango den, zentratuko gara zabalgarri menuan. Honek **kolore gradianteak** edukiko ditu. Zabalgarri menua `Div` handi bat izango da, nun beste 3 `Div` edukiko ditu haren barruan. `Div` nagusiak kolore gradiante gris  izango da, **konkretuki zilarra kolorezkoa izango da.** Barruko hiru `Div`-ak **kolore gradiante hori argiak** edukiko ditu. Hiru `Div`-en barruan orri desberdinetara juteko `botoi-estekak` edukiko ditu, nun denak **atzeko kolore zuriak** eukiko dituzte, salbu erabiltzaileak bertan dagoen orriko `botoi-esteka`, zein **beltz kolorezkoa izango da** bisualki esateko orri horretan dagoela. `Div` -en izenburuak letra beltz edo zuriak izango dira. Testeatuko da ea bietatik zein geratzen den hobeto, baina azalduko koloreekin, balitekeena kolore beltza erabiltzea kontrastearengatik, hobeto irakurri ahal izateko. Azkenik, `Div` nagusi barruan, hiru `Div`-en azpiko aldean botoi biribil bat egongo da zabalgarri menua izkutu egingo duena.

Web orriak edukiko duen tipografia aldetik, **letra biribildunak** erabiltzea pentsatu da. Edozein adinezko erabiltzaileak erabiltzeko pentsatuta dago web orri hau. Ez nahi dugu azpergarri edo zerio itxura bat ematea, kirola dibertigarria izan daiteke pertsona azkorentzat, zeriotazun itxura ematen baldin bada, ez dator bat kirola egiteko zentzazinoarekin, saiatu nahi dugu pertsonek irteerak, toki naturaletara pasatzea, kirola egitea, paisai ederrak esperimentatzea, ... Kaltegabea (Inofensivo) den web orria zentzazinoa sortu nahi diogu erabiltzaileari. Baina, bezta ez nahi degu haur ("Infantil") itxura bat egitea. Daukagun ondorioa da puntu erdi batera eramatea.


**Gauza bat bisualki erakargarria izateko, atzegina izan behar da eta garbia. Koloreekin, testuekin, edukiarekin eta itxurarekin apaindu behar da web orri guztia marrazki bat balitz bezala.**

**Gure kasuan, hainbat kolore bizidun erabiltzea pentsatu dugu,** zergatik natura, animaliak, planeta eta entorno guztiak bizirik daude eta kolore azkoz osatuta daude, azkenean, kirola bizitza da, **gizakiok historio bat sortzen dugu ibiltzen dugunean.** Batzutan bakarrik eraikiko ditugu eta beste batzutan konpainian, baina geldik egonda ez dira historia berriak sortuko. Teknologia berri askok geroz eta lausoagoak ("vagos") egiten hari gaitu, gure helburua da teknologiari erabilera on bat ematea laguntzeko toki berrietara heltzera, entretenimendua planetan sortu ahal izatea pantaila baten ordez.

Edukia aldetik informazio ugari eman behar da, eta bisualki dena laburtuta erakustea nahi da. Zailtazun maila testu bakar eta koloreez zehaztuta, klimatologia argi eta garbi, euria bero edo zer egingo duen , 
