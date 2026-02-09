# SHAMD
*** ENGLISH FOLLOW ***

SHAMD e' uno script Nautilus per Zorin OS, serve a visualizzare/confrontare hash MD5 e SHA256 del file selezionato
in caso sia presente nella clipboard un codice SHA256 o MD5 verra automaticamente confrontato con quello del file selezionato
file di grosse dimensioni richiedono molto tempo.
lo script usa i seguenti comandi che devono essere presenti nel sistema: "zenity", "python3", "md5sum" e "sha256sum"
al momento non ho trovato bug significativi, apparte il fatto che se la clipboard contiene una stringa alfanumerica di 32 o 64 caratteri che non sia un hash fa comunque il confronto ed ovviamente restrituisce errore.

Installazione:
copiare il file dentro la cartella "~/.local/share/nautilus/scripts/"
impostarlo come eseguibile con "chmod +x ~/.local/share/nautilus/scripts/SHAMD"

Uso:
lo script sara' immediatamente disponibile, selezionare un file con il tasto destro, selezionare la voce di menu "scripts" ed infine selezionare SHAMD


* English
SHAMD is a Nautilus script for Zorin OS to retrieve/compare SHA256 and MD5 hashes of selected file
if an hash SHA256 or MD5 is present in clipboard it automatically compare it with the selected file and show the result.
big file size require lot of time
the script uses some commands that must be present in system: "zenity", "python3", "md5sum" and "sha256sum"
i've not found any significant bugs atm, just if clipboard contain an alphanumeric string of 32 or 64 chars that's not an hash, it compare anyway whith the file and it return error ofcourse.

Install:
copiary the file in folder "~/.local/share/nautilus/scripts/"
make it executable with "chmod +x ~/.local/share/nautilus/scripts/SHAMD"

Use:
script will be instantly available, select a file with right mouse button, select "scripts" menu and finally select SHAMD
