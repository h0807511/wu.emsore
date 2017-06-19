---
output: 
  pdf_document:
    citation_package: natbib
    #keep_tex: TRUE
    #fig_caption: TRUE
    number_sections: TRUE
    #toc: TRUE
    latex_engine: pdflatex
    #template: latex_template.tex
title: "Zur Wahrnehmung und Einstellung von WU-Studierenden gegenüber Fremden"
author: Boris Podzeit, Yasir Khan
#keywords: ""
#bibliography: literatur.bib
#biblio-style: apsr
endnote: no
---


\begin{center}
\vspace{5mm}
Forschungsarbeit für die Kurse\\
Methoden der empirischen Sozialforschung I und II \par
\vspace{5mm}
Wirtschaftsuniversität Wien\\
Sommersemester 2017
\vfill
\textit {Letztes Update: 19. Juni 2017}
\end{center}
\clearpage

\begin{abstract}
Im vorliegenden Paper wird überprüft, ob die Ausprägung von Fremdenfeindlichkeit bei WU StudentInnen mit dem persönlichen und universitären Umfeld, mit dem Konsum bestimmter Medien und persönlichen Merkmalen (Geschlecht) in Zusammenhang steht. Die Daten wurden mittels schriftlichem Fragebogen bei +100 Studenten der WU Wien erhoben. Es konnte gezeigt werden dass, bla bla männliche Studenten ein signifikant höheres Mass an ausländerfeindlicher Einstellung aufweisen als weibliche Studenten. Die Befragten, die freundschaftlichen Kontakt zu Personen mit Migrationshintergrund pflegen, wiesen unabhängig vom Geschlecht ein signifikant geringeres Mass an Fremdenfeindlichkeit auf als jene, die keinen Kontakt zu Personen mit Migrationshintergrund hatten. 
\end{abstract}

\renewcommand*\contentsname{Inhaltsverzeichnis}
\tableofcontents

## Tabellenverzeichnis
Tabellenverzeichnis hierher

## Abbildungsverzeichnis
Abbildungsverzeichnis hierher

## Datenauszug

Ein Auszug der Daten ist im Anhang zu finden

```r
fragebogen <- read.csv("./data.csv")
nrow(fragebogen)
```

```
## [1] 101
```

```r
# summary(fragebogen)
```

## Fragebogen

Der Fragebogen ist im Anhang zu finden


\clearpage

\section{Fremdenfeindlichkeit als Thema}

## Warum das Thema Fremdenfeindlichkeit?
Fremdenfeindlichkeit und Migration ist besonders in den letzen beiden Jahren ein heiß diskutiertes Thema geworden. Die Gründe für Fremdenfeindlichkeit mögen auf den ersten Blick durch Zuwanderung und die damit einhergehende Änderung demographischer Verhältnisse verursacht worden sein, eine grosse Rolle spielt jedoch die Wahrnehmung von Fremden und die damit einhergehenden Gefühlslagen der Menschen. Diese Entwicklung macht es notwendig zu verstehen welche Faktoren für die Entstehung, Verbreitung und Verfestigung von Fremdenfeindlichkeit verantwortlich sind, denn Ausländer (auch Deutsche, Schweizer, ..) haben häufig mit Diskriminierung zu kämpfen. In demokratischen Staaten kann jedoch nur die Gleichberechtigung aller das Ziel sein und daher ist es notwendig, Mittel und Wege zu erforschen um ein besser integriertes Zusammenleben zu ermöglichen. 

Mit dem Thema der Wahrnehmung von Fremden die Ursachen für die Entstehung von Stereotypen haben sich unzählige Arbeiten beschäftigt. Die Entstehung von Ängsten gegenüber Fremden wird von Stolz (2000) folgendermassen kategorisiert: 

* Konkurrenz um Wohlstand, Marktposition und Statussymbole
* Konkurrenz Raum und infrastruktur
* Konkurrenz um gemeinschaftliche Solidarität und Leistungen
* Bedrohung von Sicherheit und Eigentum
* Probleme in der Interaktion
* Bedrohung von Kultur, Gemeinschaft und sozialem Frieden



## Der Begriff der Fremdenfeindlichkeit

Fremdenfeindlichkeit ist ist die negative Bewertung von Menschen, die bestimmte  charakterisierende Eigenschaften aufweisen wie beispielsweise Hautfarbe, Sprache oder kulturelle Praktiken. Menschen mit abweichenden Eigenschaften werden als fremd identifiziert und als nicht zur Eigengruppe zugehörig empfunden. Fremdenfeindlichkeit wird fälschlicherweise gemeinhin mit Ausländerfeindlichkeit gleich gesetzt - doch das stimmt nicht. Wörtlich genommen, bezeichnet Ausländerfeindlichkeit die Angst vor einer Person die aus einem anderen Land stammt. Fremdenfeindlichkeit hingegen die Angst vor Menschendie anders sind. Xenophobie bezeichnet eher eine Persönlichkeitsstörung bei der die Angst im Vordergrund steht. In der vorliegenden Arbeit und im Fragebogen wird mit dem Begriff Ausländerfeindlichkeit gearbeitet. 


## Mögliche Einflussfaktoren

Hierher Text persönliches Umfeld (Stichwort Kontakthypothese), persönliche Merkmale (Männer eher fremdenfeindlich? -> rechte Aufmärsche, Gewalttaten), Bildungsniveau

Auch das Bildungsniveau spielt eine Rolle bei der Entstehung von Fremdenfeindlichkeit, denn Bildung gilt als wichtiger Faktor für die Vermittlung von demokratischen Gedanken und Werten. Aber ist Immunität von Höhergebildeten gegenüber menschenfeindlichen Ideologien zwangsläufig gegeben? Aktülle Wahlanalysen in Deutschland zeigen beispielsweise, dass AfD-Wähler in allen Wählerschichten zu finden sind. Der negative Zusammenhang von Bildung und Fremdenfeindlichkeit gilt offenbar nicht in allen Kontexten (Susanne Rippl, 2016). Höhher gebildete haben jedoch meist stärkere kognitive Fähigkeiten; komplexe gesellschaftliche Zusammenhänge werden gedanklich durchdrungen, Vorurteile zur Kompensation sind dann nicht notwendig. Niedrige Bildungsgrade führen hingegen eher zu geringeren Anpassungsgraden. Sozialer Wandel fährt in dieser Gruppe zu vermehrten Sicherheitsstreben und der Beschwörung der Eigengruppe  (Citation needed). 

## Hypothesen
+-------+----------------------------------------------------+--------------------+
| Nr.   | Hypothese                                          | Dimension          |
+=======+====================================================+====================+
| 1     | LeserInnen von Gratiszeitungen sind AusländerInnen |                    |
|       | gegenüber eher negativ eingestellt.                |                    |
+-------+----------------------------------------------------+--------------------+
| 2     | Extrovertierte Menschen haben eine positivere Wahr-|                    |
|       | nehmung von Migranten als introvertierte Menschen. |                    |
+-------+----------------------------------------------------+--------------------+
| 3     | Je mehr Menschen im persönlichen Umfeld (Freunde,  |                    |
|       | Familie) ausländerfeindlich sind, umso negativer   |                    |
|       | ist die eigene Haltung gegenüber AusländerInnen.   |                    |
+-------+----------------------------------------------------+--------------------+
| 4     | Je höher die Zufriedenheit der Studenten mit der   |                    |
|       | Diversität der Studierenden auf der Wirtschafts-   |                    |
|       | univiersität, umso positiver die eigene Haltung    |                    |
|       | gegenüber AusländerInnen.                          |                    |
+-------+----------------------------------------------------+--------------------+
| 5     | Je mehr Kontakt zu ausländischen Mitbürgern be-    |                    |
|       | steht, desto besser sind die Einstellungen Aus-    |                    |
|       | länderInnen gegenüber.                             |                    |
+-------+----------------------------------------------------+--------------------+
| 6     | Männer sind fremdenfeindlicher als Frauen.         |                    |
+-------+----------------------------------------------------+--------------------+

\begin{center}
\textit{Tabelle 1: Übersicht der Hypothesen}
\bigskip
\end{center}

\section{Forschungsdesign und Methode}

Die im Kurs ausgearbeiteten Hypothesen sollen in dieser Arbeit empirisch geprüft werden. Bei der Ausarbeitung der Hypothesen wurde im Vorfeld von allen Beteiligten besonders bei der Abfrage der Fremdenfeindlichkeit mit verschiedenen Zugangsmöglichkeiten experimentiert. (Beispiele, Thematisieren Absprung Kollege)

## Befragung

Die Befragung wurde schriftlich und im Zeitraum vom 10.5. bis 22.5. mittels Fragebogen bei insgesamt 101 Studierenden der Wirtschaftsuniversität Wien durchgeführt. Die Befragten waren ausschliesslich Studenten und Studentinnen der WU. Bei der Ausgabe des Fragebogens wurde die Frage gestellt "Bist du Student der WU?" um andere Studierende auszuschliessen. Auf eine Unterscheidung nach Studiengang (Bachelor, Master PhD) wurde verzichtet. Die Fragebögen wurden am Campus in den Gebäuden D2 und TC bei den für die Studenten vorgesehenen Lernplätzen und -räumen verteilt. Die Grundgesamtheit besteht daher aus allen Studierenden der WU. 

Die Bereitschaft den Fragebogen auszufüllen war generell hoch, besonders als das Thema "Migration" erwähnt wurde. Den Beobachtungen zufolge nahmen sich die meisten Personen ausreichend Zeit (> 5 min.) den Fragebogen zu beantworten In einigen Fällen gab es von den Personen mündliches oder schriftliches Feedback zum Design aber auch zur inhaltlichen Natur des Fragebogens: 

* Rechtschreibfehler (1x)
* einen Vorschlag die Bezeichnung der Likert-Blöcke auf der folgenden Seite zu wiederholen (1x)
* die Nachfrage den Endbericht zuzuschicken (2x)
* Vorschläge zur Erweiterung und eigenen Gedanken (1x, FB Nr. 83)
* Nachfragen zum Verständnis (v.a. bei der Definition von AusländerInnen, Begleittext Frage 4)
* in ~5 Fällen wurden bereits angekreuzte Items wieder ausgebessert (Beispiel: FB Nr. 95/F5, F6)

Der Fragebogen wurde durchgehend und ohne Änderung bei allen Personen ausgegeben. Die Ausnahme bildet der Rechtschreibfehler der zu einer einmaligen Korrektur des Fragebogens führte (ab ~ Nr. 75 FB). 

Im Vorfeld wurde ein einmaliger Pretest mit 3 Personen durchgeführt um Feedback zur Qualität des Fragebogens zu erhalten. Der Test hat zu Anpassungen und Präzisierungen bei der Fragenformulierung geführt. Das grundlegende Design wurde positiv aufgenommen. Alle Testpersonen sind in keinem persönlichen Naheverhältnis zueinander oder mit den Durchführenden gestanden.


## Fragebogen

In ausgedruckter Form besteht der Fragebogen aus 4 A4-Seiten und umfasst 7 Fragen die grossteils mit Hilfe von Item-Batterien in Form von Likert-Skalen erhoben wurden. Die der Likert-Skala zugrunde liegenden Intervallskala waren sechsstufig. Die Antwortmöglichkeiten waren die beiden Extrempole "Trifft sehr zu" (1) und "Trifft gar nicht zu" (6) mit  dazwischenliegenden Werte die mit Zahlen (2,3,4,5) ohne Beschriftung angegeben worden sind um einerseits den Fragebogen optisch nicht zu überladen und andererseits subjektiv wahrgenommene Unterschiede bei Abstufungen in Textform zu vermeiden.

## Variablen

Allen Hypothesen liegt die gleiche abhängige Variable (AV) zugrunde, diese lautet: "Ausmaß der Fremdenfeindlichkeit". Es wird der Einfluss verschiedener Faktoren auf die Stärke der Fremdenfeindlichkeit untersucht. Aus diesem Grund wird dieselbe AV in der Untersuchung aller Hypothesen zur Verwendung kommen. Die unabhängigen Variablen (UV) sind passend zur Fragestellung für jede Hypothese unterschiedlich gewählt. (erklärung welche metrische, kategoriale)


\section{Der Datensatz}

## Kodierung

Beschreibung der Kodierung


## Datenkontrolle 

Da es in der Praxis oft vorkommt dass beim Ausfüllen des Fragebogens nicht alle Fragen beantwortet wurden oder Fehler bei der Übertragung passieren, wird eine Datenkontrolle durchgeführt um ungewöhnliche Fälle aufzuspüren und 'missing values' (NAs) festzustellen. Einen Auszug des gesamten Datensatzes ist im Anhang zu finden. 

### Missing values

