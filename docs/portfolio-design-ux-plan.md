# Portfolio Design & UX Plan

## 1. Tavoite

Portfolion tarkoitus on rakentaa selkeä, moderni ja persoonallinen kokonaisuus, joka viestii Ron Gustafssonista ammattimaisena ohjelmistokehittäjänä.

Sivusto ei pyri näyttämään pitkän linjan seniorikehittäjän portfoliolta, vaan korostaa kolmea asiaa:

- nykyinen osaaminen
- potentiaali ja ajattelutapa
- selkeä kehityssuunta kohti full-stack- ja AI-painotteista ohjelmistokehitystä

Portfolion itsensä tulee toimia yhtenä teknisen osaamisen näyttönä.

---

## 2. Tavoiteltava vaikutelma

### Ammattimainen ohjelmistokehittäjä

- ei opiskelijaportfolion näköinen
- ei harjoitustöiden kokoelma
- selkeä, harkittu ja teknisesti uskottava kokonaisuus
- antaa vaikutelman siitä, että sivuston suunnittelu ja toteutus on tehty tarkoituksella

### Teknisesti osaava mutta kokonaisuuksia ymmärtävä

- frontend + backend
- vahva kiinnostus AI-painotteiseen kehitykseen
- kiinnostus ohjelmistoarkkitehtuuriin ja teknisiin ratkaisuihin
- projektien suunnittelu ja toteutus
- liiketoiminnan ymmärtäminen
- käyttäjän tarpeiden huomioiminen

### Moderni ja AI-suuntautunut

- AI kuuluu nykyiseen työskentelyyn ja tulevaan kehityssuuntaan
- AI-avusteinen kehitys tulee esiin luonnollisesti
- AI ei saa olla irrallinen markkinointielementti
- tulevat projektit voivat myöhemmin vahvistaa AI-profiilia

### Analyyttinen ja järjestelmällinen

- rakenne on erittäin selkeä
- tiedot löytyvät nopeasti
- sivustossa näkyy huolellisuus
- sisältö etenee loogisesti
- ratkaisut perustuvat mahdollisuuksien mukaan faktoihin, dataan ja perusteltuihin valintoihin

### Persoonallinen

- ei valmis portfolio-template
- ei suoraa kopiointia yksittäisestä referenssisivusta
- sivuston pitäisi jäädä mieleen omana kokonaisuutenaan
- käyttäjän pitäisi myöhemmin pystyä muistamaan: “Ai niin, se Ronin portfolio.”

### Rauhallisen itsevarma

- vältetään kliseitä, kuten “olen intohimoinen koodari, joka rakastaa haasteita”
- osaaminen näytetään rakenteen, sisällön, toteutuksen ja esimerkkien kautta
- ei liioitella kokemusta
- ei yritetä antaa vaikutelmaa kymmenen vuoden ohjelmistokehittäjätaustasta

---

## 3. Kieli

- suomi on sivuston pääkieli
- englanti on toinen kielivaihtoehto
- sivuston rakenne ja komponentit suunnitellaan alusta asti kaksikielisyyttä varten

Tarkka käännösratkaisu ja kielenvaihdon käyttöliittymä päätetään myöhemmin.

---

## 4. Sivuston pääarkkitehtuuri

Sivusto toteutetaan hybridimallina:

- vahva etusivu
- navigaatiosta suorat linkit etusivun eri osioihin
- mahdollisuus erillisiin alasivuihin myöhemmin
- erityisesti projektien case study -sivut voidaan toteuttaa erillisinä sivuina

Etusivun tulee toimia itsenäisesti ja antaa kattava yleiskuva ilman, että käyttäjän täytyy avata useita sivuja.

---

## 5. Etusivun alustava järjestys

Alustava sisältöjärjestys:

1. Hero
2. Minusta
3. Miten ajattelen
4. Miten työskentelen
5. Tekninen osaaminen
6. Kokemus / koulutus
7. Projektit
8. Mitä kehitän
9. Yhteystiedot

Järjestys ei ole vielä lopullisesti lukittu. Sitä voidaan muuttaa Figma-suunnittelun ja sisällön kehittymisen perusteella.

---

## 6. Hero-osion tehtävä

Hero-osion tulee kertoa nopeasti:

- kuka Ron Gustafsson on
- mitä hän tekee
- mihin suuntaan hän on kehittymässä
- full-stack- ja AI-painotus
- tärkeimmät toimintopainikkeet

Mahdollinen rakenne:

