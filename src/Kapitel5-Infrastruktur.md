# Kapitel 5 - Infrastruktur

Voller Vorfreude knackte Jeremy die Finger. Er hatte es tatsächlich geschafft und eine Story zum Refactoring der 10 Gebote Methode erhalten. Damit würde er die Probleme der Menschen lösen können, da war sich Jeremy sicher.

Überraschenderweise war es gar nicht so schwer gewesen, die Story dafür zu erhalten. Offenbar durfte einfach jeder Dinge in den Backlog geben.

Sie in den Sprint zu bekommen war da schon etwas schwieriger. Gaby meinte, es benötige dafür Schätzung, Planung und dann könne sie vielleicht in den nächsten Sprint. Doch Jeremy kannte da ein Zauberwort: dringend. Allein die Erwähnung dieses magischen Wortes reichte, um sofort starten zu können.

Mehrfach hatte Jeremy diese Vorgehensweise bereits verflucht – ständig wurden Prioritäten und Ziele verschoben, was ihre Arbeit deutlich erschwerte. Wenn es nach ihm ginge, würde er das sofort abdrehen. Aber egal, wie oft er das bereits angesprochen hatte, es half nichts. Wieso es also nicht selbst mal ausnutzen?

*Also, womit fange ich an?* Er hatte vor sich die neueste Version der Methode und versuchte, sich einen Überblick zu verschaffen. Zeile für Zeile ging er durch, versuchte, sie sich einzuprägen. Doch als er bei den Benimmregeln zum Essen angekommen war, hatte er die Etikette fürs Fitnessstudio bereits wieder vergessen.

Vielleicht lag es auch daran, dass diese Regeln so wahnsinnig komplex waren. Umgeben waren sie von einem CASE, das den Ländercode Abfrage. Darunter dann hunderte, vielleicht sogar Tausende IFs – für verschiedene Speisen, für Zuhause, unterwegs, für Feiern, für Beerdigungen, … *Wie soll ich das jemals auflösen?*

Regeln einfach zu streichen, wagte er nicht. *Aber vielleicht … kann ich sie irgendwie gruppieren? In eine Tabelle?* Je mehr er darüber nachdachte, desto besser gefiel ihm das. Eine einfache Tabelle, fortlaufend nummeriert, mit allen Regeln. Dazu Kategorie, Länderschlüssel, Bedingung und Priorität. Der Code könnte dann super schlank laufen und neue Regeln könnte er einfügen.

Er loggte sich in die Datenbank ein und grübelte weiter. Hmm, wie nenn ich sie bloß? Der Inhalt der Methode war ein Sammelsurium an allen möglichen, einen knackigen Namen zu finden war schwer. Jeremy lehnte sich in seinem Stuhl zurück. Es sollte einfach sein, so dass jeder sofort weiß, worum es geht. *Einfach `gebote_der_menschheit`? Nein, das ist zu lange. Oder `regeln_für_das_leben`? Oh Mist, Umlaute gehen auch nicht. Und ist sogar noch länger.*

Nach einigem Hin und Her entschied er schließlich, sie einfach `zehn_gebote` zu nennen. Es war zwar etwas irreführend, da darin Tausende, wenn nicht Millionen Einträge stehen würden, doch zumindest war jedem klar: Es geht dabei um die Methode `get_10_gebote`.

Er tippte den Namen ein, wollte die Tabelle anlegen, doch bekam eine Fehlermeldung. Jeremy runzelte die Stirn. *Was? Das kann nicht sein! Die Tabelle gab es bereits!* Und er selbst hatte sie vor fünfhundert Jahren angelegt? *Hab ich schon mal versucht, die Methode anzupassen, oder was steht in der Tabelle?*

Ungläubig prüfte er den Inhalt, und darin befanden sich tatsächlich zehn Einträge. Der erste war für die Sonne, die anderen für neun Planeten, die darum kreisten, mit komplizierten Berechnungen, wie sich die Himmelskörper verhielten. *Stimmt ja! Damals haben wir das Sonnensystem so umgebaut, dass sich die Planeten um den Stern drehen, nicht umgekehrt!*

Mittlerweile war das völlig überholt, aber Jeremy wusste, dass die Tabelle immer noch verwendet wurde. Dann mach ich halt eine neue Tabelle. Kurz grübelte er, doch ihm fiel nichts Besseres ein, als sie zehn_gebote_neu zu nennen. Er tippte den Namen ein, doch wieder spuckte die Datenbank eine Fehlermeldung aus.

