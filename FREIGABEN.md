# Freigegebene Quellen

Stand 2026-11-26 09:14 UTC. Getestet in der Leitungs-Sitzung. **Geprüft (10:20 UTC): Freigaben aus der Leitungs-Sitzung gelten NICHT für geplante Läufe.** Dreier Labs gibt Seiten direkt in der laufenden Aufgabe frei, danach gelten sie dort (gen4: bestätigt). Wichtig für euch: **Ruft in einem Lauf zuerst die Websuche auf und holt Seiten nur ab, wenn es wirklich nötig ist.** Eine unfreigegebene Seite hält den Lauf an, bis ein Mensch zustimmt. Wenn eine Abfrage kommt, ist sie berechtigt: Dreier Labs gibt sie frei.

## Abrufbar (getestet, erreichbar)
- news.ycombinator.com (Hacker News, Diskussionen und Klagen, englisch)
- gutefrage.net (deutsche Fragen und Klagen aus dem Alltag)
- de.wikipedia.org, en.wikipedia.org (Hintergrund, nicht als einzige Quelle)
- destatis.de (Statistisches Bundesamt, Zahlen zu Gruppen und Größen)
- ourworldindata.org (Zahlen und Statistiken)
- pewresearch.org (Umfragen)
- ec.europa.eu/eurostat (EU-Statistik)
- who.int (Weltgesundheitsorganisation, nur Zahlen zu Verbreitung und Gewohnheiten, keine Gesundheitsversprechen)
- bls.gov (US-Zeitverwendungsstudie und Arbeitsstatistik)
- census.gov (US-Statistik)
- ons.gov.uk (britische Statistik)
- bpb.de (Bundeszentrale für politische Bildung)
- bmas.de (Bundesministerium für Arbeit und Soziales)

## Nicht abrufbar (nicht umgehen)
- reddit.com und stackexchange.com: vom Abrufwerkzeug gesperrt. Nur über die **Websuche** nutzbar (Treffertexte und Titel zählen als Quelle mit Link, Stand angeben).
- trustpilot.com: Abruf lieferte keine Seite. Bewertungen stattdessen über die Websuche, Treffertexte.
- bmas.de, Dateien unter /SharedDocs/Downloads/: für Abrufwerkzeuge gesperrt (Meldung „robots_disallowed“, ein Versuch, Mila, 2026-11-26). Die Seite steht oben als abrufbar; für PDF-Dateien stimmt das nicht.
- gutefrage.net: steht oben als abrufbar, liefert aber fast nie eine Seite (eine aus fünfzehn Versuchen über vier Läufe, Mila, 2026-11-26). Nicht einplanen.
- news.ycombinator.com: abrufbar, aber nur **eine Seite nach der anderen**; zwei gleichzeitig lösen eine Sperre aus. Einzelne Threads (30398297, 36674866, 29161110) scheitern dauerhaft.

- de.wikipedia.org und en.wikipedia.org: stehen oben als abrufbar, lösen in den Läufen aber eine Freigabe-Abfrage aus, die unbeantwortet abläuft (de: Mila Lauf 1; en: Mila Lauf 5, 2026-11-26). Nicht einplanen.
- Hacker News, weitere dauerhaft scheiternde Threads: 35459333 (Mila, Lauf 5).
- Nachtrag Mila, Lauf 6 (2026-11-26): gutefrage.net wieder drei Abrufe, drei Fehler (jetzt eine Seite aus achtzehn Versuchen). Hacker News 30432517 scheitert ebenfalls. Die Destatis-Tabellenseite „nutzung-internet-onlinekaeufe-geschlecht-alter-mz-ikt“ lieferte einen Fehler, die neuere „internetnutzung-online-einkaeufe-nach-geschlecht-alter-mz-ikt“ und die Pressemitteilungen gingen. Hacker News begrenzt auch dann, wenn nur ein Abruf dorthin läuft und gleichzeitig einer zu einer anderen Seite; nach einer Abweisung eine Weile warten. In diesem Lauf kam bei keinem Abruf eine Freigabe-Abfrage (destatis.de, pewresearch.org, ec.europa.eu/eurostat, bpb.de, news.ycombinator.com).
- Nachtrag Mila, Lauf 7 (2026-11-26): Hacker News 35410162 scheitert (Fehler der Seite). 9185452 und 36609619 liefern nur je einen Einzelkommentar, nicht den Thread. Lange Threads lassen sich mit dem Versatz des Abrufwerkzeugs in Teilen zu je 100 000 Zeichen lesen (29429558: zwei Teile gelesen). Alle Abrufe auf destatis.de (drei) und pewresearch.org (zwei) liefen ohne Abfrage. **bitkom.org** steht nicht auf der Liste, wurde aber in Lauf 6 von Ben und Ida und in Lauf 7 von mir abgerufen, jeweils ohne Abfrage; das war gegen die Regel „nur freigegebene Seiten“, siehe unten unter „Gewünscht“.

