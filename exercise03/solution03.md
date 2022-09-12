1. Fare il checkout sul branch feature/\<mio-nome\>, aggiungere un file chiamato ```mio-nome.txt```, e verificare lo stato della repository.
>(potete creare il file come preferite. A titolo di esempio in questo corso è stato creato usando vi)
```
$ git checkout feature/mio-nome
$ vi mio-nome.txt
$ git status
```
>Osservare l'output dell'ultimo comando
2. Aggiungere il contenuto appena creato ```all'indice``` e commitare con il messaggio ```'git crash course'```
```
$ git add .
$ git commit -m "git crash course"
```
3. Pushare il commit appena fatto verso la repository remota (origin)
```
$ git push origin
```