- RON GUSTAFSSON
- Software Developer
- Full-Stack · AI
- lyhyt positiointiteksti
- tärkeimmät CTA-painikkeet

Mahdollisia CTA-painikkeita:

- Tutustu osaamiseeni
- Katso projektit
- GitHub
- Ota yhteyttä

Hero-osion lopullinen teksti ja visuaalinen toteutus päätetään myöhemmin.

---

## 7. Persoonallinen interaktiivinen elementti

Sivustolle suunnitellaan yksi selkeä tunnistettava interaktiivinen elementti.

Ensisijainen konsepti on käyttäjän toimintaan reagoiva developer profile / `ron.ts` -tyyppinen koodinäkymä.

Mahdollisia toimintoja:

- `profile()`
- `skills()`
- `experience()`
- `currentlyBuilding()`

Elementin tarkoitus:

- tehdä sivustosta tunnistettava
- tuoda tekninen tunnelma ilman kliseistä “fake VS Code” -ratkaisua
- osoittaa React-, TypeScript- ja UI-osaamista
- toimia osana sivuston sisältöä, ei vain koristeena

Toteutuksen tarkka muoto päätetään myöhemmin.

---

## 8. Visuaalisen ilmeen periaatteet

### Yleinen tyyli

- selkeä
- moderni
- tumma
- minimalistinen
- paljon tyhjää tilaa
- vahva typografia
- harkitut tekniset yksityiskohdat
- ei cyberpunk- tai gaming-ilmettä
- ei visuaalista ylikuormaa
- ei tarpeettomia efektejä

Sivuston pitäisi tuntua modernilta ohjelmistotuotteelta yhdistettynä henkilökohtaiseen portfolioon.

---

## 9. Väripaletti

### Midnight
`#0C090A`

Käyttö:
- päätausta
- sivuston hallitseva tumma väri

### White
`#FFFFFF`

Käyttö:
- pääteksti
- otsikot
- korkean kontrastin sisältö

### Platinum
'#E5E4E2'

Käyttö:
- Käytetään otsikoissa tuomaan erottavuutta teksteihin
- matalamman kontrastin sisältö

### Dark Slate Grey
`#25383C`

Käyttö:
- sekundääriset pinnat
- kortit
- paneelit
- koodieditori
- rajat
- taustan sävyerot

### Cyan / Aqua
`#00FFFF`

Käyttö:
- pääkorostusväri
- linkit
- aktiiviset tilat
- valitut elementit
- tekniset yksityiskohdat
- interaktiiviset elementit

Cyania käytetään hallitusti, jotta kokonaisuus ei muutu cyberpunk-tyyliseksi.

### Cantaloupe
`#FFA62F`

Käyttö:
- erittäin rajattu sekundäärinen korostus
- pienet visuaaliset yksityiskohdat
- yksittäiset huomionkohteet

### Ferrari Red
`#F70D1A`

Käyttö:
- semanttiset tilanteet
- virheet
- varoitukset
- mahdolliset status-tilat

Ferrari Red ei toimi varsinaisena brändivärinä.

### Värien painotus

Alustava suhde:

- noin 75 % Midnight ja muut tummat pinnat
- noin 20 % White ja harmaat
- noin 4 % Cyan
- noin 1 % Cantaloupe
- Ferrari Red vain tarvittaessa semanttisiin tilanteisiin

---

## 10. Typografia

Periaatteet:

- iso
- vahva
- yksinkertainen
- hyvä kontrasti otsikoiden ja leipätekstin välillä
- teknisissä yksityiskohdissa voidaan käyttää monospace-fonttia
- leipätekstiä ei tehdä kokonaan koodifontilla

Mahdollisia teknisiä metadataelementtejä:

- `// SOFTWARE DEVELOPER`
- `01 / MITEN AJATTELEN`
- `STATUS: AVAILABLE`

Lopullinen fonttipari päätetään myöhemmin.

---

## 11. Animaatioiden periaate

Animaatioiden tarkoitus on:

- selventää rakennetta
- antaa palautetta käyttäjän toiminnasta
- tehdä sivustosta elävä
- osoittaa frontend-osaamista

Animaatioita ei lisätä vain siksi, että niitä osataan tehdä.

Painotetaan esimerkiksi:

- accordionien avautumista
- hover-tiloja
- scroll reveal -liikettä
- aktiivisten tilojen vaihtumista
- yhtä näyttävämpää interaktiivista elementtiä

