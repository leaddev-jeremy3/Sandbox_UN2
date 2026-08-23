# Kapitel 3 - Coding Guidelines

Wie in Trance schleppte sich Jeremy durch das Großraumbüro im vierzehnten Stock. Schreibtisch stand neben Schreibtisch, mehrere hundert Entwickler arbeiteten dicht an dicht. Angeblich sollten ja diese Büros die Zusammenarbeit fördern, aber bereits wenige Tage nach der Einführung wurde eine Sammelbestellung für Noise-Cancelling Kopfhörer durchgeführt.

So saßen sie da, alle in ihrer eigenen Welt, und hämmerten fleißig in die Tasten. Alle, bis auf einen. Seth hatte ein eigenes Büro, ganz am Ende des Ganges. Offiziell als Belohnung für seine Leistungen. Ohne Seth gäbe es die Sandbox in der heutigen Form nicht mehr. Täglich kämpfte er gegen den mysteriösen Hacker Aphis, der aus irgendwelchen Gründen versuchte, die Sonne zu hacken.

Inoffiziell, weil der Typ einfach allen unheimlich war. Irgendwann konnte sich selbst der sparsame Harry nicht mehr wehren und genehmigte die Umwidmung des Besprechungsraums.

Jeremy atmete tief durch und klopfte an die Tür. „Herein!“, tönte es, und er nahm all seinen Mut zusammen.

Der Raum selbst war stockdunkel, beleuchtet nur durch den sanften Schein mehrerer Bildschirme. Viel konnte er nicht erkennen, außer eine seltsame Figur mit langer, gekrümmter Schnauze, mandelförmigen Augen und rechteckigen Ohren. *Ah, das Tier, das er entwickelt hat. Irgendwie schade, dass wir es nie implementiert haben.*

Hinter dem Tisch saß er, Seth höchstpersönlich, und aß einen Salat mit Joghurtdressing. Als er Jeremy sah, nickte er ihm respektvoll zu. „Ah, Jeremy, was verschafft mir die Ehre? Magst du auch einen Bissen?“

„Ähm, danke, nein“, antwortete er verwirrt.

„Ach, kein Thema, falls du dirs anders überlegst, gib Bescheid. War ein Friedensangebot von Holm. Schmeckt zwar etwas… eigen. Aber er hat mir versichert, da steckt viel Liebe drinnen. Also, setz dich. Was kann ich für dich tun?“

Überrascht über den freundlichen Empfang näherte er sich und setzte sich ihm gegenüber. *Was haben die Leute eigentlich gegen ihn? Wirkt ja ganz nett.* „Also, es geht um die Energiewende. Ich hatte zuletzt ein Meeting mit dem Steering Committee, und die haben da ein paar… Bedenken bezüglich der neuesten Entwicklungen. Ich wollte mal fragen, wie es da läuft? Man hat mir gesagt, du arbeitest an den Stories.“

Seth stellte den Salat beiseite und wischte sich Reste vom weißen Dressing aus dem Gesicht. „Ah ja, Energiewende. Cooles Projekt. Hab da beim letzten Sprint schon dran gearbeitet. Mal sehen, ich hab da eingebaut… Solarzelleneffizienz um 50% gesteigert, Kosten um 40% gesenkt. Elektroautos weiter ausgerollt. Wartungsarbeiten am Öffentlichen Verkehr. Mehrere Maßnahmen zur Erhöhung der Öl- und Gaspreise.“

Ein leichter Schauer lief Jeremy über den Rücken. Gerade beim letzten Satz huschte ein böses Funkeln durch Seths Augen. „Wow, klingt ja gut. Also, ist die Klimakrise abgewendet?“

„Also, die Tools dafür sind alle deployed. Aber die Verwendung in den verschiedenen Programmen und Paketen ist noch sehr durchwachsen. Also, die Deadlines und das 1,5Grad Sprintgoal sind nicht zu erreichen. Hab ich aber eh bei der letzten Planung erzählt.“

„Mist, das ist nicht gut“, murmelte Jeremy. „Wir müssen da mehr tun.“

Seth blickte ihn böse an. „Willst du damit sagen, ich mach meinen Job schlecht?“ Seine Arme umklammerten die Lehnen des Bürostuhls, und es wirkte, als ob er gleich aufstehen würde.

„Nein, nein, natürlich nicht“, warf Jeremy schnell nach. „Du machst das fantastisch, die Tools, von denen du sprichst – tip top! Und die Annahme bei den Menschen und Regierungen sind eigentlich nicht dein Thema.“ Er begann an den Fingernägeln zu kauen, als ihm plötzlich eine Idee kam. „Aber ich dachte – auch wenn es nicht deine Aufgabe ist, du hast doch sicher eine Idee, was wir da machen könnten, oder?!“

Seth entspannte sich wieder. „Nö, keine Idee. Also, das können wir unmöglich umsetzen.“

Etwas baff schaute ihn Jeremy einige Momente an, bevor er antwortete. „Aber wieso denn nicht?“

„Entwicklerrichtlinien“, antwortete Seth. „Seite 4231, Absatz 12, Punkt zur Vermeidung von Laufzeitfehlern: Solange die Programme laufen, darf ihr Quellcode nicht verändert werden. Also können wir bei diesen Menschen in der Generation nichts mehr tun. Vielleicht bei der nächsten, dann.“

„Da muss es doch einen Ausweg geben, oder? Wir könnten doch an ein paar Parametern schrauben?“

