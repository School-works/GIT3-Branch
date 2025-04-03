## Es 03/04/25

# Git - Working with remotes
* I repository remoti sono versioni del tuo progetto che sono ospitate su Internet
* La collaborazione con altri programmatori implica la gestione di questi repository remoti e il push e il pull di dati

Fondamentalmente è saper **sincronizzare il nostro lavoro locale con un repository remoto.**

*comandi principali:*

`git restore --v` --> visualizza i server remoti collegati al nostro repository

## Aggiungere o rimuovere un repository remoto

`git remote add <nome> <url>`

## Caricare il lavoro locale sul repository remoto

`git push <remote> <ramo-locale>`

## Aggiungere la copia locale del repository, allinandola con la versione remota

`git pull <remote> <ramo-locale>`