Koko sivustolla pyritään yhtenäiseen animaatiologiikkaan.

---

# 12. Miten ajattelen

Tämä on yksi portfolion tärkeimmistä osa-alueista.

Tarkoitus ei ole näyttää geneeristä “soft skills” -listaa, vaan avata sitä, miten Ron ajattelee ja ratkaisee ongelmia.

## 12.1 Kokonaisuuksien hahmottaminen

### Tiivistelmä

Pyrin ymmärtämään järjestelmän kokonaisuutena ennen yksittäisiin ratkaisuihin keskittymistä.

### Avattaessa

- hahmotan, miten järjestelmän eri osat liittyvät toisiinsa
- tunnistan riippuvuuksia komponenttien, käyttäjien ja liiketoiminnan välillä
- mietin yksittäisen muutoksen vaikutusta koko järjestelmään
- pyrin välttämään ratkaisuja, jotka korjaavat yhden ongelman mutta aiheuttavat uusia muualla
- pystyn kokonaisuuden ymmärtämisen jälkeen arvioimaan myös tulevia tarpeita

---

## 12.2 Analyyttinen ongelmanratkaisu

### Tiivistelmä

Teen päätöksiä mieluummin faktojen, datan ja loogisen päättelyn kuin oletusten perusteella.

### Avattaessa

- pilkon ongelmat pienempiin ratkaistaviin osiin
- etsin ongelman varsinaista syytä oireen sijasta
- vertailen vaihtoehtoisia ratkaisuja ennen päätöstä
- hyödynnän dataa, tilastoja ja mitattavaa tietoa silloin kun sitä on saatavilla
- erotan mahdollisuuksien mukaan faktat, oletukset ja mielipiteet toisistaan
- arvioin ratkaisujen hyötyjä, haittoja ja riskejä

---

## 12.3 Syy–seurausajattelu

### Tiivistelmä

Minulle on luontevaa miettiä, miksi jokin tapahtuu ja mitä seurauksia muutoksella on myöhemmin.

### Avattaessa

- etsin ongelmien taustalla olevia syitä
- mietin, mitä muita järjestelmän osia muutos koskettaa
- arvioin päätösten lyhyen ja pitkän aikavälin vaikutuksia
- pyrin tunnistamaan mahdollisia sivuvaikutuksia ennen toteutusta
- käytän tätä ajattelua myös virheiden ja teknisten ongelmien selvittämiseen

---

## 12.4 Tulevaisuus- ja kehitysajattelu

### Tiivistelmä

Kun ymmärrän nykyisen kokonaisuuden, alan luonnostaan miettiä, miten sitä voisi kehittää seuraavaksi.

### Avattaessa

- tunnistan nykyisten ratkaisujen kehitysmahdollisuuksia
- mietin tulevia käyttötapauksia ja vaatimuksia
- arvioin, kannattaako jokin asia huomioida jo nykyisessä toteutuksessa
- etsin tapoja tehdä ratkaisusta yksinkertaisempi, hyödyllisempi tai tehokkaampi
- seuraan uusia teknologioita ja arvioin niiden käytännön hyötyä
- erityisesti AI:n mahdollisuudet ohjelmistokehityksessä kiinnostavat minua

---

# 13. Miten suunnittelen ja rakennan

## 13.1 Suunnittelen ennen toteutusta

### Tiivistelmä

Haluan ymmärtää ongelman, tavoitteet ja riippuvuudet ennen kuin alan rakentaa ratkaisua.

### Avattaessa

- selvitän mitä oikeasti ollaan ratkaisemassa
- määrittelen olennaiset vaatimukset
- hahmottelen tarvittavan rakenteen
- tunnistan teknisiä riippuvuuksia ja riskejä
- pyrin välttämään tarpeetonta uudelleentekemistä
- jaan suuret kokonaisuudet hallittaviksi työvaiheiksi

Periaate:

> Suunnitelman pitää auttaa toteutusta, ei muuttua toteutuksen esteeksi.

---

## 13.2 Tutkin ongelmat itsenäisesti

### Tiivistelmä

Ensimmäinen reaktioni ongelmaan on yleensä tutkia, testata ja etsiä tietoa itse.

### Avattaessa

- luen dokumentaatiota
- etsin tietoa luotettavista lähteistä
- testaan vaihtoehtoja käytännössä
- hyödynnän virheilmoituksia ja debuggausta
- käytän AI-työkaluja tiedonhaun ja ongelmanratkaisun tukena
- kysyn muilta silloin, kun se on tehokkaampaa kuin asian selvittäminen yksin

