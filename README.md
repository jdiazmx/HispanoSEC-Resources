# HispanoSEC-Resources

# Getting Started

* [Overthewire - Sitio web de Wargames para empezar desde 0](https://overthewire.org/wargames/)
Diversos wargames que permiten iniciar en el mundo de la seguridad sin tener ningun tipo de conocimiento previo, siguiendo la guia recomendada por el sitio.

* [Crear laboratorio de pentesting con GNS3](https://www.dragonjar.org/creando-un-laboratorio-de-pentesting-gns3.xhtml)</br>
Guía para la creación de laboratorio de pentesting con soporte para multidispositivos de diferentes fabricantes tales como Cisco, Juniper, Cumulus, Fortinet, PFsense etc., y de diferentes tecnologías de virtualización tales como Docker, QEMU, Dynamips, etc., además que nos ofrece la posibilidad de integrar nuestras máquinas virtuales de VirtualBox o VMware a nuestra topología de red, y software de análisis de red como Wireshark y SolarWinds.


# Misceláneas

* [Ataque dirigido con JS Botnet](http://www.elladodelmal.com/2012/07/ataque-dirigido-con-javascript-botnet.html?m=1)</br>
Ataques dirigidos a webs cuando aún está conectada la víctima al payload, para que una vez que se desconecte, la web que visite esté infectada.

* [Stealking wifi password via browsers cache poisoning](https://rhaidiz.net/2018/10/25/dribble-stealing-wifi-password-via-browsers-cache-poisoning/ )</br>
Artículo que indica como robar claves de wifi explotando la cache del navegador con javascript.

* [Pastejacking](https://www.hackplayers.com/2017/11/comprometido-por-solo-copiar-y-pegar.html)</br>
Explicación de ésta maravillosa técnica para hackear con solo copiar y pegar el contenido de una página.

# Malware 

* [Malware Sample Sources for Researchers](https://zeltser.com/malware-sample-sources/)</br>
Lista de distintos malwares para descargar y analizar.

* [Javascript Malware Explained](https://heimdalsecurity.com/blog/javascript-malware-explained/amp/)</br>
Explicación sobre malware hecho en javascript, y sus efectos letales.

* [Ransomware %100 Javascript](https://nakedsecurity.sophos.com/es/2016/06/20/ransomware-thats-100-pure-javascript-no-download-required)</br>
Ransomware que es 100% puro JavaScript, sin necesidad de descargar

* [1 - Introducción a los crypters](http://www.securitybydefault.com/2013/07/introduccion-los-crypters.html)</br>
[2 - Funcionamiento de los crypters](http://www.securitybydefault.com/2013/07/funcionamiento-de-los-crypters.html)</br>
[3 - El stub, la pieza clave del crypter](http://www.securitybydefault.com/2013/08/el-stub-la-pieza-clave-del-crypter.html)</br>
[4 - Modding 'Crypters': el arte de la evasión](http://www.securitybydefault.com/2013/08/modding-crypters-el-arte-de-la-evasion.html)</br>
[5 - Crypter: practicando la técnica dsplit/avfucker](http://www.securitybydefault.com/2013/09/crypters-practicando-la-tecnica.html)</br>
Serie de posts algo viejos, pero que sirven para entender como funciona un crypter, la cuál es una herramienta para ofuscar malware y hacerlo indetectable por los antivirus.

* [The Antivirus Hacker's Handbook](https://repo.zenk-security.com/Magazine%20E-book/Antivirus%20hackers%20handbook.pdf)</br>
Libro completo sobre el funcionamiento interno de antivirus, métodos para reversearlos y poder bypassearlos.

* [Subverting the windows kernel](https://www.pdfdrive.com/rootkits-subverting-the-windows-kernel-pdf-micropenguin-d12315832.html)</br>
Libro sobre creación de rootkits para windows.

### Tools:

* [VirusTotal](https://www.virustotal.com/gui/home/upload)</br>
Famosa web para escanear malware con multiples antivirus. Lo malo es que venden copias de los malwares subidos a empresas de antivirus.

* [NoDistribute](https://nodistribute.com/)</br>
Web para escanear malware, tal vez con menos antivirus que VirusTotal, pero proclama no vender ni distribuir copias de malware a empresas de antivirus.

* [Metadefender OPSWAT](https://metadefender.opswat.com/#!/)</br>
Servicio al que se le puede enviar archivos, IPs, dominios para detectar malware, contenido sensible, vulnerabilidades introducidas por las aplicaciones. La politica es: no confiar en ningún archivo ni dispositivo.

* [nuk3gh0st](https://github.com/JuanSchallibaum/Nuk3Gh0st)</br>Universal LKM rootkit que compila en la mayoría de distros y kernels. No funciona en sistemas multicore. Sirve para ocultar archivos, procesos y conexiones para que sean invisibles por el sistema operativo.

# Hacking web

* [Bug Bounty Hunter Methodology v3](https://www.youtube.com/watch?v=Qw1nNPiH_Go&t=2847s)</br>
Presentación sobre la metodología y herramientas actuales utilizadas para hacking web y bug bounty hunting.

* [the unofficial HackerOne disclosure timeline](http://h1.nobbd.de/)</br>
Reportes de vulnerabilidades del programa de hackerOne, para aprender nuevas técnicas empleadas por bug bounty hunters para atacar empresas grandes.
* [Brutelogic](https://brutelogic.com.br/blog/)</br>
Sitio con multiples posts sobre distintas formas de realizar ataques XSS.

* [Philippe Harewood](https://philippeharewood.com/)</br>
Posts sobre fallas lógicas poco habituales descubiertas en Facebook por Philippe Harewood.

* [SecLists](https://github.com/danielmiessler/SecLists)</br>
Wordlists con passwords, users, dominios, directorios, más ampliamente usado por bug bounty hunters.

* [LFI to RCE (old techniques)](https://www.rcesecurity.com/2017/08/from-lfi-to-rce-via-php-sessions/)</br>
Guía sobre posibles métodos para convertir un LFI en un RCE. La mayoría de éstos métodos quedaron obsoletos en la actualidad.

* [LFI to RCE (new technique)](https://dustri.org/b/from-lfi-to-rce-in-php.html)</br>
Otra técnica un poco más moderna para convertir un LFI en un RCE.

* [Subdomain Takeover](https://www.hackerone.com/blog/Guide-Subdomain-Takeovers)</br>
Guía sobre como detectar vulnerabilidades del tipo subdomain takeover.

* [Can I take over XYZ](https://github.com/EdOverflow/can-i-take-over-xyz)</br>
Lstado de ayuda para comprobar si existe la posibilidad de realizar un Subdomain Takeover.

* [HTTP Parameter Pollution](https://www.owasp.org/images/b/ba/AppsecEU09_CarettoniDiPaola_v0.8.pdf)</br>
Explicación sobre como realizar distintos ataques empleando la técnica de HTTP Parameter Pollution.

* [PHP Object Injection](http://www.elladodelmal.com/2014/11/ataques-de-php-object-injection-en.html)</br>
Buena explicación sobre la vulnerabilidad PHP Object Injection.

* [PHP Object Injection con ejercicios](https://www.tarlogic.com/blog/php-object-injection/)</br>
Breve explicación sobre PHP Object Injection y ejercicios prácticos.

* [SSRF](http://www.elladodelmal.com/2015/04/ssrf-server-side-request-forgery-xspa.html)</br>
Guía sobre como explotar una vulnerabilidad del tipo Server Side Request Forguery.

* [SSTI](https://www.owasp.org/images/7/7e/Owasp_SSTI_final.pdf)</br>
Explicación sobre como identificar y explotar una falla del tipo Server Side Template Injection.

* [CSTI in AngularJS](https://portswigger.net/blog/xss-without-html-client-side-template-injection-with-angularjs)</br>
Explicación de la vulnerabilidad Client Side Template Injection, y como efectuarla cuando encontramos un sitio con AngularJS.

* [Type jugling](https://www.hackplayers.com/2018/03/hashes-magicos-en-php-type-jugling.html)</br>
Explicación de la importancia de utilizar '===' en lugar '==' en PHP a la hora de comparar hashes de contraseñas.

* [Hacking JWT](https://medium.com/101-writeups/hacking-json-web-token-jwt-233fe6c862e6)</br>
Artículo que da una breve explicación sobre JSON Web Token como método de manejo de sesiones en lugar de cookies, y las posibles formas de hackearlo.

* [Bypassing Anti-CSRF tokens](https://haiderm.com/10-methods-to-bypass-cross-site-request-forgery-csrf/)</br>
10 métodos para explotar un CSRF incluso cuando existen tokens anti-CSRF.

* [Bypassing WAF](https://www.owasp.org/images/6/66/OWASP_Stammtisch_Frankfurt_-_Web_Application_Firewall_Bypassing_-_how_to_defeat_the_blue_team_-_2015.10.29.pdf)</br>
Explicación del funcionamiento de los WAFs y los distintos métodos para bypassearlos y lograr explotar una vulnerabilidad.

* [Bypassing WAF in RCE (part 1)](https://medium.com/secjuice/waf-evasion-techniques-718026d693d8)</br>
[Bypassing WAF in RCE (part 2)](https://medium.com/secjuice/web-application-firewall-waf-evasion-techniques-2-125995f3e7b0)</br>
Técnicas para bypassear WAFs cuando existe una vulnerabilidad del tipo RCE.

### Tools:

* [Burpsuite Proffesional con crack](https://www.youtube.com/watch?v=aYwiY934Hh4)</br>
Herramienta N°1 para la labor de hacking web. Mejor que OWASP ZAP.

* [brutespray](https://github.com/x90skysn3k/brutespray)</br>
Tool para bruteforcear credenciales por defecto de los servicios detectados por nmap.

* [masspwn](https://github.com/JuanSchallibaum/masspwn)</br>
Tool para escanear puertos abiertos velozmente y trabajar de forma conjunta con brutespray, haciendo el trabajo más eficiente.

* [subfinder](https://github.com/subfinder/subfinder) y [amass](https://github.com/OWASP/Amass)</br>
Tools para enumerar subdominios a través de distintas fuentes (sin usar fuerza bruta).

* [massdns](https://github.com/blechschmidt/massdns)</br>
Tool más eficiente para bruteforcear subdominios.

* [EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness)</br>
Tool que recibe una lista de dominios y toma screenshots de las páginas, para hacer un reconocimiento visual de como se verían las páginas. Muy util cuando logramos enumerar una amplia cantidad de subdominios de una empresa.

# Network hacking

* [MITM Attacks](https://www.blackhat.com/presentations/bh-europe-03/bh-europe-03-valleri.pdf)</br>
Paper con muchos métodos distintos para realizar ataques MITM.

* [BGP MITM](https://github.com/JuanSchallibaum/BGP-MITM)</br>
Topologías para practicar ataques BGP MITM, sus contramedidas, y otros temas relacionados con seguridad en BGP.

* [SNMP Hacking](https://hacking-etico.com/2014/03/27/leyendo-informacion-snmp-con-snmpwalk/)</br>
Breve explicación del protocolo SNMP, y como podemos extraer una gran cantidad de información de distintos dispositivos de red.

* [UPnP Hacking](https://www.dragonjar.org/hacking-de-redes-upnp-parte-i.xhtml)</br>
Posibles ataques al protocolo UPnP, explicacion de la herramienta miranda. Con ésto por ejemplo, podemos abrir puertos en un router del que no conocemos las credenciales.

* [Kerberos Hacking](https://www.tarlogic.com/blog/tickets-de-kerberos-explotacion/)</br>
Explicación básica sobre el protocolo Kerberos y los posibles ataques al mismo. Primero recomiendo leer la explicación del funcionamiento de Kerberos en Wikipedia.

* [DDoS](https://mundocontact.com/los-10-tipos-de-ataques-ddos-mas-comunes/)</br>
Explicación de los tipos más comunes de ataques DDoS.

* [IDS bypassing with nmap](https://nmap.org/man/es/man-bypass-firewalls-ids.html)</br>
Técnicas para bypassear firewalls o IDS/IPS mientras escaneamos puertos con nmap.

* [Hacking mobile networks](https://www.owasp.org/images/0/0b/OWASP_MCT.pdf)</br>
Guía de OWASP sobre ataques a redes móviles 2G y 3G.

### Tools:

* [Bettercap](https://github.com/bettercap/bettercap)</br>
Herramienta más completa y eficiente de la actualidad para hacer ataques MITM.

* [MITMf](https://github.com/byt3bl33d3r/MITMf)</br>
Otra tool bastante actual para hacer ataques MITM.

* [masscan](https://github.com/robertdavidgraham/masscan)</br>
Tool más rápida y eficiente para escanear puertos en redes grandes.

* [LOIC](https://sourceforge.net/projects/loic/)</br>
Tool para automatizar ataques DDoS.

# Wi-Fi Hacking

* [WiFu](https://mega.nz/#!TcoUjZZY!fC4jyr__Be_kWMJJuGtICpTL_kaSYu4CZ-CTlEmv57k)</br>
Libro bastante completo sobre el protocolo Wi-Fi, sus tipos de paqutes y distintos ataques en profundidad a redes WEP y WPA. Está escrito por los creadores de Kali Linux y es el material ofrecido por ellos para obtener la certificacion OSWP.

* [Choosing a Wireless Adapter for Hacking](https://null-byte.wonderhowto.com/how-to/hack-wi-fi-choosing-wireless-adapter-for-hacking-0157057/)</br>
Guía para elegir el adaptador Wi-Fi para auditorias que más nos convenga según nuestras necesidades.

* [Best Wireless Network Adapter for Wi-Fi Hacking in 2019](https://null-byte.wonderhowto.com/how-to/buy-best-wireless-network-adapter-for-wi-fi-hacking-2019-0178550/)</br>
Listado de los mejores adaptadores de Wi-Fi para auditorias.

* [Construir antena casera](https://www.taringa.net/+hazlo_tu_mismo/antena-wifi-casera-papas-pringles_12uqmr)</br>
Guía sobre como construir una antena direccional con una lata de pringless.

* [Cracking WEP](https://www.youtube.com/watch?v=m0uEXw0fkUw)</br>
Video ultra sencillo sobre como emplear la herramienta goyscript wep disponible en Wifislax, la cuál utiliza en paralelo muchas de las técnicas para crackear contraseñas WEP mencionadas en el libro WiFu.

* [Cracking Wi-Fi with WPS](https://www.youtube.com/watch?v=_d7EHujPt-U)</br>
Tres videos explicando como atacar a redes Wi-Fi con cualquier cifrado, mientras tengan WPS habilitado. Los routers empleados hoy en día bloquean WPS al realizar muchos intentos de pines distintos, asi que existen otras herramientas para volver a desbloquearlas. Es posible que nada de ésto funcione xD

* [Evil Twin Attack with Fluxion](https://www.taringa.net/+hazlo_tu_mismo/antena-wifi-casera-papas-pringles_12uqmr)</br>
Explicación sobre como montar un ataque del tipo evil twin con la tool Fluxion para obtener contraseñas de Wi-Fi a través de phishing. Sirve para redes con cualquier tipo de cifrado.

* [Cracking Fibertel Wi-Fi default passwords](http://usedmyhead.blogspot.com/2017/06/como-hackear-contrasenas-wpa-wpa2-psk.html)</br>
Con ésta guía podemos ver como crackear muy rápidamente una red Wi-Fi con cualquier encriptación, siempre y cuando mantenga la contraseña por defecto establecida por Fibertel.

* [Cracking WPA/WPA2 with rainbow tables](https://www.renderlab.net/projects/WPA-tables/)</br>
Aquí se pueden descargar tablas rainbow para crackear passwords WPA/WPA2 a gran velocidad. Solo funciona con redes que tengan uno de los SSID's con los que se generaron las tablas rainbow. Se habla sobre la tool cowpatty.

* [Pwning WiFi Networks con bettercap y PMKID](https://www.evilsocket.net/2019/02/13/Pwning-WiFi-networks-with-bettercap-and-the-PMKID-client-less-attack/)
Explicación sobre nuevos tipos de ataques para descubrir claves WPA PSK sin clientes conectados en el AP

# Binary Exploitation

* [Corelan.be](https://www.corelan.be/index.php/articles/)</br>
Página con muchos artículos relacionados con exploit writing para vulnerabilidades del tipo Stack Based Buffer Overflow en Windows de 32 bits.

* [Heap exploitation](http://security.cs.rpi.edu/courses/binexp-spring2015/lectures/17/10_lecture.pdf)</br>
Paper que explica muchas vulnerabilidades en binarios relacionadas con la heap: Heap Based Buffer Overflow, UAF (User After Free), Heap Spraying, y Metadata Corruption.

* [Format String](https://fundacion-sadosky.github.io/guia-escritura-exploits/format-string/5-format-string.html)</br>
Artículo que explica como explotar una vulerabilidad del tipo format string en binarios.

# Privilege escalation

* [Linux privilege escalation (resumed)](https://payatu.com/guide-linux-privilege-escalation/)</br>
Guía resumida sobre la metodología para escalar privilegios en Linux

* [Linux privilege escalation (extended)](https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/)</br>
Guía más amplia, con muchos más comandos para usar, pero no está tan explícito de que forma usar la información que te dan los comandos.

### Tools:

* [LinEnum](https://github.com/rebootuser/LinEnum)</br>
Bash script automatizado para lanzar muchos de los comandos de las guías anteriores y checkear la posibilidad de escalación de privilegios en Linux.

# Password cracking

* [Cracking windows passwords](https://c43s4rs.blogspot.com/2017/03/cracking-windows-passwords.html)</br>
Explicación sobre las contraseñas de windows LM y NTML, y los distintos métodos y tools empleadas para crackearlas.

* [Funcionamiento de las Tablas Rainbow](https://www.semecayounexploit.com/?sec=password-cracking&nota=5)</br>
Explicación sobre el funcionamiento de las tablas rainbow para crackear passwords de forma mucho más rápida y ocupando menos almacenamiento en disco (pero habiéndolas generado previamente, lo cuál lleva mucho tiempo). Por suerte existen muchas tablas rainbow ya generadas listas para descargar.

### Tools:

* [Mimikats](https://github.com/gentilkiwi/mimikatz)</br>
Herramienta para extraer los passwords de windows directamente de la memoria.También sirve para extraer los tickets de Kerberos.

* [hashcat](https://hashcat.net/hashcat/)</br>
Herramienta más óptima para crackear passwords, con la posibilidad de emplear la GPU para acelerar al máximo el proceso.

# Bad USB

* [DigiDucky](https://underc0de.org/foro/hacking/(rubber-ducky)-digiducky-desde-0-hasta-la-intrusion/)</br>
Explicación sobre como construir un bad usb muchísimo más económico que el Rubber Ducky.

# Radiofrecuencia

* [RTL-SDR](https://www.rtl-sdr.com/)</br>
Web con muchos artículos que nos explican ataques y distintos tipos de información que podemos obtener a través de un receptor de radiofrecuencia como el mismísimo RTL-SDR, o bien HackRF One si somos millonarios.

* [Hacking Mifare Classic Cards](https://www.blackhat.com/docs/sp-14/materials/arsenal/sp-14-Almeida-Hacking-MIFARE-Classic-Cards-Slides.pdf)</br>
Paper que explica como romper el cifrado de las tarjetas Mifare que emplean RFID, para clonarlas con un lector de RFID/NFC y las herramientas mfoc y mfcuk.

* [Clone key cars](https://www.youtube.com/watch?v=LbCDpbWrdlQ)</br>
Éste video muestra como copiar una señal de 433MHz con Arduino, y retransmitirla. Con ésta técnica se podría captar la señal emitida por las llaves de un auto y luego transmitirla cuando queramos, logrando "clonar" la llave del auto.

# IoT Hacking

* [Samsung and LG TV hacking](https://ehacking.com.bo/como-hackear-facilmente-tu-smart-tv-samsung-y-lg/)</br>
Explicación sobre el funcionamiento interno de los televisores de marcas Samsung y LG, y cómo hackearlos.

* [5 worst IoT hacking vulnerabilities](https://www.iotforall.com/5-worst-iot-hacking-vulnerabilities/)</br>
Lista de 5 graves vulnerabilidades a distintos dispositivos IoT.

# Social Engineering

* [The Art of Human Hacking](http://index-of.es/Varios/The_Art_of_Human_Hacking.pdf)</br>
Libro bastante completo sobre técnicas y metodologías empleadas por ingenieros sociales.

* [The Art of Deception](https://sbisc.ut.ac.ir/wp-content/uploads/2015/10/mitnick.pdf)</br>
Libro de ingenieria social escrito por Kevin Mitnick, el hacker más famoso del mundo, especializado en ingeniería social.

# Criptografía

* [Introducción a la criptografía](https://www.ucm.es/data/cont/docs/72-2016-11-10-2%20Comunicaciones%20seguras.pdf)</br>
Libro introductorio sobre conceptos y algoritmos criptográficos.

* [Manual sobre GPG](https://www.genbeta.com/desarrollo/manual-de-gpg-cifra-y-envia-datos-de-forma-segura)</br>
Tutorial sobre el uso de la herramienta gpg para emplear cifrado simétrico o asimétrico, exportar la clave pública a un servidor de claves, cifrar, descifrar, firmar y comprobar la firma de los archivos.

* [Poodle Attack](https://www.genbeta.com/seguridad/poodle-asi-es-el-ataque-que-deja-por-fin-obsoleto-a-sslv3)</br>
Ataque criptográfico a SSL (completamente parchado por browsers y servers), pero interesante para analizar.

# Esteganografía

* [Cheatsheet Steganography 101](https://pequalsnp-team.github.io/cheatsheet/steganography-101)</br>
Cheatsheet básico sobre métodos empleados en esteganografía.

* [Cheatsheet 2](https://trailofbits.github.io/ctf/forensics/)</br>
Cheatsheet que explica de forma un poco más completa métodos y herramientas empleados en esteganografía.

* [File format descriptions](https://github.com/corkami/pics/blob/master/binary/README.md)</br>
Descripción de los formatos de los distintos tipos de archivos con imágenes muy interesantes.

### Tools:

* [stego-toolkit](https://github.com/DominicBreuker/stego-toolkit)</br>
Imagen de docker que incluye decenas de herramientas de esteganografía, muy utiles para los CTFs.

# Forensia

* [Análisis Forense Digital](https://www.oas.org/juridico/spanish/cyb_analisis_foren.pdf)</br>
Breve libro que explica procedimientos llevados a cabo a la hora de realizar un análisis forense digital.

* [Coold boot attacks](https://www.youtube.com/watch?v=XfUlRsE3ymQ)</br>
Al apagar la PC los datos de la RAM permanecen por un instante de tiempo y pueden ser recuperados luego de apagar la PC. En la descripción del video hay links para crear un usb booteable que trata de leer los datos que aun persisten en la RAM.

# Hardening

* [Linux Server Hardening](https://www.cyberciti.biz/tips/linux-security.html)</br>
40 tips actualizados del 2019 para securizar un servidor Linux.

* [Nginx Web Server Hardening](https://www.cyberciti.biz/tips/linux-unix-bsd-nginx-webserver-security.html)</br>
25 mejores tips para securizar un servidor web Nginx.

* [Apache Web Server Hardening](https://www.apachecon.eu/)</br>
Tips para securizar un servidor Apache.

* [PHP Hardening](https://www.cyberciti.biz/tips/linux-unix-bsd-openssh-server-best-practices.html)</br>
25 tips para securizar PHP en nuestro servidor web.

* [OpenSSH Server Hardening](https://www.cyberciti.biz/tips/linux-unix-bsd-openssh-server-best-practices.html)</br>
20 mejores tips para securizar un servidor OpenSSH.

* [BIND DNS Server Hardening](https://securiteam.com/unixfocus/5up0l0u5gy/)</br>
Guía completa sobre como instalar un servidor DNS BIND y securizarlo.

* [FTP Server Hardening](https://likegeeks.com/ftp-server-linux/)</br>
Guía sobre el funcionamiento e instalación de un servidor ftp en linux y como securizarlo.

* [OWASP Secure Coding Practices](https://www.owasp.org/images/a/aa/OWASP_SCP_Quick_Reference_Guide_SPA.pdf)</br>
Guía de OWASP sobre buenas prácticas para desarrollar aplicaciones seguras.


# CTF platforms

* [CTF365](https://ctf365.com/)
* [Hack The Box](https://www.hackthebox.eu/)
* [WarZone elhacker.net](warzone.elhacker.net/)
* [CTF Platforms](https://github.com/We5ter/Awesome-Platforms/blob/master/CTF-Platforms.md)</br>
Repo de github que incluye una gran cantidad de CTF's para realizar en un entorno local.

# Blogs
* [Hacking Articles] (https://www.hackingarticles.in/)
* [Infocon] (https://infocon.org/cons/)
* [El lado del mal (Chema Alonso)](https://www.elladodelmal.com/)
* [Hacker Players](https://www.hackplayers.com/)
* [The Hacker News](https://thehackernews.com/)
* [Linuxito](https://www.linuxito.com/)
* [Criptored](http://www.criptored.upm.es/)
* [TroyHunt](https://www.troyhunt.com/)
* [Underc0de](https://underc0de.org/)
* [elhacker.net](https://elhacker.net/)
* [Null Byte](https://null-byte.wonderhowto.com/)

# Web utilities

* [Shodan](https://www.shodan.io/)</br>
El buscador de los hackers. Funciona distinto a los buscadores convencionales. No usa spiders para encontrar páginas web, sino que es un buscador de dispositivos conectados a Internet.

* [ZoomEye](https://www.zoomeye.org/)</br>
Buscador similar a Shodan de origen Chino que dice aportar más cantidad de información.

* [Exploit Database](https://www.exploit-db.com/)</br>
Mayor base de datos de exploits. También incluye una base de datos de dorks de google hacking, shellcodes y pappers.

* [0day.today](https://0day.today/)</br>
Otra base de datos de exploits. Algunos exploits son de pago.

* [bgp.he.net](https://bgp.he.net/)</br>
Página completa para encontrar sistemas autónomos buscando por IP o palabras claves.

* [BuiltWith](https://builtwith.com/)</br>
Página que detecta las tecnologías empleadas en una web.

* [CyberChef](https://gchq.github.io/CyberChef/)</br>
Página todo en uno, con herramientas de defodificación, cifrado, subnetting, etc. 

* [Dcode](https://www.dcode.fr/)</br>
Herramienta útil para decodificar automáticamente distintos tipos de mensajes codificados.

* [HaveIbeenPwned](https://haveibeenpwned.com/)</br>
Sitio en el que ingresamos nuestro e-mail y nos informa si hubo una filtración de datos en las que nuestra cuenta está involucrada.

* [Online regex tester](https://regex101.com/)</br>
Sitio para testear si las regex que estamos utilizando son válidas para lo que necesitamos.

* [ListDiff](http://www.listdiff.com/compare-2-lists-difference-tool)</br>
Sitio para comparar dos wordlists y ver que lineas aparecen solo en el primero de los dos, cuales aparecen solo en el segundo de los dos, cuales aparecen en ambos, y un merge de todas las lineas de ambos wordlist sin repetir. Con ésto podemos unir dos wordlist de password cracking en uno evitando que se repitan las palabras, o al hacer subdomain scrapping con dos tools distintas, como subfinder (más rápida y descubre más subdominios), y sublist3r (más lenta y descubre menos subdominios), y juntar todos los subdominios encontrados en un solo archivo.


# More tools

* [Python pentest tools](https://github.com/dloss/python-pentest-tools)</br>
Compilado con muchísimas tools escritas en python para realizar pentesting en sus distintas áreas.

# More books

* [Libros para principiantes](https://foro.elhacker.net/dudas_generales/listado_de_libros_para_principiantes-t497312.0.html)</br>
Listado completo de libros sobre programación, criptografía, y pentesting.

# Random webs

* [Internet Map](http://as2914.net/#/?_k=a39i1a)</br>
Mapa de interconecciones entre sistemas autónomos que conforman a la Internet. Interfaz excelente en 3D hecha con three.js

* [Submarine Cable Map](https://www.submarinecablemap.com/)</br>
Mapa con los cables submarinos que mantienen al mundo conectado a Internet.
