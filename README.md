# NOVA

Next documentation is in Italian because the system has been developed for an Italian public administration.

## Introduzione

Nova è il market place che il Comune di Genova ha realizzato con i fondi Pon Metro 2014 – 2020 in collaborazione con Liguria Digitale e con gli stakeholder pubblici e privati della Città Metropolitana di Genova per rendere accessibili con un click tutti i servizi necessari alla creazione ed innovazione d’impresa.

Nell’ecosistema digitale sarete orientati nella scelta di servizi per essere ancora più competitivi nei settori strategici della Città di Genova: innovazione tecnologica, industria creativa, turismo sostenibile. Il sistema di e-commerce di Nova vi permette di selezionare e accedere in tempo reale a tutti i servizi fruibili e resi disponibili dagli stakeholder aderenti al Progetto.

Nella sezione Vetrina delle Imprese potete accreditare con il vostro spid la vostra azienda iscritta nel Registro delle imprese innovative della Camera di Commercio per valorizzare e condividere i vostri prodotti, servizi, progetti e tecnologie più all’avanguardia.

Se sei un futuro imprenditore, hai una PMI Innovativa, una Spin off, una SIAVS o una grande impresa puoi incrementare il tuo business, attivare network e sinergie di co-produzione con altre organizzazioni, aggiornandoti sulle sezioni partecipative di Bacheca e Magazine.
Il sistema è stata realizzato dall'impresa [BBS S.r.l.](http://www.bbsitalia.com)

Link alle pagine relative al progetto:

[Ponmetro Comune di Genova](https://smart.comune.genova.it/ponmetro)

Accesso all'applicativo [NOVA](https://nova.comune.genova.it)


## Struttura del repository
Le principali cartelle/files usati dal repository sono

* web/modules: cartella dei moduli personalizzati dell'applicazione
* web/themes: cartella dei temi personalizzati dell'applicazione
* web/sites: cartella delle configurazioni dell'applicazione
* composer.json e composer.lock: files di configurazione del CMS Drupal

Documentazione allegata:

* [Modello database](./doc/nova_database_schema.md)
* [Manuale utente amministratore](./doc/ManualeUtenteAmministratore.md)
* [Manuale utente accreditato](./doc/ManualeUtenteAccreditati.md)
* [Manuale utente accesso libero](./doc/ManualeUtenteAccessoLibero.md)


## System requirements

L'applicazione è stata realizzata come customizzazione del CMS Open Source Drupal versione 9.
Il funzionamento è stato verificato e testato con successo sul seguente ambiente:
* [CMS Drupal 9](https://www.drupal.org)
* Sistema operativo Linux Ubuntu 22.04 LTS
* Web Server Apache 2.4
* PHP 7.4
* Mysql 8
	

## Accesso all'applicazione tramite credenziali SPID

L'accesso all'applicazione è consentito con il sistema SPID per gli utenti interni ed esterni.

La gestione dell'autenticazione è garantita dal sistema SIRAC SSO che è definito tra i service provider SPID 
(https://registry.spid.gov.it/service-providers)

Noto il CF dell'utente il sistema verifica in una tabella del DB l'appartenenza dell'utente tra quelli di sistema.


## Copyleft and License

This web page was developed starting from CMS Open Source Drupal Core and Contrib Modules

[BBS S.r.l.](https://www.bbsitalia.com) change the license to GPL v.3 (see license file attached)

This work is financed by [PON Metro 2014-2020](http://www.ponmetro.it) funding.



## Versioning

La prima versione stabile è stata creata nel febbraio 2023 all'atto dell'inserimento del SW nel catalogo del riuso.

Il progetto è stabile al netto di continue migliorie e bug detection che sono possibili attraverso l'uso dell'ambiente in produzione presso il Comune di Genova

Il soggetto detentore del software è il Comune di Genova

## Contatti

* Amministrazione proprietaria: Comune di Genova
* Contatto e-mail referente di progetto (per segnalazioni e richiesta informazioni): [gestionesistemi@comune.genova.it](mailto:gestionesistemi@comune.genova.it)
