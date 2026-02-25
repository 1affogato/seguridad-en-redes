# Reto
# Descripcion
There is some interesting information hidden around this site. Can you find it?

Additional details will be available after launching your challenge instance.
# Solucion
html:
```
<!-- Here's the first part of the flag: picoCTF{t -->
```
css:
```
/* CSS makes the page look nice, and yes, it also has part of the flag. Here's part 2: h4ts_4_l0 */
```

robots.txt:
```
# Part 3: t_0f_pl4c
# I think this is an apache server... can you Access the next flag?
```

.htaccess
```
# Part 4: 3s_2_lO0k
# I love making websites on my Mac, I can Store a lot of information there.
```

.DS_Store
```
Congrats! You completed the scavenger hunt. Part 5: _f7ce8828}
```
### Flag: picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_9588550}
# Notas
Para realizar este reto revise el codigo fuente primero como rutina, aparecio comentada una parte de la bandera, me puse a revisar el css y aparecio la segunda parte, al ver el js no aparecio nada pero pero al revisar robots.txt me dio otra parte y me dejo una pista de que era un servidor apache, lo que sugiere buscar archivos de configuración de ese servidor. Al encontrar la cuarta parte tambien da una pista sobre mac asi qu deduzco que puede haber un archivo .DS_Store subido, me dio la ultima parte y junte todas las partes para armar la bandera y listo
# Referencias
https://httpd.apache.org/docs/2.4/en/howto/htaccess.html
https://en.wikipedia.org/wiki/.DS_Store