Die Prüfung des Datensatz ergibt eine auffällige Häufung von NA bei der Variable "andere" (siehe Fragebogen im Anhang Frage 3, Item 12 "Eine Andere [bitte eintragen]" der Frage "Wie häufig liest du folgende Medien?"). Die Antwortmöglichkeit wurde als 4-stufige Intervallskala angeboten mit der Möglichkeit ein individuelles Medium schriftlich anzugeben. Im Ergebnis gibt es:

* 18 NA für Antworten die keine Angabe zum Medium haben in Kombination mit keiner Auswahl auf der Skala  
* nur 5 Ergebnisse mit schriftlichen Angaben (Beispiel: FAZ, Handelsblatt (FB Nr. 89), Economist (FB Nr. 90)) kombiniert mit einer Auswahl auf der Skala.

Letzteres wäre die beabsichtigte Antwortkombination gewesen, jedoch hat sich herausgestellt dass die meisten Fragebögen bei diesem Item unvollständig ausgefüllt sind. 


```r
summary(fragebogen$andere)
```

```
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max.    NA's 
##   1.000   4.000   4.000   3.455   4.000   4.000      24
```

```r
nrow(fragebogen)
```

```
## [1] 101
```


Die meisten (ZAHL) Antwortmöglichkeiten sind eine Auswahl auf der Skala ohne einer schriftlichen Angabe zum Medium. 

Bei den korrekt ausgefüllten Items gibt es zusätzlich auch Fälle mit mehreren schriftlichen Angaben, die im engeren Sinne auch als nicht korrekt ausgefüllt gewertet werden müssen. Bei diesen Mehrfachangaben ist nicht klar ob sich die Auswahl auf der Skala auf alle angegeben Medien gleichermaßen bezieht. Zusätzlich würde bei der Auswertung ein weiteres Item und damit eine Verzerrung entstehen. 

Ein weiteres Problem entstand, dass es Angaben von Medien gibt die den Autoren unbekannt sind (Beispiel: FB 96 "Rocks Magazine"). Dies macht es schwierig eine Bewertung vorzunehmen. 

Die Auswahl auf der Skala in Kombination mit der Bewertung eines einzelnen angegebenen (bekannten) Mediums wäre die intendierte Form der Auswertung gewesen.

Diese Umstände führten zur Entscheidung die fragliche Variable gänzlich aus der Auswertung zu entfernen. Die meisten Fälle haben nur eine Auswahl auf der Skala ohne zusätzlicher Angabe auf welches Medium sich diese bezieht, dies ist für die Auswertung  wertlos und ohne Aussage.


```r
fragebogen$andere <- NULL
nrow(fragebogen)
```

```
## [1] 101
```

Folgende Fragebögen haben fast ausschliesslich NA bei den Antworten und wurden von der Auswertung ausgenommen:

* FB Nr. 47
* FB Nr. 65


```r
nrow(fragebogen)
```

```
## [1] 101
```

```r
fragebogen[47, ]
```

```
##    Nr. wu publikum spass wohl reden party kurier presse krone oesterreich
## 47  47  2        4     3    3     4     6      4      4     4           4
##    standard heute wiener kleine orf zeit bild diskut scherzen erfahrung
## 47        4     4      4      4   4    4    4      6        5         5
##    demo gewalt krimi fpoe sicherheit feindlich kreis arbeiten skype
## 47    6      6     3    2         NA        NA    NA       NA    NA
##    treffen engag lv heimat rechte kultur verlassen partner knapp pflegen
## 47      NA    NA NA     NA     NA     NA        NA       6     4       6
##    politik verdienen egal sex
## 47       6         6    6   1
```

```r
fragebogen[65, ]
```

```
##    Nr. wu publikum spass wohl reden party kurier presse krone oesterreich
## 65  65  2        2     3    2     4     5      4      4     4           4
##    standard heute wiener kleine orf zeit bild diskut scherzen erfahrung
## 65        4     4      4      4   1    4    4      3        1         2
##    demo gewalt krimi fpoe sicherheit feindlich kreis arbeiten skype
## 65    5      6     1    1         NA        NA    NA       NA    NA
##    treffen engag lv heimat rechte kultur verlassen partner knapp pflegen
## 65      NA    NA NA     NA     NA     NA        NA       5     5       4
##    politik verdienen egal sex
## 65       4         5    6   2
```

```r
fragebogen <- fragebogen[-c(47, 65), ]
nrow(fragebogen)
```

```
## [1] 99
```

Eine Übersicht weiterer NA ist im Anhang zu sehen.

### Ausreisser

Analyse für Ausreisser hierher


\section{Empirie}

In diesem Bereich wird der Datensatz aus der Befragung mit verschiedenen statistischen Verfahren ausgewertet. Allen statistischen Untersuchungen wird ein Signifikanzniveau von 5% ($\alpha = .05$) zugrunde gelegt.

## Demographische Daten

Im demographischen Teil zum Schluss des Fragebogens wurde auf Fragen zu persönlichen Merkmalen bis auf das Geschlecht verzichtet um den Fragebogen möglichst anonym zu halten. Dieser eher "minimalistische" Ansatz hat sich bei der Auswertung zwar als nicht hinderlich jedoch reduzierten sich die Möglichkeiten um zusätzliche "kostenlose" Auswertungen durchzuführe. Beispielsweise wäre es möglich gewesen die UV mit "Alter" zu analysieren, wobei hier die Repräsentativität zu prüfen gewesen wäre. 


```r
sex_count <- table(fragebogen$sex)
rownames(sex_count) <- c("weiblich", "männlich")
barplot(sex_count, main="Geschlecht", ylim=c(0,70), xlab="Frage: 'Ihr Geschlecht?'", ylab="Anzahl", col=c("mistyrose", "lightblue"))
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/barplot Geschlecht-1.pdf)<!-- --> 

\begin{center}
\textit{Abbildung 1: Frage nach Geschlecht}
\bigskip
\end{center}

## Prüfung der Repräsentativität

In Abbildung 1 ist die Verteilung der Befragten nach ihrem Geschlecht dargestellt. Dabei ist zu erkennen, dass sich unter den Befragten Personen 53 männliche Studierende und 46 weibliche Studierende befinden. Dies deutet auf ein Ungleichgewicht hin. Ob die Stichprobe dennoch repräsentativ ist, kann festgestellt werden, wenn wir die Verteilung dieser Stichprobe mit der Verteilung der Grundgesamtheit vergleichen. Die Statistik Austria gibt an, das im Studienjahr 2015/16 insgesamt 21.842 Personen an der WU studiert haben. 11.558 davon sind männliche und 10.284 sind weibliche Studierende (Statistik Austria, abgerufen am 19.6.2017 https://www.statistik.at/web_de/statistiken/menschen_und_gesellschaft/bildung_und_kultur/formales_bildungswesen/universitaeten_studium/021635.html). Wenn wir davon ausgehen, dass sich dieses Verhältnis im Studienjahr 2016/17 nicht verändert hat, ergibt dies eine Verteilung von etwa 53% männlichen und 47% weiblichen Studierenden. Mit einem Chi-Quadrat Test können wir feststellen, ob sich unsere Stichprobe von der erwarteten Verteilung der Grundgesamtheit unterscheidet. Die beobachteten und erwarteten Werte der Verteilung der Geschlechter sehen wir in Tabelle XY. Für den Chi-Quadrat Test werden folgende Hypothesen aufgestellt:

+-----------+-------------------------------------------------------------------------------------------+
| H~0~:     | Die Verteilung der Geschlechter unterscheidet sich nicht von der erwarteten Verteilung    |
+-----------+-------------------------------------------------------------------------------------------+
| H~A~:     | Die Verteilung der Geschlechter unterscheidet sich von der erwarteten Verteilung          |
+-----------+-------------------------------------------------------------------------------------------+


Chi-Quadrat Test hierher


```r
#chisq.test(na.omit(fragebogen$sex))
chisq.test(c(10.284,11.558),c(sex_count[1], sex_count[2]))
```

```
## Warning in chisq.test(c(10.284, 11.558), c(sex_count[1], sex_count[2])):
## Chi-squared approximation may be incorrect
```

```
## 
## 	Pearson's Chi-squared test with Yates' continuity correction
## 
## data:  c(10.284, 11.558) and c(sex_count[1], sex_count[2])
## X-squared = 0, df = 1, p-value = 1
```


## Die abhängige Variable

Allen Hypothesen liegt die gleiche abhängige Variable (AV) zugrunde und lautet: "Ausmaß der Fremdenfeindlichkeit". Zur Messung der AV wurde den Studierenden eine Likertskala mit 10 Items vorgelegt. Die Antwortmöglichkeiten waren auf einer 6-stufigen Intervallskala mit den Ausprägungen "Stimme sehr zu" bis "Stimme gar nicht zu" vorgegeben. Die Frage lautete "Wie ist deine Meinung zur Migration?" (siehe im Anhang Frage 6 im Fragebogen). 


+-----------+------------------------------------------------------------------------------------------------------------------+
| Variablen | Item                                                                                                             |
+===========+==================================================================================================================+
| heimat    | Wenn Arbeitsplätze knapp werden, sollte man AusländerInnen wieder in Ihre Heimat schicken                        |
+-----------+------------------------------------------------------------------------------------------------------------------+
| rechte    | AusländerInnen sollten nicht die gleichen Rechte in allen Lebensbereichen haben wie ÖsterreicherInnen            |
+-----------+------------------------------------------------------------------------------------------------------------------+
| kultur    | Ich bin nicht für die Anwesenheit von AusländerInnen weil sie unsere Kultur negativ beeinflussen                  |
+-----------+------------------------------------------------------------------------------------------------------------------+
| verlassen | Es wäre am besten, wenn alle AusländerInnen Österreich verlassen würden                                          |
+-----------+------------------------------------------------------------------------------------------------------------------+
| partner   | In Österreich lebende AusländerInnen sollen sich Ihre (Ehe-)partner unter ihren eigenen Landsleuten wählen       |
+-----------+------------------------------------------------------------------------------------------------------------------+
| knapp     | Wenn Studierendenplätze an der WU noch knapper werden, sollte man bei der Zulassung InländerInnen bevorzugen     |
+-----------+------------------------------------------------------------------------------------------------------------------+
| pflegen   | AusländerInnen sollen ihre Kultur nicht bei uns pflegen, sie sollen sich an die Kultur in Österreich anpassen    |
+-----------+------------------------------------------------------------------------------------------------------------------+
| politik   | Politiker sollen sich vor allem für InländerInnen einsetzen                                                      |
+-----------+------------------------------------------------------------------------------------------------------------------+
| verdienen | AusländerInnen sollen sich nach dem Zuzug erstmal die Privilegien des Sozialstaates in Österreich (...)verdienen |
+-----------+------------------------------------------------------------------------------------------------------------------+
| egal      | Wenn ich mit AusländerInnen in einer Arbeitsgruppe bin, ist mir das nicht egal                                   |
+-----------+------------------------------------------------------------------------------------------------------------------+


Um eine Dimensionsreduktion zu erreichen wird eine Hauptkomponentenanalyse durchgeführt da die Zuordnung der Items zu spezifischen Komponenten eine einfachere Interpretation der Fremdenfeindlichkeit ermöglicht. 

NOCH SCHREIBEN: warum item 10 "egal" weggelassen (weggelassen weil Personen vermutlich falsch angekreuzt -> missverständliches item)


```r
countr <- table(fragebogen$egal)
rownames(countr) <- c("1", "2", "3", "4", "5", "6")
barplot(countr, main="Variable 'egal'", ylim=c(0,70), xlab="Item: 'Wenn ich mit AusländerInnen in einer Arbeitsgruppe bin, ist mir das nicht egal'", ylab="Anzahl")
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/barplot var egal-1.pdf)<!-- --> 


Zunächst werden die Voraussetzungen für die Hauptkomponentenanalyse geprüft. 


```r
library("psych")
# fragebogen[1:2,34:42]
av <- fragebogen[,34:42]
nrow(av)
```

```
## [1] 99
```

```r
library("REdaS")
```

```
## Loading required package: grid
```

```r
bart_spher(av)
```

```
## 	Bartlett's Test of Sphericity
## 
## Call: bart_spher(x = av)
## 
##      X2 = 486.101
##      df = 36
## p-value < 2.22e-16
```


Die Teststatistik zeigt ein klares Ergebnis, da die Teststatistik einen p-Wert unter 0.00000000000000022 erzeugt. Je kleiner der p-Wert ist, desto mehr Grund gibt es, die Nullhypothese zu verwerfen. Die Nullhypothese, dass es keine Korrelationen zwischen den Variablen gibt kann verworfen werden und das Resultat daher als statistisch signifikant (überzufällig) bezeichnet werden.



```r
kmosmd <- KMOS(av)
print(kmosmd, stats="KMO")
```

```
## 
## Kaiser-Meyer-Olkin Statistic
## Call: KMOS(x = av)
## 
## KMO-Criterion: 0.8155905
```

