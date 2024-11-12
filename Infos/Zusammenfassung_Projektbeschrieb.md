# Echtdarstellung von Wassermessungen in WebGIS-Popup Fenster kombiniert mit KI-generierten Prognosekarten für Naturgefahren
Das [WebGIS](https://map.geo.sz.ch) stellt zahlreiche Daten mit Koordinatenbezug dar. Viele der Daten sind eher statisch und werden nur einmal täglich (Nacht) oder bei Bedarf aktualisiert. Neu eingepflegte Daten werden dadurch erst am nächsten Tag ersichtlich. Ausserdem stellen die Werte nur die aktuelle Situation dar. Der dynamische Wandel der Werte über eine Periode kann heute nicht über das WebGIS nachverfolgt werden. </br>
</br> 
Das Amt für Gewässer AFG betreibt Messstellen an Gewässer, die in einer höheren zeitlichen Auflösung über den Tag Daten liefern. Die zahlreichen Informationen werden in das WISKI-System, einer Datenbank, eingespiesen. Jedoch werden diese Daten noch nicht ausgewertet und dargestellt. Neben dem AFG gibt es noch andere Interessenten für die Darstellung von dynamischen Daten im GIS. </br>
</br> 
Künstliche Intelligenz ist heutzutage in aller Munde und ein sehr mächtiges Tool. Aus Trainingsdaten kann eine KI-Applikation lernen, wie sich künftige Daten verhalten könnten. Dies könnte man beispielsweise für Prognosekarten im Bereich der Naturgefahren oder Klimaentwicklung nutzen. </br>
</br>

## Idee
Der Challenge Task besteht aus zwei teilen. Der erste Teil ist die Darstellung der Messungen über einen Zeitraum. Der zweite Teil der Aufgabe ist die Entwicklung einer Prognosekarte für aktuelle 

### Teil 1 der Challenge: Echtzeit-Darstellung
Bei den Messstationen sind Links hinterlegt, die einen Request an das Backend senden. Also Response soll ein Popup-Fenster zurückgeliefert werden, welches aufbereitete Informationen zu der jeweiligen Station darstellet. Das Fenster soll folgende Informationen erhalten:
-	Stationsinformation
-	Aktuelle Messdaten (Text, aufbereitet)
-	Diagramme (Grafisch aufbereitet)

Für diese Challenge gibt es ein konkretes Beispiel, welches uns das Amt für Gewässer Kanton Schwyz zur Verfügung gestellt hat. Über eine Schnittstelle können dynamischen Daten einer bestimmten Messstation abgefragt werden. Es werden folgende Daten gemessen:
-	Wassertemperatur
-	pH-Wert
-	Elektrische Leitfähigkeit

Ähnliche Beispiele der Umsetzung finden sich bei den Kantonen:
- [Luzern](https://www.geo.lu.ch/messdaten/hydrometrie)
- [Uri](https://geo.ur.ch/?basemap=PKGRAU&center=960861%2C5921756&layers=Oberfl%C3%A4chengew%C3%A4sser%20Pegel%20und%20Abfluss&layersidebarvisible=true&opacity=1&visibility=true&zoom=13)

### Teil 2 der Challenge: KI-Prognosen 

## Anforderung

### Teil 1
| Id | Anforderung | Gewichtung | Priorität | Ergänzung |
| -- | ----------- | ---------- | --------- | --------- |
| | | | | |

## Ziel
