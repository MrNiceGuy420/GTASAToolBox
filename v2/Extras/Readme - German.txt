*** Extras ***


*** Wichtig ***
In diesem Ordner findest du einige Dateien, die du mit der GTA San Andreas ToolBox und/oder mit GTA San Andreas verwenden kannst.
Diese Dateien sind in Ordner sortiert.
Alle Dateien, die sich in diesem Ordner befinden, in dem auch diese Readme-Datei ist, k�nnen direkt in den Ordner der GTA San Andreas ToolBox kopiert werden.
Wenn sich eine Datei in einem Unterordner befindet, muss diese auch in den selben Ordner im ToolBox-Verzeichnis kopiert werden.

Beispiel:

Die GTA San Andreas ToolBox ist in dem Verzeichnis "C:\Programme\SelfCoders\GTA San Andreas ToolBox\" installiert. Das ist somit das ToolBox-Verzeichnis.
Wenn du nun zum Beispiel die Datei "XYZ.ini" installieren m�chtest, welche sich im Ordner "ABC\Test\" (C:\Programme\SelfCoders\GTA San Andreas ToolBox\Extras\ABC\Test\) befindet,
muss diese zum Installieren auch in den Ordner "C:\Programme\SelfCoders\GTA San Andreas ToolBox\ABC\Test\" kopiert werden.


Es gibt ein paar Besonderheiten der Ordnerstruktur.
Die Dateien und Ordner im Ordner "GTASA" m�ssen in das Verzeichnis von GTA San Andreas kopiert werden, sofern es nicht durch eine Readme-Datei bestimmt wird.

Befindet sich in einem der Ordner eine Readme-Datei, wird m�glicherweise in dieser Readme-Datei beschrieben, wo die Datei(en) hinkopiert werden m�ssen und welche man daf�r kopieren muss, damit es funktioniert.
Es gibt Extras, die zus�tzliche Dateien ben�tigen. Dies wird dann in der entsprechenden Readme-Datei angegeben.
Achte darauf, dass du vor dem �berschreiben von Dateien ein Backup erstellst, da ein �berschreiben von Dateien nicht mehr r�ckg�ngig gemacht werden kann.


Wenn du Dateien in den Ordner "Update" kopierst, werden diese Dateien beim n�chsten Start der GTA San Andreas ToolBox GUI automatisch in die Ordner verschoben.

Ein kleines Beispiel dazu:
Du kopierst eine Datei mit dem Name "X.txt" in den Ordner "Update", welcher sich im ToolBox-Ordner befindet. In unserem Beispiel ist dies "C:\Programme\SelfCoders\GTA San Andreas ToolBox\Update\".
Beim n�chsten Start der GTA San Andreas ToolBox GUI, werden alle Dateien aus diesem Ordner in den ToolBox-Ordner verschoben. Ist das Verschieben nicht erfolgreich,
zum Beispiel weil die zu verschiebende Datei gerade verwendet wird, wird versucht die Datei beim n�chsten Start der ToolBox GUI erneut zu kopieren. Erst wenn die Datei erfolgreich kopiert worden ist, wird die Datei aus dem Update-Ordner gel�scht.
Ist ein Ordner im Update-Ordner leer, wird dieser auch gel�scht. Befinden sich keine Dateien und Ordner im Update-Ordner, wird der Update-Ordner gel�scht.

Die Ordnerstruktur:
ToolBox-Ordner\Update\Datei.txt => ToolBox-Ordner\Datei.txt
ToolBox-Ordner\Update\X\ABC.exe => ToolBox-Ordner\X\ABC.exe

Ist der Zielordner, in welche die Datei kopiert werden soll, nicht vorhanden, wird er automatisch erstellt.



*** Automatische Ausf�hrung eines Scripts beim Start der GTA San Andreas ToolBox ***
Nun ist es M�glich, mit der GTA San Andreas ToolBox Scripts automatisch beim Start der ToolBox GUI auszuf�hren.
Hierzu muss nur ein San Andreas ToolBox Script (satbs) im ToolBox-Ordner mit dem Name "Startup.satbs" vorhanden sein.
Diese Datei wird bei jedem Start der ToolBox GUI ausgef�hrt.