```r
print(kmosmd, stats="MSA", sort=TRUE, digits=3, show=1:5)
```

```
## 
## Kaiser-Meyer-Olkin Statistics
## 
## Call: KMOS(x = av)
## 
## Measures of Sampling Adequacy (MSA):
## verlassen   pflegen    kultur   partner verdienen 
##     0.709     0.762     0.768     0.795     0.818
```

Der Wert des KMO liegt bei 0.8155905 und die MSA-Werte liegen bei > als 0,7. Die Daten sind also als sehr gut geeignet einzustufen weil genügend Informationen zur Durchführung einer Hauptkomponentenanalyse vorliegen. 


```r
VSS.scree(av)
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/Hauptkomponentenanalyse: Scree plot-1.pdf)<!-- --> 

Der Screeplot zeigt, dass die ersten 2 Komponenten einen Eigenwert > 1 haben, die anderen liegen unter diesem Kriterium. 

Komponenten ergeben sich aus der Gruppierung von miteinander korrelierter Variablen wobei die Komponenten selbst miteinander nicht korrelieren. Die Gründe des einzelnen Eigenwertes beschreibt den Anteil der Varianz in den Daten, die durch diese Komponente erklärt wird. Der Eigenwert wird durch die Anzahl der Items die zu einer Komponente zusammengefasst werden und der Korrelation innerhalb dieser Gruppe bestimmt. Je größer der Eigenwert desto mehr trägt er zur Erklärung der Gesamtstreuung bei. Komponenten mit einem Wert von 1 liefern den gleichen Erklärungswert wie die einzelne ursprüngliche Variable, darunter ist der Erklärungswert sogar geringer. 


```r
pca.av <- principal(av, 2, rotate="none")
pca.av
```

```
## Principal Components Analysis
## Call: principal(r = av, nfactors = 2, rotate = "none")
## Standardized loadings (pattern matrix) based upon correlation matrix
##            PC1   PC2   h2   u2 com
## heimat    0.82  0.28 0.75 0.25 1.2
## rechte    0.62  0.32 0.49 0.51 1.5
## kultur    0.82  0.31 0.77 0.23 1.3
## verlassen 0.67  0.61 0.82 0.18 2.0
## partner   0.59  0.04 0.34 0.66 1.0
## knapp     0.66 -0.43 0.61 0.39 1.7
## pflegen   0.76 -0.42 0.76 0.24 1.6
## politik   0.81 -0.35 0.78 0.22 1.4
## verdienen 0.78 -0.29 0.69 0.31 1.3
## 
##                        PC1  PC2
## SS loadings           4.79 1.23
## Proportion Var        0.53 0.14
## Cumulative Var        0.53 0.67
## Proportion Explained  0.80 0.20
## Cumulative Proportion 0.80 1.00
## 
## Mean item complexity =  1.4
## Test of the hypothesis that 2 components are sufficient.
## 
## The root mean square of the residuals (RMSR) is  0.07 
##  with the empirical chi square  37.83  with prob <  0.0062 
## 
## Fit based upon off diagonal values = 0.98
```

Komponente PC1 erklärt 53% der Varianz und Komponente PC2 14%. Beide Komponenten zusammen erklären einen Gutteil der Varianz, 67%, und sind > 1. Die Hinzunahme weiterer Variablen ist nicht sinnvoll weil alle weiteren Eigenwerte kleiner als 1 sind. 


```r
pca.av_r <- principal(av, 2)
pca.av_r$criteria <- NULL
print(pca.av_r, cut=0.43, sort=TRUE, digits=3)
```

```
## Principal Components Analysis
## Call: principal(r = av, nfactors = 2)
## Standardized loadings (pattern matrix) based upon correlation matrix
##           item   RC1   RC2    h2    u2  com
## pflegen      7 0.844       0.761 0.239 1.14
## politik      8 0.829       0.781 0.219 1.27
## knapp        6 0.769       0.612 0.388 1.07
## verdienen    9 0.765       0.690 0.310 1.35
## verlassen    4       0.901 0.816 0.184 1.01
## kultur       3       0.794 0.772 0.228 1.43
## heimat       1       0.769 0.753 0.247 1.51
## rechte       2       0.662 0.489 0.511 1.22
## partner      5       0.431 0.344 0.656 1.99
## 
##                         RC1   RC2
## SS loadings           3.092 2.927
## Proportion Var        0.344 0.325
## Cumulative Var        0.344 0.669
## Proportion Explained  0.514 0.486
## Cumulative Proportion 0.514 1.000
## 
## Mean item complexity =  1.3
## Fit based upon off diagonal values = 0.978
```

Es werden 2 Hauptkomponenten extrahiert und nach der Varimaxmethode rotiert. Die Komponenten mit den hoch ($\ge 0.43$) auf ihnen ladenden Variablen sind:


1. Komponente (RC1): moderate Einstellung (Eigenwert: 3.092, erklärte Varianz: 34,4%)
  "Bevorzugung von Inländern bei Knappheit von Studienplätzen"  .769
  "Anpassung an Kultur in Österreich" .844
  "Einsatz Politiker für Inländer"  .829
  "Verdienst Privilegien Sozialstaat" .765
2. Komponente (RC2): aggressive Einstellung (Eigenwert: 2.972, erklärte Varianz: 32,5%)
  "Wieder in die Heimat schicken" .769
  "Nicht die gleichen Rechte wie Österreicher"  .662
  "Negative Beeinflussung Kultur" .794
  "Österreich verlassen"  .901
  "Ehepartner unter eigenen Landsleuten"  .431



```r
fa.diagram(pca.av_r, cut=0.43, cex=0.8, rsize=0.5, main="")
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/Hauptkomponentenanalyse: diagramm-1.pdf)<!-- --> 

--> Weitere Erklärung noch aus Buch S.465 zb Eine Analyse der Variablen der 2. Komponente zeigt, dass die gestellten Fragen von der Mehrheit stark abgelehnt werden -> aggressive Fragestellung -> hohe Ablehnung -> keine ausgeprägte Fremdenfeindlichkeit


