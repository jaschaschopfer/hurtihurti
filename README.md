# hurtihurti - Website mit 5 Unterseiten


## Wie haben wir gearbeitet

Jascha und Nick haben den Lead übernommen. Basierend auf dem CD/CI wurde das :root und die Unterseiten mit dazugehörigen HTML/CSS erstellt.
Anschliessend haben wird die Unterseiten in der Gruppe aufgeteilt. Die einzelnen CSS ermöglichten es uns, simultan an der Website zu arbeiten. 

Wir haben den Mobile First Ansatz gewählt. 

Navigation und Footer hat Nick erstellt und auf alle Seiten kopiert. Dies war effizient und lies alles gleich aussehen. 
Das :root mit voreingestellten Paddings, Margins, Gaps usw. hat ebenfalls geholfen einen konsistente Umsetzung hinzubekommen.

Bilder, Logo und Icons haben wir selbst aufbereitet und passend auf die den Anwendungsort formatiert, damit wir dies nicht per CSS machen mussten. Dies hat sich als hilfreich herausgestellt.

Als alle Teammitglieder ihre Unterseiten fertiggestellt haben, wurden die nochmals aufeinander abgestimmt und mit Navigation und Footer versehen. 

## Was hat geklappt

Das :root war sehr hilfreich und sinnvoll. Die vielen CSS's auch, haben das Arbeiten aber etwas unübersichtlich gemacht.

Das Endprodukt ist bis auf einige Details identisch mit dem Figma.

Die Website ist responsive und weist z.B mit der Hoverfunktion im Menu auch eine gute Usability auf.

HTML/CSS ist valide

## Was hat nicht geklappt

Wir haben aufgrund der Verwendung von section/article anstatt div einige Warnungen im HTML-Validator, weil keine H2 zu erkennen sind. Für SEO ist das nicht optimal, wir haben uns dazu entschieden hier keine Anpassungen vorzunehmen. Grund dafür ist die Begrenzung auf eine Max Seitenbreite von 1440px im Main, welche dafür sorgt, dass die Seite auf breiteren Bildschirmen nicht verzogen, sondern mit weiss umgeben wird. Wenn wir die H2 aus der section/article genommen hätten, würde die Position nicht auf allen Seiten übereinstimmen. (Manchmal ist das H2 Teil eines Grids, manchmal Teil einer Flexbox). Durch den Validator sind wir darauf aufmerksam geworden, dass wir zukünftig jeden Titel mit in die Section nehmen, statt die Titel direkt in den Body zu schreiben und die Titel so mit ihrem Content zusammen einzurücken bzw. in der Mitte der 1440px zu zentrieren.

## Hilfsmittel

Folgende Hilfsmittel haben wir benutzt:
- ChatGPT 4.0
- W3 Schools
- Unterrichtsunterlagen
- https://jigsaw.w3.org/css-validator/
- https://validator.w3.org/nu/
- https://squoosh.app
- weitere HTML/CSS Hilfeseiten nach Googlesuche z.B. https://css-tricks.com/snippets/css/a-guide-to-flexbox/

ChatGPT war insbesondere hilfreich, kleine Fehler zu finden, die wir zwar im auf der Live-Website gesehen, aber im Code nicht gefunden haben. Wir haben oft einzelne Teile des HTML-Codes zusammen mit dem CSS eingespeist und meistens schnell den Fehler aufgezeigt bekommen. Ebenfalls haben wir uns Lösungsvorschläge anzeigen lassen. Dabei haben wir aber strikt darauf geachtet, dass wir nur Dinge von ChatGPT in unseren Code kopieren, die wir auch verstehen. Ansonsten wäre es für den Lernprozess und die anderen Gruppenmitglieder nicht sinnvoll gewesen.

Hier notieren was geklappt hat, was nicht, wie gearbeitet wurde, wo ChatGPT gebraucht wurde etc.


## Unsere Wünsche/Rückmeldung an die Dozierenden

Schwierig war mit fünf Personen am Projekt zu arbeiten, weil alle den Code etwas anders verfassen. Hier waren wir zu Beginn etwas verloren und hätten uns mehr Input von den Dozierenden gewünscht. z.B. Wie entscheiden wir ob Flex/Grid in der Anwendung sinnvoller sind, Tipps für die Zusammenarbeit, Tipps zum Start mit Webseite (bspw. wo braucht man welche Einheit (px, %, rem etc.), Mobile First/Desktop First Vor- und Nachteile, Tipps und Tricks wie root wurden erst im Coaching Thema). Der Übergang vom Üben mit ZenGarden/IMP-News zum Coden an der eigenen Website war etwas zu sprunghaft. 

Nach einiger Zeit (und Fehlern) haben wir aber dennoch für das Meiste eigenständig eine Lösung gefunden. Die Tage an denen Dozierende vor Ort waren, war für uns sehr hilfreich, weil wir jederzeit und mehrmals Fragen stellen konnten. Online Coaching haben wir als weniger effektiv und zu kurz empfunden. 