---

## 13.3 Huolellisuus ja laatu

### Tiivistelmä

Pyrin siihen, että ratkaisu ei ainoastaan toimi vaan on myös ymmärrettävä ja ylläpidettävä.

### Avattaessa

- tarkistan yksityiskohtia
- testaan toiminnallisuuksia
- huomioin poikkeustilanteita
- pyrin kirjoittamaan selkeää ja ylläpidettävää koodia
- dokumentoin asioita, joiden ymmärtäminen myöhemmin säästää aikaa
- arvioin omaa työtäni kriittisesti ennen kuin pidän sitä valmiina

---

## 13.4 Vastuun ottaminen

### Tiivistelmä

Kun otan tehtävän vastuulleni, haluan myös varmistaa, että se etenee loppuun asti.

### Avattaessa

- seuraan työn etenemistä
- pidän sovituista asioista kiinni
- reagoin ongelmiin sen sijaan, että odottaisin niiden ratkeavan itsestään
- tuon epäselvyydet ja riskit esille
- dokumentoin tarvittaessa tilanteen seuraavaa tekijää varten
- en pidä tehtävää valmiina vain siksi, että oma koodiosuuteni valmistui

---

## 13.5 Resurssien järkevä käyttö

### Tiivistelmä

Pyrin löytämään ratkaisun, jonka hyöty on oikeassa suhteessa sen kustannuksiin ja monimutkaisuuteen.

### Avattaessa

- vältän tarpeetonta teknistä monimutkaisuutta
- vertailen olemassa olevia ratkaisuja ennen uuden rakentamista
- huomioin kehitysajan ja ylläpidon
- mietin, tarvitseeko ongelma todella uuden työkalun tai palvelun
- pyrin käyttämään aikaa ja rahaa siellä, missä ne tuottavat eniten arvoa

---

# 14. Tuote ja käyttäjä

## 14.1 Käyttäjän näkökulma

### Tiivistelmä

Tekninen ratkaisu on onnistunut vasta silloin, kun se ratkaisee käyttäjän todellisen ongelman.

### Avattaessa

- mietin, mitä käyttäjä yrittää oikeasti saavuttaa
- arvioin käyttöliittymää käyttäjän näkökulmasta
- tunnistan epäselviä tai tarpeettoman vaikeita työvaiheita
- pyrin ymmärtämään käyttäjän odotuksia
- erotan teknisesti kiinnostavan ominaisuuden käyttäjälle hyödyllisestä ominaisuudesta

---

## 14.2 Kehitystarpeiden tunnistaminen

### Tiivistelmä

Katson sovelluksia helposti myös siitä näkökulmasta, mitä niistä puuttuu ja mitä voisi tehdä paremmin.

### Avattaessa

- tunnistan puuttuvia ominaisuuksia
- huomaan käytettävyyteen liittyviä ongelmia
- etsin epäjohdonmukaisuuksia
- ehdotan vaihtoehtoisia toteutustapoja
- mietin, voidaanko jokin prosessi automatisoida
- arvioin, tuottaako uusi ominaisuus oikeasti lisäarvoa

---

## 14.3 Liiketoimintaymmärrys

### Tiivistelmä

Ohjelmisto ei ole vain tekninen järjestelmä, vaan yleensä väline jonkin liiketoiminnallisen tavoitteen saavuttamiseen.

### Avattaessa

- kiinnostun siitä, miksi ratkaisu rakennetaan
- huomioin kustannukset ja resurssit
- mietin käyttäjälle syntyvää arvoa
- ymmärrän markkinoinnin ja tuotteen yhteyttä
- huomioin, että teknisesti paras ratkaisu ei aina ole liiketoiminnallisesti paras ratkaisu
- kiinnostun tuotteiden kaupallistamisesta ja kehittämisestä

---

## 14.4 Ideointi ja innovointi

### Tiivistelmä

Pidän ongelmien lisäksi myös mahdollisuuksien etsimisestä.

### Avattaessa

- ideoin uusia toiminnallisuuksia
- yhdistelen olemassa olevia ratkaisuja uusilla tavoilla
- etsin automatisoitavia työvaiheita
- arvioin uuden teknologian tarjoamia mahdollisuuksia
- mietin, voisiko olemassa olevan ongelman ratkaista kokonaan toisella tavalla

---

# 15. Projektit ja tiimityö

## 15.1 Teknisen ja liiketoiminnan yhdistäminen

