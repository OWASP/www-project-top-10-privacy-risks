---
title: Translation
layout:  null
tab: true
order: 4
tags: example-tag
---
Currently project documentation is available in English and German. If you are interested in helping to translate to another language, please contact the project leaders.
## German
### Top 10 Datenschutzrisiken
<table style="background-color:#FFFFFF;border-collapse:collapse;border:1px solid #000000;color:#000000;width:100%" cellspacing="3" cellpadding="3" border="1">

<tr>
<td bgcolor="#D8D8D8" width="64"><b>#</b></td>
<td bgcolor="#D8D8D8" width="70"><b>Typ</b></td>
<td bgcolor="#D8D8D8" width="160"><b>Titel</b></td>
<td bgcolor="#D8D8D8" width="120"><b>Häufigkeit</b></td>
<td bgcolor="#D8D8D8" width="110"><b>Schaden</b></td>
<td bgcolor="#D8D8D8"><b>Beschreibung</b></td>
</tr>

<tr>
<td>P1</td>
<td>:woman_technologist:</td>
<td>Schwachstellen in Web-Anwendungen</td>
<td bgcolor="orange">Hoch</td>
<td bgcolor="red">Sehr hoch</td>
<td>Schwachstellen sind ein zentrales Problem in jedem System, mit dem sensible Nutzerdaten erhoben, verarbeitet und genutzt werden. Bestehen Fehler im Design oder in der Implementierung der Applikation, werden Probleme nicht entdeckt oder Sicherheitspatches nicht unverzüglich eingespielt, führt dies mit hoher Wahrscheinlichkeit zu einer Verletzung des Persönlichkeitsrechts. Dieses Risiko wird bereits in anderen Projekten behandelt, wie der OWASP Top 10 Liste der häufigsten Sicherheitsrisiken für Webanwendungen.</td>
</tr>

<tr>
<td>P2</td>
<td>:woman_technologist::man_office_worker:</td>
<td>Datenabfluss beim Betreiber</td>
<td bgcolor="orange">Hoch</td>
<td bgcolor="red">Sehr hoch</td>
<td>Wird die unerwünschte Preisgabe personenbezogener oder personenbeziehbarer Daten an nicht autorisierte Personen nicht wirksam verhindert, ist dies ein Verlust der Vertraulichkeit. Ursachen sind entweder ein vorsätzlich durchgeführter Datenabzug oder unbeabsichtigte Fehler wie beispielsweise unzureichendes Zugriffsmanagement, unsichere Datenablage, Datendopplung oder fehlendes Problembewusstsein (Awareness).</td>
</tr>

<tr>
<td>P3</td>
<td>:woman_technologist::man_office_worker:</td>
<td>Unzureichende Reaktion bei einer Datenpanne</td>
<td bgcolor="orange">Hoch</td>
<td bgcolor="red">Sehr hoch</td>
<td>Betroffene werden nicht über mögliche Pannen oder Datenlecks benachrichtigt, die durch Angriffe oder unbeabsichtigte Ereignisse entstehen. Angemessene Abhilfemaßnahmen zum Schließen der Lücken und Beseitigung der Ursache fehlen.</td>
</tr>

<tr>
<td>P4</td>
<td>:woman_technologist::man_office_worker:</td>
<td>Unzureichende Löschung personen-bezogener Daten</td>
<td bgcolor="red">Sehr hoch</td>
<td bgcolor="orange">Hoch</td>
<td>Personenbezogene Daten werden nicht termingerecht oder nicht effektiv nach Zweckablauf bzw. aufgrund einer Löschanfrage gelöscht.</td>
</tr>

<tr>
<td>P5</td>
<td>:man_office_worker:</td>
<td>Intransparente Nutzungs-bedingungen</td>
<td bgcolor="red">Sehr hoch</td>
<td bgcolor="orange">Hoch</td>
<td>Informationen zur Datenverarbeitung wie Erhebung, Speicherung und Nutzung personenbezogener Daten sind unzureichend. Diese Informationen sind nicht leicht zugänglich oder für juristische Laien nicht verständlich aufbereitet.</td>
</tr>

