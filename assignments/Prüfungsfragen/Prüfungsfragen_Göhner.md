# Prüfungsfragen (Göhner)

## Graphen

### Grundbegriffe & Aufbau von Graphen

1. Wie definieren Sie einen gerichteten Graphen? Nennen Sie die Mengen V und E und erklären Sie, was „adjazent“ bedeutet.
2. Worin unterscheiden sich gerichtete und ungerichtete Graphen? Welche Eigenschaften müssen ungerichtete Kanten erfüllen?
3. Was ist ein gewichteter Graph? Nennen Sie Beispiele aus der Praxis.
4. Beschreiben Sie die Menge der Knoten und Kanten in einem vorliegenden Graphen.
5. Was ist ein Pfad? Was ist ein Zyklus? Was ist ein einfacher Pfad?

### Zusammenhang & Komponenten

1. Erklären Sie Zusammenhangskomponenten in ungerichteten Graphen. Wie erkennt man sie
2. Was verstehen Sie unter starker und schwacher Zusammenhangskomponente in gerichteten Graphen?
3. Was bedeutet zweifach zusammenhängend? Was ist ein Artikulationspunkt?

### Darstellung von Graphen

1. Wie kann ein Graph abgespeichert werden? Beschreiben Sie Adjazenzmatrix und Adjazenzliste.
2. Welche Vor- und Nachteile hat eine Adjazenzmatrix?
3. Was ist eine kantenorientierte Darstellung? Wann ist sie sinnvoll?
4. Was ist ein „dichter“ und was ein „dünner“ Graph? Warum ist das relevant?

### Topologisches Sortieren

1. Erklären Sie das topologische Sortieren. Was bedeutet es, eine totale Ordnung aus einer Halbordnung zu erzeugen?
2. Welche Voraussetzung muss ein Graph erfüllen, damit topologisches Sortieren möglich ist?
3. Beschreiben Sie das Prinzip des Algorithmus zum topologischen Sortieren anhand eines Beispiels.

## Kürzeste Wege

### Dijkstra & A\*

1. Erklären Sie den Dijkstra-Algorithmus und seine drei Kategorien von Knoten. (innere / Randknoten / äußere)
2. Warum funktioniert Dijkstra nur mit nichtnegativen Kantengewichten?
3. Erklären Sie den A\*-Algorithmus. Welche Rolle spielen g(u), h(u) und f(u)?
4. Was unterscheidet A\* vom Dijkstra-Algorithmus?
5. Welche Eigenschaften muss eine Heuristik bei A\* haben? Erklären Sie Zulässigkeit und Monotonie.
6. Wie berechnet man die A\*-Heuristik in einem konkreten Beispiel?
7. Was passiert, wenn die Heuristik nicht zulässig oder nicht monoton ist?
8. Wie wird die OPEN-Liste effizient implementiert und warum nutzt man einen Heap?
9. Wie laufen beim A\* die ersten beiden Iterationen ab? Beschreiben Sie sie für ein gegebenes Beispiel.

### Floyd–Warshall

1. Erklären Sie den Floyd-Algorithmus zur Berechnung aller kürzesten Wege.
2. Was ist die zugrunde liegende DP-Formel von Floyd?
3. Warum funktioniert Floyd auch mit negativen Gewichten?
4. Was ist der Unterschied zwischen dem Floyd-Algorithmus und dem Warshall-Algorithmus?
5. Was ist die transitive Hülle eines Graphen—und wie berechnet der Warshall-Algorithmus diese?

## Minimum Spanning Tree

### Definitionen

1. Was ist ein Spannbaum?
2. Was ist ein minimaler Spannbaum? Warum ist dieser eindeutig oder auch nicht?

### Prim-Algorithmus

1. Erklären Sie den Prim-Algorithmus. Welche Datenstrukturen werden typischerweise genutzt?
2. Was sind die Vorteile des Prim-Algorithmus gegenüber Kruskal?

### Kruskal-Algorithmus

1. Erklären Sie den Kruskal-Algorithmus. Wie verhindert man Zyklen?
2. Welche Nachteile hat Kruskal?
3. Führen Sie beide Algorithmen Schritt für Schritt an einem kleinen Beispiel aus.

### Vergleich

1. Wann ist Prim effizienter, wann Kruskal?
2. Welchen Einfluss hat die Graphdichte auf die Wahl des Algorithmus?

## Flüsse

### Grundlagen

1. Was ist ein Netzwerk? Erklären Sie Quelle, Senke, Kapazität und Fluss.
2. Was ist das Restnetzwerk und was sind Rückkanten?
3. Erklären Sie den Begriff Erweiterungspfad.

### Ford–Fulkerson

1. Wie funktioniert der Ford-Fulkerson-Algorithmus?
2. Warum kann Ford-Fulkerson bei irrationalen Kapazitäten nicht terminieren? (klassische Zusatzfrage)
3. Wie sieht die Komplexität von Ford-Fulkerson aus?

### Min-Cut Max-Flow Theorem

1. Formulieren und erklären Sie den Satz von Max-Flow–Min-Cut.
2. Wie erkennt man einen minimalen Schnitt in einem konkreten Netzwerk?
3. Wo setzen Sie Schnitte im Flussdiagramm, und was haben Rückkanten damit zu tun?

### Edmonds-Karp / Dinic

1. Was verändert Edmonds-Karp an Ford-Fulkerson?
2. Was ist ein Niveaunetzwerk im Dinic-Algorithmus?
3. Erklären Sie den Begriff Sperrfluss.

## Suchen & weitere Algorithmen

1. Nennen Sie drei Suchalgorithmen auf Graphen.
2. Erklären Sie einen der Suchalgorithmen