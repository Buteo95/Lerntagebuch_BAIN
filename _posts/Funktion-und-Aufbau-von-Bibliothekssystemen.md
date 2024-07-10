---
title: "Funktion und Aufbau von Bibliothekssystemen"
date: 21.02.2024
---

Im Unterricht wird MARC21 genauer betrachtet, wie auch Dublin Core und Koha.
Dublin Core ist quasi der Minimum Standard auf welchen man sich geeinigt hat, damit die Daten 
mindestens ein bisschen ähnlich erfasst werden, während MARC21 versucht alle möglichen Felder 
Abzudecken. Der Dublin Core Standard kann für HTML und auch für RSS-Dokumente genutzt werden.

Vorteile von Dublin Core sind:

- Leichtere Klassifikatinon und auslesen von Suchmaschinen
  
- Einfaches einfügen der Elemente in das Dokument
  
- Keine beeinträchtigung des Quellcodes des Elementes durch Dublin Core.

Die Marc-Formate. mrc sind quasi Standards darüber wie die Daten Repräsentiert und ausgetauscht 
werden und dies in maschinenlesbarer Form. 2004 wurde im Rahmen der Internationalisierung der 
deutschen Standards beschlossen MARC21 als einheitliches Austauschformat zu verwenden. 

MARC21 hat jedoch auch wenn es als einheitliches Austauschs Format gilt je nach Institution sehr viel 
Abweichungspotenzial, dies liegt darin begründet, dass Beispielsweise die Schweizerische 
Nationalbibliothek andere Kriterien bezüglich der Erfassung von Datensätzen haben, als die kleine 
Schulbibliothek auf dem Lande, dieser Vergleich wirkt ein wenig an den Haaren herbeigezogen, 
jedoch soll damit verbildlicht werden, dass die Umgebung der Institution massgebliche Auswirkungen 
auf die Vergabe von unterschiedlichen Feldern oder gar der Erstellung eigener Felder. Ich persönlich 
finde den Standard MARC21 sehr komplex. Dieser Nachteil wird für mich aber durch die Möglichkeit 
der viel genaueren Abbildung der Metadaten ausgeglichen. Marc21 soll in Zukunft von BIBFRAME 
abgelöst werden, bezüglich dieser Ablösung von MARC21 bin ich eher skeptisch ob dies auch wirklich 
in absehbarer Zeit geschehen wird, da ich denke, dass die Institute nicht so leicht von Ihrer 
bisherigen Praxis loslösen können oder den Institutionen schlichtweg das Geld und die nötigen 
Ressourcen fehlen. 

MARC2 hat auch eine spezielle Struktur welche ich für mich noch spannend fand, weshalb hier ein 
kurzer Einblick über die MARC21 Struktur gegeben werden soll.
MARC-Datensätze beginnen stehts mit einem Leader, dieser enthält die wichtigen Informationen 
bezüglich der Verarbeitung dieses Datensatzes. Hierbei können Zahlen und Buchstaben stehen
welche die Information Codier abbilden. Bibliografische Informationen werden im MARC-Datensatz 
in Feldern und Unterfeldern gespeichert, wobei diese Unterfelder auch wieder durch Trennzeichen 
getrennt werden. Die Felder an sich bestehen aus dreistelligen Nummern. Ob gewisse Felder 
wiederholbar sind wird mit R oder NR angegeben wobei R für repeatable und NR für non repeatable.
Was für mich bei der Recherche zu diesem Thema noch sehr entmutigt hat, war das man jedem noch 
zwei zusätzliche Indikatoren vergeben kann, was das Gesamte für mich noch komplizierter oder 
anders gesagt unnötig «aufbläst», auch wenn ich dies im Bezug zu beispielsweise wissenschaftlicher 
Literatur als nachvollziehbar erfinde, wenn hierbei die Sprache zum Erfassen dieser Daten nur nicht 
so kompliziert wäre. Zum Glück kann man dies aber in der MARC-Feldbeschreibung nachlesen.

BIBFRAME soll MARC21 ablösen, da MARC21 den neuen Anforderungen die durch die zunehmende
stärkere digitale Vernetzung nicht mehr gerecht wird. In BIBFRAME sollen Möglichkeiten 
berücksichtigt werden die Linked-Data und semantische Web Technologien mit sich bringen. Aus 
einer weiteren Recherche im Internet konnte ich gewisse «absolute» Vorteile von BIBFRAME 
herausfinden welche ich als sehr wichtig Empfinde.

- BIBFRAME soll es allen ermöglichen Zugang zu bibliografischen Daten von Bibliotheken
erhalten, welche seit langen sorgfältig gepflegt und verwaltet werden. Aber es liegt in einem
Datenformat in diesem Falle MARC21 vor, das von Nicht-Bibliotheksfachleuten nicht leicht 
verstanden oder einfach eingesetzt werden kann, hierbei sollen die Zugangshürden für 
Personen welche nicht aus der Bibliotheks- und Archivwelt stammen gesenkt werden.

- BIBFRAME ermöglicht es den Bibliotheken und Archiven Ihre Daten einem globalen Publikum
zugänglich zu machen.

KOHA ist eine integrierte Open-Source-Software für Bibliothekssystem welches zum Verwalten von 
Katalogisaten dient. Koha verfügt über eine SQL-Anbindung oftmals wird dafür MYSQL verwendet. In 
der Koha Datenbank werden die die Katalogisate nach dem MARC-Regelwerk gespeichert. Die UX von 
Koha finde ich persönlich ganz gut, jedoch ist es beim Erfassen von neuen Katalogisaten aufgrund des 
MARC-Standards oftmals auch mühselig, wenn man nicht alle Regeln in und auswendig kennt und
man somit quasi gezwungen ist stets das MARC-Regelwerk in einem anderen Tab offen zu haben.
Einfach zusammengefasst würde ich sagen, dass Koha auf den oberen Interaktionsebenen sehr 
angenehm ist um damit zu arbeiten jedoch immer komplizierter und Komplexer wird, wenn man auf 
die tiefergehenden Interaktionsebenen zugreift.

Für die Übungen haben wir uns mit der von Admin Kuhn zur Verfügung gestellten Demo befasst. Die
Einführungsaufgaben um ein Gespür für die Software Koha zu erhalten bestand darin, dass wir ein 
Buch im System erfassen, einen Benutzer anlegen welcher das Buch ausleiht und wieder 
zurückbringt. Die Aufnahme eines neuen Buches in die Datenbank gelang sehr schnell, dafür 
mussten wir über den Reiter Katalogisierung neuen Titel auswählen und anschliessend die 
Schnellaufnahme auswählen. Wichtig war hierbei zu beachten die Pflichtfelder 000 und 008 
auszufüllen, da ansonsten die MARC-Regeln nicht eingehalten werden und somit eine Fehlermeldung 
aufpoppt. Der Nutzer konnte wie auch das erfassen des Buches mit einer Benutzer-Schnellerfassung 
erledigt werden.
