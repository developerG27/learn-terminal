La linea di comando è lo strumento più potente che abbiamo all'interno del nostro computer, ci permette di fare tutto

ls - list directory contents
Lista normale

ls -a
Lista anche i file nascosti

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

top
tutti i processi che si stanno eseguendo nel computer, è interattivo

ps -wA
mostra tutti i processi che si stanno eseguendo e da dove arrivano, non è interattivo

kill -9 [id processo]
Interrompe un processo

ps -wA | wc -l
Mostra la quantità di processi che si stanno eseguendo

uptime
Mostrada quando tempo è acceso il computer, quanti utenti sono loggati, 

Si possono eseguire più comandi contemporaneamente inserendo il ;
ls; echo 'hello'
si esegue prima ls e poi echo 'hello'

grep
cerca all'interno di un documento, incluso i binari

date; [comando]; date;
misura il tempo di esecuzione di un comando

find [path] -name [nome]
cerca in nome nel path che gli diciamo

time
mostra il tempo nel processore

curl [link]
emula un browser e ritorna tutti i valori del file

zip [nome.zip] [file]
crea un archivio e al suo interno inserisce il file come parametro

unzip [nome.zip]
Unzippa il file

unzip [nome.zip] -vl
Non scomprire lo zip ma mostra il suo contenuto

pipe
Ci permette concatenare comandi

Crontab: ci permette automatizzare la terminale
Per eseguier Crontab il computer deve essere acceso

du - disk usage
mostr quanti kb sta usando

ln -s [path] [alias] 
Crea un alias che ritorna il path
esempio:
ls -s C:/cartella alias_file
cd alias_file


whoami - Who am i - Chi sono


Tipologie di permesso
--- : 0
--x : 1
-w- : 2
-wx : 3
r-- : 4
r-x : 5
rw- : 6
rwx : 7
r: Lettura
w: Lettura e scrittura
x: esecuzione

In binario
000 => 0
001 => 1
010 => 2
011 => 3
100 => 4
101 => 5
110 => 6
111 => 7