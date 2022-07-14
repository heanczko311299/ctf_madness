# Internal

## Recon
### Hostname:

  internal.thm

### Puertos y servicios:

| Puerto | Servicio | Version |
| -------| ---------| ---------|
| 0  | http | Apache x.x  |
| 1  | smb  | x.x.x |

### Detalle de los servicios:

1. Servicio 1:
      - Detalle:
      **VULNERABLE**

2. Servicio 2:
      - Detalle:
      NO VULNERABLE


## Exploit
### Detalle de la exploitacion:

1. Exploit1:
      - Detalle:


## PrivEsc
### Detalle de PrivEsc:

1. PrivEsc1:
      - Detalle:

## Proof & Flags
### Usuarios

| Users | Passwords |
| ------| --------- |
| 0  | xxxxxxxx |
| 1  | xxxxxxxx |

### Flags

| # | Flags |
| --| ----- |
| user.txt | xxxxxxxx |
| root.txt  | xxxxxxxx |




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



Evidencia de credenciales, flags, datos confidenciales, etc:

[80][http-post-form] host: internal.thm   login: admin   password: my2boys

aubreanna:bubb13guM!@#123
