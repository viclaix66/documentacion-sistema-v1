# Guia de Despliegue e Instalación del Sistena

## 1. Requisitos Previos del Servidor
Para poner en marcha la aplicacion e-commerce, se requiere disponer del siguiente entorno:
* ** Servidor Web :** Node.js v18.x o superior.
" ** Base de Datos :** PostgreSQL v15.0.
* ** Memoria RAM Minima :** 2 GB RAM / 2 Cores CPU.
· ** Sistema Operativo :** Ubuntu Server 22.04 LTS (Recomendado).

## 2. Procedimiento de Instalacion Tecnicamente Despachado

### Paso 2.1: Obtencion del Código Fuente
El administrador del sistema debe clonar el repositorio remoto oficial desde la plataforma GitHub hacia
el servidor de destino y navegar a la carpeta raíz del proyecto.

### Paso 2.2: Instalacion de Dependencias del Proyecto
Se deben instalar los paquetes y dependencias requeridas mediante el gestor de paquetes del entorno Node.
js, ejecutando la descarga automatica descrita en el archivo de configuración.

### Paso 2.3: Configuracion de Variables de Entorno
Crea un archivo llamado [.envi en la raiz del proyecto tomando como base el archivo
definiendo los parametros de conexión:
. Puerto de red del servicio (|PORT"])
* Direccion de host de la base de datos (|DB_HOST'|)
Puerto de base de datos (|DB_PORT"])
* Usuario y clave de acceso a la base de datos (DB_USER

### Paso 2.4: Puesta en Marcha del Servicio
Iniciar el servicio web en modo de desarrollo o produccion verificando en la consola que los puertos de
enlace esten abiertos y escuchando peticiones

.env.example

DB PASS