<tr>
<td>P6</td>
<td>:man_office_worker:</td>
<td>Sammeln von Daten, die über den eigentlichen Zweck hinaus gehen</td>
<td bgcolor="red">Sehr hoch</td>
<td bgcolor="orange">Hoch</td>
<td>Es werden Beschreibungsdaten, demographische Daten oder sonstige personenbezogene Daten gesammelt, die nicht für den vereinbarten Zweck der Anwendung benötigt werden. Ebenso werden Daten gesammelt, für deren Erhebung der Nutzer keine Einverständniserklärung abgegeben hat.</td>
</tr>

<tr>
<td>P7</td>
<td>:woman_technologist::man_office_worker:</td>
<td>Weitergabe von Daten an Dritte</td>
<td bgcolor="orange">Hoch</td>
<td bgcolor="orange">Hoch</td>
<td>Personenbezogene Daten werden ohne Einverständnis des Nutzers an Dritte weiter gegeben bzw. diesen zur Verfügung gestellt. Die Weitergabe von Daten und Erkenntnissen erfolgt entweder direkt oder auf Anfrage, gegen Zahlung oder auch durch unsachgemäßen Einsatz von Diensten Dritter wie beispielsweise Widgets für Webseiten (z.B. Landkarten, Buttons von sozialen Netzwerken), Analysetools oder Web Bugs (z.B. Beacons).</td>
</tr>

<tr>
<td>P8</td>
<td>:woman_technologist::man_office_worker:</td>
<td>Veraltete personen-bezogene Daten</td>
<td bgcolor="orange">Hoch</td>
<td bgcolor="red">Sehr hoch</td>
<td>Es werden veraltete, inkorrekte oder gefälschte personenbezogene Daten genutzt. Datenaktualisierungen oder -korrekturen finden nicht in ausreichendem Maße statt.</td>
</tr>

<tr>
<td>P9</td>
<td>:woman_technologist:</td>
<td>Fehlendes oder unzureichendes Session-Ende</td>
<td bgcolor="yellow">Mittel</td>
<td bgcolor="red">Sehr hoch</td>
<td>Unzureichendes Beenden von Sessions. Dies kann dazu führen, dass zusätzliche Nutzerdaten ohne Einverständnis oder Wissen des Nutzers gesammelt werden.</td>
</tr>

<tr>
<td>P10</td>
<td>:woman_technologist:</td>
<td>Unsichere Datenüber-tragung</td>
<td bgcolor="yellow">Mittel</td>
<td bgcolor="red">Sehr hoch</td>
<td>Die Datenübermittlung erfolgt nicht auf verschlüsselten und sicheren Kanälen, so dass ein unautorisierter Zugriff nicht verhindert wird. Mechanismen zum Verringern der Angriffsfläche, werden nicht umgesetzt. Hierzu gehört es zu verhindern, dass durch das Verhalten der Webanwendung Rückschlüsse auf Nutzerdaten möglich sind.</td>
</tr>
</table>

