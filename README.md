# proju.github.io

# Proju
Ajax proju APIa hyödyntäen


# Projektin nimi: Osakehaku  
**Tekijä:** Atte Liikanen

---

## Verkkolinkit
Julkaistu sovellus: https://kuningasvoittamaton1.github.io/proju.github.io/osakehaku.html

Videoesittely: tulossa myöhemmin

---

# Työn jakautuminen
Suoritin projektin teon yksin  

---

# Oma arvio työstä ja osaamisen kehittymisestä

**Mielestäni onnistuin:**  
- AJAX-kutsujen tekemisessä  
- Ulkoasun rakentamisessa jossakin määrin 
- Dynaamisten tapahtumien lisäämisessä  
- API-datan käyttämisessä

**Parantamista olisi:**  
- Koodin optimoinnissa  
- Toiminnallisuuksissa (enemmän niitä) 
- Muotoilussa (siinä piti hyödyntää hieman tekoälyä kun en löytänyt kaikkea muuten järkevästi)

**Sovelluksesta jäi puuttumaan:**  
- graafinen pörssihistoria sen vaikeuden vuoksi
- lukujen välit kuten osakevaihdossa kymmenien- ja satojentuhansien välit (100 000) koska en saanut sitä järkevästi toimimaan

**Koen, että olen oppinut:**  
- AJAX-pyyntöjen ja API-datan käyttöä  
- CSS:n käyttöä sivun ulkonäön rakentamisessa 
- DOM-manipulaation käyttöä ilman kirjastoja  
- Projektin julkaisemisen GitHubissa ja Netlifyssä


**Arvioisin työni:**  
4/10 pistettä (ehkä plussia jos ehdin tekemään sairastumisesta huolimatta)

---

# Palaute opettajalle
Kurssi on ollut erittäin hyvä niinkuin sinun kurssisi aina! Olen huomannut että panostat hyvin paljon tekemiseesi 
ja siksi olen nauttinut kaikista kursseistasi todella paljon! Kiitos siitä!
Tällä kyseisellä kurssilla lähiopetus on osaksi ollut hyödyllistä minulle, 
mutta en omista keskittymisvaikeuksista johtuen pysty oikeen tunnilla tekemään joten olen jättänyt niitä väliin.

---

# Sisällysluettelo
- [Tietoja sovelluksesta](#tietoja-sovelluksesta)  
- [Tunnetut virheet/bugit](#tunnetut-virheetbugit)  
- [Kuvakaappaukset](#kuvakaappaukset)  
- [Teknologiat](#teknologiat)  
- [Asennus](#asennus)  
- [Lähestymistapa](#lähestymistapa)  
- [Kiitokset](#kiitokset)  
- [Lisenssi](#lisenssi)

---

# Tietoja sovelluksesta
**Osakehaku** on JavaScriptillä toteutettu web-sovellus, joka hakee osaketietoja reaaliaikaisesti 
Financial Modeling Prep -rajapinnasta APIa käyttäen.

Sovellus:
- hakee yrityksen perustiedot (nimi, symboli, ala, pörssi, valuutta)  
- näyttää hinnan ja vaihdon  
- tukee AJAX-pyyntöjä ilman kirjastoja  
- sisältää modernin, tumman käyttöliittymän  
- lisää tapahtumankäsittelijät dynaamisesti  

---

# Tunnetut virheet/bugit
- Joidenkin symbolien kohdalla logo ei ole saatavilla  
- Yrityksen kuvaus boxin avattaessa footer tms tulee tekstin päälle sivua isommaksi zoomatessa(en tiedä miten sen saisi korjattua)

---

# Kuvakaappaukset

EN SAA KUVAKAAPPAUSTA LISÄTTYÄ SIVULLE KOSKA SE EI TÄYTÄ MINIMI MP KOKOA: 
1 file did not meet the minimum size

Please upload images over 5MP

![Sovelluksen näkymä](https://unsplash.com/photos/VBPzRgd7gfc)

*Kuva: Kelly Sikkema*

Lisää omat kuvakaappaukset esimerkiksi:
- hakunäkymästä  
- tuloskortista  
- mahdollisesta virhetilanteesta  

---

# Teknologiat

Käytetyt teknologiat ja niiden rooli:

| Teknologia | Tarkoitus |
|-----------|-----------|
| **HTML5** | Sivun rakenne ja elementit |
| **CSS3** | Tumma ulkoasu ja animaatiot |
| **JavaScript (native)** | AJAX-kutsut, DOM-manipulaatio, dynaamiset event handlerit |
| **XMLHttpRequest** | API-kyselyt ilman kirjastoja |
| **Netlify** | Julkaisu mutta ei tunnu toimivan oikein |
| **GitHub** | Versionhallinta ja repositorio |


Lähteet:
MDN Web Docs
Financial Modeling Prep API 
Stack Overflow
CSS Tricks
W3Schools

Lähteitä on hankala merkata laurean ohjeistuksen mukaan koska olen katsonut monesta paikasta ohjeita miten saisin mitäkin tehtyä ja yrittänyt yhdistellä oppimaani.

CSS:ään käytetty hieman chatgpt:tä auttamaan muotoilullisia asioita tehtäessä jotta saisin sivusta hieman enemmän omaan silmään sopivan, 
olen myös pyytänyt sitä kertomaan mitä osa netistä löytämäni koodi tekee jotta voin kirjoittaa ne omalla tavallani.

