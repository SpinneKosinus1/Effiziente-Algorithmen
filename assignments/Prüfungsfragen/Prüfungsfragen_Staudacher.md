# Prüfungsfragen (Staudacher)
## Asymptotik & Grundlagen
### Landau-Symbole

1. Was bedeuten O, o, Θ?
2. Unterschied zwischen O und Θ?
3. Warum verschwinden Konstanten?
4. Warum betrachtet man asymptotisches Verhalten?

### Entscheidungsprobleme

1. Was ist ein Entscheidungsproblem?
2. Warum lassen sich Entscheidungsprobleme als boolesche Funktionen auffassen?
3. Warum werden Eingaben binär codiert?
4. Zusammenhang zwischen Eingabelänge und Laufzeit?

## Berechenbarkeit & Modelle
### Berechnungsmodelle

1. Was ist ein computational model?
2. Warum spielt das konkrete Modell für Komplexitätsklassen keine Rolle?

### Church-Turing-These

1. Aussage der Church-Turing-These
2. Warum ist sie nicht beweisbar?
3. Bedeutung für die Informatik

### Halteproblem

1. Was ist gegeben, was ist gesucht?
2. Warum ist das Halteproblem unentscheidbar?
3. Warum reicht „Simulation“ nicht aus?

## Komplexitätsklassen P und NP
### Klasse P

1. Definition von P
2. Bedeutung von „effizient lösbar“
3. Beispielproblem aus P (Eulerkreis)

### Klasse NP

1. Definition von NP
2. Was bedeutet „polynomiell verifizierbar“?
3. Was ist ein Lösungskandidat?

### Kurze Zertifikate

1. Was ist ein Zertifikat?
2. Warum sind Zertifikate in NP kurz?
3. Beispiel: CLIQUE, Hamiltonkreis

## P vs. NP

1. Formulierung der P-vs-NP-Frage
2. Was ist das Entscheidende an dieser Frage?
3. Bedeutung für:

   - Kryptographie
   - Optimierungsprobleme
   - Praxis allgemein

4. Konsequenzen, falls P=NP P=NP
5. Warum ist die Frage offen?

## Reduktionen & Vollständigkeit
### Polynomialzeit-Reduktionen

1. Definition
2. Wozu dienen Reduktionen?
3. Bedeutung für Schwierigkeit von Problemen

### NP-hart & NP-vollständig

1. Definition NP-hart
2. Definition NP-vollständig
3. Unterschied 
4. Beispiele aus:

    - Graphentheorie
    - Aussagenlogik

### Cook-Levin-Theorem

1. Aussage
2. Bedeutung für NP-Vollständigkeit

## Klassische Graphenprobleme
### Eulerkreis & Eulerweg

1. Definition Eulerkreis
2. Entscheidendes Kriterium
3. Warum in P?
4. Haus vom Nikolaus:

   - Warum kein Eulerkreis? 
   - Warum Eulerweg?

### Hamiltonkreis

1. Definition
2. Warum in NP?
3. Unterschied zum Eulerkreis
4. Warum kein strukturelles Kriterium bekannt?

## Reduktionen zwischen Graphproblemen

1. Definition:

    - Clique
    - Independent Set
    - Vertex Cover

2. Reduktionsideen

    - Clique → Independent Set (Komplementärgraph)
    - Vertex Cover → Independent Set (Restgraph)

3. Warum reicht die Idee, nicht der Beweis?

## coNP

1. Definition von coNP
2. Warum geht es um Nichtexistenz?
3. Warum ist coNP „unangenehmer“ als NP?
4. Warum gibt es keine kurzen Zertifikate?
5. Beispiel:

    - Hamiltonkreis in NP vs. coNP 

6. coNP-vollständige Probleme 
    - Beispiel: Tautologie

## Ladner-Theorem & Klassenhierarchie

1. Aussage des Ladner-Theorems
2. Was muss gelten, damit es zutrifft?
3. NP-intermediate Probleme
4. Beispiel: PPAD
5. „Weltsicht“ unter der Annahme $P⊊NP$
6. Existieren Probleme außerhalb von EXP?

## Spieltheorie: Grundlagen
### Spiele & Strategien

1. Reine vs. gemischte Strategien
2. Bimatrixspiele lesen
3. Dominierte vs. dominante Strategien

### Dominanzbegriffe

1. Stark dominante Strategie
2. Schwach dominante Strategie
3. Risikodominante Strategie
4. Unterschiede & typische Beispiele

## Nash-Gleichgewicht

1. Definition Nash-GG
2. Warum zentrales Lösungskonzept?
3. Existenz
4. Nash-GG vs. Pareto-Optimum
5. Beispiele:
   - Gefangenendilemma
   - Schotterspiel 
   - Hirschjagd 
     - Nash-GGs 
     - Warum (1,1) risikodominant ist

## Spezielle Spiele
### Schach

1. Spieltyp
   - Nullsummenspiel
   - Perfekte Information

2. Minimax-Prinzip
3. Nash-GG in reinen Strategien

### Wahr/Falsch-Fragen

1. Aussagen zu Dominanz
2. Aussagen zu Nash-GG
3. Aussagen zu Pareto-Optimalität (Begründung, keine Rechnungen)

## Auktionen & Mechanismusdesign
### Zweitpreisauktion (Vickrey)

1. Ablauf 
2. Nash-GG 
3. Schwach dominante Strategie 
4. Offenbarungsprinzip

### Weitere Begriffe

1. Winner’s Curse 
2. Bidder Collusion 
3. Revenue Equivalence Theorem (Idee)
4. Einordnung von Ebay

## Anwendungen der Spieltheorie

1. Warum relevant für Informatik?
2. Beispiele
   - Netzwerke
   - Auktionen
   - Routing
3. Braess-Paradoxon
   - Erklärung 
   - Bedeutung

## Dynamische Programmierung & Rekursion

1. Grundidee dynamischer Programmierung 
2. Überlappende Teilprobleme 
3. Bottom-Up vs. Top-Down 
4. Rekursionen mit/ohne Kardinalität

## Subset Sum & Pseudopolynomielle Algorithmen

1. Definition Subset Sum 
2. Entscheidungsvariante 
3. Warum pseudo-polynomiell? 
4. Einsatz in der Kryptographie

## Machtindizes & Abstimmungsspiele
### Gewichtete Abstimmungsspiele

1. Definition 
2. Gewinnkoalitionen

### Banzhaf-Index

1. Idee des Index
2. Kritischer Spieler
3. Berechnung „von unten“
4. Prinzipielle algorithmische Lösung

### Banzhaf „von oben“

1. Wann sinnvoll?
2. Unterschied zur expliziten Zählung

### Weitere Machtindizes

1. Shapley-Shubik-Index
2. Unterschied zum Banzhaf-Index