<!-- TITLE: Identity Verification -->
<!-- SUBTITLE: A quick summary of Identity Verification -->

# Überblick
Jeder Akzession ist ein bestimmter Name zugewiesen. Das ist entweder ein Art Name oder, wenn nur der Name der Gattung bekannt ist, der Name der Gattung mit dem Zusatz "species". Die Information welchen Namen die Akzession besitzt stammt in erster Linie von der Bezugsquelle (dem Provider). Die Anwendung geht davon aus, dass die Namenszuordnung intern noch nicht überprüft wurde. Beim Anlegen einer neuen Akzession befindet sich daher kein Haken bei "Wurde die Identität überprüft?".
![Collmngmnt Newaccession](/uploads/collection/collmngmnt-newaccession.png "Collmngmnt Newaccession")
# Aktueller Status
## Editor
Im Editor findet man unter Identität einen Hinweis zum aktuellen Status der Namenszuodnung.
**Beispiel Akzession mit fehlender Bestätigung der Identität (roter Stern)**
![Collmngmnt Identity Short Eg Nocuration](/uploads/collection/collmngmnt-identity-short-eg-nocuration.png "Collmngmnt Identity Short Eg Nocuration")
**Beispiel Akzession mit vollständiger Bestätigung der Identität (grüner Stern)**
![Collmngmnt Identity Short Eg Curationok](/uploads/collection/collmngmnt-identity-short-eg-curationok.png "Collmngmnt Identity Short Eg Curationok")
## Listen Ansicht
In der [Listen Ansicht](/nick-lab/accession-list-view) findet man die Spalte Identität, in der über Symbole und deren Färbung der aktuelle Status der Namenszuordnung erkannt werden kann:
* grüner Haken = Identität wurde verifiziert und Angaben zur Methodik wurden hinterlegt.
* orangener Haken = Identität wurde verifiziert. Angaben zur Methodik fehlen.
* rotes Fragezeichen = Identität wurde nicht verifiziert.

![Statusverificationlistview](/uploads/nicklab/statusverificationlistview.png "Statusverificationlistview"){.align-center}
# Details zur Bestätigung
Details zu einer Bestätigung werden in Form eines Kommentars mit dem Betreff "Determination" gespeichert. Der Kommentar selbst sollte die verwendete Literatur und, wenn nicht selbst bestimmt wurde, den Namen der Person, welche die Bestimmung durchgeführt hat, enthalten.
![Collmngmnt Identity Curation](/uploads/collection/collmngmnt-identity-curation.png "Collmngmnt Identity Curation")