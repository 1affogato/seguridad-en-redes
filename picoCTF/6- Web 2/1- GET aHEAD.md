# Reto
# Descripcion
Find the flag being held on this server to get ahead of the competitionhttp://wily-courier.picoctf.net:56923/
# Solucion
![[Pasted image 20260224201436.png]]
### Flag: picoCTF{r3j3ct_th3_du4l1ty_8b13f07}
# Notas
Las pistas mencionan utilizar burpsuite, al ver que los botones hacian peticiones post y get en el html hice referencia al nombre del reto y le puse head cuando al request cuando lo intercepte en burpsuite, y al enviarlo la pagina respondio dandome la bandera.

Burpsuite:
Burp Suite es una herramienta de software propietaria para la evaluación de seguridad y las pruebas de penetración de aplicaciones web.
# Referencias
https://en.wikipedia.org/wiki/Burp_Suite