## Jekyll ja CI/CD

- GitHub actions avulla voidaan määritellä miten ja milloin koodia testataan, rakennetaan ja julkaistaan. Kun repositoryyn pushataan uutta koodia tai pull requestin yhteydessä, voidaan github actions määritellä suoraan testaamaan koodia esimerkiksi mahdollisten turvallisuus riskien löytämiseksi, tarkistamaan testikattavuus ja testamaan koodin toimivuus. Prosessi lähtee tekemällä projektille GitHub repository, johon luodaan workflow, minne määritellään toiminnot, jotka tehdään aina kun uutta koodia pushataan repositoryn tai pull requestin yhteydessä main haaraan. Jotain yleisempiä CI (continuous integration) ja CD (continuous deployment/delivery) työkaluja GitHub actionsin lisäksi tähän on esimerkiksi Jenkins ja GitLab. 

[Takaisin](../index.md)