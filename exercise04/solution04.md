1. Creare il file ```.gitignore```
```
$ vi .gitignore
```
2. Creare un altro file chiamato ```no-add.txt```
```
$ vi no-add.txt
``` 
2. Aggiungere all'indice solo il file ```.gitignore```, committarlo (con il messaggio "gitignore") e pusharlo verso origin
```
$ git add .gitignore
$ git commit -m "gitignore"
$ git push origin
```
