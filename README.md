# Sistema de Parqueos - Móvil
Aplicación móvil correspondiente al proyecto Sistema de Gestión de Parqueos, desarrollada con el objetivo de facilitar la interacción de los usuarios con los servicios ofrecidos por el sistema de parqueo.

## Descripción
El módulo móvil forma parte del Sistema de Gestión de Parqueos y está orientado a permitir que los usuarios accedan de manera sencilla a información relacionada con el uso del parqueo.
La aplicación se integrará con el sistema principal mediante servicios proporcionados por el backend, permitiendo consultar información y recibir notificaciones relacionadas con el ingreso, permanencia y salida de vehículos.


## Funcionalidades previstas
***completar****
## Tecnologías
***completar***
## Arquitectura / estructura del proyecto
app/: contiene las rutas y navegación principal de la aplicación.

app/(auth)/: contiene las pantallas relacionadas con autenticación, como inicio de sesión o registro.

app/(tabs)/: contiene las principales secciones accesibles mediante la navegación de la aplicación.

inicio/: pantalla o módulo principal del usuario.

perfil/: gestión y visualización de información del perfil.

reservas/: funcionalidades relacionadas con la reserva de espacios de parqueo.

tickets/: gestión y visualización de tickets generados por el sistema.

assets/: almacena los recursos estáticos utilizados por la aplicación.

fonts/: fuentes personalizadas.

icons/: iconos.

images/: imágenes y recursos gráficos.

src/: contiene la lógica y elementos reutilizables de la aplicación.

components/: componentes reutilizables.

components/ui/: componentes visuales de interfaz de usuario.

config/: configuración general de la aplicación.

constants/: constantes y valores utilizados en diferentes partes del proyecto.

context/: contextos globales para compartir estados entre componentes.

hooks/: hooks personalizados.

screens/: componentes correspondientes a pantallas de la aplicación.

services/: comunicación con servicios externos y API del backend.

types/: definición de tipos e interfaces.

utils/: funciones auxiliares reutilizables.

## Instalación
Clonar el repositorio:

git clone URL_DEL_REPOSITORIO
Ingresar al directorio del proyecto:

cd SISTEMAPARQUEO-MOVIL
Las instrucciones para instalar dependencias y ejecutar la aplicación serán agregadas una vez definida la tecnología de desarrollo.

## Configuración
En caso de utilizar variables de entorno, se deberá crear un archivo local de configuración utilizando como referencia un archivo:

.env.example
Las credenciales, contraseñas, tokens y claves privadas no deberán ser almacenadas directamente en el repositorio.

## Flujo de trabajo con Git
Para mantener organizado el desarrollo del proyecto se utilizarán ramas.

main
│
└── develop
    │
    ├── feature/nombre-funcionalidad
    ├── feature/nombre-funcionalidad
    └── fix/nombre-error
Ramas principales
main: contiene la versión estable del proyecto.

develop: contiene los cambios que se encuentran en proceso de integración.

feature/*: utilizadas para desarrollar nuevas funcionalidades.

fix/*: utilizadas para solucionar errores.