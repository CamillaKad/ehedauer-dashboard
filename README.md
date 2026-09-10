[README.md](https://github.com/user-attachments/files/32065099/README.md)
# Ab wann kippt eine Ehe?

Power-BI-Dashboard zu 45.000 Ehen. Abschlussprojekt meiner Weiterbildung zur
Datenanalystin, September 2026.

## Worum es geht

Die Leitfrage: **Ab welchem Punkt kippt eine Ehe, und ab wann lässt sie sich noch
retten?**

Dahinter stecken zwei Teilfragen. Erstens: Was trennt schärfer zwischen bestehenden
und geschiedenen Ehen – Bildung, Einkommen und Alter, oder das Verhalten im Streit?
Zweitens: Wenn das Verhalten kritisch ist, wirken Schutzfaktoren wie Reparaturversuche
oder wöchentliche Aktivitäten dann überhaupt noch?

Das Dashboard hat vier Seiten: Übersicht, Demografie, Gottmans Four Horsemen und eine
Gegenprobe mit dem Key-Influencers-Visual.

## Was dabei herauskam

Verhalten schlägt Demografie. Bei niedriger Verachtung liegt die Scheidungsrate bei
31 %, bei hoher bei 80 %. Das stärkste demografische Merkmal ist der Bildungsstand mit
33 Prozentpunkten Spanne – weniger als jeder einzelne der Four Horsemen.

Reparaturversuche helfen in jeder Gruppe, aber sie gleichen hohe Verachtung nicht aus.
Der beste Fall bei hoher Verachtung liegt mit 63 % immer noch über dem schlechtesten
Fall bei niedriger Verachtung mit 57 %.

Religiöse Teilnahme und Zusammenleben vor der Ehe zeigen in diesen Daten keinen
Unterschied.

## Die Daten

[Marriage Longevity — What Makes Relationships Last?](https://www.kaggle.com/datasets)
von sergionefedov. 45.000 Zeilen, 24 Spalten, Lizenz CC0.

Die Daten sind vollständig synthetisch. Es geht um keine realen Paare. Der Autor hat
den Generator an publizierten Statistiken kalibriert – Scheidungsraten nach Ehe-Nummer,
mittlere Ehedauer, Bildungsgefälle – und die Verhaltensmerkmale dem Gottman-Rahmenwerk
nachgebildet.

Der Scheidungsdatensatz auf Kaggle geht auf dieselbe Studie zurück: 170 türkische
Paare, 54 Fragen. Dieser Datensatz ist ausdrücklich als größerer Gegenentwurf dazu
gebaut.