```r
countr <- table(fragebogen$rechte)
rownames(countr) <- c("1", "2", "3", "4", "5", "6")
barplot(countr, main="Variable 'rechte'", ylim=c(0,60), xlab="Item: AusländerInnen sollten nicht die gleichen Rechte \n in allen Lebensbereichen haben wie ÖsterreicherInnen", ylab="Anzahl")
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/barplot var rechte-1.pdf)<!-- --> 

Für die weitere Analyse werden factor scores angelegt. 


```r
round(head(pca.av_r$scores), 4)
```

```
##       RC1    RC2
## 1  1.3661 0.3307
## 2 -0.4883 0.4607
## 3 -0.0334 0.8614
## 4  1.3661 0.3307
## 5 -0.0516 0.8780
## 6 -0.7460 0.5157
```

```r
av_r.scores <- data.frame(pca.av_r$scores)
names(av_r.scores) <- c("moderat", "aggressiv")
round(head(av_r.scores), 4)
```

```
##   moderat aggressiv
## 1  1.3661    0.3307
## 2 -0.4883    0.4607
## 3 -0.0334    0.8614
## 4  1.3661    0.3307
## 5 -0.0516    0.8780
## 6 -0.7460    0.5157
```

```r
# Weitere Analyse mit den folgenden beiden Variablen:
av_r.scores$moderat
```

```
##  [1]  1.366091e+00 -4.883442e-01 -3.339595e-02  1.366091e+00 -5.157928e-02
##  [6] -7.460068e-01 -2.228172e+00  1.885807e-01 -1.008100e+00  5.181124e-01
## [11] -1.461072e+00 -1.520975e+00  1.188650e+00  2.527261e-01 -8.804113e-02
## [16] -8.017079e-01 -5.275213e-01 -6.425426e-01  1.366091e+00  1.366091e+00
## [21] -8.773640e-01 -1.707386e+00 -8.064045e-01 -4.932594e-01 -4.262787e-01
## [26] -7.329794e-01 -2.149755e+00 -2.477882e-01  1.366091e+00 -3.247262e-01
## [31]  9.648289e-01  1.366091e+00  6.000234e-01  7.019214e-01  1.629138e+00
## [36]  1.366091e+00 -2.608005e-01 -1.566282e-01  5.916297e-02  2.177391e+00
## [41] -6.043733e-01 -5.086249e-01 -1.320391e-01 -1.088600e+00  1.629138e+00
## [46]  1.169882e+00  7.762045e-01 -2.210222e+00  2.003489e-01 -1.401177e-01
## [51]  6.350812e-01  4.343351e-01  2.402967e-01 -2.302441e-01  2.175294e-01
## [56]  8.495617e-01  1.366091e+00  1.366091e+00  1.366091e+00 -8.488815e-01
## [61] -1.211061e+00  1.188650e+00  2.568942e-01 -2.111124e+00 -1.147838e+00
## [66] -2.864318e-02 -2.613852e-01 -1.525991e+00 -8.730946e-01  6.423122e-01
## [71] -3.281128e-02 -1.267839e+00  7.462686e-01 -1.442374e+00 -4.492347e-01
## [76]  7.451459e-02 -4.122141e-01 -3.675397e-01  1.366091e+00  1.366091e+00
## [81] -3.746807e-01  4.854804e-05  1.128492e-01  8.785518e-01 -2.628421e-01
## [86] -4.582365e-02  3.408385e-01 -1.524328e+00  9.924412e-01 -8.757256e-01
## [91] -1.433988e+00  2.772772e-01  5.682431e-01 -4.557166e-01 -5.476288e-01
## [96]  6.740465e-01  6.450049e-01  6.057791e-01  1.366091e+00
```

```r
av_r.scores$aggressiv
```

```
##  [1]  0.33074730  0.46072646  0.86139672  0.33074730  0.87796460
##  [6]  0.51574894  1.42449083  0.49569675  1.17489060 -0.35964818
## [11] -0.66561700 -0.62774722  0.36935596  0.46236938  0.29041014
## [16]  0.20975880  0.30366879  0.14544555  0.33074730  0.33074730
## [21]  0.10299877  1.17681145 -1.94544408  0.36372050 -1.94928602
## [26]  0.99615210  0.49923009  0.96919665  0.33074730  0.81426257
## [31]  0.31182106  0.33074730  0.64305211 -0.03267838 -0.49515657
## [36]  0.33074730  0.91520918 -0.45616121  0.40362445 -3.66540232
## [41] -0.38956631 -1.12840965 -2.29879784  1.07349664 -0.49515657
## [46]  0.42197935  0.14515305 -0.55336772  0.66491789 -1.10283752
## [51] -0.09298379  0.27635784 -2.07030825 -2.54519127  0.57150248
## [56] -2.96047074  0.33074730  0.33074730  0.33074730 -1.80650166
## [61]  0.66677411  0.36935596  0.31496650 -0.35662517  0.95929390
## [66]  0.67793833  0.95126470  0.52562738 -2.59727227  0.35434694
## [71]  0.82534121  0.10800217  0.56702386  0.24810343 -0.62273664
## [76]  0.46149824  0.05946390 -0.27804394  0.33074730  0.33074730
## [81]  0.95654599  0.37130120  0.78536847  0.37484520 -1.26289106
## [86]  0.77135374  0.69550050  0.52329675  0.46058801 -1.56024683
## [91] -2.81945581 -0.47272624  0.64168804 -0.03068128  0.26608368
## [96]  0.27527097 -0.34699752  0.53644126  0.33074730
```

In der weiteren Analyse wird mit zwei metrischen Variablen weitergearbeitet. 



## Hypothese 1

## Hypothese 2

## Hypothese 3
### Problemanalyse
In diesem Abschnitt wollen wir überprüfen, ob die Einstellung der Studierenden abhängig von der Einstellung der Personen in Ihrem sozialen Umfeld ist.

Unsere Hypothese dazu latüt:
*Je mehr Menschen im persönlichen Umfeld (Freunde, Familie) ausländerfeindlich sind, umso negativer ist die eigene Haltung gegenüber AusländerInnen.*

#### Welche Variablen kommen vor?
Erklärende Variable: Umfeld  
   
Besteht aus neun Items; --> metrisch
     
Responsevariable: Fremdenfeindlichkeit  
    
Wurde bereits im Kapitel x behandelt; Die Ergebnisse werden für die Analyse weiterverwendet 
     
   - av_r.scores$moderat, Fremdenfeindlichkeit "moderat"", metrisch
      
   - av_r.scores$aggressiv, Fremdenfeindlichkeit "aggressiv", metrisch

  
  


#### Welche Methode ist angebracht?
t-Test

#### Welche Hypothesen können formuliert werden?

+-----------+---------------------------------------------------------------------------+
| H~0~:       |   Die eigene Einstellung zu MigratenInnen ist unabhängig von der Einstellung der Personen im eigenen Umfeld.               |
+-----------+---------------------------------------------------------------------------+
| H~A~:       |   Die eigene Einstellung zu MigratenInnen ist abhängig von der Einstellung der Personen im eigenen Umfeld.                  |
+-----------+---------------------------------------------------------------------------+

#### Die unabhängige Variable - Umfeld

+-----------+------------------------------------------------------------------------------------------------------------------+
| Variablen | Item                                                                                                             |
+===========+==================================================================================================================+
| diskut    | Ich diskutiere mit meinen Familienmitgliedern/Freunden oft über AusländerInnen                                       |
+-----------+------------------------------------------------------------------------------------------------------------------+
| scherzen  | Ich kenne Familienmitglieder/Freunde, die oft über AusländerInnen im negativen Sinne scherzen            |
+-----------+------------------------------------------------------------------------------------------------------------------+
| erfahrung | Einige meiner Familienmitglieder/Freunde haben bereits negative Erfahrungen mit AusländerInnen gemacht                       |
+-----------+------------------------------------------------------------------------------------------------------------------+
| demo      | Ich würde einigen meiner Familienmitglieder/Freunde zutraün, dass Sie bei Demonstrationen gegen AusländerInnen teilnehmen                                          |
+-----------+------------------------------------------------------------------------------------------------------------------+
| gewalt    | Heutzutage muss man Verständnis haben, wenn Familienmitglieder/Freunde Gewalt gegen AusländerInnen ausüben müssen       |
+-----------+------------------------------------------------------------------------------------------------------------------+
| krimi     | Ich kenne Familienmitglieder/Freunde, die AusländerInnen für Kriminelle halten     |
+-----------+------------------------------------------------------------------------------------------------------------------+
| fpö      | Ich kenne Familienmitglieder/Freunde, die FPÖ wählen        |
+-----------+------------------------------------------------------------------------------------------------------------------+
| sicherheit| Seit der Flüchtlingskrise haben einige meiner Familienmitglieder/Freunde Angst um Ihre eigene Sicherheit                                                      |
+-----------+------------------------------------------------------------------------------------------------------------------+
| feindlich | Ich kenne Familienmitglieder/Freunde,die fremdenfeindlich sind |
+-----------+------------------------------------------------------------------------------------------------------------------+

\begin{center}
\textit{Tabelle 2: Unabhängige Variable: Umfeld}
\bigskip
\end{center}

### Kurzbericht

Die Einstellung der Personen im sozialen Umfeld wurde anhand von neun Items überprüft. 
Die übergerordente Frage dazu lautet: "Einstellung zur Migration in deinem sozialen Umfeld?" 
Als Maßstab wurde eine Intervallskala von eins bis sechs verwendet, wobei 1 = "Trifft sehr zu" und 6 = "Trifft gar nicht zu".  

Da wir hier mit multivairate Datean zu tun haben, wird eine Hauptkomponentenanalyse durchtgeführt, um die Datendimension zu reduzieren.  

#### Voraussetzungen für die Hauptkomponentenanalyse

Bevor wir die Voraussetzungen überprüfen, müssen wir die richtigen Daten auswählen. Wir werden alle Daten mit NAs entfernen und schaün uns das Ergebniss an. 


```r
library("psych")
library("zoo")
```

```
## 
## Attaching package: 'zoo'
```

```
## The following objects are masked from 'package:base':
## 
##     as.Date, as.Date.numeric
```

```r
umfeld<-na.omit((fragebogen[,19:27]))
nrow(umfeld)
```

```
## [1] 94
```
  
Wenn wir für die  ausgewählten Items alle Zeilen wo mindestens ein NA vorkommt entfernen, dann bleiben uns in Summe nur noch 94 Datensätze übrig. An erster Stelle ist es natürlich Schade, Datensätze wegen ein bis zwei NA zu entfernen. Aber wir erinnern uns zurück, dass wir für die abhängige Variable "Fremdenfeindlichkeit" 99 Datensätze verwendet haben.  

Damit wir gleich vielen Daten für die abhängige- und unabhängige Variable verwenden können, werden wir die Rohdaten wieder hernehmen und fehlende Einträge mit der *na.approx*-Funktion ergänzen. Und danach die Datensätze mit der "!is.na"-Funktion auf jene Daten reduziert, die in der Variable "Heimat", welche im Datensatz der Hautpkomponentenanalyse der "Fremdenfeindlichkeit" vorkommt.


```r
library("psych")
library("zoo")
umfeld<-na.approx(fragebogen[,19:27])
umfeld<-umfeld[!is.na(av["heimat"]),]
nrow(umfeld)
```

```
## [1] 99
```
   
Jetzt haben wir exakt 99 Datensätze, die mit der abhängigen Varialbe "Fremdenfeindlichkeit" übereintimmen.  

##### Bartlett-Test: "Umfeld"

Nachdem unser Datensatz für die weitere Bearbeitung dementsprechend vorbereitet wuden, können wir nun mit der überprüfung der Voraussetzungen für die Hauptkomponentenanalyse loslegen.  

Als Erstes führen wir den Bartlett-Test durch: 

```r
library("REdaS")
bart_spher(umfeld)
```

```
## 	Bartlett's Test of Sphericity
## 
## Call: bart_spher(x = umfeld)
## 
##      X2 = 312.309
##      df = 36
## p-value < 2.22e-16
```


Die Teststatistik zeigt ein klares Ergebnis, da die Teststatistik $X^2=312.309$ mit einer $\chi^2$-Verteilung mit 36 Freiheitsgraden einen p-Wert unter 0.00000000000000022 erzeugt. Je kleiner der p-Wert ist, desto mehr Grund gibt es, die Nullhypothese zu verwerfen. Die Nullhypothese, dass es keine Korrelationen zwischen den Variablen gibt kann verworfen werden und das Resultat daher als statistisch signifikant bezeichnet werden.  
       
##### KMO und MSA: "Umfeld" 
Als nüchstes werden wir die MSAs und die KMO überprüfen.

```r
kmosmd <- KMOS(umfeld)
print(kmosmd, stats="KMO")
```

```
## 
## Kaiser-Meyer-Olkin Statistic
## Call: KMOS(x = umfeld)
## 
## KMO-Criterion: 0.8040357
```

```r
print(kmosmd, stats="MSA", sort=TRUE, digits=3, show=1:5)
```

```
## 
## Kaiser-Meyer-Olkin Statistics
## 
## Call: KMOS(x = umfeld)
## 
## Measures of Sampling Adequacy (MSA):
##     gewalt sicherheit  erfahrung     diskut       demo 
##      0.626      0.687      0.769      0.816      0.828
```

Der Wert des KMO liegt bei 0.8040357 und die MSA-Werte liegen bei > als 0,6. Die Daten sind also als sehr gut geeignet einzustufen weil genügend Informationen zur Durchführung einer Hauptkomponentenanalyse vorliegen. 

##### Scree Plot: Umfeld
Mittels Scree Plot können wir nun überprüfen, wieviele Hauptkomponenten für die Hauptkomponentennalyse benötigt werden.
  

```r
VSS.scree(umfeld)
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/Umfeld: Scree plot-1.pdf)<!-- --> 

\begin{center}
\textit{Abbildung 2: Scree Plot:Umfeld}
\bigskip
\end{center}

Der Screeplot zeigt, dass die ersten 2 Komponenten einen Eigenwert > 1 haben, die anderen liegen unter diesem Kriterium.   

##### Hauptkomponentenanalyse: "Umfeld"
Basierend auf der Information aus dem Screeplot werden wir im ersten Versuch zwei Komponenten extrahieren und vorerst keine Rotation durchführen. Um den Output zu reduzieren, wird die Objektkomponente *criteria* entfernt. 
  

```r
pca.umfeld <- principal(umfeld, 2, rotate="none")
pca.umfeld$criteria<-NULL
pca.umfeld
```

```
## Principal Components Analysis
## Call: principal(r = umfeld, nfactors = 2, rotate = "none")
## Standardized loadings (pattern matrix) based upon correlation matrix
##             PC1   PC2   h2   u2 com
## diskut     0.46  0.23 0.27 0.73 1.5
## scherzen   0.71  0.12 0.51 0.49 1.1
## erfahrung  0.69 -0.26 0.55 0.45 1.3
## demo       0.72  0.25 0.58 0.42 1.2
## gewalt     0.44  0.68 0.65 0.35 1.7
## krimi      0.78  0.17 0.64 0.36 1.1
## fpoe       0.72 -0.13 0.53 0.47 1.1
## sicherheit 0.58 -0.61 0.70 0.30 2.0
## feindlich  0.82 -0.21 0.72 0.28 1.1
## 
##                        PC1  PC2
## SS loadings           4.04 1.12
## Proportion Var        0.45 0.12
## Cumulative Var        0.45 0.57
## Proportion Explained  0.78 0.22
## Cumulative Proportion 0.78 1.00
## 
## Mean item complexity =  1.3
## Fit based upon off diagonal values = 0.94
```
  
Komponente PC1 erklärt 45% der Varianz und Komponente PC2 12%. Beide Komponenten zusammen erklären 57% und sind > 1. Die Hinzunahme weiterer Variablen ist nicht sinnvoll weil alle weiteren Eigenwerte kleiner als 1 sind. 

##### Varimax-Rotation: Umfeld

Es werden zwei Hauptkomponenten extrahiert und nach der Varimaxmethode rotiert. 
  

```r
pca.umfeld_r <- principal(umfeld, 2)
pca.umfeld_r$criteria <- NULL
print(pca.umfeld_r, cut=0.48, sort=TRUE, digits=3)
```

```
## Principal Components Analysis
## Call: principal(r = umfeld, nfactors = 2)
## Standardized loadings (pattern matrix) based upon correlation matrix
##            item    RC1    RC2    h2    u2  com
## sicherheit    8  0.834        0.701 0.299 1.02
## feindlich     9  0.756        0.720 0.280 1.49
## erfahrung     3  0.694        0.549 0.451 1.27
## fpoe          7  0.624        0.530 0.470 1.64
## gewalt        5         0.800 0.654 0.346 1.04
## demo          4         0.664 0.583 0.417 1.59
## krimi         6         0.642 0.640 0.360 1.85
## scherzen      2         0.558 0.513 0.487 1.91
## diskut        1         0.481 0.268 0.732 1.32
## 
##                         RC1   RC2
## SS loadings           2.761 2.396
## Proportion Var        0.307 0.266
## Cumulative Var        0.307 0.573
## Proportion Explained  0.535 0.465
## Cumulative Proportion 0.535 1.000
## 
## Mean item complexity =  1.5
## Fit based upon off diagonal values = 0.939
```

Es werden zwei Hauptkomponenten extrahiert und nach der Varimaxmethode rotiert. Die Komponenten mit den hoch ($\ge 0.48$) auf ihnen ladenden Variablen sind:


1. Komponente (RC1): Passives Umfeld (Eigenwert: 2.761, erklärte Varianz: 30,7%)
  "Angst um die eigene Sicherheit"  .834
  "Fremdenfeindliche Personen im Umfeld" .756
  "Bereits negative Erfahrung mit AusländerInnen"  .694
  "FPÖ-Wähler im Umfeld" .624
2. Komponente (RC2): Aktives Umfeld (Eigenwert: 2.396, erklärte Varianz: 26,6%)
  "Gewalt ausüben" .8
  "Bei Demosnstrationen gegen AusländerInnen teilnehmen"  .664
  "AuländerInnen für Kriminelle halten" .642
  "über AusländerInnen scherzen"  .558
  "über AusländerInnen diskutieren"  .481

##### Zuordnung der Items: "Umfeld"
Als nüchstes schaün wir uns die Ergebnisse grafisch an.
   