### Tiivistelmä

Pyrin ymmärtämään sekä teknisen toteutuksen että sen ympärillä olevan tavoitteen.

### Avattaessa

- pystyn keskustelemaan teknisestä ratkaisusta myös ei-teknisestä näkökulmasta
- ymmärrän asiakkaan tarpeiden vaikutuksen toteutukseen
- pystyn osallistumaan määrittelyyn ennen varsinaista ohjelmointia
- huomioin käyttäjän, projektin ja teknologian samassa kokonaisuudessa

---

## 15.2 Prosessien kehittäminen

### Tiivistelmä

Jos työskentelytavassa on selvä ongelma, mietin mielelläni myös itse prosessin parantamista.

### Avattaessa

- selkeytän dokumentointia
- mietin tiedon löydettävyyttä
- ehdotan rakenteita ja toimintamalleja
- pyrin vähentämään epäselviä vastuita
- tunnistan toistuvia ongelmia, jotka voisi ratkaista prosessitasolla

---

## 15.3 Yhteistyö ja tiedon jakaminen

### Tiivistelmä

Hyvä ratkaisu ei auta paljon, jos kukaan muu ei ymmärrä sitä.

### Avattaessa

- dokumentoin olennaiset päätökset
- perustelen ratkaisujani
- annan rakentavaa palautetta
- otan vastaan palautetta
- jaan löytämäni hyödyllisen tiedon muiden kanssa
- pyrin jättämään työn sellaiseen tilaan, että toinen pystyy jatkamaan siitä

---

## 15.4 Laadun arviointi

### Tiivistelmä

En tarkastele vain sitä, toimiiko ratkaisu, vaan myös sitä, onko se järkevä tapa ratkaista ongelma.

### Avattaessa

- tarkastelen toteutuksia kriittisesti
- etsin mahdollisia virhetilanteita
- arvioin ylläpidettävyyttä
- vertailen vaihtoehtoisia ratkaisuja
- annan tarvittaessa palautetta myös muiden toteutuksista

---

# 16. Tekninen osaaminen

Tekninen osaaminen pidetään erillään ajattelutavasta ja työskentelytavasta.

## Frontend

- React
- React Native
- Next.js
- TypeScript
- JavaScript
- HTML
- CSS
- Tailwind CSS

## Backend

- Node.js
- Express
- NestJS
- REST API
- JWT
- RBAC

## Data

- MongoDB
- MongoDB Atlas
- Mongoose
- SQL
- MySQL

## Kehitystyökalut

- Git
- GitHub
- VS Code
- Postman
- Thunder Client
- ESLint
- Prettier

## AI-avusteinen kehitys

Tätä osiota tarkennetaan myöhemmin.

Mahdollisia sisältöjä:

- AI-avusteinen tiedonhaku
- ongelmanratkaisu
- vaihtoehtoisten ratkaisujen arviointi
- koodin analysointi
- dokumentointi
- suunnittelu
- AI-agentit
- kehitystyön automatisointi

---

# 17. Mitä kehitän

Osiota ei kutsuta “heikkouksiksi”.

Tarkoitus on osoittaa realistista itsearviointia ja jatkuvaa kehittymistä.

## 17.1 Laatu vs. nopeus

### Tiivistelmä

Luontainen työskentelytapani on perusteellinen. Kehitän jatkuvasti kykyä tunnistaa, milloin lisäviimeistely tuottaa todellista arvoa.

### Avattaessa

- kaikkea ei tarvitse optimoida täydelliseksi
- projektin tavoite määrittää vaadittavan laatutason
- joskus nopea ensimmäinen versio on paras tapa saada lisää tietoa
- pyrin tunnistamaan tilanteet, joissa lisätyö ei enää tuo suhteessa riittävästi hyötyä

---

## 17.2 Analyysi vs. toiminta

### Tiivistelmä

Haluan ymmärtää ongelman perusteellisesti, mutta kaikkiin kysymyksiin ei tarvitse löytää vastausta ennen ensimmäistä kokeilua.

### Avattaessa

- toisinaan pieni prototyyppi kertoo enemmän kuin lisäsuunnittelu
- opettelen tunnistamaan päätökset, jotka voidaan tehdä myöhemmin
- erotan vaikeasti peruttavat päätökset helposti muutettavista
- pyrin etenemään vaiheittain silloin, kun epävarmuutta on paljon

---

## 17.3 Tiedon ulkoistaminen

### Tiivistelmä

