# Reto
# Descripcion
Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...[warm](https://challenge-files.picoctf.net/c_wily_courier/70013ed41d4cfe2bb48628471dac6fc12238b5dbe164301ae3b4e35277b1e80b/warm)
# Solucion 1

```
affogato1-picoctf@webshell:~$ chmod +x warm
affogato1-picoctf@webshell:~$ ./warm
Hello user! Pass me a -h to learn what I can do!
affogato1-picoctf@webshell:~$ ./warm -h
Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_ac5832c}
```
# Solucion 2 

```
affogato1-picoctf@webshell:~$ strings warm | grep pico
Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_ac5832c}
```
### Flag: picoCTF{b1scu1ts_4nd_gr4vy_ac5832c}
# Notas 
chmod +x  permite agregar permisos de ejecucion, se puede agregar comandos a un archivo ejecutable
# Referencias