*Was, zur Hölle? Die wurde vor siebzig Jahren angelegt und beinhaltet Anleitungen zur Fußpflege? Da muss sich jemand vertippt haben...* Er wollte gerade prüfen, wer sich diesen Schwachsinn hatte einfallen lassen, als er neben sich einen Luftzug spürte und hochschreckte. „Du, Jeremy, hast du schnell Zeit für mich?“, fragte ihn Hermert.

Seufzend drehte er sich um, zu ihm. „Wieso ich? Frag doch Seus.“

„Das geht nicht, der ist außer Haus und kommt erst morgen zurück. So lange kann ich nicht warten.“ Hermerts Stimme überschlug sich fast, so schnell kamen die Worte aus seinem Mund.

Jeremy legte die Hand auf die Stirn und schloss die Augen. „Lass mich raten, er hat ein Date?“

„Familiengericht, hab ich gehört. Gerüchten zufolge geht es um so eine Vaterschaftsklage.“

„Na gut, hilft ja nichts, oder?“ Er sperrte seinen PC und stand auf. „Also, was kann ich für dich tun?“

„Es geht um die Performance der Sandbox“, sprudelte Hermert los. „Egal, was ich tue, das Ding schafft nicht mal 300.000 km/s. Je näher wir kommen, desto mehr beginnt es zu laggen, und irgendwann geht gar nichts mehr. So kann ich nicht arbeiten!“

Schulterzuckend schaute Jeremy ihn an. „Und was soll ich da bitte tun?“

„Also meiner Meinung nach ist das definitiv ein Infrastruktur Thema. Ich hab da schon vor 350 Jahren ein Ticket aufgemacht, da ist mir das zum ersten Mal aufgefallen. Aber immer noch keine Antwort!“ Verächtlich schüttelte Hermert den Kopf. „Die sollen sich mal beeilen! Kann doch nicht so lange dauern, das alles!“

„Ich schaue mal, was ich tun kann, okay? Aber ich bin da gerade mitten in einer wichtigen Sache, also vielleicht demnächst mal…“

„Das geht mir viel zu langsam!“, erwiderte Hermert, bevor Jeremy überhaupt ausreden konnte. „Wir brauchen mehr Performance!“

Da machte es plötzlich Klick in Jeremys Kopf. *Performance, davon hat doch Luki auch gesprochen.* Vielleicht würde eine Verbesserung hier die Kunden überzeugen? „Ok, gut, Hermert, ich schau gleich zu Betlas, ok?“

„Danke!“, sagte Hermert, noch bevor er genauso schnell wieder verschwand, wie er angekommen war.

Beflügelt von der Unterhaltung, ging Jeremy in den Westflügel ihrer Firmenzentrale. Je näher er kam, desto kälter wurde es. Fenster waren keine zu sehen, nur Reihen um Reihen von undefinierbaren Schränken voller bunt blinkender. Das laute Brummen von Lüftern war allgegenwärtig, hier in der Zentrale der Sandbox.

Es dauerte einige Zeit, bis Jeremy schließlich die Kommandozentrale erreichte. Da war er, Betlas, umgeben von unzähligen Bildschirmen, Tastaturen und Mäusen. Pausenlos huschte er von einem zum anderen, drückte irgendwelche Tasten, grunzte, nickte und schien seinen Besucher gar nicht zu bemerken.

Jeremy räusperte sich. „Hallo Betlas, sag, hättest du kurz? Es geht da um ein Ticket“.

Ohne ihn anzublicken, setzte er seine Arbeit fort, aber antwortete schließlich trotzdem. „Keine Zeit, siehst du nicht, dass ich zu tun habe? Das nächste Wartungsfenster der Sonne steht an!“

„Was, Wartungsfenster? Mitten am Tag?“

„Ach, das fällt doch keinem auf“, erwiderte Betlas. „Zum Glück haben wir da noch die Früchte von Selenas Ausrutscher damals.“

„Ah, verstehe.“ Damals, ziemlich zu Beginn der Sandbox, gab es einen Riesen Merge-Conflict mit dem Theia Branch, wodurch ein kleiner Mond entstand. Hatte es also doch was Gutes. „Aber wann hättest du denn Zeit, dir das anzusehen? Es geht da um so ein Performance Thema…“