„Seite 2132, Absatz 12, Punkt Freier Wille: Parameterwerte dürfen nur bei vereinzelten und isolierten Programmen angepasst werden!“, hielt Seth dagegen.

*Mist, den Absatz hab ich damals selbst hinzugefügt.* Er wollte ja damals eine stabile, selbsterhaltende Systemlandschaft aufbauen und hatte es satt, dass andere Entwickler on the fly ihre schlampige Programmierung im Debugger korrigierten. „Was ist mit … wir löschen einfach den ganzen alten Dinosauriercode? Dann müssen sie umsteigen?“

„Glaubst du, daran habe ich nicht gedacht?“ Seth schüttelte energisch den Kopf. „Seite 2, Absatz 1: Energieerhaltung. Code darf nicht einfach so verschwinden oder hinzugefügt werden.“

Seufzend lehnte sich Jeremy zurück. „Aber das waren doch alles nur grobe Handlungsanweisungen! Dutzende Entwickler haben die über die Jahre gebrochen…“

„Und alle von ihnen habe ich gemeldet.“ Böse grinste Seth hinter dem Tisch hervor. „Aris freut sich immer tierisch darüber. Wenn du weitere kennst, solltest du das auch tun. Du erinnerst dich doch sicher an das Compliance Training?“

„Ähm, ja, natürlich hast du Recht.“ Sorgfältig überlegte Jeremy, ob er die Commits von damals mit dem Brennenden Dornenbusch und dem geteilten Meer gut versteckt hatte. Auf ein 1:1 mit Aris konnte er getrost verzichten. Die Arena zum Durchsetzen von Disziplinarmaßnahmen war ihm sogar noch unheimlicher als Seths Büro. „Hmm, was ist mit … der 10 Gebote Methode? Wir könnten es doch einfach da rein geben? Oder gibt’s da auch eine Regel dagegen?“

„Hm?“, grunzte Seth. „Wenn du dir das wirklich antun willst …“

„Wieso nicht? Ein elftes Gebot sollte ich doch schnell einbauen können, oder?“

Schallendes Lachen schlug ihm entgegen. „Sag, wann hast du da zum letzten Mal reingeschaut?“

Verwirrt blickte Jeremy ihn an.

„Komm mal her, die Methode, meinst du doch, oder?“

Er rutschte neben Seth. Da war sie, die Tafelberg Klasse, Methode GET_10_GEBOTE – genau wie er sie hinterlassen hatte. Seth öffnete sie und zeigte den Code. *Ah ja, du sollst nicht töten, Vater Mutter ehren, etc., genau wie ich sie in Erinnerung habe.* Dann begann Seth zu scrollen, und Jeremy begann zu lesen.

`IF weather = COLD. WEAR_LONG_SOCKS()` *Ist doch sinnvoll.*

`IF religion = 15. DONT_EAT_PIGS()` *Hmm, wirkt etwas random, aber, von mir aus.* 

`IF DNA[5611] = 'A'. CHECK_DOOR_3_TIMES()` *Wer hat das nochmal angefordert?*

Seth scrollte weiter und weiter, es wollte gar nicht aufhören. „Wie lange geht das bitte so weiter?“, fragte Jeremy.

„Also, es sind ziemlich genau 45.231.235 Zeilen Code da drinnen“, erwiderte Seth.

„Aber wieso denn das?“, fragte Jeremy bestürzt. „In den Richtlinien steht doch sicher auch was von Modularisierung, maximaler Methodengröße und so?“

„Ja, schon, aber nur, von wegen, es muss auf eine Bildschirmseite passen. Und mit den neuen 100k Monitoren und weit rausgezoomt… geht das schon.“

Er scrollte weiter und weiter, bis Jeremy plötzlich Stopp rief. Ein großer Kommentar fiel ihm ins Auge: Umweltschutz. Doch darunter stand erstmal nichts. „Wo ist der Code?“, fragte Jeremy.

Seth grinste ihn süffisant an. „Warte, ich muss nur etwas nach rechts scrollen.“ Offensichtlich war der Code nicht nur in die Länge, sondern auch in die Breite gewachsen. Mit beiden Händen hielt Seth die Maus und zog den Scrollbalken, der sich sichtlich wert, immer weiter nach rechts. „Schau, hier fängt es an, die ganzen Prüfungen bzgl. Umweltschutz.“

Jeremy scannte sie mit geschultem Blick. „Schaut doch … ganz vernünftig aus? Aber wieso steht das so weit rechts? Und wird das nicht aufgerufen?“

„Naja, da sind halt ein paar verschachtelte IFs drüber. Nach der Position im Code würde ich schätzen … so 15.000?“ Seth knackte mit den Fingern, das Scrollen hatte ihn sichtlich mitgenommen. „Also, wenn du mal Lust hast, schau gerne rein. Wie du sagtest – ist jetzt nicht Teil meiner Story.“

Geknickt stand Jeremy auf. „Danke, ich werde mal schauen, was ich tun kann.“

Er ging zur Tür, und fragte sich, wie seine einfachen, eleganten 10 Gebote so ausarten konnten, als er plötzlich Seths Stimme hinter sich hörte. „Und, Jeremy…?“

Vorsichtig drehte er sich um. „Ja?“

„Ohne Story darfst du da aber nichts ändern. Seite 42, Absatz 1 der Richtlinien. Vergiss das nicht.“

„Natürlich nicht, Seth. Danke für deine … Hilfe.“

Der Entwickler setzte ein freundliches Grinsen auf. „Immer wieder gern, Jeremy.“

[Kapitel 4 - Sales](./Kapitel4-Sales.md)