En rakenna työskentelyäni muistin varaan, vaan käytän järjestelmällisesti dokumentaatiota ja työkaluja.

### Avattaessa

- muistiinpanot
- tehtävienhallinta
- dokumentaatio
- versionhallinta
- AI-työkalut
- projektikohtaiset ohjeet ja päätöslokit

---

# 18. Osaamisosion interaktiivinen rakenne

Kaikkia asioita ei esitetä kortteina.

Sisältö rakennetaan tasoiksi, joissa käyttäjä näkee ensin pääkohdat ja voi avata kiinnostavan kohdan tarkemmin.

Esimerkki:

```text
01

MITEN AJATTELEN

Kokonaisuuksien hahmottaminen              +
Analyyttinen ongelmanratkaisu              +
Syy–seurausajattelu                        +
Tulevaisuus- ja kehitysajattelu            +
```

Klikkaus:

- avaa lisätiedot pehmeällä animaatiolla
- muuttaa aktiivisen kohdan visuaalista tilaa
- voi käynnistää pienen teknisen animaation tai muun visuaalisen reaktion

Tavoitteena on yksi yhtenäinen interaktiologiikka koko osaamisosion läpi.

---

# 19. Osaamisosion hierarkia

```text
01  MITEN AJATTELEN
    ├─ Kokonaisuuksien hahmottaminen
    ├─ Analyyttinen ongelmanratkaisu
    ├─ Syy–seurausajattelu
    └─ Tulevaisuus- ja kehitysajattelu

02  MITEN SUUNNITTELEN JA RAKENNAN
    ├─ Suunnittelen ennen toteutusta
    ├─ Tutkin ongelmat itsenäisesti
    ├─ Huolellisuus ja laatu
    ├─ Vastuun ottaminen
    └─ Resurssien järkevä käyttö

03  TUOTE JA KÄYTTÄJÄ
    ├─ Käyttäjän näkökulma
    ├─ Kehitystarpeiden tunnistaminen
    ├─ Liiketoimintaymmärrys
    └─ Ideointi ja innovointi

04  PROJEKTIT JA TIIMITYÖ
    ├─ Teknisen ja liiketoiminnan yhdistäminen
    ├─ Prosessien kehittäminen
    ├─ Yhteistyö ja tiedon jakaminen
    └─ Laadun arviointi

05  TEKNINEN OSAAMINEN
    ├─ Frontend
    ├─ Backend
    ├─ Data
    ├─ Kehitystyökalut
    └─ AI-avusteinen kehitys

06  MITÄ KEHITÄN
    ├─ Laatu vs. nopeus
    ├─ Analyysi vs. toiminta
    └─ Tiedon ulkoistaminen
```

---

# 20. Portfolion rooli nykyisessä vaiheessa

Koska pitkää ohjelmistokehittäjäuraa ja laajaa omaa projektikatalogia ei vielä ole:

- ajattelutapa ja vahvuudet saavat tavallista suuremman roolin
- portfolio itsessään toimii teknisenä näyttönä
- nykyisiä projekteja voidaan esitellä tarkoituksenmukaisella painoarvolla
- projektiosio suunnitellaan skaalautumaan uusien projektien mukana
- sivusto näyttää tarkoituksella potentiaalin, nykyisen osaamisen ja kehityssuunnan

Sivusto ei yritä teeskennellä pitkää ohjelmistokehittäjäkokemusta.

---

# 21. Vielä avoimet asiat

Seuraavia asioita ei lukita vielä:

- lopullinen fonttipari
- tarkka layout
- Figma-komponentit
- lopulliset hero-tekstit
- tarkat animaatiot
- `ron.ts`-elementin tarkka toiminta
- projektien lopullinen esitystapa
- osioiden lopullinen järjestys
- tarkka kielenvaihdon toteutus
- yksittäisten tekstien lopullinen sanamuoto

Näitä tarkennetaan Figma- ja kehitysvaiheen aikana.

---

# 22. Seuraava vaihe

Seuraava vaihe on siirtää tämä suunnitelma visuaaliseksi konseptiksi:

1. määritellään ensimmäinen Figma-rakenne
2. hahmotellaan desktop-etusivu
3. testataan typografia, spacing ja värien toimivuus
4. suunnitellaan yksi osaamisosion interaktiivinen näkymä
5. hahmotellaan `ron.ts`-elementin ensimmäinen versio
6. vasta tämän jälkeen siirrytään varsinaiseen UI-toteutukseen
