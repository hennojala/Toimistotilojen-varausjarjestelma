# Toimistotilojen varausjärjestelmä
Ohjelmistotuotanto I -kurssin harjoitustyö, ryhmätyönä (6hlo), 5op, 2023. Tekniikat: Visual Studio, WPF(C#, XAML), MariaDB, HeidiSQL, ERDPlus(suunnittelussa), Azure DevOps (versionhallinta ja projektinseuranta).

Tämän harjoitustyön ideana oli luoda toimistotilojen varausjärjestelmä. Järjestelmään tuli pystyä lisäämään eri toimitiloja toimipisteille.
Tilojen vuokra-ajat vaihtelevat. Tilojen varauksen yhteydessä voi vuokrata laitteita ja palveluita. Vuokrattavat laitteet ja palvelut vaihtelevat toimipisteittäin, mutta ne ovat aina sidoksissa vuokrattuun tilaan ts. laitteet ja palvelut vuokrataan samalle ajanjaksolle kuin toimistotila. Järjestelmän tuli sisältää varaus- ja asiakashallintajärjestelmän, jonka tavoitteena oli mahdollistaa reaaliaikainen toimipisteiden varaustilanteen seuranta- ja raportointi. Kuviteltu yritys siis tarvitsi tietojärjestelmän, jossa on vähintään seuraavat ominaisuudet:
- toimipisteiden hallinta
- palveluiden hallinta
- toimistotilavarausten hallinta
- asiakashallintajärjestelmä
- laskujen hallinta ja seuranta
- vuokrattujen tilojen raportointi aikajaksolla valituissa
toimipisteissä
- ostettujen lisäpalvelujen ja vuokrattujen laitteiden raportointi aikajaksolla valituissa
toimipisteissä
- Laskutusmahdollisuudet;
● Paperilasku
● Sähköpostilasku (Tätä ei tarvinnut toteuttaa oikeasti, kunhan sen olemassaolo oli jotenkin ilmi käyttöliittymässä).

Tietoturvasyistä yhteysdata tietokantaan on poistettu, joten käy lisäämässä "Repository" koodiin oma yhteysdatasi, jotta ohjelma toimii.
Ohjelma poistaa ja luo uuden tietokannan joka ajon yhteydessä, tämä oli myös harjoitustyön vaatimuksena.
Ohjelmassa on pieniä puutteita, esimerkiksi koodi ei ole aina kovin johdonmukaista, paikoitellen huonosti kommentoitua ja kielessä käytetty sekaisin suomea ja englantia. Tämä osaksi sen vuoksi, että tiimissämme oli useita eritasoisia koodareita ja jokaisella oma tyyli tehdä, vaikka alussa sovimme koodauskieleksi englannin. Käyttöliittymässä myös parannettavaa, ja pieniä ongelmakohtia myös löytyy. Kaikesta huolimatta tasoon nähden jolla opiskelimme, saimme työstä arvioinniksi 5(asteikko 1-5) ja saman numeron sain itselleni myös koko kurssista.
Oma roolini työssä oli suuri, olin projektinjohtaja, käyttöliittymän suunnittelija, testaaja, Azuren ylläpitäjä, sekä koodasin ja avustin muita. Työhön liittyi paljon suunnitelmia, dokumentaatiota, testausta, palavereja ja raportteja.
