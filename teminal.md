La linea di comando è lo strumento più potente che abbiamo all'interno del nostro computer, ci permette di fare tutto

ls - list directory contents
Lista normale

ls -l 
Lista verso il basso

ls -lh
Lista leggibile per l'essere umano

Ctrl + l - Pulisce la terminale

clear - Pulisce la terminale

ls /usr/bin
Mostra tutti i binari (.exe) che sono installati all'interno del computer

ls /usr/bin | wc -l
La quantità di comandi disponibili

pwd
Working directory

cd ~ 
ritorna alla home

cd .. 
torna indietro di una cartella

mkdir nome
crea una cartella con il nome che gli hai passato

touch file.txt
crea un file, in questo caso file.txt

rm -remove
cancella un file

mv [file] [nuova_directory]
Sposta un file

mv [nomeFile] [nuovoNome]
Rinomina il file

cp [file] [directory]
Copia il file nella nuova directory

pushd
salva la directory dove siamo e ci porta al directory che gli passiamo come parametro

popd
ritorna il directory che abbiamo salvato con 

open [file]
Apriamo il file

more [file]
ritorna le prime tre linee 

less [file]
nelle nuove distribuzioni non si usa più more ma less, è stato riscritto

cat [file]
stampa il contenuto del file nella terminale

tail [file]
mostra le ultime 10 linee del file

echo 'testo'
stampa in console il parametro