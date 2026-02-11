# Reto
# Descripcion
Unzip this archive and find the file named 'uber-secret.txt'
- [Download zip file](https://artifacts.picoctf.net/c/501/files.zip)
# Solucion 1

```
affogato1-picoctf@webshell:~$ grep -r pico files
files/adequate_books/more_books/.secret/deeper_secrets/deepest_secrets/uber-secret.txt:picoCTF{f1nd_15_f457_ab443fd1}
files/14789.txt.utf-8:brassa un picotin d'orge_. Comme depuis une demi-heure environ c'était
```

# Solucion 2

```
affogato1-picoctf@webshell:~$ find -name uber*       
./files/adequate_books/more_books/.secret/deeper_secrets/deepest_secrets/uber-secret.txt
affogato1-picoctf@webshell:~$ cat ./files/adequate_books/more_books/.secret/deeper_secrets/deepest_secrets/uber-secret.txt
picoCTF{f1nd_15_f457_ab443fd1}
```
### Flag: picoCTF{f1nd_15_f457_ab443fd1}
# Notas
Find busca en el subdicrectorio en nombre cualquier archivo o carpeta
# Referencias
