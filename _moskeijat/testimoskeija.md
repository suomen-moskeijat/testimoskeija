---
# Lisätty automaattisesti. Täydennä ja korjaa tietoja Pages CMS:ssä (https://app.pagescms.org).
luonnos: true        # uusi sivu on luonnos (palkki ylhäällä, ei Googlessa); kun moskeija hyväksyy → false
title: "Testimoskeija"
slug: testimoskeija
kaupunki: "Helsinki"
osoite: "Testikatu 1, 00100 Helsinki"   # esimerkkiosoite (testimoskeija)
sijainti: { lat: 60.16662, lon: 24.943541 }

puhelin: ""
whatsapp: ""
sahkoposti: ""
nettisivu: ""
kielet: [suomi]
juma: "13.30"

# Rukousajat: rukousajat.fi (Helsinki/Espoo/Vantaa) tai laskenta sijainnista
rukousajat:
  lahde: ""
  tunnus: ""
  iqamah_oletus: { fajr: 10, dhuhr: 10, asr: 10, maghrib: 5, isha: 10 }

some:
  instagram: ""
  facebook: ""
  youtube: ""      # uusimmat videot näkyvät sivulla
  tiktok: ""
  telegram: ""     # julkisen kanavan julkaisut näkyvät sivulla
  snapchat: ""
  x: ""
  threads: ""
  whatsapp_kanava: ""

teema:
  vari: oma           # valmis värimaailma (esim. smaragdi, sininen) tai oma = alla olevat värikoodit
  logo: ""            # ilman logoa yläpalkissa näkyy moskeijan nimi
  hero: vaalea
  # Omat värit (tyhjä = pohjan kulta-ruskea)
  paa: ""
  korostus: ""
  korostus_vaalea: ""

hero_tunniste: { fi: "Helsinki" }
esittely: { fi: "Tämä on testimoskeija: esimerkkisivu uusien ominaisuuksien kokeiluun. Tiedot ovat keksittyjä." }

# Etusivun yläosa: tausta kuvio | kuva | vari, napit (enintään 2):
# lapsi, toiminta, rukousajat, lahjoita, yhteys, oma tai oman sivun nimi
alku:
  tausta: kuvio
  kuva: ""
  napit: [toiminta, yhteys]

# Yhteiset artikkelit (islaminusko.fi, lähdemerkinnällä). Tyhjä lista = vain omat artikkelit.
artikkelit:
  lahteet: [islaminusko]

# Valikosta piilotettavat sivut, esim. [tapahtumat]. Lahjoita näkyy, kun lahjoitustiedot on lisätty.
valikko_piilota: []
galleria: []

# Esimerkki: Ramadanin asetukset (testidata)
ramadan:
  testi: true  # testimoskeija: ramadan-osio näkyy aina (esikatselu ?ramadan=ennen|5|eid)
  tarawih: "20.30"
  tarawih_huom: { fi: "Isha-rukouksen jälkeen, naisille oma tila" }
  eid_aika: "08.30"
  eid_aika_2: "10.00"
  eid_paikka: { fi: "Testihalli, Testikatu 5" }
  fitra: { fi: "10 € / henkilö" }
  teksti: { fi: "Iftar moskeijalla joka perjantai – tervetuloa koko perheen kanssa!" }
palvelut_esittely:
  fi: Palvelut, joita moskeijalta voi pyytää. Ota yhteyttä, niin sovitaan aika.
palvelut:
  - kuvake: sydan
    nimi:
      fi: Janaza – hautajaiset
    kuvaus:
      fi: Autamme vainajan pesussa (ghusl), janaza-rukouksessa ja hautajaisjärjestelyissä. Ota yhteyttä heti, niin hoidamme asiat yhdessä – myös iltaisin ja viikonloppuisin.
  - kuvake: tahti
    nimi:
      fi: Nikah – avioliiton solmiminen
    kuvaus:
      fi: Imaami solmii nikahin moskeijassa tai kotona. Varaa aika, niin kerromme, mitä tietoja ja todistajia tarvitaan.
  - kuvake: moskeija
    nimi:
      fi: Shahada – islamiin kääntyminen
    kuvaus:
      fi: Haluatko kääntyä islamiin? Imaami keskustelee kanssasi ja todistaa shahadan. Saat todistuksen ja tukea alkuun.
  - kuvake: lapsi
    nimi:
      fi: Aqiqa ja lapsen nimenanto
    kuvaus:
      fi: Neuvomme aqiqan järjestämisessä ja lapsen nimen valinnassa.
  - kuvake: ryhma
    nimi:
      fi: Kouluvierailut ja tutustumiset
    kuvaus:
      fi: Koululuokat, päiväkodit ja muut ryhmät ovat tervetulleita tutustumaan moskeijaan. Sovi aika etukäteen.
  - kuvake: kirja
    nimi:
      fi: Keskusteluapu ja neuvonta
    kuvaus:
      fi: Imaami tarjoaa luottamuksellista keskusteluapua perhe- ja elämäntilanteisiin sekä uskonnollisiin kysymyksiin.
---
