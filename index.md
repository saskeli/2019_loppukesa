---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
title: Tiralabra
---

<script src="assets/fuu.js"></script>

## Link to english materials

[Link to english materials](en/)

## Ohjaaja

* Saska Dönges, (etunimi@cs.helsinki.fi), saskeli@IRCnet

## 📅 Aikataulu

Tarkempi aikataulu [täällä](fi/aikataulu/).

<script>
    script = document.scripts[document.scripts.length - 1];
    script.parentElement.insertBefore(makeCalendarFi(), script);
</script>

## 📣 Ajankohtaista

 * <script>
   if (doodleSent) {
    if (timing["demo"]) {
      document.write("Demotilaisuuden ajankohdat on lyöty lukkoon. Ottakaa yhteyttä jos ette pääse paikalle.")
    } else {
      document.write("Doodle linkki demotilaisuuden aikatauluttamiseksi on lähetetty kurssille ilmoittautuneille opiskelijoille. Sähköposti on lähtenyt siihen osoitteseen mikä on weboodiin rekisteröity.")
    }
   } else {
    document.write("Kysely demotilaisuuden aikatauluttamiseksi lähetetään kurssin puolivälin paikkeilla.")
   }
 </script>
 * Lopullinen palautus <script>document.write(fiString(timing["end"].date));</script>, tähän ei ole saatavilla lisäaikaa.
 * Jos löydät kurssisivuilta jotain parannettavaa. Voit seurata [täältä](fi/bug_bounty) löytyviä ohjeita virheen korjaamisesksi. Hyvistä korjauksista on mahdollista saada yhden kurssipisteen "bug bounty" (max 1 per oppilas)

## Linkkejä materiaaliin

* [Tarkka aikataulu](fi/aikataulu)

* [Aiheideoita](fi/aiheet)

* [Tietoja dokumentaatiosta](fi/dokumentaatio)

* [Ohjeita gitin käyttöön](fi/git-ohje)