„Performance ist doch sicher ein Code-Thema. Da kann ich kaum was machen.“ Betlas begann, in einer Kiste zu kramen, und holte einige Riegel Arbeitsspeicher hervor. „Abgesehen davon – ich hab absolut keine Zeit. Ich schultere hier die ganze Last der Server, ganz alleine. Weißt du eigentlich, wann ich zuletzt Pause hatte?“

Zögerlich blickte ihn Jeremy an. „Ähm, nein, weiß ich nicht?“

„Ich auch nicht mehr so genau….“ Betlas schnaubte. „Ich glaub, so vor 3000 Jahren war das, als Hermankles ausgeholfen hat. Aber Herta musste ihm ja danach unbedingt noch elf andere Aufgaben geben. Seitdem bin ich hier am Schuften.“ Er eilte mit den RAM-Riegeln von dannen, zog gekonnt irgendeine Lade aus einem Serverschrank und steckte sie rein.

„Aber Betlas, es ist wirklich dringend…“, versuchte es Jeremy.

„Pfft. Dringend, wenn ich das schon höre.“ Genervt verdrehte Betlas die Augen. „Ich muss mir schön langsam mal die Beine vertreten. Das ist wirklich dringend.“ Plötzlich hielt er inne und schaute Jeremy an. „Du, Jeremy… Vielleicht können wir einen Deal machen. Du hältst hier kurz die Stellung, ich trete ganz schnell aus, und danach schau ich mir dein Ticket an. Was meinst du?“

Jeremy verzog skeptisch den Mund. „Aber ich kenne mich damit doch gar nicht aus. Was, wenn ich es kaputt mache?“

„Ach“, winkte Betlas ab. „Ich kannte mich doch damals auch nicht aus, als mich Seus hierhin strafversetzt hat. Das wird schon, ok? Mach einfach, was auf den Monitoren steht, da drüben, probier mal eine Aufgabe.“

Langsam näherte sich Jeremy dem Bildschirm. Darauf stand: „Kritischer Bugfix bei Quantenengine – Teilchen verheddern sich. Einspielen?“. Jeremy klickte auf Ja. „War ja ganz einfach, ich glaub, ich kann kurz…“

„Danke, Jeremy, du bist der Beste“, hörte er und sah Betlas nur noch von hinten verschwinden.

Nun war er da, alleine im Serverraum, und führte eine Aufgabe nach der anderen durch. Kaum hatte er eine erledigt, kam die nächste. Die Updates kamen im Sekundentakt, immer wieder fielen einzelne Geräte aus, es war ein ewiger Wettlauf mit der Zeit. *Schön langsam verstehe ich, wieso das keiner machen will.*

Ob er hier nun seit Minuten, Stunden oder Tagen war, konnte er nicht einschätzen. Im ewigen Strom der aufpoppenden Warnleuchten verlor er jegliches Zeitgefühl. Schön langsam ging Jeremy die Puste aus, aber zum Müde werden hatte er einfach keine Zeit. Ein Fehler, und die Sandbox könnte abstürzen.

Erleichtert drehte er sich um und sah Betlas, wie er genüsslich in einen Apfel biss. „Da bist du ja endlich wieder, also wegen den Performancetickets…“

„Achtung!“, rief Betlas. „Da, hinter dir, eine Festplatte ist ausgefallen.“

Gekonnt tauschte Jeremy sie aus, sprach aber weiter. „Es geht um das Geschwindigkeitsmaximum, irgendwie läuft alles bei maximal 300.000 km/s. Kriegen wir das irgendwie schneller hin?“

„Hmm, nein, glaub nicht, dass das schneller geht. Nicht mit dieser Hardware.“ Es knirschte, als Betlas in den Apfel biss, und mit vollem Mund fügte er schnell hinzu. „Aber ich werde noch drüber nachdenken. Mach noch ein bisschen weiter, ich komm dann demnächst wieder“.

*Wer’s glaubt…* Jeremy konnte einfach nicht mehr hier sein. Er musste etwas voranbringen, nicht nur die Maschine am Laufen halten. „Ok, ich mach gleich weiter, aber meine Robe ist verrutscht. Kannst du vielleicht nur ganz kurz, während ich sie richte?“

„Danke, Betlas, ich melde mich!“, rief Jeremy, während er in Windeseile zurück ins Büro eilte. *Dann mach ich doch lieber bei der `get_10_gebote` Methode weiter.*

**Fortsetzung folgt!**