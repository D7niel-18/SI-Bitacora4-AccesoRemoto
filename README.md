# SI-Bitacora4-AccesoRemoto
- Profesor: Willman Acosta
- Actividad: BITACORA IV

## Objetivo  
Con esta práctica he aprendido a:

- Configurar acceso remoto seguro por SSH sin contraseñas
- Acceder a un escritorio remoto mediante RDP o navegador
- 
## Herramientas utilizadas  
- Visual Studio Code  
- Docker
- SSH
- RDP
## Tareas realizadas  

### Tarea 1: Despliegue de la Infraestructura
He creado una carpeta llamada SI_Bitacora4_DanielJimenezRamirez donde he guardado un archivo docker-compose.yml.
He abierto una terminal dentro de esa carpeta y he ejecutado: docker-compose up -d
Y he verificado con docker ps que todo este correcto
<img width="865" height="412" alt="1" src="https://github.com/user-attachments/assets/4ebcba6a-aa43-4a26-a7d1-58739df580b1" />
### 2. Fase de Ejecución
### 2.1. SSH: Forjando la Llave Maestra
He usado SSH en una terminal y me he conectado al contenedor usando el comando ssh danieljim@127.0.0.1 -p2222
Tambien me encontre con un problema que detectaba un ataque ya que el servidor SSH generó claves nuevas, pero mi equipo tiene claves antiguas. Entonces lo solucione usando el comando ssh-keygen -R "[127.0.0.1]:2222" 
y luego volvi a conectarme y no me dio problemas.

<img width="773" height="448" alt="2" src="https://github.com/user-attachments/assets/15375747-3fcf-4820-b9f5-dca1e5d47d81" />

Tambien ejecute un whoami para demostrar que estaba dentro del contenedor
<img width="268" height="104" alt="3" src="https://github.com/user-attachments/assets/f5137b85-52e7-4007-99d1-9f318505e9c3" />
### 2.2. RDP: El Escritorio en tu Navegador
En mi caso mi conexion por RDP me dio problemas y tuve que hacerlo desde el navegador colocando en el navegador http://localhost:3000 y ya veo el escritorio
Cree un archivo de texto llamado PRUEBA_conseguida_danieljim para demostrar que lo he conseguido.
<img width="1919" height="840" alt="4" src="https://github.com/user-attachments/assets/5e917945-d82b-4489-a664-d02b593f762f" />
