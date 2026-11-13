# Yöloki

Puhelimen selaimessa toimiva yösovellus, jolla tarkan kellonajan voi kirjata yhdellä napautuksella pimeässä ja puoliunessa ja koota kirjauksista raportin.

**Kokeile:** https://asser-anttila.github.io/yoloki/

## Ominaisuudet

- Kirjaus yhdellä napautuksella. Näyttö on jaettu kahteen isoon kosketusalueeseen, joihin osuu pimeässäkin.
- Lisätiedot voi lisätä jälkikäteen. Jälkikäteen lisätyt tai korjatut merkinnät näkyvät raportissa, jotta loki on uskottava.
- Kirjaus toimii myös ilman verkkoyhteyttä.
- Näyttö pysyy himmeänä päällä koko yön.
- Sovellus voi tuottaa valkoista kohinaa ajastimella.
- Kirjauksista syntyy raportti.

## Tietosuoja

Kirjaukset tallentuvat vain omaan selaimeesi. Esittelyversiossa ei ole kenenkään kirjauksia.

## Miten sovellus tehtiin

Rakensin Yölokin tekoälyn (Claude) avulla. Määrittelin tarpeen ja käyttöliittymän keskeiset ratkaisut, kuten näytön jaon kahteen isoon kosketusalueeseen, arvioin tekoälyn ehdotukset ja testasin sovellusta omalla puhelimellani. Koodin kirjoitti Claude.

Toinen versio, jossa oli jo lähes kaikki toiminnot, valmistui noin kolmessa tunnissa ideasta, ja kolmas syntyi käyttökokemukseni pohjalta.

## In English

Night Log is a night-time web app for the phone that logs the exact time with a single tap, even in the dark and half asleep, and turns the entries into a report. Details can be added afterwards, and entries added or corrected later are marked in the report so the log stays credible. Logging works offline, the screen stays dimly on all night, and the app can generate its own white noise with a timer. Entries are stored only in your own browser.

I built it with AI (Claude): I defined the need and the key interface decisions, such as splitting the screen into two large touch areas, evaluated the AI's suggestions and tested the app on my own phone. Claude wrote the code. The second version, with almost all of its features, was ready about three hours after the idea, and the third came from my experience of using it.

---

Asser Anttila · [LinkedIn](https://www.linkedin.com/in/asser-anttila) · [GitHub](https://github.com/asser-anttila)