<!--|Nr.|Titel|Häufigkeit|Schaden|Beschreibung|
|---|------|-----|-----|------------------|
|P1 |Schwachstellen in Webanwendungen|Hoch|Sehr hoch|Schwachstellen sind ein zentrales Problem in jedem System, mit dem sensible Nutzerdaten erhoben, verarbeitet und genutzt werden. Bestehen Fehler im Design oder in der Implementierung der Applikation, werden Probleme nicht entdeckt oder Sicherheitspatches nicht unverzüglich eingespielt, führt dies mit hoher Wahrscheinlichkeit zu einer Verletzung des Persönlichkeitsrechts. Dieses Risiko wird bereits in anderen Projekten behandelt, wie der OWASP Top 10 Liste der häufigsten Sicherheitsrisiken für Webanwendungen. 
|P2 |Datenabfluss beim Betreiber|Hoch|Sehr hoch|Wird die unerwünschte Preisgabe personenbezogener oder personenbeziehbarer Daten an nicht autorisierte Personen nicht wirksam verhindert, ist dies ein Verlust der Vertraulichkeit. Ursachen sind entweder ein vorsätzlich durchgeführter Datenabzug oder unbeabsichtigte Fehler wie beispielsweise unzureichendes Zugriffsmanagement, unsichere Datenablage, Datendopplung oder fehlendes Problembewusstsein (Awareness). 
|P3 |Unzureichende Reaktion bei einer Datenpanne|Hoch|Sehr hoch|Betroffene werden nicht über mögliche Pannen oder Datenlecks benachrichtigt, die durch Angriffe oder unbeabsichtigte Ereignisse entstehen. Angemessene Abhilfemaßnahmen zum Schließen der Lücken und Beseitigung der Ursache fehlen. 
|P4 |Unzureichende Löschung personenbezogener Daten|Sehr hoch|Hoch|Personenbezogene Daten werden nicht termingerecht oder nicht effektiv nach Zweckablauf bzw. aufgrund einer Löschanfrage gelöscht.
|P5 |Intransparente Nutzungsbedingungen|Sehr hoch|Hoch| Informationen zur Datenverarbeitung wie Erhebung, Speicherung und Nutzung personenbezogener Daten sind unzureichend. Diese Informationen sind nicht leicht zugänglich oder für juristische Laien nicht verständlich aufbereitet.
|P6 |Sammeln von Daten, die über den eigentlichen Zweck hinaus gehen|Sehr hoch|Hoch|Es werden Beschreibungsdaten, demographische Daten oder sonstige personenbezogene Daten gesammelt, die nicht für den vereinbarten Zweck der Anwendung benötigt werden. Ebenso werden Daten gesammelt, für deren Erhebung der Nutzer keine Einverständniserklärung abgegeben hat.
|P7 |Weitergabe von Daten an Dritte|Hoch|Hoch|Personenbezogene Daten werden ohne Einverständnis des Nutzers an Dritte weiter gegeben bzw. diesen zur Verfügung gestellt. Die Weitergabe von Daten und Erkenntnissen erfolgt entweder direkt oder auf Anfrage, gegen Zahlung oder auch durch unsachgemäßen Einsatz von Diensten Dritter wie beispielsweise Widgets für Webseiten (z.B. Landkarten, Buttons von sozialen Netzwerken), Analysetools oder Web Bugs (z.B. Beacons).
|P8 |Veraltete personenbezogene Daten|Hoch|Sehr hoch|Es werden veraltete, inkorrekte oder gefälschte personenbezogene Daten genutzt. Datenaktualisierungen oder -korrekturen finden nicht in ausreichendem Maße statt.
|P9 |Fehlendes oder unzureichendes Session-Ende|Mittel|Sehr hoch|Unzureichendes Beenden von Sessions. Dies kann dazu führen, dass zusätzliche Nutzerdaten ohne Einverständnis oder Wissen des Nutzers gesammelt werden.
|P10|Unsichere Datenübertragung|Mittel|Sehr hoch|Die Datenübermittlung erfolgt nicht auf verschlüsselten und sicheren Kanälen, so dass ein unautorisierter Zugriff nicht verhindert wird. Mechanismen zum Verringern der Angriffsfläche, werden nicht umgesetzt. Hierzu gehört es zu verhindern, dass durch das Verhalten der Webanwendung Rückschlüsse auf Nutzerdaten möglich sind.-->

### Flyer
[Infoflyer in German](Top_10_Privacy_Risks_German.png)

## Japanese
[Link to slidedeck](https://speakerdeck.com/owaspjapan/introducing-owasp-top10-privacy-risks-number-owasp-night-21th)
