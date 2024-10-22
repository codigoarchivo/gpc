# gpc
#### Gestor de Proyectos de Construcción
**¡Sígueme en github semanalmente! Voy subiendo avances y aplicando las mejores prácticas.**
### Objetivo General
Desarrollar un gestor de proyectos de construcción que permita gestionar múltiples proyectos con cronogramas detallados, inventario de materiales, asignaciones de tareas y generación de reportes de progreso.
#### Pasos a Seguir
1. Instalación de Dependencias
  - Instala Django, Django Rest Framework y Djoser:
 ```
  pip install django djangorestframework djoser
 ```
2. Configuración Inicial de Django
  - Añade 'rest_framework' y 'djoser' a INSTALLED_APPS en settings.py.
  - Configura las URLs de Djoser en urls.py
3. Configuración de Django Rest Framework
  - Configura la autenticación en settings.py usando rest_framework_simplejwt.
4. Configuración de Djoser
  - Personaliza la configuración de Djoser en settings.py para manejar el registro, activación de cuentas, y recuperación de contraseñas.
5. Migraciones de Base de Datos
  - Ejecuta las migraciones de base de datos:
```
  python manage.py makemigrations
  python manage.py migrate
```
6. Implementación de Funcionalidades CRUD
  - Implementa funcionalidades CRUD para gestionar proyectos, tareas y materiales:
       - Crear Proyecto: Función para crear proyectos en la base de datos.
       - Crear Tarea: Función para agregar tareas a los proyectos.
       - Crear Material: Función para gestionar los materiales de construcción.
7. Seguimiento de Proyectos
  - Implementa funciones para obtener el progreso de los proyectos y registrar el historial de peticiones con acciones específicas.
8. Generación de Repor
  - Desarrolla funciones para generar reportes de progreso detallados para los proyectos.tes
## Bonus: Mejoras Futuras
  - Podrías agregar una interfaz de usuario utilizando Django Templates, React
  - Integrar notificaciones por email para alertar a los usuarios sobre próximos eventos y tareas pendientes.

  
