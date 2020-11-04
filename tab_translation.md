---
title: Translation
layout:  null
tab: true
order: 4
tags: example-tag
---
Currently project documentation is available in English, German and French. If you are interested in helping to translate to another language, please contact the project leaders.
## German
### Top 10 Datenschutzrisiken
Der Typ gibt an, ob ein Risiko eher :man_office_worker: organisatorisch, :woman_technologist: technisch oder beides ist.
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
<td align=center>:woman_technologist:</td>
<td>Schwachstellen in Web-Anwendungen</td>
<td bgcolor="orange">Hoch</td>
<td bgcolor="red">Sehr hoch</td>
<td>Schwachstellen sind ein zentrales Problem in jedem System, mit dem sensible Nutzerdaten erhoben, verarbeitet und genutzt werden. Bestehen Fehler im Design oder in der Implementierung der Applikation, werden Probleme nicht entdeckt oder Sicherheitspatches nicht unverzüglich eingespielt, führt dies mit hoher Wahrscheinlichkeit zu einer Verletzung des Persönlichkeitsrechts. Dieses Risiko wird bereits in anderen Projekten behandelt, wie der OWASP Top 10 Liste der häufigsten Sicherheitsrisiken für Webanwendungen.</td>
</tr>

<tr>
<td>P2</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Datenabfluss beim Betreiber</td>
<td bgcolor="orange">Hoch</td>
<td bgcolor="red">Sehr hoch</td>
<td>Wird die unerwünschte Preisgabe personenbezogener oder personenbeziehbarer Daten an nicht autorisierte Personen nicht wirksam verhindert, ist dies ein Verlust der Vertraulichkeit. Ursachen sind entweder ein vorsätzlich durchgeführter Datenabzug oder unbeabsichtigte Fehler wie beispielsweise unzureichendes Zugriffsmanagement, unsichere Datenablage, Datendopplung oder fehlendes Problembewusstsein (Awareness).</td>
</tr>

<tr>
<td>P3</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Unzureichende Reaktion bei einer Datenpanne</td>
<td bgcolor="orange">Hoch</td>
<td bgcolor="red">Sehr hoch</td>
<td>Betroffene werden nicht über mögliche Pannen oder Datenlecks benachrichtigt, die durch Angriffe oder unbeabsichtigte Ereignisse entstehen. Angemessene Abhilfemaßnahmen zum Schließen der Lücken und Beseitigung der Ursache fehlen.</td>
</tr>

<tr>
<td>P4</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Unzureichende Löschung personen-bezogener Daten</td>
<td bgcolor="red">Sehr hoch</td>
<td bgcolor="orange">Hoch</td>
<td>Personenbezogene Daten werden nicht termingerecht oder nicht effektiv nach Zweckablauf bzw. aufgrund einer Löschanfrage gelöscht.</td>
</tr>

<tr>
<td>P5</td>
<td align=center>:man_office_worker:</td>
<td>Intransparente Nutzungs-bedingungen</td>
<td bgcolor="red">Sehr hoch</td>
<td bgcolor="orange">Hoch</td>
<td>Informationen zur Datenverarbeitung wie Erhebung, Speicherung und Nutzung personenbezogener Daten sind unzureichend. Diese Informationen sind nicht leicht zugänglich oder für juristische Laien nicht verständlich aufbereitet.</td>
</tr>

<tr>
<td>P6</td>
<td align=center>:man_office_worker:</td>
<td>Sammeln von Daten, die über den eigentlichen Zweck hinaus gehen</td>
<td bgcolor="red">Sehr hoch</td>
<td bgcolor="orange">Hoch</td>
<td>Es werden Beschreibungsdaten, demographische Daten oder sonstige personenbezogene Daten gesammelt, die nicht für den vereinbarten Zweck der Anwendung benötigt werden. Ebenso werden Daten gesammelt, für deren Erhebung der Nutzer keine Einverständniserklärung abgegeben hat.</td>
</tr>

<tr>
<td>P7</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Weitergabe von Daten an Dritte</td>
<td bgcolor="orange">Hoch</td>
<td bgcolor="orange">Hoch</td>
<td>Personenbezogene Daten werden ohne Einverständnis des Nutzers an Dritte weiter gegeben bzw. diesen zur Verfügung gestellt. Die Weitergabe von Daten und Erkenntnissen erfolgt entweder direkt oder auf Anfrage, gegen Zahlung oder auch durch unsachgemäßen Einsatz von Diensten Dritter wie beispielsweise Widgets für Webseiten (z.B. Landkarten, Buttons von sozialen Netzwerken), Analysetools oder Web Bugs (z.B. Beacons).</td>
</tr>

<tr>
<td>P8</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Veraltete personen-bezogene Daten</td>
<td bgcolor="orange">Hoch</td>
<td bgcolor="red">Sehr hoch</td>
<td>Es werden veraltete, inkorrekte oder gefälschte personenbezogene Daten genutzt. Datenaktualisierungen oder -korrekturen finden nicht in ausreichendem Maße statt.</td>
</tr>

<tr>
<td>P9</td>
<td align=center>:woman_technologist:</td>
<td>Fehlendes oder unzureichendes Session-Ende</td>
<td bgcolor="yellow">Mittel</td>
<td bgcolor="red">Sehr hoch</td>
<td>Unzureichendes Beenden von Sessions. Dies kann dazu führen, dass zusätzliche Nutzerdaten ohne Einverständnis oder Wissen des Nutzers gesammelt werden.</td>
</tr>

