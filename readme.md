# Git ja Git Hub


<img src="./gitjagithub.jpg" width="300">


### Mitä versiohallinnalla tarkoitetaan?
Versionhallinnalla tarkoittaa menetelmää, joka säilöö tietoa ja siihen tehtyjä muutoksia.

1. Versionhallinta mahdollistaa tiedon varmuuskopioinnin. Varmuuskopiot (*commitit*) sisältävät sekä tiedon nykyisen, että aikaisemman tilan.  
2. Versiohallinta (*GitHub:n* kautta) mahdollistaa tiedon jakamisen muille, sekä osallistumisen muiden projekteihin.

#### Mikä (Git) (https://git-scm.com) on?

*GitHub* mahdollistaa myös saman tiedon parissa työskentelyn eri tietokoneilla. Saman tiedon parissa työskennellään kuitenkin usein eri tietokoneilta 


<img src="./gitjagithub.jpg" width="300">



*GitHub* (ja myös [GitLab](https://about.gitlab.com/)) ovat palveluita, joissa voidaan pitää Git-muotoisia varastoja (*Repository*). Ne mahdollistavat tiedon jakamisen muille saman tiedon parissa työskenteleville henkilöille. *GitHub*:a olevia repositorio joka on kytketty paikalliseen Git työkansioon on ns. *remote*. *Remote* taas puolestaan tunnetaan Git komennoissa nimellä *Origin*, tosin nimi on vaihdettavissa.  


### Mikä GitHub on?
on vuonna 2008 avattu verkkosivusto, joka tarjoaa paikan Git-versionhallintaa käyttäville ohjelmakehitysprojekteille.
Git on hajautettu versionhallintajärjestelmä, joka mahdollistaa 
ohjelmakoodin hallinnan ja seurannan.

 Git tallentaa tiedostojen tilan kullekin tallennukselle ja havaitsee, mitä tietovarastossa on muuttunut. Muutokset tiedoston sisältöön muuttavat sen omaa tiivistettä, tiedoston sisältävän hakemiston tiivistettä ja tietovaraston tilaan viittaavaa tietoa

 GitHub puolestaan tarjoaa käyttöliittymän ja tallennuskapasiteetin Gitillä hallittuihin tietovarastoihin (engl. repository). Sen avulla voit ladata lähdekoodia, seurata bugeja, hallita kehitystoiveita ja tehtäviä sekä luoda wikisivuja. GitHub tarjoaa palvelunsa ilmaiseksi julkisesti nähtävillä oleville tietovarastoille, ja yksityiset tietovarastot ovat myös mahdollisia rajoitetuilla ominaisuuksilla


<img src="./github.jpg" width="300">


### Git työskentely:


Git versiohallinnan ottaminen käyttöön työkansiossa: git init
Git käyttäjänimen määrittäminen: git config user.name "etunimi sukunimi"
Sähköpostiosoitteen määrittäminen: git config --global user.email "erkki.esimerkki@example.com"
Git tietojen näyttäminen: git config --list --global

Git haarojen listaaminen: git branch
Uuden haaran lisääminen: git branch haaran_nimi tai git checkout haaran_nimi
Haaran tietojen yhdistäminen master päähaaraan: git merge haaran_nimi
Haaran poistaminen: git branch -d uusibranch