* [Ohjeita ja esimerkkejä testauksen tekemiseen Javalla](https://github.com/TiraLabra/Testing-and-rmq)

* [Yksinkertaiset ohjeet Maven- tai Gradle-projektin luontiin](fi/maven-gradle)

* [Ohjeet palautuksien ja viikkoraportin tekemiseen](fi/palautukset)

* [Ohjeet vertaisarviointiin](fi/vertaisarvioinnit)

## 🗒️ Labtool

 * [https://studies.cs.helsinki.fi/labtool/](https://studies.cs.helsinki.fi/labtool/)
 * Kirjaudu Yliopiston tunnuksilla.

## IRC ja telegram
Kurssin IRC-kanava on **#tiralabra** @IRCnet.
Kurssin [telegram-kanava](https://t.me/tkttiralabra).

Telegram kanava on (yleensä) sillattu irkkiin, joten ohjaajaan päässee käsiksi kumpaakin kautta.

## Ohjaus

* Kesän intensiivikursseilla ei järjestetä viikottaista pajaa. Jos haluat henkilökohtaista ohjausta kumpulassa niin ota yhteyttä ohjaajaan.
* Voit myös ottaa yhteyttä [Telegramissa](https://t.me/tkttiralabra) tai ircissä.
* Tai tarvittaessa sähköpostilla.

<!--### Algopaja

* Pajaohjausta järjestetään parjantaisin [algoritmipajan](https://courses.helsinki.fi/en/tkt20000/126082463) yhteydessä. BK107 15-18.
* Algopajasta voi myös muihin aikoihin pyytää apua aloritmeihin liittyen.
-->
## Demotilaisuus

* <script>
  if (timing["demo"]) {
    document.write("Paikka ja aika: " + fiEvent(timing["demo"]) + ".");
  } else {
    document.write("Aika ja paikka vahvistuvat myöhemmin.");
  }
</script>
* **PAKOLLINEN!** Ota yhteyttä jos et pääse demotilaisuuteen, se on läpipääsyyn pakollinen!
* One erittäin suositeltavaa demota omalta kannettavalta. Tässa tapauksessa voi olla hyvä saapua demoon hyvissä ajoin ja varmistaa että projektori toimii koneen kanssa. Jos omaa kannettavaa ei ole kannattaa demoamisesta sopia kaverin tai ohjaajan kanssa erikseen.
* Projektit ladataan myös etukäteen esityskoneelle. Mutta ei omalta koneelta esittäminen ei perinteisesti onnistu kauhean hyvin. Esityskoneet eivät läheskään aina toimi ollenkaan, ja kun toimivat niin projektit eivät välttämättä toimi esityskoneen ympäristössä.
* Noin 5min per projekti.
* Ei tarvitse dioja, mutta halutessaan niitä voi käyttää, tosin ne vie aikaa, joten ei suositeltu, etenkään ellei tuo omaa konetta esitykseen.

## Esimerkkiprojektit

* [Saskelin projekti](https://github.com/saskeli/NonogramSolver_TiRa) **Huom:** että etenkin tämän jälkeen kurssi on jonkin verran muuttunut.
* Ja Jussi sanoi että [oma projektinsa](https://github.com/yussiv/Compress) oli kiireessä tehty mahdollisimman helpolla suoritettu.
* Molemmat kuitenkin (kuulemma) projektirakenteiltaan hyviä, jos haluaa esimerkkejä.

## 🏆 Kurssin suorittaminen
Kurssin työmäärä on opintopisteiden (4) perusteella n. 107 tuntia. Varaudu siis käyttämään työhön 15-20 tuntia viikossa jokaisella viikolla.

Kurssilla opiskelija toteuttaa ohjelman, joka ratkaisee jonkin ohjelmointiongelman. Ongelmanratkaisuun käytetään sopivia algoritmeja sekä tietorakenteita. Oppimismatriisin tiedoista poiketen, opiskelja valitsee ratkaistavan ongelman yhdessä ohjaajan kanssa. Suoritus ei edellytä oman algoritmin kehittämistä. Tämäkin on mahdollista, mikäli opiskelija haluaa haastavamman aiheen. Keskeistä työssä on, että ohjelma on toimiva ja tehokas. Sen tulee kaikissa tapauksissa antaa nopeasti oikea vastaus. Työn aiheesta riippuu, miten suuria tapauksia ohjelman tulee pystyä käsittelemään. Tämä sovitaan ohjaajan kanssa. Mahdollisia aiheita voi katsoa [täältä](fi/aiheet).

Kurssi pidetään osittain verkkokurssina, kaikki viikoittaiset palautukset tapahtuvat verkon kautta. Ainoa pakollinen tapaaminen laitoksella on aloitusluento sekä loppudemot. Lisätietoa palautuksista [täällä](fi/palautukset).

Ohjelma toteutetaan **ohjaajan hyväksymällä** kielellä, melkein poikkeuksetta Javalla.

Kurssin ensisijainen tavoite on oppia toteuttamaan itse tietorakenteita, ja tästä syystä tarvittavat algoritmit ja tietorakenteet tulee toteuttaa itse. Nyrkkisääntönä vain perustietotyyppejä, taulukoita ja merkkijonoja saa käyttää, muu on tehtävä itse, erityisesti Tietorakenteet-kurssilla opetellut rakenteet. Muita apuvälineitä, kuten tiedostonkäsittelyluokkia, saa tietenkin käyttää. **Valmiita tietorakenteita (esim. Javassa: ArrayList, HashMap...) tai algoritmeja (esim. Collections.sort) ei saa käyttää lopullisessa työssä** ja myös niiden importit kannattaa poistaa. Jos olet epävarma jonkin luokan käyttämisestä, kysy ohjaajalta.

Hyväksi koettu tapa tehdä työ vaiheittain on laittaa ensin kuntoon algoritmin ydin käyttäen kielen standardikirjastojen valmista kalustoa (jonot, keot, järjestämisalgoritmit). Kannattaa siis pyrkiä toteuttamaan algoritmin ydin nopeasti ja sen jälkeen korvata käytetty kalusto omilla toteutuksilla. Eli toteuttaa rajapintojen takana olevat rakenteet ja/tai algoritmit itse.  Tätä tapaa käytetään osapalautusten pohjana algoritmin/tietorakenteiden kehityksen osalta. Mikäli toteutat työn erilaisella lähestymistavalla, sovi työn edistymisen "Milestone":t jo 1. viikon aikana ohjaajan kanssa.

## 📈 Arvosteluperusteet
* Ohjelma: 30 p
   * Toimivuus ja ominaisuudet 10 p
   * Testaus 10 p
   * Dokumentoiva koodi (JavaDoc sekä itsedokumentoiva) 5 p
   * Ohjelmakoodin selkeys 5 p

* Dokumentaatio 10 p
   * Aiheen määrittely 2p
   * Ongelman toteutus 3p
   * Testaus 3p (myös suorituskykytestaus!)
   * Käyttöohje 2p

* Arvostelu kurssin aikana 20p
    * Vertaisarvioinnit 2 * 2p = 4p
    * Viikkopalautukset 1p +  5 x 3p = 16 p

(Yhteensä 60 p)

Kurssin hyväksytysti suorittaminen vaatii ohjelmalta itsetoteutettuja tietorakenteita sekä toiminnallisuutta. Kukin työ arvioidaan omana kokonaisuutenaan, alla viitteelliset pisterajat.

* 5: 50 p
* 4: 45 p
* 3: 40 p
* 2: 35 p
* 1: 30 p
