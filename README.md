# intraaktion.de

Inhalte auf intraaktion.de .
Die Texte sind verfasst in ahrf (https://github.com/Ypnose/ahrf).
Ein commit hier löst eine webhook aus, die dem Server mitteilt, einen "pull"
der Änderungen vorzunehmen. Die Dateien werden in den src-Ordner eines lokalen
wswsh (https://github.com/Ypnose/wswsh) kopiert, welches dann auch ausgeführt wird.
Die Ergebnisse im dest-Ordner werden dann in das webroot-Verzeichnis kopiert und
damit sichtbar.


Contents facing on intraaktion.de .
Texts are written in ahrf (https://github.com/Ypnose/ahrf).
A commit here invokes a webhook that makes the server pull the changes,
sync the files into the src/ of a local wswsh (https://github.com/Ypnose/wswsh),
which also gets executed. dest/ is then being sync'ed with the webroot.
