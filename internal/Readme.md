
██╗███╗░░██╗████████╗███████╗██████╗░███╗░░██╗░█████╗░██╗░░░░░
██║████╗░██║╚══██╔══╝██╔════╝██╔══██╗████╗░██║██╔══██╗██║░░░░░
██║██╔██╗██║░░░██║░░░█████╗░░██████╔╝██╔██╗██║███████║██║░░░░░
██║██║╚████║░░░██║░░░██╔══╝░░██╔══██╗██║╚████║██╔══██║██║░░░░░
██║██║░╚███║░░░██║░░░███████╗██║░░██║██║░╚███║██║░░██║███████╗
╚═╝╚═╝░░╚══╝░░░╚═╝░░░╚══════╝╚═╝░░╚═╝╚═╝░░╚══╝╚═╝░░╚═╝╚══════╝


█▀█ █▀▀ █▀▀ █▀█ █▄░█
█▀▄ ██▄ █▄▄ █▄█ █░▀█

Puertos y servicios:

PORT   STATE SERVICE REASON         VERSION
22/tcp open  ssh     syn-ack ttl 61 OpenSSH 7.6p1 Ubuntu 4ubuntu0.3 (Ubuntu Linux; protocol 2.0)
Detalles:

PORT   STATE SERVICE REASON         VERSION
80/tcp open  http    syn-ack ttl 61 Apache httpd 2.4.29 ((Ubuntu))
Detalles:
        index.html    Apache Default
        Directorios:
        200     4KB  http://internal.thm:80/blog/wp-login.php
        200    53KB  http://internal.thm:80/blog/
        200    11KB  http://internal.thm:80/index.html
        200    13KB  http://internal.thm:80/phpmyadmin/doc/html/index.html
        200    10KB  http://internal.thm:80/phpmyadmin/index.php
        200    10KB  http://internal.thm:80/phpmyadmin/
        200     4KB  http://internal.thm:80/wordpress/wp-login.php

    VULNERABLE

    NO VULNERABLE


█░█░█ █▀▀ ▄▀█ █▀█ █▀█ █▄░█
▀▄▀▄▀ ██▄ █▀█ █▀▀ █▄█ █░▀█

Scripts generados para explotar

Ataque diccioanrio a servicios SSH y HTTP
    Localizacion:internal/Weapon/ataque_diccionario.txt

Reverse Shell php:
    Localizacion:internal/Weapon/shell.php



█▀▄ █▀▀ █░░ █ █░█ █▀▀ █▀█ █▄█
█▄▀ ██▄ █▄▄ █ ▀▄▀ ██▄ █▀▄ ░█░

Localizacion de las vulnerabilidades:

Vulnerabilidad1:
Evidencia de Localizacion: EV1

Vulnerabilidad2:
Evidencia de Localizacion: EV2


█▀▀ ▀▄▀ █▀█ █░░ █▀█ █ ▀█▀
██▄ █░█ █▀▀ █▄▄ █▄█ █ ░█░

Evidencia del exploit:

Exploit1:
Evidencia del exploit exitoso: EV1

Esploit2:
Evidencia del exploit exitoso: EV2


█ █▄░█ █▀ ▀█▀ ▄▀█ █░░ █░░ ▄▀█ ▀█▀ █ █▀█ █▄░█
█ █░▀█ ▄█ ░█░ █▀█ █▄▄ █▄▄ █▀█ ░█░ █ █▄█ █░▀█

Evidencia del PrivEsc:

PrivEsc1:
Evidencia de localizacion de PrivEsc1: EV1

ExploitPrivEsc1:
Evidencia del exploit exitoso: EV2



█▀▀ █▀█ █▀▄▀█ █▀▄▀█ ▄▀█ █▄░█ █▀▄   ▄▀█ █▄░█ █▀▄   █▀▀ █▀█ █▄░█ ▀█▀ █▀█ █▀█ █░░
█▄▄ █▄█ █░▀░█ █░▀░█ █▀█ █░▀█ █▄▀   █▀█ █░▀█ █▄▀   █▄▄ █▄█ █░▀█ ░█░ █▀▄ █▄█ █▄▄

Evidencia del Control remoto del equipo:

C&C1:
Evidencia de localizacion de C&C1: EV1

InstalacionC&C1:
Evidencia del C&C1 exitoso: EV2


▄▀█ █▀▀ ▀█▀ █ █▀█ █▄░█ █▀
█▀█ █▄▄ ░█░ █ █▄█ █░▀█ ▄█

Evidencia de credenciales, flags, datos confidenciales, etc:

[80][http-post-form] host: internal.thm   login: admin   password: my2boys

aubreanna:bubb13guM!@#123
