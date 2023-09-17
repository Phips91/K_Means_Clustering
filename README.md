# K_Means_Clustering


#Projektname: K-Mean Clustering

Anleitung zum Betrieb des Codes: 
1. MyBinder über den BinderBatch öffnen
2. Nach dem öffnen des MyBinder, das Notebook ist auf der Linken Seite der Webpage zu finden, durch doppelklick wird es geöffnet.
3. Über den PlayButton können Sie das Notebook Schritt für Schritt durchführen.


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Phips91/K_Means_Clustering.git/HEAD)

Dieser Code ist eine Dokumentation für ein K-Means-Clustering-Projekt, bei dem Daten von Universitäten in den USA analysiert werden, um sie in zwei Gruppen (private und öffentliche Universitäten) zu unterteilen. Hier ist eine Zusammenfassung der wichtigsten Teile des Codes und der erwarteten Ergebnisse:

1. **Importieren der Bibliotheken:** Zunächst werden die erforderlichen Python-Bibliotheken importiert, darunter Pandas, NumPy, Matplotlib und Seaborn.

2. **Daten einlesen:** Die Daten werden aus einer CSV-Datei mit dem Namen "College_Data" eingelesen, wobei die erste Spalte als Index festgelegt wird.

3. **Datenüberblick:** Es wird eine Übersicht über die Daten erstellt, einschließlich eines Ausdrucks des Kopfbereichs des DataFrames, Informationen zur Datenstruktur und eine statistische Zusammenfassung der Daten.

4. **Explorative Datenanalyse:** Hier werden verschiedene Visualisierungen erstellt, um die Daten besser zu verstehen. Dazu gehören Scatterplots und Histogramme, die die Beziehung zwischen verschiedenen Variablen in Bezug auf die Art der Universität (privat oder öffentlich) zeigen.

5. **Korrektur der Daten:** Es wird festgestellt, dass es eine Universität gibt, die eine Abschlussrate von mehr als 100% hat, was unmöglich ist. Die Abschlussrate dieser Universität wird auf 100% gesetzt, um die Daten zu korrigieren.

6. **K-Means-Clustering erstellen:** Ein K-Means-Clustering-Modell mit 2 Clustern wird erstellt und auf die Daten angewendet.

7. **Auswertung:** Eine Spalte namens "Cluster" wird erstellt, um die Zuordnung der Universitäten zu den Clustern darzustellen. Anschließend werden eine Confusion Matrix und ein Classification Report erstellt, um die Qualität des K-Means-Clustering-Modells zu bewerten.

Die erwarteten Ergebnisse dieses Codes sind:

- Die explorative Datenanalyse zeigt Visualisierungen der Beziehung zwischen verschiedenen Variablen und der Art der Universitäten.
- Die Korrektur der Daten behebt das Problem mit der Abschlussrate von über 100%.
- Das K-Means-Clustering-Modell weist den Universitäten Cluster zu.
- Die Auswertung zeigt, wie gut das Modell die Universitäten in private und öffentliche Universitäten aufteilt, obwohl die tatsächlichen Zuordnungen bekannt sind. Das Modell sollte eine vernünftige Zuordnung zeigen, die in der Confusion Matrix und im Classification Report angezeigt wird.

Der Code dient dazu, die Grundlagen des K-Means-Clustering-Algorithmus zu demonstrieren und wie er auf reale Daten angewendet werden kann, selbst wenn die tatsächliche Zuordnung der Daten bekannt ist.
