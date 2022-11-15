#Mostrar claves wlan con CMD

1. Obtener los nombres de los perfiles de wifi `netsh wlan show profiles`
2. Obtener la clave de un perfil `netsh wlan show profiles "nombre_de_perfile" key=clear`
3. en la seccion `Security settings` --> `Key Content` aparece la clave en texto plano.