```r
fa.diagram(pca.umfeld_r, cut=0.43, cex=0.8, rsize=0.5, main="")
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/Umfeld PCA: diagram-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 3: Fa-Diagram: Umfeld}
\bigskip
\end{center}
  
Anhand der durchwegs positiven Ladungen kann man erkennen, dass Personen mit hohen Werten bei den jeweiligen Items auch hohe Auspr?gungen auf der Komponente haben. Die zwei extrahierten Hauptkomponenten sind direkt interpretierbar als "aktives-" und "passives Umfeld". Menschen die bereit sind Gewalt gegen AusländerInnen auszuüben, bei Demonstrationen teilzunehmen, über Ausländer scherzen und diskutieren oder diese für Kriminelle halten, befinden sich auf der aktiven Seiten.

##### Factor Scores: "Umfeld"
für die weitere Analyse werden factor scores angelegt. 


```r
round(head(pca.umfeld_r$scores), 4)
```

```
##          RC1     RC2
## [1,] -0.7416 -0.0137
## [2,] -0.3407  0.8159
## [3,]  1.0228  0.7525
## [4,]  1.3662  0.1100
## [5,] -0.9171 -0.1063
## [6,]  0.5026  0.7708
```

```r
umfeld_r.scores <- data.frame(pca.umfeld_r$scores)
names(umfeld_r.scores) <- c("passiv", "aktiv")
round(head(umfeld_r.scores), 4)
```

```
##    passiv   aktiv
## 1 -0.7416 -0.0137
## 2 -0.3407  0.8159
## 3  1.0228  0.7525
## 4  1.3662  0.1100
## 5 -0.9171 -0.1063
## 6  0.5026  0.7708
```

```r
# Weitere Analyse mit den folgenden beiden Variablen:
umfeld_r.scores$passiv
```

```
##  [1] -0.74162049 -0.34069773  1.02277703  1.36624408 -0.91709156
##  [6]  0.50257924 -0.28787047  1.39297226 -0.29674112  1.20436535
## [11] -0.08211912 -0.58425545  1.39959899  0.31154646 -0.07274143
## [16] -0.59687912 -0.53761796 -1.02250005  1.48654333  0.24074306
## [21]  0.69104841  0.26148127  0.01732844  0.26785772 -0.29189852
## [26]  0.51504005 -1.05209634  1.33903607  0.42980979 -0.21143500
## [31] -0.18695940  0.52391305 -0.10047140 -1.53108045 -1.29568541
## [36]  0.51309767 -0.19503007  0.61385698  0.54001928  1.05322026
## [41] -0.47019345 -1.52633469 -0.11409551 -1.85814944 -0.37397494
## [46] -0.52915935 -0.05775366 -0.67506252  0.85433033  0.04113291
## [51] -1.85301447 -0.42397250 -1.01297461  1.52572883  1.48216314
## [56]  0.72574588  1.60145424 -0.12040041  1.16982914  0.07726273
## [61] -0.77918691  1.56096381 -1.74612719 -0.18119992 -0.45956690
## [66]  0.22015353  1.62315118 -0.04728601 -0.88615866 -1.46385148
## [71] -0.15619856 -0.94795952  0.60956393  0.94679048 -1.96465345
## [76]  0.99737002 -0.68416797  2.15643833  1.63747710  0.33969053
## [81] -0.74732787 -1.16111061  1.56691802  1.10006025  0.31142305
## [86] -1.11541827  0.56894319 -0.51021129  0.75939892 -0.60809049
## [91] -2.15014303 -1.03124291  1.40174060 -2.03131571 -1.54329830
## [96]  0.82890372 -0.64390921 -0.46291524  0.88150351
```

```r
umfeld_r.scores$aktiv
```

```
##  [1] -0.013719474  0.815949448  0.752477658  0.109965840 -0.106272527
##  [6]  0.770817455 -0.255141911  0.423550502 -0.544030411  0.623260277
## [11]  1.089432843 -0.250822318  1.030692653  0.906416750  0.478739774
## [16]  0.136978499  0.273225630  0.795618033 -0.418002634  0.615734420
## [21] -0.490530154  0.675567958 -3.315231116  0.507448521 -0.636525182
## [26]  1.139288453  1.411228461 -1.731832633 -0.003400310  0.615862248
## [31]  1.188783793 -3.874778150 -1.674300560 -0.626290887  0.968380839
## [36]  0.197708629 -0.006406447  0.776843715  0.843716126 -1.615809458
## [41] -1.077824674 -0.713034999  0.329078769  0.022077310  1.429851199
## [46]  0.488374111  0.994330502 -1.954319670  0.183607813 -1.787679645
## [51] -0.308586976 -0.120512178  0.148184104 -2.436312372  0.135106425
## [56]  0.540328399  0.832007236 -0.187398030  0.509045471 -0.883588429
## [61] -1.240604638 -0.564841839  0.014208927  0.043417340 -0.469657871
## [66]  0.690054024  0.207439036 -1.255395060 -2.927407266  0.483173260
## [71] -0.159163829  0.344814633  0.692355860 -0.190130196  0.037640319
## [76] -0.060649964  0.483770501 -0.656813571  0.670768534  1.433102990
## [81]  0.075945222  0.796870801  0.717792429  0.911338417 -0.678710889
## [86]  0.182276354  0.455125153 -0.249794288  0.953859122 -1.249966564
## [91] -0.119478738  0.785869509  0.063628652  0.117673182  1.021930656
## [96]  0.136343902 -0.510870570  1.631509667 -0.344751928
```

#### überprüfung der Hypothesen
In der weiteren Analyse wird mit vier metrischen Variablen weitergearbeitet. 
     
Responsevariable "Fremdenfeindlichkeit": Moderat und Aggressiv   
   
Erklärende Variable "Umfeld": Aktiv und Passiv
    
Mittels linearen Regressionsmodells sollen die Responsevariablen durch die erklärende Variablen beschreiben werden. Ein Streudiagramm ist eine geeignete Variante, um den Zusammenhang bildhaft überprüfen zu können.
    
##### Moderat und Passiv
In diesem Streudiagramm ist die Responsebariable (Moderat) auf der y-Achse und die erklärende Variable (Passiv) auf der x-Achse. Anhand der *lm()*-Funktion erfolgt die Schätzung des Modells. Die Schätzung kann für zwei Zwecke verwendet werden. Als erstes benötigen wir sie, um eine Gerade im Streudiagrmam mit der Funkton *abline()* einzeichnen zu können. Und später können wir die Ergebnisse für den *t-test für den Regressionsköffizienten* verwenden. 


```r
mopa<-lm(av_r.scores$moderat ~ umfeld_r.scores$passiv)
plot(umfeld_r.scores$passiv, av_r.scores$moderat, xlab="Passiv", ylab="Moderat")
abline(mopa)
```

![](bericht_files/figure-latex/boxplot: moderat - Passiv-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 4: Boxplot: Moderat und Passiv}
\bigskip
\end{center}  

Nachdem das Steudiagramm nicht eindeutig ist, führen wir im nüchsten Schritt einen *t-test* durch. 
  
##### T-test: Moderat und Passiv  
Die Schätzung haben wir bereits ausgerechnent, und können mit *summary()* ausgeben.


```r
summary(mopa)
```

```
## 
## Call:
## lm(formula = av_r.scores$moderat ~ umfeld_r.scores$passiv)
## 
## Residuals:
##      Min       1Q   Median       3Q      Max 
## -2.13209 -0.63763 -0.08479  0.74963  2.06159 
## 
## Coefficients:
##                         Estimate Std. Error t value Pr(>|t|)    
## (Intercept)            2.907e-17  9.523e-02   0.000 1.000000    
## umfeld_r.scores$passiv 3.338e-01  9.571e-02   3.487 0.000735 ***
## ---
## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
## 
## Residual standard error: 0.9475 on 97 degrees of freedom
## Multiple R-squared:  0.1114,	Adjusted R-squared:  0.1022 
## F-statistic: 12.16 on 1 and 97 DF,  p-value: 0.0007353
```
  
Die Schätzung für die Regressionsgleichung ergibt einen Anstieg der Regressionsgeraden von 0.3338. Der t-Test für diesen Regressionsköffizienten ist hoch signifikant (p<0.005). Die Nullhypothese wird beibehalten.
    
     
Im Prinzip wird für die nachfolgenden Variablen immer dieselbe Methodik verwendet. Daher wird nur noch der T-Test analysiert.  
  
##### Boxplot: Moderat und Aktiv

```r
moak<-lm(av_r.scores$moderat ~ umfeld_r.scores$aktiv)
plot(umfeld_r.scores$aktiv, av_r.scores$moderat, xlab="Aktiv", ylab="Moderat")
abline(moak)
```

![](bericht_files/figure-latex/boxplot: moderat - Aktiv-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 5: Boxplot: Moderat und Aktiv}
\bigskip
\end{center}  
##### T-Tet: Moderat und Aktiv  
  

```r
summary(moak)
```

```
## 
## Call:
## lm(formula = av_r.scores$moderat ~ umfeld_r.scores$aktiv)
## 
## Residuals:
##      Min       1Q   Median       3Q      Max 
## -2.39003 -0.60346 -0.03349  0.72769  2.45250 
## 
## Coefficients:
##                        Estimate Std. Error t value Pr(>|t|)  
## (Intercept)           5.685e-18  9.955e-02   0.000    1.000  
## umfeld_r.scores$aktiv 1.703e-01  1.001e-01   1.702    0.092 .
## ---
## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
## 
## Residual standard error: 0.9905 on 97 degrees of freedom
## Multiple R-squared:  0.02899,	Adjusted R-squared:  0.01898 
## F-statistic: 2.896 on 1 and 97 DF,  p-value: 0.09201
```
  
Die Schätzung für die Regressionsgleichung ergibt einen Anstieg der Regressionsgeraden von 0.1703. Der t-Test für diesen Regressionsköffizienten ist nicht signifikant (p>0.005). Die Nullhypothese wird verworfen.  
  
  

```r
agpa<-lm(av_r.scores$aggressiv ~ umfeld_r.scores$passiv)
plot(umfeld_r.scores$passiv, av_r.scores$aggresiv, xlab="Passiv", ylab="Aggresiv")
abline(agpa)
```

![](bericht_files/figure-latex/boxplot: Aggressiv - Passiv-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 6: Boxplot: Aggressiv und Passiv}
\bigskip
\end{center}
  
##### T-Tet: Aggressiv und Passiv  

```r
summary(agpa)
```

```
## 
## Call:
## lm(formula = av_r.scores$aggressiv ~ umfeld_r.scores$passiv)
## 
## Residuals:
##     Min      1Q  Median      3Q     Max 
## -3.7920 -0.3339  0.2815  0.5308  1.4591 
## 
## Coefficients:
##                          Estimate Std. Error t value Pr(>|t|)
## (Intercept)            -2.375e-16  1.003e-01   0.000    1.000
## umfeld_r.scores$passiv  1.202e-01  1.008e-01   1.192    0.236
## 
## Residual standard error: 0.9979 on 97 degrees of freedom
## Multiple R-squared:  0.01445,	Adjusted R-squared:  0.004287 
## F-statistic: 1.422 on 1 and 97 DF,  p-value: 0.236
```
  
Die Schätzung für die Regressionsgleichung ergibt einen Anstieg der Regressionsgeraden von 0.1202. Der t-Test für diesen Regressionsköffizienten ist nicht signifikant (p<0.236). Die Nullhypothese wird verworfen.  
  
  

```r
agak<-lm(av_r.scores$aggressiv ~ umfeld_r.scores$aktiv)
plot(umfeld_r.scores$aktiv, av_r.scores$aggressiv, xlab="Aktiv", ylab="Aggresiv")
abline(agak)
```

![](bericht_files/figure-latex/boxplot: Aggressiv - Aktiv-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 7: Boxplot: Aggressiv und Aktiv}
\bigskip
\end{center}
  
##### T-Tet: Aggressiv und Aktiv  
  

```r
summary(mopa)
```

```
## 
## Call:
## lm(formula = av_r.scores$moderat ~ umfeld_r.scores$passiv)
## 
## Residuals:
##      Min       1Q   Median       3Q      Max 
## -2.13209 -0.63763 -0.08479  0.74963  2.06159 
## 
## Coefficients:
##                         Estimate Std. Error t value Pr(>|t|)    
## (Intercept)            2.907e-17  9.523e-02   0.000 1.000000    
## umfeld_r.scores$passiv 3.338e-01  9.571e-02   3.487 0.000735 ***
## ---
## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
## 
## Residual standard error: 0.9475 on 97 degrees of freedom
## Multiple R-squared:  0.1114,	Adjusted R-squared:  0.1022 
## F-statistic: 12.16 on 1 and 97 DF,  p-value: 0.0007353
```
  
Die Schätzung für die Regressionsgleichung ergibt einen Anstieg der Regressionsgeraden von 0.377. Der t-Test für diesen Regressionsköffizienten ist hoch signifikant (p<0.005). Die Nullhypothese wird beibehalten.  
  
  
 
## Hypothese 4


*Je höher die Zufriedenheit der Studenten mit der Diversität der Studierenden auf der Wirtschafts- univiersität, umso positiver die eigene Haltung gegenüber AusländerInnen.*

### Problemanalyse

#### Welche Variablen kommen vor?

Erklärende Variable: Zufriedenheit mit der WU Wien --> kategorial
Responsevariable: Fremdenfeindlichkeit
    
  - av_r.scores$moderat, Fremdenfeindlichkeit moderat, metrisch  
  - av_r.scores$aggressiv, Fremdenfeindlichkeit stark, metrisch

#### Welche Methode ist angebracht?
Unabhängigkeitstest

#### Welche Hypothesen können formuliert werden?

+-----------+---------------------------------------------------------------------------+
| H~0~:       |   Die Fremdenfeindlichkeit ist unabhängig von der Zufriedenheit auf der WU. |
+-----------+---------------------------------------------------------------------------+
| H~A~:       |   Die Fremdenfeindlichkeit ist abhängig von der Zufriedenheit auf der WU.   |
+-----------+---------------------------------------------------------------------------+

#### Die unabhängige Variable - WU 

+-----------+------------------------------------------------------------------------------------------------------------------+
| Variable  | Item                                                                                                             |
+===========+==================================================================================================================+
| wu        | Wie zufrieden bist du mit dem multikulturellen Umfeld auf der WU Wien?                       |
+-----------+------------------------------------------------------------------------------------------------------------------+

### Kurzbericht

#### Zufriedenheit mit der WU 
Die Zufriedenheit der Studierenden mit dem multikulturellen Umfeld auf der Wirtschaftsuniversität Wien wurde anhand eines einzigen Items gemessen.   
Die Formlierung des Items lautet: "Wie zufrieden bist du mit dem multikulturellen Umfeld auf der WU Wien?"    
Als Maßstab wurde eine Intervallskala von eins bis sechs verwendet, wobei 1 = sehr zufrieden und 6 = nicht zufrieden.

##### Balkendiagramm: Zufriedenheit
Zürst schaün wir uns die Daten mit Hilfe eines Balkendiagramms an.  
  

```r
countr <- table(fragebogen$wu)
rownames(countr) <- c("1", "2", "3", "4", "5")
barplot(countr, main="Variable 'wu'", ylim=c(0,60), xlab="Item: Wie zufrieden bist du mit dem multikulturellen Umfeld auf der WU Wien", ylab="Anzahl")
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/barplot var wu-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 8: Barplot: Zufriedenheit - WU}
\bigskip
\end{center}
  
