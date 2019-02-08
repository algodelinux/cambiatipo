cambiatipo
==========

Script para cambiar el tipo de un equipo en el fichero /etc/escuela2.0 y realizar un sinc_puppet y un pkgsync tras cambiarlo    
Para evitar que se realice un sinc_puppet o un pkgsync, cambiamos los valores:

SINCPUPPET=1   
PKGSYNC=1   
   
Por:   
   
SINCPUPPET=0   
PKGSYNC=0   
   
   
Instalación
-----------

La forma más sencilla de instalarlo es ejecutar los siguientes comandos:

   wget --no-check-certificate -O /usr/local/sbin/cambiatipo https://raw.githubusercontent.com/algodelinux/cambiatipo/master/cambiatipo  
   chmod 755 /usr/local/sbin/cambiatipo  
  

Uso
---

* Es posible introducir el tipo de la máquina como parámetro.   
* Si no se introduce el tipo de la máquina como parámetro, se solicita su introdución mediante teclado.   
  

Sintaxis
--------

```bash
cambiatipo [nombre-del-host]
```
   
   
Ejemplos
--------

```bash
# cambiatipo
# cambiatipo siatic
```
   
   
Authors
-------

Esteban M. Navas <algodelinux@gmail.com>   
Fecha creación:      08/07/2016   
Última modificación: 07/02/2019   
