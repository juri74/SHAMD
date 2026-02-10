# SHAMD
*** ENGLISH FOLLOW ***

*** Italiano:

SHAMD è uno script BASH Nautilus per Zorin OS, serve a visualizzare/confrontare hash MD5, SHA1 e SHA256 del file selezionato,
in caso sia presente nella clipboard un codice MD5, SHA1 o SHA256 verrà automaticamente confrontato con quello del file selezionato.
File di grosse dimensioni richiedono molto tempo.

Lo script usa i seguenti comandi che devono essere presenti nel sistema: "zenity", "md5sum" ,"sha1sum", "sha256sum", "python3". Tutti i comandi dovrebbero essere già presenti in Zorin OS.
Al momento non ho trovato bug significativi, apparte il fatto che se la clipboard contiene una stringa alfanumerica di 32, 40 o 64 caratteri che non sia un hash fa comunque il confronto ed ovviamente restrituisce errore.

Installazione:<br>
copiare il file dentro la cartella "~/.local/share/nautilus/scripts/"<br>
impostarlo come eseguibile con "chmod +x ~/.local/share/nautilus/scripts/SHAMD"


Uso:<br>
lo script sara' immediatamente disponibile, selezionare un file con il tasto destro, selezionare la voce di menu "scripts" ed infine selezionare SHAMD

v1.0 Versione iniziale<br>
v1.1 Aggiunto calcolo/controllo HASH SHA1

*** English:

SHAMD is a Nautilus BASH script for Zorin OS to retrieve/compare MD5, SHA1 and SHA256 hashes of selected file,
if an hash MD5, SHA1 or SHA256 is present in clipboard it automatically compare it with the selected file and show the result.
Big file size require lot of time.

The script uses some commands that must be present in system: "zenity", "md5sum", "sha1sum", "sha256sum", "python3". All commands should already present in Zorin OS.
I've not found any significant bugs atm, just if clipboard contain an alphanumeric string of 32, 40 or 64 chars that's not an hash, it compare anyway whith the file and it return error ofcourse.

Install:<br>
copy the file in folder "~/.local/share/nautilus/scripts/"<br>
make it executable with "chmod +x ~/.local/share/nautilus/scripts/SHAMD"


Use:<br>
script will be instantly available, select a file with right mouse button, select "scripts" menu and finally select SHAMD

v1.0 Initial Version<br>
v1.1 Added SHA1 HASH calculation/check
