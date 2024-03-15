# Toimistotilojen varausjärjestelmä
Ohjelmistotuotanto I -kurssin harjoitustyö, ryhmätyö (6hlo), 2023.

Tekniikat: Visual Studio, WPF(C#, XAML), MariaDB, HeidiSQL, ERDPlus(suunnittelussa), Azure DevOps (versionhallinta ja projektinseuranta).

---
### Harjoitustyön kuvaus
Toimistotilojen varausjärjestelmä.

- Järjestelmään pystyy lisäämään eri toimitiloja toimipisteille.
- Vuokra-ajat voivat vaihdella.
- Tilojen varauksen yhteydessä voi vuokrata laitteita ja palveluita.
- Vuokrattavat laitteet ja palvelut vaihtelevat toimipisteittäin, mutta ne ovat aina sidoksissa vuokrattuun tilaan ts. laitteet ja palvelut vuokrataan samalle ajanjaksolle kuin toimistotila.
- Järjestelmä sisältää varaus- ja asiakashallintajärjestelmän, joka mahdollistaa reaaliaikaisen toimipisteiden varaustilanteen seurannan- ja raportoinnin.
  
- Palveluiden hallinta
- Toimistotilavarausten hallinta
- Asiakashallintajärjestelmä
- Laskujen hallinta ja seuranta
- Vuokrattujen tilojen raportointi aikajaksolla valituissa
toimipisteissä
- Ostettujen lisäpalvelujen ja vuokrattujen laitteiden raportointi aikajaksolla valituissa
toimipisteissä
- Laskutusmahdollisuudet;
    - Paperilasku
    - Sähköpostilasku (Tätä ei tarvinnut toteuttaa oikeasti, kunhan sen olemassaolo oli jotenkin ilmi käyttöliittymässä).

--- 
### Huomioita

**- Käy lisäämässä "Repository" koodiin oma yhteysdatasi, jotta ohjelma toimii.**
Ohjelma vaatii Visual Studion ja MariaDB:n toimiakseen.


- Ohjelma poistaa ja luo uuden tietokannan joka ajon yhteydessä, tämä oli myös harjoitustyön vaatimuksena.

Harjoitustyö arvioitu 5 (asteikko 1-5) ja sama numeron itselleni koko kurssista.
Oma roolini työssä oli suuri projektinjohtajana, yhtenä käyttöliittymän suunnittelijana, testaajana, Azuren ylläpitäjänä, sekä koodasin ja avustin muita.
Työhön liittyi paljon suunnitelmia, dokumentaatiota, testausta, palavereja ja raportteja.

Poikkileikkaus ohjelmasta:

Ohjelman etusivu:

<img width="806" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/990514b6-71cd-480b-8c4e-5435d114bc2b">

Uuden asiakkaan lisäys:

<img width="360" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/d744a8cc-af62-435e-b727-9ef405466418">

Tilan valinta:

<img width="803" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/ffee0f10-4685-4965-96a8-c9b510e2768e">

Arvio varauksen hinnalle:

<img width="793" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/b405afb6-159f-4605-8ece-e3e9510c7170">

Varaukseen:

<img width="616" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/60879ddf-86ba-4c98-b744-248913c0f3d7">

Lisäpalveluiden lisäys ja valinta:

<img width="614" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/5c5d79d1-26ad-414d-9ce2-67a05d3484bf">

Vahvistetaan laskun tallennus:

<img width="616" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/8fea2a2a-53d3-41bb-b9c9-55d4d0b49c49">

Laskuja voi hallita valitsemalla asiakas ja sen lasku:

<img width="615" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/0449343c-d259-47a7-ab9d-10fe1abebb86">

<img width="614" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/cc653ae8-c360-4b46-9913-8a1fe065fbfe">

Kaikki laskut on alasvetovalikossa:

<img width="614" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/d6f7abb1-2e94-4c5e-be05-13e75d2a1a96">

Laskua voi muokata, vaihtamalla asiakasta, tilaa, varauksen ajankohtaa, lisäpavleluita. Esimerkiksi tilan vaihdosta tulee varmistus:

<img width="615" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/ddd8e1d5-0f51-4ded-a6d8-78e17fc17d86">

<img width="613" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/d58b63d1-8dd8-41b7-befa-1e3e40c505f8">

ASIAKASREKISTERI
Asiakkaita voi hakea, lisätä, muokata ja poistaa.

<img width="593" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/9027e2bf-398d-4986-9d41-26540a29d695">

Lisää uusi asiakas:

<img width="360" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/007135c4-f082-4931-9f6d-13a71f87fc17">

Päivitä asiakas:

<img width="362" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/14ebd036-3143-4f54-9d8a-2c7cfb65b3ab">

LISÄPALVELUT

Lisäpalveluita voi hallinnoida, muokata, lisätä, poistaa, hakea

<img width="396" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/a3c3c5f1-2055-40b9-a159-5b46b8686451">

<img width="393" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/a3a8221d-a35d-4b65-a554-04535687ee24">

Lisäys:

<img width="294" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/bc342414-0fcc-41a5-a958-1c6489f407f5">

Muokkaus:

<img width="239" alt="image" src="https://github.com/hennojala/Toimistotilojen-varausjarjestelma/assets/108032404/bd471457-87c0-41a3-bedb-bde7de09f944">