Wie man aus der Grafik ablesen kann, ist erstaunlicherweise niemand völlig unzufrieden mit dem multikulturellen Umfeld auf der Wirtschaftsuniversität Wien. Keine einzige Person hat eine "sechs" ankreuzt. Grundsötzlich sieht man auch, dass die meisten Studierenden zufrieden mit dem multikulturellen Umfeld auf der WU Wien sind.  
  
Um die Hypothesen zu überprüfen, wollen wie zunüchst  die Daten mittels Boxplot darstellen.
Im ersten Boxplot wird die Komponente "Moderat" überprüft. 
  
#### überprüfung der Hypothesen
Die Ergebnisse der unabhängigen Variable, die wir im Abschnitt 4.3 bereits ausgewertet haben, werden wir für die weitere Analyse verwenden. Wir erinnern uns zurück, dass wir zwei Komponente haben: *Moderat* und *Aggressiv*
  
##### Boxplot: Moderat und WU
Um die Fragestellung, ob Fremdenfeindlichkeit mit der Zufriedeheit mit dem multikulturellen Umfeld zusammenhängt, schaün wir uns die Ergebnisse mittels Boxplot an
  

```r
boxplot(av_r.scores$moderat ~ fragebogen$wu)
```

![](bericht_files/figure-latex/boxplot: moderat - wu-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 9: Boxplot: Moderat und WU}
\bigskip
\end{center}

Mittels *describeBy()*-Funktion können wir uns auch eine numerische Beschreibung der Daten ansehen, die prinzipell unterstützend für die Interpretation des Boxplots verwendet werden kann.
  

```r
describeBy(av_r.scores$moderat, fragebogen$wu, skew=FALSE)
```

```
## 
##  Descriptive statistics by group 
## group: 1
##    vars  n mean   sd   min  max range   se
## X1    1 27 0.01 0.89 -1.53 1.37  2.89 0.17
## -------------------------------------------------------- 
## group: 2
##    vars  n  mean   sd   min  max range   se
## X1    1 38 -0.17 0.92 -2.23 1.37  3.59 0.15
## -------------------------------------------------------- 
## group: 3
##    vars  n mean   sd   min  max range   se
## X1    1 25 0.11 1.22 -2.21 2.18  4.39 0.24
## -------------------------------------------------------- 
## group: 4
##    vars n mean   sd  min  max range   se
## X1    1 5 0.86 0.48 0.19 1.37  1.18 0.21
## -------------------------------------------------------- 
## group: 5
##    vars n  mean   sd   min  max range   se
## X1    1 4 -0.19 1.16 -1.43 1.37   2.8 0.58
```

Die Ergebnisse des Boxplots lassen sich schwer interpretieren. Man sieht, dass die ersten drei Gruppen ziemlich ident sind. Die Gruppe vier weist die höchsten Werte auf, während die Gruppe fünf die niedrigsten Werte aufweist. Daher werden wir weitere Tests durchführen.

##### Bartlet test
Mit diesem Test werden wir überprüfen, ob die Varianzen in den Gruppen gleich sind.  
  

```r
bartlett.test(av_r.scores$moderat~fragebogen$wu)
```

```
## 
## 	Bartlett test of homogeneity of variances
## 
## data:  av_r.scores$moderat by fragebogen$wu
## Bartlett's K-squared = 5.8941, df = 4, p-value = 0.2072
```
Der p-Wert ist >0.01 und daher nicht signifikant. Nun können wir weitere Tests durchführen. 


##### $\chi^2$-Unabhängigkeitstest
Nachdem wir herausfinden möchten, ob eine Abhängigkeit zwischen der Zufriedenheit mit dem multikulturellen Umfeld auf der WU und Fremdenfeindlichkeit besteht, werden wir einen $\chi^2$-Unabhängigkeitstest durchführen.


```r
chisq.test(av_r.scores$moderat, fragebogen$wu)
```

```
## Warning in chisq.test(av_r.scores$moderat, fragebogen$wu): Chi-squared
## approximation may be incorrect
```

```
## 
## 	Pearson's Chi-squared test
## 
## data:  av_r.scores$moderat and fragebogen$wu
## X-squared = 315.86, df = 336, p-value = 0.7784
```
   
Die Nullhypothese wird beibehalten (p = 0.7784). Die Fremdenfeindlichkeit hängt nicht von der Zufriedenheit der Studierenden mit dem multikulturellen Umfeld auf der WU ab.

##### Boxplot: Aggressiv und WU
Im Zweiten Boxplot wird die Komponente "Aggressiv" überprüft.
  

```r
boxplot(av_r.scores$aggressiv ~ fragebogen$wu)
```

![](bericht_files/figure-latex/boxplot: aggresiv - wu-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 10: Boxplot: Aggressiv und Passiv}
\bigskip
\end{center}
  
Mittels describeBy()-Funktion können wir uns auch eine numerische Beschreibung der Daten ansehen, die
prinzipell unterstützdend für die Interpretation des Boxplots verwendet werden kann.  
  

```r
describeBy(av_r.scores$aggressiv, fragebogen$wu, skew=FALSE)
```

```
## 
##  Descriptive statistics by group 
## group: 1
##    vars  n mean   sd  min  max range   se
## X1    1 27 0.15 0.81 -2.6 1.07  3.67 0.16
## -------------------------------------------------------- 
## group: 2
##    vars  n  mean   sd   min  max range   se
## X1    1 38 -0.04 1.06 -2.96 1.42  4.38 0.17
## -------------------------------------------------------- 
## group: 3
##    vars  n  mean   sd   min  max range   se
## X1    1 25 -0.15 1.07 -3.67 0.96  4.62 0.21
## -------------------------------------------------------- 
## group: 4
##    vars n mean   sd  min  max range   se
## X1    1 5 0.43 0.14 0.31 0.64  0.33 0.06
## -------------------------------------------------------- 
## group: 5
##    vars n  mean   sd   min  max range   se
## X1    1 4 -0.18 1.78 -2.82 0.96  3.78 0.89
```
  
Die Ergebnisse des Boxplots lassen sich schwer interpretieren. Man sieht, dass die Ergbenisse keiner logischen Verteilung unterliegen. Wähend die erste Gruppe hochen Werte aufweist, sind die Gruppen zwei und drei absteigend. Gruppe vier wieder hoch und und die letzte Gruppe wieder niedrig.
  
Daher werden wir weitere Tests durchführen.
  

##### Bartlet test
Mit diesem Test werden wir überprüfen, ob die Varianzen in den Gruppen gleich sind.
  

```r
bartlett.test(av_r.scores$aggressiv~fragebogen$wu)
```

```
## 
## 	Bartlett test of homogeneity of variances
## 
## data:  av_r.scores$aggressiv by fragebogen$wu
## Bartlett's K-squared = 16.447, df = 4, p-value = 0.002474
```

Der p-Wert ist >0.01 und daher nicht signifikant. Nun können wir weitere Tests durchführen
  
##### $\chi^2$-Unabhängigkeitstest

Nachdem wir herausfinden möchten, ob eine Abhängigkeit zwischen der Zufriedenheit mit der WU und Fremdenfeindlichkeit besteht, werden wir einen $\chi^2$-Unabhängigkeitstest durchführen.
  

```r
chisq.test(av_r.scores$aggressiv,fragebogen$wu)
```

```
## Warning in chisq.test(av_r.scores$aggressiv, fragebogen$wu): Chi-squared
## approximation may be incorrect
```

```
## 
## 	Pearson's Chi-squared test
## 
## data:  av_r.scores$aggressiv and fragebogen$wu
## X-squared = 315.86, df = 336, p-value = 0.7784
```
  
Die Nullhypothese wird beibehalten (p = 0.7784). Die Fremdenfeindlichkeit hängt nicht von der Zufriedenheit der Studierenden mit dem multikulturellen Umfeld auf der WU ab.

## Hypothese 5

### Problemanalyse
In diesem Abschnitt wollen wir überprüfen, ob die Einstellung der Studierenden gegenüber AusländerInnen abhängig vom Kontakt zu ausländischen Personen ist.

Unsere Hypothese dazu lautet:
*Je mehr Kontakt Studenten zu ausländischen Mitbürgern haben, desto besser sind die Einstellungen Ausländern gegenüber.*

#### Welche Variablen kommen vor?
Erklärende Variable: Kontakt zu Ausländern
  
  - Likertskala mit 5 Items;
  - Ordinalskala mit einem Item;

   
Responsevariable: Fremdenfeindlichkeit  
    
Wurde bereits im Kapitel x behandelt; Die Ergebnisse werden für diese Analyse weiterverwendet 
     
   - av_r.scores$moderat, Fremdenfeindlichkeit "moderat"", metrisch
      
   - av_r.scores$aggressiv, Fremdenfeindlichkeit "aggressiv", metrisch

  
  


#### Welche Methode ist angebracht?
t-Test; Unabhängigkeitstest

#### Welche Hypothesen können formuliert werden?
+-----------+------------------------------------------------------------------------------------------------------------------+
| H~0~     | Die eigene Einstellung zu MigratenInnen ist unabhängig von Kontakt zu ausländischen Personen.             |
+-----------+------------------------------------------------------------------------------------------------------------------+
| H~A~    | Die eigene Einstellung zu MigratenInnen ist abhängig von Kontakt zu ausländischen Personen.                  |
+-----------+------------------------------------------------------------------------------------------------------------------+
  
+-----------+------------------------------------------------------------------------------------------------------------------+
| H~0~    | Die eigene Einstellung zu MigratenInnen ist unabhängig von der Anzahl ausländischer Freunde.             |
+-----------+------------------------------------------------------------------------------------------------------------------+
| H~A~    | Die eigene Einstellung zu MigratenInnen ist abhängig von der Anzahl ausländischer Freunde.                  |
+-----------+------------------------------------------------------------------------------------------------------------------+

  

#### Die unabhängige Variable - Kontakt zu Ausländern

+-----------+------------------------------------------------------------------------------------------------------------------+
| Variablen | Item                                                                                                             |
+===========+==================================================================================================================+
| arbeiten  | Ich arbeite oft mit AusländerInnen zusammen                                       |
+-----------+------------------------------------------------------------------------------------------------------------------+
| skype     | Ich skype oft mit Freunden in anderen ländern            |
+-----------+------------------------------------------------------------------------------------------------------------------+
| treffen   | Ich treffe oft Freunde, viele davon sind AusländerInnen                  |
+-----------+------------------------------------------------------------------------------------------------------------------+
| engag     | Ich engagiere mich in einem Verein um AusländerInnen besser zu integrieren (z.B. Fussballclub)                                          |
+-----------+------------------------------------------------------------------------------------------------------------------+
| lv        | In Lehrveranstaltungen auf der Uni habe ich oft mit ausländischen Studierenden zusammengearbeitet       |
+-----------+------------------------------------------------------------------------------------------------------------------+
  
#### Die unabhängige Variable - Anzahl ausländischer Freunde

+-----------+------------------------------------------------------------------------------------------------------------------+
| Variablen | Item                                                                                                             |
+===========+==================================================================================================================+
| kreis     | Wieviele AusländerInnen gibt es in deinem engeren Freundeskreis?                                       |
+-----------+------------------------------------------------------------------------------------------------------------------+

