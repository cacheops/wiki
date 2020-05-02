

docker 
    run             # Direttiva RUN che permette di eseguire un instanza 
    --rm            # Cancella l'instanza dalla memoria dopo l'esecuzione 
    -v ${PWD}:/app  # Condivido la mia cartella corrente con la cartella del container per permettere 
                    # il salvataggio dei cambiamenti
    -u $(id -u)     # Condivido il mio utente locale con l'utente che dentro il container eseguirà l'app  
    composer        # Immagine da eseguire 
    --version       #