<tr>
<td>P10</td>
<td align=center>:woman_technologist:</td>
<td>Unsichere Datenüber-tragung</td>
<td bgcolor="yellow">Mittel</td>
<td bgcolor="red">Sehr hoch</td>
<td>Die Datenübermittlung erfolgt nicht auf verschlüsselten und sicheren Kanälen, so dass ein unautorisierter Zugriff nicht verhindert wird. Mechanismen zum Verringern der Angriffsfläche, werden nicht umgesetzt. Hierzu gehört es zu verhindern, dass durch das Verhalten der Webanwendung Rückschlüsse auf Nutzerdaten möglich sind.</td>
</tr>
</table>


### Flyer
[Infoflyer in German](Top_10_Privacy_Risks_German.png)


## French
### Top 10 Risques pour la vie privée
<!--Der Typ gibt an, ob ein Risiko eher :man_office_worker: organisatorisch, :woman_technologist: technisch oder beides ist.-->
<table style="background-color:#FFFFFF;border-collapse:collapse;border:1px solid #000000;color:#000000;width:100%" cellspacing="3" cellpadding="3" border="1">

<tr>
<td bgcolor="#D8D8D8" width="64"><b>#</b></td>
<td bgcolor="#D8D8D8" width="70"><b>Type</b></td>
<td bgcolor="#D8D8D8" width="160"><b>Titre</b></td>
<td bgcolor="#D8D8D8" width="120"><b>Fréquence</b></td>
<td bgcolor="#D8D8D8" width="110"><b>Impact</b></td>
<td bgcolor="#D8D8D8"><b>Description</b></td>
</tr>

<tr>
<td>P1</td>
<td align=center>:woman_technologist:</td>
<td>Application avec vulnérabilités</td>
<td bgcolor="orange">Élevé</td>
<td bgcolor="red">Très élevé</td>
<td>Une application contenant des vulnérabilités logicielles est un problème clé pour des systèmes qui traitent des données personnelles sensibles. Un manque dans la conception, dans l’implémentation, une détection de failles insuffisante, une incapacité à appliquer une solution (patch) à une faille mènent à une fuite de données personnelles.</td>
</tr>

<tr>
<td>P2</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Fuite de données par l’opérateur</td>
<td bgcolor="orange">Élevé</td>
<td bgcolor="red">Très élevé</td>
<td>L’impossibilité de prévenir la fuite de données concernant ou pas des données personnelles à des groupes non autorisés mène à une perte de confidentialité. Que ce soit intentionnel ou une erreur (mauvaise gestion des accès, stockage non sécuritaire, duplication de données ou manque de réactivité).</td>
</tr>

<tr>
<td>P3</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Mauvaise réponse suite à une fuite de données</td>
<td bgcolor="orange">Élevé</td>
<td bgcolor="red">Très élevé</td>
<td>Ne pas informer les gens affectés à propos d’une fuite de données. Ne pas remédier à la situation en identifiant et en réparant la cause. Ne pas tenter de limiter la fuite.
</td>
</tr>

<tr>
<td>P4</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Suppression insuffisante des données personnelles</td>
<td bgcolor="red">Très élevé</td>
<td bgcolor="orange">Élevé</td>
<td>Ne pas supprimer les données personnelles convenablement à la fin de l’utilisation précisée à l’utilisateur.</td>
</tr>

<tr>
<td>P5</td>
<td align=center>:man_office_worker:</td>
<td>Conditions d’utilisation opaques</td>
<td bgcolor="red">Très élevé</td>
<td bgcolor="orange">Élevé</td>
<td>Ne pas fournir suffisamment d’information sur la collecte, le stockage et le traitement de vos données. Ne pas fournir l’information claire et facilement accessible. Information seulement compréhensible par des avocats.</td>
</tr>

<tr>
<td>P6</td>
<td align=center>:man_office_worker:</td>
<td>Collecte de données excessive</td>
<td bgcolor="red">Très élevé</td>
<td bgcolor="orange">Élevé</td>
<td>Collecter de l’information descriptive, géographique, démographique ou toute autre information qui n’est pas nécessaire pour le système. S’applique aussi pour les données qui n’ont pas fait le consentement de l’utilisateur.</td>
</tr>

<tr>
<td>P7</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Partage de données</td>
<td bgcolor="orange">Élevé</td>
<td bgcolor="orange">Élevé</td>
<td>Partager des données à des tiers sans obtenir le consentement de l’utilisateur.  Partager des données en échange d’argent ou via des widgets : maps, réseau social, boutons et analytiques.</td>
</tr>

<tr>
<td>P8</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Données personnelles périmées</td>
<td bgcolor="orange">Élevé</td>
<td bgcolor="red">Très élevé</td>
<td>L’utilisation de données incorrectes ou en lien avec des utilisateurs fictifs. Impossibilité de mettre à jour ces données.</td>
</tr>

<tr>
<td>P9</td>
<td align=center>:woman_technologist:</td>
<td>Expiration de session manquante ou insuffisante</td>
<td bgcolor="yellow">Moyen</td>
<td bgcolor="red">Très élevé</td>
<td>Échec à mettre fin convenablement à une session. Cela permet de collecter de l’information supplémentaire sur l’utilisateur sans son consentement ou sa connaissance.</td>
</tr>

<tr>
<td>P10</td>
<td align=center>:woman_technologist:</td>
<td>Transmission de données non sécurisée</td>
<td bgcolor="yellow">Moyen</td>
<td bgcolor="red">Très élevé</td>
<td>Ne pas sécuriser le transfert de données permettant la fuite de ces dernières. Ne pas renforcer les mécanismes qui pourraient limiter les fuites. Permettre de sortir des données d’utilisateur à l’extérieur des limites de l’opération de l’application.</td>
</tr>
</table>

### Flyer
[Infoflyer in French](Top_10_Privacy_Risks_French.jpg)


## Japanese
[Link to slidedeck](https://speakerdeck.com/owaspjapan/introducing-owasp-top10-privacy-risks-number-owasp-night-21th)
