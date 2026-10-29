# Ron Gustafsson – portfolion tekninen projektimuistio

Tämä muistio kokoaa hyväksytyn portfolio-suunnitelman teknologiavalinnat, julkaisuratkaisun ja työjärjestyksen. Tavoitteena on rakentaa henkilökohtainen portfoliosivusto staattisena sivustona ilman omaa palvelinbackendiä.

## Tech Stack

| Teknologia | Käyttötarkoitus |
| --- | --- |
| Next.js | Sivuston sovelluskehys ja staattinen vienti (static export). |
| React | Käyttöliittymän rakentaminen komponenteista. |
| TypeScript | Sovelluskoodin tyypitys. |
| Next.js App Router | Sivujen, reitityksen ja yhteisten asettelujen rakenne. |
| Tailwind CSS | Ulkoasu ja responsiivinen toteutus. |
| shadcn/ui + Base UI | Valmiit ja muokattavat käyttöliittymäkomponentit. |
| Lucide | Ikonit. |
| Motion | Harkitut animaatiot vasta perusrakenteen ja visuaalisen ilmeen valmistuttua. |
| pnpm | Pakettienhallinta. |
| Git + GitHub | Versionhallinta ja lähdekoodin säilytys. |

Muita kirjastoja lisätään vain tarpeen mukaan. Projektin riippuvuudet pidetään tarkoituksenmukaisina.

## GitHub-repo

- **GitHub-tili:** [Ron-Gustafsson](https://github.com/Ron-Gustafsson)
- **Suositeltu repositorion nimi:** `ron-gustafsson-portfolio`
- **Näkyvyys:** julkinen (public).
- **Nimen tila:** suositus; repositorion tarkkaa nimeä ei ole vielä lukittu.
- Paikallinen projektikansio voi käyttää samaa nimeä kuin repository.

GitHubissa säilytetään lähdekoodi ja sen muutoshistoria. Varsinainen sivuston hosting toteutetaan StaticHost.eu:ssa.

## Hosting

**Valittu palvelu: StaticHost.eu.**

Suunnitelmana on käyttää yhden staattisen sivuston ilmaista palvelua ja julkaista GitHubissa oleva projekti StaticHostiin. Next.js-projekti toteutetaan staattiseen vientiin sopivaksi: julkaistu sivusto ei tarvitse omaa palvelinbackendiä tai Next.js:n palvelinpuolen ominaisuuksia.

## Domain

**Tämänhetkinen valinta: `ron-gustafsson.fi`.**

Domain ostetaan erikseen ja liitetään StaticHostiin. Domainin mukana ei tarvita erillistä webhotellia, koska StaticHost.eu hoitaa sivuston hostingin.

Sovitussa työjärjestyksessä domain ostetaan ja liitetään julkaisun loppuvaiheessa. Sen voi halutessaan varata aikaisemmin, jotta nimi ei ehdi mennä toiselle.

## Työvaiheet sovitussa järjestyksessä

1. **Luo GitHub-repository.**
   - Luo julkinen repository, suositusnimellä `ron-gustafsson-portfolio`.

2. **Luo Next.js-projekti paikallisesti.**
   - Ota käyttöön Next.js, TypeScript, App Router ja Tailwind CSS.
   - Käytä pakettienhallintaan pnpm:ää.

3. **Yhdistä projekti GitHub-repoon.**
   - Tee ensimmäinen commit.
   - Vie projekti GitHubiin (push).

4. **Asenna käyttöliittymän perustyökalut.**
   - Ota käyttöön shadcn/ui + Base UI sekä Lucide.
   - Motionia ei tarvitse vielä käyttää.

5. **Tee sivuston rakenne ensin.**
   - Navigaatio ja etusivu.
   - About / Minusta.
   - Skills / Osaaminen.
   - Projects / Projektit.
   - Education / Koulutus.
   - Experience / Kokemus.
   - Contact / Yhteystiedot.

6. **Rakenna etusivu kunnolla.**
   - Hero-osio: kuka olet, mitä osaat ja mitä haet.
   - Tärkeimmät CTA-painikkeet eli toimintakehotteet.
   - Ensimmäinen projektinosto.

7. **Rakenna projektiosio.**
   - BetNator.
   - GatherHub.
   - Kasauslaitos.
   - Full Stack Open -projektit.
   - Lisää muita projekteja vain, jos ne vahvistavat portfoliota.

8. **Lisää muu sisältö.**
   - Työkokemus, koulutus, teknologiat ja saavutukset.
   - GitHub, LinkedIn ja CV.

9. **Viimeistele visuaalinen ilme.**
   - Typografia, välit ja komponentit.
   - Responsiivisuus: mobiili, tabletti ja työpöytä.
   - Lisää tämän jälkeen harkitut Motion-animaatiot.

10. **Tee tekninen viimeistely.**
    - Hakukoneoptimointi (SEO) ja metadata.
    - Open Graph -kuvat.
    - Saavutettavuus ja suorituskyky.
    - Favicon ja virhesivut.

11. **Tee Next.js static export.**
    - Varmista, että koko sivusto voidaan julkaista StaticHostissa ilman palvelinpuolen ominaisuuksia.

12. **Julkaise StaticHost.eu:ssa.**
    - Yhdistä GitHub-projekti StaticHostiin ja julkaise sivusto.
    - Testaa ensin StaticHostin omalla osoitteella.

13. **Osta ja liitä `ron-gustafsson.fi`.**
    - Liitä domain StaticHostiin ja määritä DNS-asetukset.
    - Varmista HTTPS ja tee lopulliset testit.

## Ensimmäinen konkreettinen tehtävä

Luo tyhjä julkinen GitHub-repository ja sen jälkeen paikallinen Next.js-projekti. Domainin ja StaticHostin käyttöönotto tulee myöhemmin, kun sivustosta on julkaistava versio.