##### Balkendiagramm: Anzahl ausländischer Feunde
Zürst schaün wir uns die Daten mit Hilfe eines Balkendiagramms an.  
  

```r
countr <- table(fragebogen$kreis)
rownames(countr) <- c("0-1", "2-3", "4-5", "6-7", "8-9", ">10")
barplot(countr, main="Anzahl ausländischer Freunde", ylim=c(0,60), xlab="Item: wieviele AusländerInnen gibt es in deinem engeren Freundeskreisö", ylab="Anzahl")
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/barplot var Kreis-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 11: Barplot: ausländische Freunde}
\bigskip
\end{center}
  
Aus dem Balkendiagramm können wir erkennen, dass knapp 6% der Befragen nur 0-1 ausländische Freunde haben. Alleine, dass die Meisten mehr als zwei ausländische Freunde haben, ist es ein zeichen für einen multikulturellen Umfeld auf der WU-Wien. Hinzu kommt noch, dass über 40% der Befragten mehr als 10 angekreuzt haben.        

### Kurzbericht

Die Einstellung der Personen im sozialen Umfeld wurde anhand von neun Items überprüft. 
Die übergerordente Frage dazu lautet: "Einstellung zur Migration in deinem sozialen Umfeld?" 
Als Maßstab wurde eine Intervallskala von eins bis sechs verwendet, wobei 1 = "Trifft sehr zu" und 6 = "Trifft gar nicht zu".  

Da wir hier mit multivairate Datean zu tun haben, wird eine Hauptkomponentenanalyse durchtgeführt, um die Datendimension zu reduzieren.  

#### Voraussetzungen für die Hauptkomponentenanalyse

Bevor wir die Voraussetzungen überprüfen, müssen wir die richtigen Daten auswählen. Wir werden alle Daten mit NAs entfernen und schaün uns das Ergebniss an. 


```r
library("psych")
library("zoo")
kontakt<-na.omit((fragebogen[,29:33]))
nrow(kontakt)
```

```
## [1] 99
```

```r
kontakt
```

```
##     arbeiten skype treffen engag lv
## 1          1     4       2     6  1
## 2          2     6       4     6  3
## 3          2     6       2     6  2
## 4          3     6       5     6  4
## 5          1     6       5     6  2
## 6          1     6       5     6  3
## 7          1     1       1     6  1
## 8          1     4       2     5  1
## 9          1     6       1     6  1
## 10         1     6       3     6  3
## 11         1     6       3     6  1
## 12         2     6       4     6  1
## 13         2     6       4     6  1
## 14         2     6       1     6  4
## 15         1     1       1     6  2
## 16         1     5       5     6  1
## 17         3     1       2     5  3
## 18         4     6       3     6  2
## 19         3     4       1     5  4
## 20         1     3       1     6  1
## 21         5     6       5     6  4
## 22         3     6       2     1  3
## 23         5     6       5     5  6
## 24         2     1       3     5  5
## 25         1     3       3     3  1
## 26         6     6       3     6  3
## 27         4     6       4     6  6
## 28         1     1       1     6  1
## 29         1     1       1     1  1
## 30         4     3       2     4  1
## 31         1     1       1     4  1
## 32         1     1       1     1  1
## 33         1     4       1     4  1
## 34         1     3       2     6  2
## 35         1     1       1     3  5
## 36         2     3       2     6  1
## 37         3     6       3     6  1
## 38         2     6       2     6  1
## 39         2     2       3     6  6
## 40         1     6       1     6  6
## 41         2     4       2     6  4
## 42         1     6       1     6  3
## 43         2     5       1     6  4
## 44         6     4       2     5  1
## 45         1     1       1     1  1
## 46         2     1       1     5  2
## 48         5     6       6     6  2
## 49         5     6       6     6  4
## 50         2     6       4     6  4
## 51         2     3       3     2  2
## 52         2     6       2     6  1
## 53         4     5       5     6  2
## 54         5     6       5     5  3
## 55         6     6       6     5  5
## 56         2     4       3     1  1
## 57         4     5       2     3  2
## 58         5     5       5     6  3
## 59         3     2       5     6  1
## 60         4     3       5     6  2
## 61         3     5       5     4  3
## 62         3     6       4     6  4
## 63         1     3       1     1  1
## 64         1     3       4     6  1
## 66         3     6       3     6  2
## 67         3     5       5     6  1
## 68         5     6       6     6  3
## 69         4     6       5     6  2
## 70         4     6       5     5  1
## 71         2     4       2     6  5
## 72         3     2       2     6  1
## 73         1     3       1     5  2
## 74         1     1       1     6  1
## 75         2     3       2     6  2
## 76         3     3       3     5  2
## 77         3     4       3     6  3
## 78         2     6       5     6  6
## 79         3     5       3     6  3
## 80         2     2       2     3  3
## 81         1     1       1     1  2
## 82         1     6       1     6  1
## 83         6     6       6     2  5
## 84         1     1       3     5  1
## 85         1     4       1     2  2
## 86         4     6       5     6  3
## 87         2     6       4     6  4
## 88         1     3       1     6  4
## 89         1     4       1     6  1
## 90         2     2       2     5  2
## 91         2     6       3     6  1
## 92         3     6       6     6  6
## 93         6     6       6     6  5
## 94         1     4       2     6  2
## 95         1     1       1     3  1
## 96         2     4       2     1  1
## 97         2     1       3     6  1
## 98         3     5       4     6  2
## 99         5     6       2     6  5
## 100        1     3       4     6  3
## 101        1     1       1     6  1
```
  
Wenn wir für die  ausgewählten Items alle Zeilen wo mindestens ein NA vorkommt entfernen, dann bleiben uns in Summe nur noch 94 Datensätze übrig. An erster Stelle ist es natürlich Schade, Datensätze wegen ein bis zwei NA zu entfernen. Aber wir erinnern uns zurück, dass wir für die abhängige Variable "Fremdenfeindlichkeit" 99 Datensätze verwendet haben.  

Damit wir gleich vielen Daten für die abhängige- und unabhängige Variable verwenden können, werden wir die Rohdaten wieder hernehmen und fehlende Einräge mit der *na.approx*-Funktion ergänzen. Und danach die Datensätze mit der "!is.na"-Funktion auf jene Daten reduziert, die in der Variable "Heimat", welche im Datensatz der Hautpkomponentenanalyse der "Fremdenfeindlichkeit" vorkommt.


```r
library("psych")
library("zoo")
kontakt<-kontakt[!is.na(av["heimat"]),]
nrow(kontakt)
```

```
## [1] 99
```
   
Jetzt haben wir exakt 99 Datensätze, die mit der abhängigen Varialbe "Fremdenfeindlichkeit" übereintimmen.  

##### Bartlett-Test: "Kontakt"

Nachdem unser Datensatz für die weitere Bearbeitung dementsprechend vorbereitet wuden, können wir nun mit der überprüfung der Voraussetzungen für die Hauptkomponentenanalyse loslegen.  

Als Erstes führen wir den Bartlett-Test durch: 

```r
library("REdaS")
bart_spher(kontakt)
```

```
## 	Bartlett's Test of Sphericity
## 
## Call: bart_spher(x = kontakt)
## 
##      X2 = 116.202
##      df = 10
## p-value < 2.22e-16
```


Die Teststatistik zeigt ein klares Ergebnis, da die Teststatistik $X^2=312.309$ mit einer $\chi^2$-Verteilung mit 36 Freiheitsgraden einen p-Wert unter 0.00000000000000022 erzeugt. Je kleiner der p-Wert ist, desto mehr Grund gibt es, die Nullhypothese zu verwerfen. Die Nullhypothese, dass es keine Korrelationen zwischen den Variablen gibt kann verworfen werden und das Resultat daher als statistisch signifikant bezeichnet werden.  
       
##### KMO und MSA: "Kontakt" 
Als nüchstes werden wir die MSAs und die KMO überprüfen.

```r
kmosmd <- KMOS(kontakt)
print(kmosmd, stats="KMO")
```

```
## 
## Kaiser-Meyer-Olkin Statistic
## Call: KMOS(x = kontakt)
## 
## KMO-Criterion: 0.7412688
```

```r
print(kmosmd, stats="MSA", sort=TRUE, digits=3, show=1:5)
```

```
## 
## Kaiser-Meyer-Olkin Statistics
## 
## Call: KMOS(x = kontakt)
## 
## Measures of Sampling Adequacy (MSA):
## arbeiten    engag  treffen    skype       lv 
##    0.700    0.706    0.711    0.787    0.853
```

Der Wert des KMO liegt bei 0.8040357 und die MSA-Werte liegen bei > als 0,6. Die Daten sind also als sehr gut geeignet einzustufen weil genügend Informationen zur Durchführung einer Hauptkomponentenanalyse vorliegen. 

##### Scree Plot: kontakt
Mittels Scree Plot können wir nun überürfen, wieviele Hauptkomponenten für die Hauptkomponentennalyse benötigt werden.

```r
VSS.scree(kontakt)
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/Umfeld: Scree plot5-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 12: Scree Plot:Umfeld}
\bigskip
\end{center}

Der Screeplot zeigt, dass die ersten 2 Komponenten einen Eigenwert > 1 haben, die anderen liegen unter diesem Kriterium.   

##### Hauptkomponentenanalyse: "Umfeld"
Basierend auf der Information aus dem Screeplot werden wir im ersten Versuch zwei Komponenten extrahieren und vorerst keine Rotation durchführen. Um den Output zu reduzieren, wird die Objektkomponente *criteria* entfernt. 

```r
pca.kontakt <- principal(kontakt, 2, rotate="none")
pca.kontakt$criteria<-NULL
pca.kontakt
```

```
## Principal Components Analysis
## Call: principal(r = kontakt, nfactors = 2, rotate = "none")
## Standardized loadings (pattern matrix) based upon correlation matrix
##           PC1   PC2   h2    u2 com
## arbeiten 0.78 -0.38 0.75 0.254 1.5
## skype    0.78  0.16 0.63 0.368 1.1
## treffen  0.83 -0.11 0.70 0.300 1.0
## engag    0.48  0.83 0.92 0.078 1.6
## lv       0.60 -0.22 0.41 0.588 1.3
## 
##                        PC1  PC2
## SS loadings           2.49 0.92
## Proportion Var        0.50 0.18
## Cumulative Var        0.50 0.68
## Proportion Explained  0.73 0.27
## Cumulative Proportion 0.73 1.00
## 
## Mean item complexity =  1.3
## Fit based upon off diagonal values = 0.91
```

Komponente PC1 erklärt 45% der Varianz und Komponente PC2 12%. Beide Komponenten zusammen erklären 57% und sind > 1. Die Hinzunahme weiterer Variablen ist nicht sinnvoll weil alle weiteren Eigenwerte kleiner als 1 sind. 


Es werden zwei Hauptkomponenten extrahiert und nach der Varimaxmethode rotiert. Die Komponenten mit den hoch ($\ge 0.48$) auf ihnen ladenden Variablen sind:


1. Komponente (RC1): Passives Umfeld (Eigenwert: 2.761, erklärte Varianz: 30,7%)
  "Angst um die eigene Sicherheit"  .834
  "Fremdenfeindliche Personen im Umfeld" .756
  "Bereits negative Erfahrung mit AusländerInnen"  .694
  "FPÖ-Wähler im Umfeld" .624
2. Komponente (RC2): Aktives Umfeld (Eigenwert: 2.396, erklärte Varianz: 26,6%)
  "Gewalt ausüben" .8
  "Bei Demosnstrationen gegen AusländerInnen teilnehmen"  .664
  "AuländerInnen für Kriminelle halten" .642
  "über AusländerInnen scherzen"  .558
  "über AusländerInnen diskutieren"  .481

##### Zuordnung der Items: "Kontakt"
Als nüchstes schaün wir uns die Ergebnisse grafisch an.

