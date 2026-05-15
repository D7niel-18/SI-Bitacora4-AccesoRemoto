Alumno: Daniel Jiménez Ramírez  
Grupo: 1º Desarrollo de Aplicaciones Web  
Profesor: Willman Acosta  
Título actividad:  Sprint 1: El Marco Legal y la Estructura del "Relato"  
Fecha: 15/05/2026

   
ÍNDICE

[**Tarea 1: El Escudo Legal**](#tarea-1:-el-escudo-legal)

[**Tarea 2: La Memoria Técnica**](#tarea-2:-la-memoria-técnica)

[**Tarea 3: Análisis de Necesidades**](#tarea-3:-análisis-de-necesidades)

[1\. Análisis de Necesidades](#1.-análisis-de-necesidades)

[¿Qué problema de la empresa resolvemos con Guacamole y Docker?](#¿qué-problema-de-la-empresa-resolvemos-con-guacamole-y-docker?)

[¿Por qué elegimos esta solución y no conectar directamente por RDP a cada máquina?](#¿por-qué-elegimos-esta-solución-y-no-conectar-directamente-por-rdp-a-cada-máquina?)

[**Referencias IEEE**](#referencias-ieee)

# Tarea 1: El Escudo Legal {#tarea-1:-el-escudo-legal}

He subido al github un archivo [LICENSES.md](http://LICENSES.md) donde esta incluida toda la información de las licencias.

# Tarea 2: La Memoria Técnica {#tarea-2:-la-memoria-técnica}

Documento subido correctamente dentro de la carpeta docs

# Tarea 3: Análisis de Necesidades  {#tarea-3:-análisis-de-necesidades}

## **1\. Análisis de Necesidades** {#1.-análisis-de-necesidades}

### **¿Qué problema de la empresa resolvemos con Guacamole y Docker?**  {#¿qué-problema-de-la-empresa-resolvemos-con-guacamole-y-docker?}

Con docker podemos montar máquinas completamente portables (resolvemos el problema de que no funciona cuando te la llevas al otro lado), son más ligeras hasta un 80% más que máquinas virtuales normales, y menor consumo de recursos. También es un entorno completamente aislado por lo tanto es muy seguro.

Con docker podemos resolver muchísimos problemas:

* Uso de menores recursos  
* Menor consumo  
* Problemas de compatibilidad  
* Mayor seguridad

Guacamole es una solución de código abierto que te permite poder acceder a otros equipos directamente desde el navegador, no necesitas instalar ningún tipo de software cliente esto hace que sea una gran ventaja contra otras aplicaciones como AnyDesk. Con Guacamole podemos administrar varias sesiones remotas a la vez usando servicios como RDP (Escritorio remoto de windows), VNC(Normalmente usado en linux con interfaz), SSH (Se usa en windows, linux y servidores) 

Con Guacamole tenemos muchas ventajas:

* Acceso universal: Podemos acceder desde cualquier dispositivo que tenga un navegador  
* Multiplataforma: Puedes conectarte a cualquier sistema que tenga RDP, VNC o SSH  
* Escalabilidad: Puedes gestionar varias conexiones a la vez  
* Seguridad: Usa HTTPS.

### **¿Por qué elegimos esta solución y no conectar directamente por RDP a cada máquina?** {#¿por-qué-elegimos-esta-solución-y-no-conectar-directamente-por-rdp-a-cada-máquina?}

Con Guacamole si nos permite tener más de una sesión remota, nos aporta mayor seguridad y también nos permite gestionar quién puede acceder y quien no.

# **Referencias IEEE** {#referencias-ieee}

*https://www.arsys.es/blog/docker-ventajas-contenedores*. (s.f.).  
*https://www.hostingtg.com/blog/apache-guacamole/*. (s.f.).  