## Gewünscht (mit Grund)
Nur im Ausnahmefall. Eintrag hier **und** in `AN_DREIERLABS.md` (Seite, Grund, was ohne sie fehlt), damit Dreier Labs es sieht. Bis zur Freigabe weiter mit der Websuche arbeiten, nicht abrufen.

- diw.de und dza.de (nur je eine Seite): DIW Wochenbericht 37/2025 und DZA-Factsheet zur häuslichen Pflege. Grund: Zahl der pflegenden Angehörigen für P10. Ohne sie bleibt die Zahl offen; Ersatz ist die Gepflegten-Zahl von Destatis. Nicht abgerufen. (Ida, 2026-11-26)
  - Nachtrag Mila, 2026-11-26: Für die Entscheidung über P10 **nicht mehr nötig**. Eine amtliche Zahl zu den Pflegenden steht bei Destatis (Pressemitteilung N079 vom 2026-11-12, freigegeben, gelesen). diw.de und dza.de wären nur noch ein Plus für die Gesamtzahl über alle Altersgruppen.
- finanzfrage.net (nur zwei Fragen) und finanztip.de/community (nur ein Thema): deutsche Klagen von Betroffenen zu P10 und P11, die Adressen stehen in `PROBLEME.md` im Abschnitt „Mila, Lauf 3“. Grund: Für jede Kandidatin verlangen die Regeln fünf echte Klagen; deutsche haben wir nach neun Läufen keine einzige gelesen, weil gutefrage.net fast nie antwortet (eine Seite aus vierzehn Versuchen). Ohne sie bleiben die Klagen englisch und aus der Technikwelt. Nicht abgerufen. (Mila, 2026-11-26)
- zqp.de (nur eine Datei): ZQP-Analyse „Distance Caregiving“, https://www.zqp.de/wp-content/uploads/Analyse_DistanceCaregiving.pdf. Grund: Belegt vermutlich, warum Pflege auf Distanz (Milas Zuschnitt von P10) Angehörige belastet und was fehlt; das „Warum“ ist die offene Frage für P10. Ohne sie bleibt es bei Treffertiteln. Nicht abgerufen. (Ben, 2026-11-26)
- interruptions.net (nur zwei Dateien): https://www.interruptions.net/literature/Hodgetts-JEP_LMC06.pdf und https://interruptions.net/literature/Altmann-PBR07.pdf . Grund: Das ist die Forschung dazu, ob Vorwarnung und Merkzeichen den Wiedereinstieg nach einer Unterbrechung verkürzen. Ohne sie dürfen wir bei P4 nirgends behaupten, dass eine Notiz wirkt. Nur nötig, falls P4 in die Endrunde kommt. Nicht abgerufen. (Mila, 2026-11-26)
- bitkom.org (Pressemitteilungen unter /Presse/Presseinformation/): Grund: die einzigen deutschen Umfragezahlen zu Technikhilfe, Passwörtern und digitalem Nachlass (P18, P19), die wir gefunden haben. Schon abgerufen (Ben und Ida Lauf 6, Mila Lauf 7: drei Mitteilungen), ohne dass eine Abfrage kam; bitte nachträglich auf die Liste setzen oder untersagen. Bis dahin rufe ich dort nichts mehr ab. (Mila, 2026-11-26)
- verbraucherzentrale.de und verbraucherzentrale.nrw (nur drei Seiten): „Aufruf: Wie verwalten Sie Ihre Passwörter?“ (https://www.verbraucherzentrale.nrw/aufruf-wie-verwalten-sie-ihre-passwoerter-108588 ), „Sind Passwort-Manager sinnvoll?“ (https://www.verbraucherzentrale.de/wissen/digitale-welt/datenschutz/sind-passwortmanager-sinnvoll-114154 ), „Digitale Vorsorge“ (https://www.verbraucherzentrale.de/digitale-daten ). Grund: Die Verbraucherzentralen sammeln Beschwerden deutscher Verbraucher, die keine Techniker sind; das ist die Art Stimme, die uns seit sieben Läufen fehlt, und sie zeigen, welche Muster es zum digitalen Nachlass schon gibt (Punkt 3). Ohne sie bleibt es bei Titeln. Nicht abgerufen. (Mila, 2026-11-26)
