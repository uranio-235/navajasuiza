## Navaja Suiza para Servidores de Linux

**ejemplo.service** - Una unit de systemd muy simple, para ejecutar un script al
inicio.

**firewall.sh** - Un sencillo cortafuegos de iptables, que al ejecutarse con -w
como argumento, almacena la reglas del cortafuegos de acorde al sistema de
persistencia de la distro (debian o centos de momento).

**salva.sh** - Lee las rutas del fichero ~/salva.lst, crea un directorio ~/salva
y hace una copia de dichas rutas ahí.

**safarrancho.sh** - De acorde a la distribución, efectúa una limpieza general
que adelgaza bastante. Borra las páginas de man en otros idiomas, borra el
contenido de /usr/share/doc/. Elimina logs antiguos.

**cronos.sh** - Usa curl para tomar el encabezado date de un servidor web
(www.google.com o alguno argumentado) y graba dicha fecha a la hora del sistema.
Literalmente se roba la hora. 😜

**vpnssh.sh** - Ejecuta ppp a través de ssh, de tal forma que crea una especie
de vpn entre el host local y remoto. Muy útil para todo tipo de situación.

**knockd.conf** - Configuración elemental de Portknocking. Recuerda cambiar los
puertos, los de ahí son un ejemplo.
