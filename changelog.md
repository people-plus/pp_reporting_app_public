# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3] - 2021-03-30
### Added
- Gestione delle timbrature tramite nuovo menu "Badge"
### Changed
- La vista di menu "Calendario" mostra ora label colorate sulla base del cliente della rapportazione, anziché in relazione allo stato confermato/draft

## [1.2] - 2021-03-18
### Changed
- L'inserimento di una rapportazione senza riga di dettaglio non è più consentita
- Il grafico di trend mostra ora le informazioni relative al mese corrente, anziché alla settimana corrente
- Anche le testate e i dettagli relativi a documenti già importati sono ora modificabili. Viene visualizzato un messaggio di conferma alla modifica, specificando nel caso in cui si stia cercando di modificare un elemento già importato.

## [1.1] - 2021-03-09
### Added
- L'utente può visualizzare e gestire unicamente i propri inserimenti
- Introdotta visualizzazione delle rapportazione a calendario, da menu laterale
 ### Changed
- Le rapportazioni in stato "Confermato" possono essere modificate per tutta  la giornata in cui è stata effettuata l'ultima modifica. Successivamente, avverrà la sincronizzazione e l'inserimento non sarà più modificabile