```r
fa.diagram(pca.kontakt, cut=0.5, cex=0.8, rsize=0.5, main="")
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/Kontakt PCA: diagram-1.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 13: Fa-Diagram: Kontakt}
\bigskip
\end{center}
  
Anhand der durchwegs positiven Ladungen kann man erkennen, dass Personen mit hohen Werten bei den jeweiligen Items auch hohe Ausprägungen auf der Komponente haben. Die zwei extrahierten Hauptkomponenten sind direkt interpretierbar als "aktives-" und "passives Umfeld". Menschen die bereit sind Gewalt gegen AusländerInnen auszuüben, bei Demonstrationen teilzunehmen, über Ausländer scherzen und diskutieren oder diese für Kriminelle halten, befinden sich auf der aktiven Seiten.

##### Factor Scores: "Umfeld"
für die weitere Analyse werden factor scores angelegt. 


```r
round(head(pca.kontakt$scores), 4)
```

```
##       PC1    PC2
## 1 -0.6187 1.1802
## 2  0.6294 0.6292
## 3  0.0718 0.9292
## 4  1.1930 0.1290
## 5  0.4677 0.9837
## 6  0.6234 0.8294
```

```r
kontakt.scores <- data.frame(pca.kontakt$scores)
names(kontakt.scores) <- c("kreis")
round(head(kontakt.scores), 4)
```

```
##     kreis     NA
## 1 -0.6187 1.1802
## 2  0.6294 0.6292
## 3  0.0718 0.9292
## 4  1.1930 0.1290
## 5  0.4677 0.9837
## 6  0.6234 0.8294
```

```r
# Weitere Analyse mit den folgenden beiden Variablen:
kontakt.scores$kreis
```

```
##  [1] -0.61865068  0.62941431  0.07183557  1.19301172  0.46766860
##  [6]  0.62339563 -1.31129858 -0.74069980 -0.49176184  0.22154393
## [11] -0.08991014  0.31796024  0.31796024  0.18236379 -1.15557154
## [16]  0.14803422 -0.50707873  0.68665048 -0.06055550 -0.98348388
## [21]  1.60690077 -0.17573847  1.79630572 -0.20164333 -0.94777954
## [26]  1.25626657  1.51048446 -1.31129858 -1.92154418 -0.40582269
## [31] -1.55539682 -1.92154418 -1.06367478 -0.62683100 -1.05453781
## [36] -0.57561350  0.32397892 -0.08389146  0.24004017  0.28687333
## [41]  0.05547494 -0.18030777  0.01845644  0.29402283 -1.92154418
## [46] -1.07067614  1.49637256  1.80782662  0.78514134 -0.70715710
## [51] -0.08389146  0.92459483  1.32912462  2.04844906 -0.82102591
## [56] -0.04433008  1.28726639  0.07020123  0.59678014  0.62927909
## [61]  0.99208587 -1.59372949 -0.38070633  0.47970595  0.56192327
## [66]  1.65209959  1.08850218  0.81072602  0.21120198 -0.53257632
## [71] -0.94980597 -1.31129858 -0.41988647 -0.13406521  0.30761829
## [76]  1.29752126  0.47152564 -0.79421415 -1.76581715 -0.49176184
## [81]  1.68230170 -1.03149600 -1.15204599  1.24422921  0.78514134
## [86] -0.51630278 -0.81957653 -0.70584294  0.11703439  1.70539164
## [91]  2.17049818 -0.46292365 -1.67744594 -1.02195176 -0.70250235
## [96]  0.51672445  1.15985025 -0.06925226 -1.31129858
```

#### Überprüfung der Hypothesen

## Hypothese 6

Das öffentliche Bild von "Fremdenfeinden" ist eher männlich durch beispielsweise fremdenfeindliche Gewalttaten, oder Aufmärsche im rechten Milieu geprägt. Daher ist es interessant zu untersuchen ob es geschlechtsabhängige Tendenzen bei Fremdenfeindlichkeit gibt. 

*Gibt es Unterschiede bei der Fremdenfeindlichkeit zwischen Frauen und Männern?*


### Problemanalyse
#### Welche Variablen kommen vor?
    
Erklärende Variable: sex, Geschlecht (kategorial)
Responsevariable(n): Fremdenfeindlichkeit

  - av_r.scores$moderat, Fremdenfeindlichkeit moderat (metrisch)
  - av_r.scores$aggressiv, Fremdenfeindlichkeit stark (metrisch)


#### Welche Methode ist angebracht?
t-Test oder Mann-Whitney U-Test

#### Welche Hypothesen können formuliert werden?

+-----------+------------------------------------------------------------------------------+
| H~0~:     | Die moderate Fremdenfeindlichkeit ist bei Männern und Frauen gleich          |
+-----------+------------------------------------------------------------------------------+
| H~A~:     | Die moderate Fremdenfeindlichkeit unterscheidet sich bei Männern und Frauen  |
+-----------+------------------------------------------------------------------------------+

+-----------+------------------------------------------------------------------------------+
| H~0~:     | Die agressive Fremdenfeindlichkeit ist bei Männern und Frauen gleich         |
+-----------+------------------------------------------------------------------------------+
| H~A~:     | Die agressive Fremdenfeindlichkeit unterscheidet sich bei Männern und Frauen |
+-----------+------------------------------------------------------------------------------+

### Kurzbericht



```r
boxplot(av_r.scores$moderat ~ fragebogen$sex, names=c("weiblich", "männlich"))
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/plots moderat-1.pdf)<!-- --> 

```r
densbox(av_r.scores$moderat ~ fragebogen$sex)
```

![](bericht_files/figure-latex/plots moderat-2.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 14 + 15: Moderate Fremdenfeindlichkeit nach Geschlecht}
\bigskip
\end{center}


```r
bartlett.test(av_r.scores$moderat~fragebogen$sex)
```

```
## 
## 	Bartlett test of homogeneity of variances
## 
## data:  av_r.scores$moderat by fragebogen$sex
## Bartlett's K-squared = 0.016051, df = 1, p-value = 0.8992
```

Generell kann man sagen, dass Frauen niedrigere Werte für moderate Fremdenfeindlichkeit aufweisen (negative Werte bedeuten eine höhere Fremdenfeindlichkeit). Die Spannweite ist bei Männern größer. Die Minima sind bei beiden gleich, das Maximum bei Männern höher. Die Streuung ist bei beiden gleich (p = 0.8992). 


```r
boxplot(av_r.scores$aggressiv ~ fragebogen$sex, names=c("weiblich", "männlich"))
box(which="figure", lty="solid", col="black")
```

![](bericht_files/figure-latex/plots agressiv-1.pdf)<!-- --> 

```r
densbox(av_r.scores$aggressiv ~ fragebogen$sex)
```

![](bericht_files/figure-latex/plots agressiv-2.pdf)<!-- --> 
\begin{center}
\textit{Abbildung 16: Agressive Fremdenfeindlichkeit nach Geschlecht}
\bigskip
\end{center}



```r
bartlett.test(av_r.scores$aggressiv~fragebogen$sex)
```

```
## 
## 	Bartlett test of homogeneity of variances
## 
## data:  av_r.scores$aggressiv by fragebogen$sex
## Bartlett's K-squared = 0.053181, df = 1, p-value = 0.8176
```

Am Boxplot sieht man dass die Verteilungen Ausreißer haben. Die Spannweite ist diesmal bei den Frauen größer. Die Streuung ist bei den Frauen geringer aber nicht signifikant (p = 0.8176). 



```r
t.test(av_r.scores$moderat~fragebogen$sex, var.equal=TRUE)
```

```
## 
## 	Two Sample t-test
## 
## data:  av_r.scores$moderat by fragebogen$sex
## t = 0.28706, df = 97, p-value = 0.7747
## alternative hypothesis: true difference in means is not equal to 0
## 95 percent confidence interval:
##  -0.3437114  0.4599506
## sample estimates:
## mean in group 1 mean in group 2 
##      0.03111453     -0.02700506
```


```r
wilcox.test(av_r.scores$moderat~fragebogen$sex, var.equal=TRUE)
```

```
## 
## 	Wilcoxon rank sum test with continuity correction
## 
## data:  av_r.scores$moderat by fragebogen$sex
## W = 1231, p-value = 0.9356
## alternative hypothesis: true location shift is not equal to 0
```


Bei der moderaten Fremdenfeindlichkeit wird die Nullhypothese wird beibehalten, es gibt daher bei Fremdenfeindlichkeit bei Männern und Frauen keine Unterschiede (t-Test p = 0.7747; Wilcox-Test p = 0.9356).  



```r
t.test(av_r.scores$aggressiv~fragebogen$sex, var.equal=TRUE)
```

```
## 
## 	Two Sample t-test
## 
## data:  av_r.scores$aggressiv by fragebogen$sex
## t = -0.68443, df = 97, p-value = 0.4953
## alternative hypothesis: true difference in means is not equal to 0
## 95 percent confidence interval:
##  -0.5393308  0.2627382
## sample estimates:
## mean in group 1 mean in group 2 
##     -0.07403741      0.06425889
```


```r
wilcox.test(av_r.scores$aggressiv~fragebogen$sex, var.equal=TRUE)
```

```
## 
## 	Wilcoxon rank sum test with continuity correction
## 
## data:  av_r.scores$aggressiv by fragebogen$sex
## W = 1037.5, p-value = 0.2037
## alternative hypothesis: true location shift is not equal to 0
```


Auch bei der starken Fremdenfeindlichkeit wird die Nullhypothese beibehalten, es gibt daher auch hier zwischen Männern und Frauen keine Unterschiede (t-Test p = 0.4953; Wilcox-Test p = 0.2037).  


\clearpage
\section{Anhang}

## Übersicht Datensatz

Ausgabe der ersten 5 Zeilen: 


 Nr.   wu   publikum   spass   wohl   reden   party   kurier   presse   krone   oesterreich   standard
----  ---  ---------  ------  -----  ------  ------  -------  -------  ------  ------------  ---------
   1    3          5       2      2       3       3        4        3       4             4          4
   2    3          4       2      3       1       3        1        4       3             4          4
   3    2          5       1      5       1       1        1        2       3             4          2
   4    3          6       2      2       4       4        4        4       4             4          3
   5    1          3       2      2       2       4        3        3       2             3          4



 heute   wiener   kleine   orf   zeit   bild   diskut   scherzen   erfahrung   demo   gewalt   krimi
------  -------  -------  ----  -----  -----  -------  ---------  ----------  -----  -------  ------
     4        4        4     1      4      4        3          2           4      3        6       5
     3        4        4     2      4      4        3          4           2      5        6       6
     4        4        3     1      4      4        5          5           5      5        6       6
     4        4        4     3      3      4        2          4           6      6        6       6
     4        4        3     2      4      4        4          1           5      3        6       3



 fpoe   sicherheit   feindlich   kreis   arbeiten   skype   treffen   engag   lv   heimat   rechte   kultur
-----  -----------  ----------  ------  ---------  ------  --------  ------  ---  -------  -------  -------
    2            3           2       6          1       4         2       6    1        6        6        6
    5            3           4       4          2       6         4       6    3        5        5        5
    5            5           6       6          2       6         2       6    2        6        6        6
    5            6           5       3          3       6         5       6    4        6        6        6
    1            2           3       2          1       6         5       6    2        6        6        6



 verlassen   partner   knapp   pflegen   politik   verdienen   egal   sex
----------  --------  ------  --------  --------  ----------  -----  ----
         6         6       6         6         6           6      6     2
         6         6       2         4         5           3      6     2
         6         6       3         4         6           4      6     2
         6         6       6         6         6           6      4     2
         6         6       3         4         5           5      6     2

\begin{center}
\textit{Tabelle 3: Ein Auszug der Daten}
\bigskip
\end{center}

## Übersicht NA


```r
na_count <- sapply(fragebogen[-1,], function(y) sum(is.na(y)))
kable(na_count, format="latex", digits=2, longtable=TRUE)
```


\begin{longtable}{l|r}
\hline
Nr. & 0\\
\hline
wu & 0\\
\hline
publikum & 0\\
\hline
spass & 0\\
\hline
wohl & 0\\
\hline
reden & 0\\
\hline
party & 0\\
\hline
kurier & 0\\
\hline
presse & 1\\
\hline
krone & 0\\
\hline
oesterreich & 0\\
\hline
standard & 0\\
\hline
heute & 0\\
\hline
wiener & 1\\
\hline
kleine & 1\\
\hline
orf & 1\\
\hline
zeit & 1\\
\hline
bild & 1\\
\hline
diskut & 0\\
\hline
scherzen & 1\\
\hline
erfahrung & 0\\
\hline
demo & 0\\
\hline
gewalt & 2\\
\hline
krimi & 1\\
\hline
fpoe & 1\\
\hline
sicherheit & 0\\
\hline
feindlich & 0\\
\hline
kreis & 0\\
\hline
arbeiten & 0\\
\hline
skype & 0\\
\hline
treffen & 0\\
\hline
engag & 0\\
\hline
lv & 0\\
\hline
heimat & 0\\
\hline
rechte & 0\\
\hline
kultur & 0\\
\hline
verlassen & 0\\
\hline
partner & 0\\
\hline
knapp & 0\\
\hline
pflegen & 0\\
\hline
politik & 0\\
\hline
verdienen & 0\\
\hline
egal & 0\\
\hline
sex & 0\\
\hline
\end{longtable}

\begin{center}
\textit{Tabelle 4: Übersicht der NA im Datensatz}
\bigskip
\end{center}



```r
# Summe aller NA im Datensatz
sum(is.na(fragebogen))
```

```
## [1] 11
```
\section{Referenzen}
\appendix

<!--
# References
\setlength{\parindent}{-0.2in}
\setlength{\leftskip}{0.2in}
\setlength{\parskip}{8pt}
\vspace*{-0.2in}
\noindent
-->

