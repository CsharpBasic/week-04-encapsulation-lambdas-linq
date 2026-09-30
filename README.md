# Week 4 — Innkapsling, Lambda-utrykk og LINQ

Denne uken starter med eierskap til tilstand og referanseatferd før vi går over til å sende inn oppførsel med delegates/lambdas og spørre collections med LINQ. Til slutt refaktoreres en monolittisk console-app til tydeligere lag.

## Oppgaver

01. **Specimen Vault** — private state og kontrollert modifikasjon
02. **The Leaking Collection** — intern collection vs kopi
03. **The Shallow Copy Surprise** — referansetyper inne i collections
04. **Rule Runner** — delegates og Func<T, bool> med named method
05. **Anonymous Rules** — single-expression lambdas
06. **Complex Scanner Rule** — multi-line lambda
07. **Artifact Projection** — LINQ Select
08. **Archive Filter** — LINQ Where
09. **Archive Questions** — LINQ Any og Count
10. **Archive Ordering** — OrderBy + chaining
11. **Reusable Search Engine** — delegate/lambda som innsendt atferd
12. **Refactor the Observatory** — lagdelt struktur / MVC-intro

Hver oppgave er et selvstendig .NET 10 console-prosjekt. En feil i én oppgave påvirker ikke de andre.

## Bruk av KI

Du kan gjerne bruke KI-verktøy som er integrert i kodeeditoren din dersom du trenger hjelp til å komme i gang, forstå en feilmelding eller står fast underveis.

I hver oppgave ligger det en `AGENTS.md`-fil med instruksjoner til KI-verktøyet. Hensikten er at KI-en skal fungere som en veileder: den kan hjelpe deg med å forstå problemet, stille spørsmål, forklare konsepter og gi hint, men skal ikke løse oppgaven for deg eller skrive ferdig løsningen.

Målet er at du selv skal få øvd på programmeringen og forstå hvorfor løsningen fungerer.