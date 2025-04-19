<a id="readme-top"></a>

# 🚀 DevOps Capstone Project | IBM Professional Certificate

![Estado de la Construcción](https://github.com/Slider2019/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://shields.io/)<br>
<br>
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![YAML](https://img.shields.io/badge/yaml-%23ffffff.svg?style=for-the-badge&logo=yaml&logoColor=151515)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-black?style=for-the-badge&logo=sonarqube&logoColor=4E9BCD)
![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Coursera](https://img.shields.io/badge/Coursera-%230056D2.svg?style=for-the-badge&logo=Coursera&logoColor=white)
<br>
<br>
<!-- Tabla de contenidos -->
<details close>
  <summary>Tabla de Contenidos</summary>
  <ol>
    <li>
        <a href="#introducción">Introducción</a>
        <ul>
            <li><a href="#escenario">Escenario</a></li>
            <li><a href="#vista-previa">Vista Previa</a></li>
        </ul>
    </li>
    <li>
      <a href="#Información del curso">Información del Curso</a>
    </li>
    <li>
      <a href="#información-acerca-del-proyecto">Información acerca del proyecto</a>
      <ul>
        <li><a href="#general">General</a></li>
        <li><a href="#tech-stack">Tech Stack</a></li>
      </ul>
    </li>
    <li>
      <a href="#lo-que-he-realizado-como-parte-del-proyecto">Lo que he realizado como parte del proyecto</a></li>
      <ul>
        <li><a href="#task-1---creating-and-executing-sprint-plans">Tarea 1 - Creando y ejecutando un plan de Sprint</a></li>
        <li>
          <a href="#task-2---developing-a-restful-service-using-test-driven-development">Tarea 2 - Desarrollar un servicio RESTfull utilizando el desarrollo dirigido por pruebas (TDD)</a>
          <ul>
            <li><a href="#rest-api-guidelines">Pautas API REST</a></li>
            <li><a href="#setting-up-the-development-environment">Configurar el entorno del Proyecto</a></li>
            <li><a href="#implementing-api-endpoint---read-an-account">Implementando Endpoint API: Leer una Cuenta</a></li>
            <li><a href="#implementing-api-endpoint---update-an-account">Implementando Endpoint API: Actualizar una Cuenta</a></li>
            <li><a href="#implementing-api-endpoint---delete-an-account">Implementando Endpoint API: Eliminar una Cuenta</a></li>
            <li><a href="#implementing-api-endpoint---list-all-accounts">Implementando Endpoint API: Listar todas las Cuentas</a></li>
            <li><a href="#improving-total-code-coverage">Mejorando la cobertura total del código</a></li>
            <li><a href="#demonstration-of-the-rest-api">Demostración del API REST</a></li>
          </ul>
        </li>
        <li>
          <a href="#task-3---adding-continuous-integration-and-security-to-the-repository">Tarea 3 - Añadir integración Contínua (CI) y seguridad a un repositorio</a>
          <ul>
            <li><a href="#additional-scenario-and-planning-sprint-2">Escenario adicional y planificación del sprint 2</a></li>
            <li><a href="#implementing-continuous-integration-automation">Implementación de la automatización de la integración continua</a></li>
            <li><a href="#implementing-security-headers-and-cors-policies">Implementación de encabezados de seguridad y políticas CORS</a></li>
          </ul>
        </li>
        <li>
          <a href="#task-4---deploying-the-application-to-kubernetes">Tarea 4 - Implementación de la aplicación en Kubernetes</a>
          <ul>
            <li><a href="#additional-scenario-and-planning-sprint-3">Escenario adicional y planificación del sprint 3</a></li>
            <li><a href="#containerizing-the-microservice-using-docker">Contenerización del microservicio mediante Docker</a></li>
            <li><a href="#deploying-to-kubernetes">Implementación en Kubernetes</a></li>
          </ul>
        </li>
        <li><a href="#task-5---building-an-automated-cd-devops-pipeline">Tarea 5 - Creación de un pipeline de DevOps de CD automatizada</a></li>
      </ul>
    </li>
    <li>
        <a href="#getting-started">Comenzando</a>
        <ul>
            <li><a href="#development-environment">Entorno de Desarrollo</a></li>
            <li>
                <a href="#useful-commands">Comandos útiles</a>
                <ul>
                    <li><a href="#activating-the-python-virtual-environment">Activación del entorno virtual de Python</a></li>
                    <li><a href="#installing-python-dependencies">Instalando dependencias de Python</a></li>
                    <li><a href="#starting-the-postgres-docker-container">Iniciando el contenedor Docker de Postgres</a></li>
                </ul>
            </li>
            <li><a href="#project-folder-layout">Diseño de la carpeta del proyecto</a></li>
            <li><a href="#data-model---account">Modelo de datos - Cuenta</a></li>
            <li><a href="#local-kubernetes-development">Desarrollo local de Kubernetes</a></li>
        </ul>
    </li>
    <li><a href="#contact">Contacto</a></li>
  </ol>
</details>
<br>


## Introducción
Este proyecto fue desarrollado como parte del curso final de la especialización `IBM DevOps and Software Engineering`. El objetivo fue construir un microservicio RESTful siguiendo principios DevOps.<br>
Se utilizó una plantilla (consulte el repositorio de IBM): https://github.com/ibm-developer-skills-network/aolwx-devops-capstone-template.<br>
¡Muchas gracias al equipo del curso de IBM, así como a John Rofrano (instructor principal) y a todos los demás colaboradores!<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Escenario
```
El gerente de cuentas de cliente de tu empresa te ha solicitado desarrollar un microservicio de cuentas
para llevar un registro de los clientes en tu sitio web de comercio electrónico. Dado que es un microservicio,
se espera que tenga una API REST bien definida que otros microservicios puedan invocar. Inicialmente,
este servicio necesita poder crear, leer, actualizar, eliminar y listar clientes.

También te han informado que otra persona ya ha comenzado con esta tarea. Ya han desarrollado el modelo
de base de datos y una API REST basada en Python Flask con un endpoint para crear una cuenta de cliente.

Tareas pendientes:

Crear y ejecutar planes de sprint
Desarrollar un servicio RESTful utilizando Desarrollo Guiado por Pruebas (TDD)
Añadir Integración Continua (CI) y Seguridad al Repositorio
Desplegar la aplicación en Kubernetes
Construir un pipeline de CD DevOps automatizado
```
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Vista Previa
Imágenes de vista previa del proyecto:<br>

![planning-kanban-done](https://github.com/user-attachments/assets/45f04eec-9f5b-4e5e-860d-01c25548fc37)
![rest-create-done](https://github.com/user-attachments/assets/3257e114-c0a0-4784-acf4-3ed0bffbf973)
![rest-setupcfg-done](https://github.com/user-attachments/assets/1cecd608-bae1-4874-8a6d-0c29152fe21e)
![security-headers-done](https://github.com/user-attachments/assets/cd419f10-690b-440c-9e32-2c1c781904ab)
![kube-images](https://github.com/user-attachments/assets/d50462af-5e4f-417b-a280-dc03c1f437ae)




<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>



## Course Information
Título: DevOps & Software Engineering<br>
Tipo: Proyecto Final<br>
Proveedor del Curso: IBM a través de Coursera<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>



## Información Acerca del Proyecto
### General
- Cliente: Yo mismo
- Objetivo del proyecto: Demostrar los conocimientos adquiridos en el programa de IBM `DevOps e Ingeniería de Software` mediante un proyecto final.
- Número de participantes: 1 (Repositorio clonado de IBM. El resto lo desarrollé por mi cuenta).
- Periodo: Marzo - Abril del 2025
- Industria/Área: DevOps, Ingeniería de Software
- Rol: Desarrollador
- Idiomas: Español e Inglés

Resultado: Creación exitosa de un microservicio de cuenta. Demostración de habilidades y adquisición de nuevos conocimientos.
<br>

### Tech Stack
Con respecto a mi rol:<br>

- GitHub (Control de Versiones, Tablero Kanban, Actions, ...)
- IBM Cloud IDE (basado en Theia y Contenedor)
- Lenguaje de Programación: Python
- Framework Web de Python: Flask
- Framework de Pruebas Unitarias de Python: nose
- Linting de Python: Flake8
- Contenerización: Docker
- Orquestación de Contenedores: Kubernetes / OpenShift
- Registro de Imágenes: IBM Cloud Container Registry
- Herramienta de CI/CD: Tekton
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>



## Lo que he realizado como parte del Proyecto
### Tarea 1 - Creando y ejecutando los planes de Sprint
El microservicio RESTful se crea con la ayuda de un plan ágil (Scrum).<br>
Esto significa que la primera tarea es el Sprint 0.<br>
<br>
El objetivo principal del Sprint 0 es preparar al equipo para futuras entregas mediante la creación del esqueleto básico del proyecto, la definición de la visión y la preparación del backlog del producto.<br>
<br>
Primero, se creó una plantilla de historia de usuario (se puede encontrar en: `.github/ISSUE_TEMPLATE`):<br>


![planning-storytemplate-done](https://github.com/user-attachments/assets/4fd1e2ac-8c00-4cbe-a624-a651a7d36c84)


La plantilla proporciona la base para las historias de usuario que se crearán para los sprints.<br>
Utiliza la sintaxis Gherkin.<br>
Gherkin es un lenguaje de descripción simple con muy pocas reglas para la formulación estructurada de escenarios en el contexto del desarrollo de software guiado por el comportamiento, según los principios de BDD.<br>
<br>
A continuación, se crearon las historias de usuario.<br>
Los títulos fueron proporcionados por IBM como parte del proyecto (por ejemplo: `Actualizar una cuenta en el servicio`) y yo los completé con contenido.<br>
Dos ejemplos (Nota: las capturas de pantalla fueron tomadas más tarde, por lo tanto, ya están etiquetadas y asignadas a un proyecto):<br>


![Issue Update an account in the service](https://github.com/user-attachments/assets/79730f04-09d3-4583-8870-bb012c041e3e)

![Issue Containerize microservice using docker](https://github.com/user-attachments/assets/64bb614c-ce2c-4d8b-b59a-68a98afb8c93)


Los criterios de aceptación definen el estado de `Hecho`.<br>
<br>
Después de completar las historias de usuario, se creó un proyecto en GitHub (tablero Kanban).<br>
Todos los issues se asignaron a la columna `New Issues`:<br>

![planning-userstories-done](https://github.com/user-attachments/assets/90dbe160-e1d6-49ff-90a9-0b01390c58e5)

Luego, los issues se movieron al icebox o al product backlog, dependiendo de su prioridad.<br>
Por ejemplo, la implementación (deploying) es uno de los últimos pasos, por lo que terminó en el icebox.<br>
<br>
También se definieron las prioridades de los issues en el backlog.<br>
P0 es la prioridad más alta y, por lo tanto, se lista en la parte superior.<br>
P2 es la prioridad más baja y, por lo tanto, se lista en la parte inferior.<br>

![planning-labels-done](https://github.com/user-attachments/assets/014600aa-01dd-4d14-8cc1-39bac4a684ed)


Al final, también se asignó lo siguiente a los issues:
- Un campo de iteración `Sprint`, que tiene una duración de 1 semana. En este punto, la fecha es 14/12/2024. Esto significa que el primer sprint comienza el 14/12/2024 y termina el 20/12/2024.
- También se determinaron el tamaño y los puntos de historia estimados. La escala (proporcionada por IBM) es 3, 5, 8, 13 = S, M, L, XL.

Los issues se movieron del product backlog al sprint backlog, y el resultado es el siguiente:<br>

![planning-kanban-done](https://github.com/user-attachments/assets/ea2c30ac-3afb-4197-8316-7e027c86c603)

La tarea 1 está terminada. La tarea 2 puede comenzar.<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>



### Tarea 2 - Desarrollar un servicio RESTfull utilizando el desarrollo dirigido por pruebas (TDD)
En esta tarea, la API REST se amplía para incluir endpoints adicionales.<br>  
En este proyecto se utiliza el Desarrollo Guiado por Pruebas (TDD, por sus siglas en inglés).<br>  
Esto significa que las pruebas siempre se escriben primero y luego el código real que debe cumplirlas.<br>  
Se aplica la siguiente regla: la cobertura de código debe ser al menos del 95 %. <br>  
<br>  
Primero, una visión general de las directrices de la API.<br>  
El desarrollo se basa en ellas.<br>  
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Pautas API REST
Las pautas API REST fueron entregadadas por IBM:<br>

![1 REST API Guidelines](https://github.com/user-attachments/assets/f249989a-8b4e-471d-9182-8f87adcf5319)

<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Configurar el entorno del Proyecto
Falta algo en la configuración del entorno de desarrollo: configurar el comando `nosetests` con opciones adicionales.<br>  
Esto nos ahorrará trabajo de escritura al ejecutar pruebas unitarias en el futuro.<br>  
<br>  
El archivo `setup.cfg` modificado:<br>  

![2 configuración del entorno de desarrollo con nosetests](https://github.com/user-attachments/assets/2587d53b-6283-463f-acec-094a47f74304)  

Esto completa la historia de usuario para la configuración del entorno de desarrollo y se actualiza el tablero Kanban:<br>  

![rest-techdebt-done](https://github.com/user-attachments/assets/7d82da29-bc5b-4e96-a58f-26988e0e0330)

Al mismo tiempo, se definió la siguiente historia de usuario: Leer una cuenta desde el servicio (ver columna `In Progress`).<br>  
![list-accounts](https://github.com/user-attachments/assets/78220090-8228-49c9-973c-f9bfa194305b)


<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Implementando Endpoint API: Leer una Cuenta
Siguiendo el enfoque TDD, primero se definieron los casos de prueba que debían cumplirse:<br>

![7 part 1 implement test for update an account](https://github.com/user-attachments/assets/a7197e1a-b82e-492f-a8bb-7b8f3a08e838)

![7 part 2 implement test for update an account](https://github.com/user-attachments/assets/4aff4c7a-fc18-464f-a98a-20f77199df76)

Luego se escribió el código para cumplir con las pruebas.<br>
La cobertura del código es superior al 95%.<br>
Esto significa que todo encaja.<br>

![8 implement update an account function](https://github.com/user-attachments/assets/64b422a2-c5e6-423f-973e-614daadc71e3)

Al mismo tiempo, se definió la siguiente historia de usuario: Eliminar una cuenta desde el servicio (ver columna `In Progress`):<br>
![update-accounts](https://github.com/user-attachments/assets/6bfe93fa-73cc-4961-b4b3-d1fe13df1b73)

<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Implementando Endpoint API: Actualizar una Cuenta
Siguiendo el enfoque TDD, primero se definieron los casos de prueba que debían cumplirse:<br>

![7 part 1 implement test for update an account](https://github.com/user-attachments/assets/a7197e1a-b82e-492f-a8bb-7b8f3a08e838)

![7 part 2 implement test for update an account](https://github.com/user-attachments/assets/4aff4c7a-fc18-464f-a98a-20f77199df76)

Luego se escribió el código para cumplir con las pruebas.<br>
La cobertura del código es superior al 95%.<br>
Esto significa que todo encaja.<br>

![8 implement update an account function](https://github.com/user-attachments/assets/64b422a2-c5e6-423f-973e-614daadc71e3)

Al mismo tiempo, se definió la siguiente historia de usuario: Eliminar una cuenta desde el servicio (ver columna `In Progress`):<br>

![update-accounts](https://github.com/user-attachments/assets/a3734146-ed9e-4364-a4b9-dbad2e453fd1)


<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Implementando Endpoint API: Eliminar una Cuenta
Siguiendo el enfoque TDD, primero se definieron los casos de prueba que debían cumplirse:<br>

![10 implement test for delete an account](https://github.com/user-attachments/assets/b42db249-da20-481d-b4bd-d44c04c12062)

Luego se escribió el código para cumplir con las pruebas.<br>
La cobertura del código es superior al 95%.<br>
Esto significa que todo encaja.<br>

![11 implement delete an account](https://github.com/user-attachments/assets/1f3cb5e7-bfb5-4093-88ca-ef689a4d0978)

Al mismo tiempo, se definió la siguiente historia de usuario: Listar todas las cuentas desde el servicio (ver columna `In Progress`):<br>

![list-accounts](https://github.com/user-attachments/assets/80a7e6a6-bd89-4d04-87b8-c77efe08b98d)

<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Implementando Endpoint API: Listar todas las Cuentas
Siguiendo el enfoque TDD, primero se definieron los casos de prueba que debían cumplirse:<br>

![13 implement test for list all accounts](https://github.com/user-attachments/assets/95e8eb2e-42d1-4605-a0a0-d6b552812ed9)

Luego se escribió el código para cumplir con las pruebas.<br>
La cobertura del código es superior al 95%.<br>
Esto significa que todo encaja.<br>

![14 implement list all accounts](https://github.com/user-attachments/assets/998d8047-63cc-44bc-a940-4a95b80cb22b)

El tablero Kanban se ha actualizado:<br>

![delete-accounts](https://github.com/user-attachments/assets/88221e46-9780-49d0-b2e3-d493213129de)


Como tarea adicional, se está mejorando la cobertura total del código.<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Mejorando la cobertura total del código
La cobertura total del código actualmente está por debajo del 95 %.<br>
Hay mucho potencial de mejora en algunas áreas (por ejemplo, el archivo `error_handlers.py`):<br>

![16 improve code coverage error handlers potencial](https://github.com/user-attachments/assets/a53dd76a-02b1-42f5-9fe8-969ec653103e)

Se creó un nuevo archivo de prueba para probar los controladores de errores: `tests/test_error_handlers.py`.<br>
Se configuró la suite de pruebas para los controladores de errores (configuración y limpieza) y se escribieron las pruebas unitarias:<br>

![17 create error handler py and implement unit tests](https://github.com/user-attachments/assets/8b2dfc10-1e93-4b2c-879a-3200876e2f94)

El objetivo se logró: La cobertura total del código ahora está por encima del 95 %.<br>

![18 total code coverage above 95 percent](https://github.com/user-attachments/assets/b8a1945c-753e-46c4-8106-14d839ced6c0)

Ahora viene el último paso de la tarea: Demostrar la API REST.<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>

### Demostración del API REST
Primero, se habilita el acceso local al servicio.<br>
Se usa el siguiente comando para refrescar la base de datos:<br>

```
flask db-create
```

Luego, se utiliza el siguiente comando para iniciar el servicio con la nueva base de datos:<br>

```
make run
```

La salida del terminal:<br>

![19 start service with new database terminal](https://github.com/user-attachments/assets/cc025051-cdad-4842-9eba-7cab41f66309)

La aplicación se inicia usando la función `Launch Application` en el IDE de IBM Cloud.<br>
También se requiere un número de puerto para iniciar la aplicación.<br>

![19 5 launch application in ide](https://github.com/user-attachments/assets/79199f9e-5c85-46dc-8160-46f615fb96fb)

Según el terminal, la aplicación escucha en el puerto 5000, por lo que se ingresa/requiere el puerto 5000.<br>
La salida:<br>

![asd1](https://github.com/user-attachments/assets/9b52fbac-51cd-46dd-b4f5-49c77dfcc928)


El servicio está ahora en funcionamiento.<br>
Se usa el comando `curl` para realizar llamadas REST a los endpoints implementados.<br>
<br>
La demostración del endpoint `Create an Account` utilizando el siguiente comando:<br>

```
curl -i -X POST http://127.0.0.1:5000/accounts \
-H "Content-Type: application/json" \
-d '{"name":"John Doe","email":"john@doe.com","address":"123 Main St.","phone_number":"555-1212"}'
```

![21 demo create an account terminal](https://github.com/user-attachments/assets/321f47f8-2856-45cf-9c82-33d229f53998)

La demostración del endpoint `List all Accounts` utilizando el siguiente comando:<br>

```
curl -i -X GET http://127.0.0.1:5000/accounts
```

![22 demo list all accounts terminal](https://github.com/user-attachments/assets/f82ccc3a-f4ee-4a3a-ae41-b8d7f8e91bf5)

La demostración del endpoint `Read an Account` utilizando el siguiente comando:<br>

```
curl -i -X GET http://127.0.0.1:5000/accounts/1
```

![23 demo read an account terminal](https://github.com/user-attachments/assets/164e5ba8-9f67-4cee-b026-90a6f0dc817c)

La demostración del endpoint `Update an Account` utilizando el siguiente comando:<br>

```
curl -i -X PUT http://127.0.0.1:5000/accounts/1 \
-H "Content-Type: application/json" \
-d '{"name":"John Doe","email":"john@doe.com","address":"123 Main St.","phone_number":"555-1111"}'
```

![24 demo update an account terminal](https://github.com/user-attachments/assets/4e50c627-2395-4a99-93c5-b4b319dbf5bb)

La diferencia: El número de teléfono ahora termina con un `1` en lugar de un `2` (`555-1112` -> `555-1111`).<br>
<br>
La demostración del endpoint `Delete an Account` utilizando el siguiente comando:<br>

```
curl -i -X DELETE http://127.0.0.1:5000/accounts/1
```

![25 demo delete an account terminal](https://github.com/user-attachments/assets/04f3b818-42a1-47cb-8315-2ffdf6d36aea)

Después de la eliminación, se mostraron todas las cuentas para demostrar que la cuenta realmente fue eliminada.<br>
La lista está vacía, por lo que la cuenta ha sido eliminada.<br>
<br>
La API REST ha sido completada, Sprint 1 ha finalizado y ahora se puede iniciar la siguiente tarea: Tarea 3 - Agregar Integración Continua y Seguridad al Repositorio.<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>

### Tarea 3 - Añadir integración Contínua (CI) y seguridad a un repositorio
### Escenario adicional y planificación del sprint 2
En la Tarea 3, se agregó un nuevo escenario (definido por IBM):<br>

```
La gerencia ha estado buscando formas de aumentar la productividad de los desarrolladores
y ha notado que los desarrolladores pasan mucho tiempo verificando
que todas las pruebas pasen antes de aprobar cada solicitud de extracción.
La gerencia ha decidido que es hora de automatizar esta tarea
implementando integración continua (CI) mediante GitHub Actions.

También ha habido muchas noticias sobre violaciones de seguridad
y exploits, y la gerencia está preocupada por la seguridad de su microservicio.
Como medida proactiva, han decidido que debe
agregar medidas de seguridad defensivas a su microservicio en forma de cabeceras de seguridad
y políticas de intercambio de recursos de origen cruzado (CORS).
```

Se crearon dos nuevas historias de usuario para cumplir con los requisitos.<br>
Esta vez, fueron especificadas por IBM.<br>
Dado que el Sprint 1 ha terminado, el Sprint 2 también está planeado. Las nuevas historias de usuario se agregan aquí.<br>
<br>
Nota: Y sí... ¡la semana del Sprint 1 en realidad no ha pasado todavía! ;-)<br>
Actualmente estoy de vacaciones del trabajo, así que tengo mucho tiempo. Y quiero terminar el proyecto antes de Navidad (día en que escribo esto: 16/12/2024).<br>
<br>
La primera historia de usuario - Necesidad de la capacidad para automatizar las comprobaciones de integración continua:<br>

![1 Feature CI Checks Issue](https://github.com/user-attachments/assets/e9b6a068-22f2-481a-ba11-abb99f810186)

La segunda historia de usuario - Necesidad de agregar cabeceras de seguridad y políticas CORS:<br>

![sprint2-plan](https://github.com/user-attachments/assets/77abe3f0-98bf-457d-a7ee-8e35eadc8584)

El tablero Kanban actualizado / Plan de Sprint 2:<br>

![asdasd11111](https://github.com/user-attachments/assets/0de88c1e-e3a0-4f34-91d7-97be945457dc)


Estas historias ahora están siendo implementadas.<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Implementación de la automatización de la integración continua
Una práctica clave en DevOps es la **Integración Continua (CI)**, donde los desarrolladores integran continuamente su código en la rama principal mediante solicitudes de extracción frecuentes.<br>
Para facilitar la vida de los desarrolladores, ahora se está implementando una canalización de CI con la ayuda de **GitHub Actions**.<br>
<br>
Asigné la historia de usuario en el tablero Kanban a mí mismo y la moví a la columna `In Progress`:<br>

![asdasd11111](https://github.com/user-attachments/assets/9d54539c-9f53-40c6-9e0f-59c00f31a5fb)


El archivo YAML implementado (`.github/workflows/ci-build.yaml`) para el flujo de trabajo de GitHub Actions:<br>

![5 part 1 implementing ci build yaml](https://github.com/user-attachments/assets/93a920c6-cb85-4862-89c5-7814955c8faa)

![5 part 2 implementing ci build yaml](https://github.com/user-attachments/assets/c6ef03a5-1b1f-4f2b-b935-46a9860d8fcf)

Una vez que el flujo de trabajo ha sido implementado, los resultados son visibles en GitHub bajo la pestaña `Actions`.<br>
Aquí se muestra que la compilación falló porque no completé el análisis de Python con **linting**:<br>

![6 failed build - linting flake8](https://github.com/user-attachments/assets/8b3d7a88-e146-41c1-8757-82b7fcfe36eb)

Parte de la historia de usuario de CI también es la adición de un **badge** en el `README.md`, que muestra el estado de la compilación.<br>
Esto también indica que la compilación ha fallado:<br>

![failedbuild](https://github.com/user-attachments/assets/490fe556-ddf6-45f2-9d60-9ae0b40d8a89)


Después de corregir los problemas de linting, el flujo de trabajo de CI que creé también funciona:<br>

![ci-workflow-done](https://github.com/user-attachments/assets/ec200fac-b0a3-46e8-af43-937da9dbb316)

![ci-badge-done](https://github.com/user-attachments/assets/7e10d324-2041-421b-bd60-777439f16485)


Esto cumple con todos los criterios de aceptación de la historia de usuario de CI y el tablero Kanban puede actualizarse.<br>
La historia de usuario de CI se movió a la columna `Done` y al mismo tiempo, la siguiente historia de usuario (Necesidad de agregar cabeceras de seguridad y políticas CORS) se movió a la columna `In Progress`:<br>

![ci-kanban-done](https://github.com/user-attachments/assets/199ce236-e91d-4a56-acc4-30e4938bc73f)

Es hora de implementar la siguiente historia de usuario.<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Implementación de encabezados de seguridad y políticas CORS
El siguiente paso es aumentar la seguridad del microservicio.<br>
<br>
Primero, se implementan **cabeceras de seguridad** con la ayuda de **Flask Talisman**.<br>
Flask Talisman obliga a los clientes de la API REST a usar el protocolo **HTTPS**.<br>
<br>
Siguiendo el enfoque de **TDD**, primero se definieron los casos de prueba que debían cumplirse:<br>

![11 part 1 implement tests security header](https://github.com/user-attachments/assets/118bf3c4-e873-4ab8-87e9-0837ea84ce75)

![11 part 2 implement tests security header](https://github.com/user-attachments/assets/6486970e-76e3-49c9-b46a-1b65291f62b1)

En cuanto a las opciones/valores de las cabeceras:<br>
Se puede encontrar más información en la documentación de Flask o aquí: https://github.com/GoogleCloudPlatform/flask-talisman<br>
<br>
Para cumplir con los casos de prueba, se instaló la dependencia **Flask Talisman** y se creó una instancia de Talisman después de la instancia de la aplicación Flask.<br>
El resultado es que todas nuestras pruebas anteriores fallan... al menos nuestra nueva prueba de seguridad funciona ;-)<br>

![12 adding Talisman tests failed](https://github.com/user-attachments/assets/e410976c-0a4e-4a76-b2a5-b899e059335d)

La razón de la falla es que **Talisman** obliga el uso de HTTPS, lo cual está bien para el sistema de producción, pero no en las pruebas, ya que aquí se usa HTTP.<br>
Por lo tanto, se desactivó la imposición de HTTPS en los archivos `test_XXXX.py`.<br>
Como resultado, todas nuestras pruebas vuelven a funcionar (¡incluida la prueba de seguridad recién escrita!):<br>

![13 disable https when testing](https://github.com/user-attachments/assets/078a2ce8-56eb-4243-8713-c315abc989e1)

Podemos probar las cabeceras de seguridad con el siguiente comando:<br>

```
curl -I localhost:5000
```

Antes de agregar las cabeceras de seguridad:<br>

![10 output before adding Flask Talisman security headers](https://github.com/user-attachments/assets/56597257-5b1a-4151-8af0-44dc4a973a08)

Después de agregar las cabeceras de seguridad:<br>

![14 output after adding Flask Talisman security headers](https://github.com/user-attachments/assets/c0a2dbd4-75d1-47e9-8c49-356e798ff073)

Las opciones como **X-Frame-Options** o **Content-Security-Policy** están incluidas. Todo funciona como se esperaba.<br>
El código de estado es **302 FOUND** en lugar de **200 OK**, ya que el comando `curl` busca HTTP por defecto, pero encuentra/realiza la redirección a HTTPS (ver `Location` en la cabecera).<br>
<br>
Ahora, la segunda parte de la historia de usuario de seguridad: **Agregar políticas CORS**.<br>
<br>
Siguiendo el enfoque de **TDD**, primero se definieron los casos de prueba que debían cumplirse:<br>

![15 implement tests cors policies header](https://github.com/user-attachments/assets/f7bf6cc8-74c6-4758-9272-6cd6569635b5)

Para cumplir con los casos de prueba, se instaló la dependencia **Flask CORS** y se creó una instancia de CORS después de la instancia de la aplicación Flask.<br>
El resultado: Todas las pruebas fueron exitosas:<br>

![16 implement cors policies tests successful](https://github.com/user-attachments/assets/a1946b7f-a4d8-43aa-915f-0bebb0529db1)

Podemos probar las políticas CORS con el siguiente comando:<br>

```
curl -I localhost:5000
```

La política CORS ahora también se muestra (ver la marca roja):<br>

![17 output after adding Flask CORS](https://github.com/user-attachments/assets/4914d865-5d36-498c-8473-1bfe8a9d2bbe)

La historia de usuario de **Seguridad** en el tablero Kanban se movió a la columna `Done`:<br>

![security-kanban-done](https://github.com/user-attachments/assets/83396b21-de8c-4cf9-b2e7-e619a65289b5)


Esto finaliza el **Sprint 2** y podemos comenzar con la siguiente tarea (**Desplegar la aplicación en Kubernetes**).<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Tarea 4 - Implementación de la aplicación en Kubernetes
### Escenario adicional y planificación del sprint 3
En la Tarea 4, se agregó un nuevo escenario (definido por IBM):<br>

```
La gerencia está muy contenta con los cambios que has realizado.
Ahora es momento de crear un plan de sprint para implementar las dos últimas historias de tu Product Backlog,
que son "Contenerizar tu microservicio usando Docker" y "Desplegar tu imagen de Docker a Kubernetes."

Una cosa más. Hay un nuevo requisito.
Hiciste un excelente trabajo automatizando la pipeline de CI con GitHub Actions, y todos los
desarrolladores parecen mucho más contentos gracias a ello. La gerencia ha decidido que si un poco de automatización
es bueno, entonces más automatización sería mejor. Les gustaría que automatices el despliegue
a Kubernetes usando Tekton una vez que hayas descubierto cómo hacerlo manualmente.
```

Se creó una nueva historia de usuario para cumplir con los requisitos.<br>
El contenido fue especificado por IBM:<br>

![cdkub8](https://github.com/user-attachments/assets/7fb41a24-d89a-4f3b-8408-4e3297c8fc42)

Como el Sprint 2 ha finalizado, también se ha planeado el Sprint 3. La nueva historia de usuario se agrega aquí.<br>
<br>
El Kanban Board actualizado / Plan de Sprint 3:<br>

![qweqwe11111](https://github.com/user-attachments/assets/5fc27d82-83d4-42c7-8d19-4e9503e1de87)

Estas historias ahora están siendo implementadas.<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Contenerización del microservicio mediante Docker
La historia de usuario `Contenerizar microservicio usando Docker` fue movida a la columna de `En progreso` y asignada a mí.<br>
El tablero de Kanban actualizado:<br>

![docker](https://github.com/user-attachments/assets/3195c1f7-1386-4615-ad2a-2dff5f850b6d)

Se requiere una imagen para crear un contenedor.<br>
Y para crear una imagen, se requiere un Dockerfile.<br>
Por lo tanto, el Dockerfile se implementa primero:<br>

![4 Crear Dockerfile](https://github.com/user-attachments/assets/8d6d52a3-2895-4540-9aaa-962808c45d68)

No habría pensado en ciertos comandos y fueron especificados por IBM.<br>
Estos incluyen el uso de la opción `--no-cache-dir` y las siguientes líneas, por ejemplo:<br>

```
RUN useradd --uid 1000 theia && chown -R theia /app
USER theia
```

Luego, la imagen de Docker se construye y el repositorio se etiqueta como `accounts` con el siguiente comando:<br>

```
docker build -t accounts .
```

Verifique si se ha creado una imagen con el siguiente comando:<br>

```
docker images
```

La salida, que parece correcta:<br>

![5 verificar imágenes docker](https://github.com/user-attachments/assets/17e7adc5-4105-4c6b-8337-7e5511f64c62)

A continuación, se creó un contenedor utilizando la imagen con el siguiente comando:<br>

```
docker run --rm \
    --link postgresql \
    -e DATABASE_URI=postgresql://postgres:postgres@postgresql:5432/postgres \
    -p 8080:8080 \
    accounts
```

Explicación (ver también la documentación de Docker):<br>
- `--rm` = Eliminar el contenedor cuando termine
- `--link postgresql` = Enlace a otro contenedor (para usar la base de datos PostgreSQL)
- `-e DATABASE_URI=postgresql://postgres:postgres@postgresql:5432/postgres` = Variable de entorno
- `-p 8080:8080` = Publicar el puerto del contenedor en el host
- `accounts` = Nombre de la imagen del contenedor

La aplicación se vuelve a iniciar utilizando la función `Launch Application` desde el IBM Cloud IDE.<br>
La salida:<br>

![6 docker run y lanzar aplicación](https://github.com/user-attachments/assets/a2ed57e3-f045-40ce-aad2-2a4a6ff1b0f9)

![ddddddddddddd1](https://github.com/user-attachments/assets/f670a962-c2f7-4968-a558-8ff406ec80be)

Luego, la imagen se etiqueta y se sube al IBM Cloud Registry con el siguiente comando:<br>

```
docker tag accounts us.icr.io/$SN_ICR_NAMESPACE/accounts:1
docker push us.icr.io/$SN_ICR_NAMESPACE/accounts:1
```

`$SN_ICR_NAMESPACE` es una variable de entorno ya predefinida por el IBM Cloud IDE y hace referencia a mi cuenta.<br>

Luego, se verifica el push con el siguiente comando:<br>

```
ibmcloud cr images
```

La salida:<br>

![kube-deploy-accounts](https://github.com/user-attachments/assets/205b709d-4369-4355-9660-efd3e1382c8c)

La imagen está allí, por lo que todo encaja.<br>
<br>
La historia de usuario (`Contenerizar microservicio usando Docker`) está ahora completamente implementada y la siguiente historia de usuario (`Desplegar tu imagen de Docker a Kubernetes`) puede ser abordada.<br>
El tablero de Kanban actualizado:<br>

![234234234234](https://github.com/user-attachments/assets/ef3a2415-71a5-4885-b445-7ad878ab72af)

<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Implementación en Kubernetes
Se deben crear los manifiestos / archivos YAML para la historia de usuario `Desplegar tu imagen Docker en Kubernetes` para que el microservicio se pueda desplegar de manera consistente.<br>
Por el momento, el microservicio se despliega manualmente.<br>
Se desplegará automáticamente en la `Tarea 5 - Construcción de una tubería automatizada de CD DevOps`.<br>
Los manifiestos luego podrán ser reutilizados.<br>
<br>
La base de datos PostgreSQL es necesaria para la aplicación.<br>
OpenShift proporciona varias plantillas para crear servicios.<br>
IBM ya ha predefinido la plantilla (archivo `postgresql-ephemeral-template.json`).<br>
<br>
Los recursos se crean y despliegan utilizando la plantilla con los siguientes comandos:<br>

```
oc create -f postgresql-ephemeral-template.json
oc new-app postgresql-ephemeral
```

Con el comando `oc get all` podemos ver que el servicio Postgres está en ejecución:<br>

![11 create postgres ephemeral and pod is running](https://github.com/user-attachments/assets/aaec18fd-5d16-40c8-a5b1-49f99cef7546)

Ahora se pueden crear los manifiestos / archivos YAML.<br>
IBM proporciona el consejo de que se puede escribir la definición del despliegue en un archivo YAML con la ayuda de las banderas `--dry-run=client` (= asegura que realmente no se cree nada) y `--output=yaml`.<br>
IBM también especifica que se debe usar la imagen creada anteriormente en el IBM Cloud Registry y tres réplicas.<br>
<br>
Encontré más información con el comando `--help`:<br>

![12 oc --help tip from ibm](https://github.com/user-attachments/assets/43aa9fd1-5990-48ec-9f6c-b13327dbb20f)

El comando resultante:<br>

```
oc create deployment accounts \
    --dry-run=client \
    --output=yaml > deploy/deployment.yaml \
    --image=us.icr.io/sn-labs-christians21/accounts:1 \
    --replicas=3
```

La salida / archivo YAML (`deploy/deployment.yaml`):<br>

![13 oc implementing ibm tip](https://github.com/user-attachments/assets/f414e5e4-8aaa-480f-9ebd-510aba17b880)

Después de aplicar el despliegue al clúster:<br>

![14 oc applying deployment yaml](https://github.com/user-attachments/assets/5e4f2a1f-42f8-4569-8946-c295fd64cce0)

Para acceder a la base de datos postgres, según IBM, se necesitan las siguientes variables de entorno:
- DATABASE_HOST
- DATABASE_NAME
- DATABASE_USER
- DATABASE_PASSWORD

También se creó un secreto para Postgres utilizando la plantilla de servicio.<br>
Contiene los nombres de las variables que se insertan en `deployment.yaml` como variables de entorno.<br>
Se utilizó el comando `oc describe secret postgresql` para obtener la información.<br>
El resultado:<br>

![14 oc implementing env vars secret](https://github.com/user-attachments/assets/6f11594a-e847-4e08-8398-7806e247f271)

El archivo `deployment.yaml` se aplicó nuevamente al clúster con el comando `oc create -f deploy/deployment.yaml`.<br>
<br>
Se creó un objeto de servicio para poder usar el servicio desde fuera.<br>
Aquí, la definición también se escribió con un comando en un archivo YAML. El comando:<br>

```
oc expose deploy accounts \
   --dry-run=client \
   --output=yaml > deploy/service.yaml \
   --port=8080 \
   --type=NodePort
```

El resultado:<br>

![15 expose service yaml with dry run](https://github.com/user-attachments/assets/aa0b5547-af33-4111-ad42-49848a2bfe75)

Después de aplicar el archivo `deploy/service.yaml` al clúster:<br>

![16 check service](https://github.com/user-attachments/assets/0e530045-055f-468a-a482-2c7cab603374)

Se creó un objeto de ruta para obtener la URL del servicio utilizando el siguiente comando:<br>

```
oc create route edge accounts --service=accounts
```

El resultado con el comando `oc get routes` (la URL está marcada en rojo):<br>

![kube-deploy-accounts](https://github.com/user-attachments/assets/50fafc84-14ed-4d11-805c-c7640b40d068)

Si ingresas la URL en tu navegador, aparecerá nuestro servicio:<br>

![kube-app-output](https://github.com/user-attachments/assets/39f4e44e-b075-4031-b787-8c66ac37fce9)

Todo funciona.<br>
Esto significa que el despliegue manual con Kubernetes / OpenShift ya está hecho y se puede actualizar el tablero Kanban.<br>
La siguiente historia de usuario se puede implementar.<br>

![ererererererer](https://github.com/user-attachments/assets/39142c7a-a7c5-446a-8b71-211414e9b4af)

<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>



### Tarea 5 - Creación de un pipeline de DevOps de CD automatizada
La vista detallada de la última historia de usuario:<br>

![pipelineCD](https://github.com/user-attachments/assets/f62054a2-1152-473b-921b-6404c621d360)

Aquí hay una visión general de las tareas relacionadas en la pipeline:<br>

![2 overview of pipeline tasks](https://github.com/user-attachments/assets/1f34bde8-2db7-4e45-b9bf-e5ffd5aa8779)

Primero, se configuró un almacenamiento / espacio de trabajo (`PersistentVolumeClaim`, `PVC`) para la pipeline y la propia pipeline con los siguientes comandos:<br>

```
oc create -f tekton/pvc.yaml
oc apply -f tekton/tasks.yaml
oc apply -f tekton/pipeline.yaml
```

Verificación de que todo ha sido creado según lo previsto:<br>

![3 verifying tasks pvc and pipeline](https://github.com/user-attachments/assets/d4151c08-47f8-44b2-a89c-a2ca3d8ce4d9)

Ya se ha implementado parte de la pipeline. Las siguientes tareas:
- init
- clone

Ver también la captura de pantalla de `tekton/pipeline.yaml` a continuación:<br>

![4 initial pipeline tasks](https://github.com/user-attachments/assets/314fa9ed-60b6-46ef-836d-d57e3dd37e74)

La tarea ya está definida en la pipeline: `git-clone`.<br>
Esto no tiene que ser escrito en `tekton/tasks.yaml` ya que ya existe una tarea predefinida en el Tekton Hub.<br>
Esta se instala en el clúster con el siguiente comando:<br>

```
tkn hub install task git-clone
```

Verificación de la instalación de la tarea `git-clone`:<br>

![5 verifying installation git-clone](https://github.com/user-attachments/assets/aa1b9288-727b-4277-82b5-9962b3827919)

Ahora se inicia la pipeline para ver la salida.<br>
Se utiliza el siguiente comando:<br>

```
tkn pipeline start cd-pipeline \
    -p repo-url="https://github.com/Slider2019/devops-capstone-project.git" \
    -p branch="main" \
    -w name=pipeline-workspace,claimName=pipelinerun-pvc \
    -s pipeline \
    --showlog
```

Use la opción `-h` para más información sobre cómo pasar los valores para PVC, etc..<br>
El valor de la rama puede ser cambiado con fines de prueba (por ejemplo, `cd-pipeline` en lugar de `main`).<br>
El resultado: la pipeline tuvo éxito.<br>

![6 starting pipeline and verifying succeeded](https://github.com/user-attachments/assets/1dccdb54-c27b-4c1e-a623-8023fb01ee1e)

La siguiente tarea es `lint` con Flake8.<br>
Esto no tiene que ser escrito en `tekton/tasks.yaml` ya que ya existe una tarea predefinida en el Tekton Hub.<br>
Esta se instala en el clúster con el siguiente comando:<br>

```
tkn hub install task flake8
```

Verificación de la instalación de la tarea `flake8`:<br>

![7 verifying installation flake8 task](https://github.com/user-attachments/assets/4c5629c4-ad65-4fc0-b031-79c119dac26d)

La tarea se integra en `tekton/pipeline.yaml`, se aplica con el comando `oc apply -f tekton/pipeline.yaml` y la pipeline se reinicia con el siguiente comando:

```
tkn pipeline start cd-pipeline \
    -p repo-url="https://github.com/Slider2019/devops-capstone-project.git" \
    -p branch="main" \
    -w name=pipeline-workspace,claimName=pipelinerun-pvc \
    -s pipeline \
    --showlog
```

Los registros:<br>

![8 implementing lint and failed linting](https://github.com/user-attachments/assets/403f7288-7a11-4c45-8cdd-8629fb8b4ae7)

Como se puede ver, la pipeline falló porque no hice el linting correctamente...<br>
Después de arreglar mi problema de linting, la pipeline funciona:<br>

![9 fixing linting and pipeline succeeded](https://github.com/user-attachments/assets/6a19cd4d-45dd-4c9d-afc7-d6907f51192a)

La siguiente tarea es `tests` con nose.<br>
Esta vez no hay una tarea predefinida en el Tekton Hub.<br>
Tenemos que crearla nosotros mismos.<br>
La definición está en `tekton/tasks.yaml`. El código implementado:<br>

![10 implementing task nosetests](https://github.com/user-attachments/assets/87bc60b6-fc38-4ae1-9ec3-9e064e9a9faf)

Luego se añadió la tarea a la pipeline (`tekton/pipeline.yaml`):<br>

![11 implementing pipeline task nosetests](https://github.com/user-attachments/assets/ccb21fc1-fcc6-4fd7-a8eb-5f9b57a30567)

Los dos cambios se añadieron al clúster:<br>

```
oc apply -f tekton/tasks.yaml
oc apply -f tekton/pipeline.yaml
```

Luego, reinicie la pipeline para ver los resultados de la tarea `tests`:<br>

```
tkn pipeline start cd-pipeline \
    -p repo-url="https://github.com/Slider2019/devops-capstone-project.git" \
    -p branch="main" \
    -w name=pipeline-workspace,claimName=pipelinerun-pvc \
    -s pipeline \
    --showlog
```

![12 pipeline succeeded task nosetests](https://github.com/user-attachments/assets/5f9296bd-aab8-45fa-9d63-3eb96ffb53f0)

Todo está bien. Ahora, la siguiente tarea en la pipeline: `build`.<br>
Esto es necesario para construir la imagen.<br>
Hay una tarea para esto en el Tekton Hub: `buildah`.<br>
<br>
No necesita ser instalada por separado ya que ya ha sido instalada como un `ClusterTask`.<br>
Los `ClusterTasks` no solo están disponibles para una pipeline, sino para varias.<br>
<br>
Con el comando `tkn clustertask ls` puedes ver todos los `ClusterTasks` y la tarea `buildah` está listada:<br>

![13 clustertask buildah](https://github.com/user-attachments/assets/75f8330b-5202-4187-ac91-d57037a4094c)

La tarea `build` (con referencia a `buildah`) se integró en la pipeline y los cambios se aplicaron con el comando `oc apply -f tekton/pipeline.yaml`:<br>

![14 part 1 implementing buildah task to pipeline](https://github.com/user-attachments/assets/49666199-b75b-4ef3-a17c-e435e55c62e3)

![14 part 2 implementing buildah task to pipeline](https://github.com/user-attachments/assets/1fd9bc4d-9984-4493-b149-8bdb6d2a6a5e)

Reinicia la pipeline nuevamente, esta vez con un parámetro adicional (`build-image`):<br>

```Bash
tkn pipeline start cd-pipeline \
    -p repo-url="https://github.com/Slider2019/devops-capstone-project.git" \
    -p branch="main" \
    -p build-image="image-registry.openshift-image-registry.svc:5000/$SN_ICR_NAMESPACE/accounts:1" \
    -w name=pipeline-workspace,claimName=pipelinerun-pvc \
    -s pipeline \
    --showlog
```

Todo funciona:<br>

![15 pipeline succeeded task buildah](https://github.com/user-attachments/assets/380ea541-c55e-4db6-9252-c9dd246b32df)

Ahora viene la última tarea: `deploy`.<br>
Hay una tarea para esto en el Tekton Hub: `openshift-client`.<br>
No necesita ser instalada por separado ya que ya ha sido instalada como un `ClusterTask`.<br>
Comando `tkn clustertask ls`:<br>

![16 clustertask openshift-client](https://github.com/user-attachments/assets/cef9e1ea-69b6-464a-b65a-0cfc6634b195)

La tarea `deploy` (con referencia a `openshift-client`) se integró en la pipeline y los cambios se aplicaron con el comando `oc apply -f tekton/pipeline.yaml`:<br>

![17 implementing pipeline task deploy](https://github.com/user-attachments/assets/daa38367-4740-41bb-be95-bc0e507f151a)

![17 part 2 implementing pipeline task deploy](https://github.com/user-attachments/assets/c15c81e6-3769-43d7-b4bb-a6e1bf212914)

Reinicia la pipeline nuevamente:<br>
```Bash
tkn pipeline start cd-pipeline \
    -p repo-url="https://github.com/Slider2019/devops-capstone-project.git" \
    -p branch="main" \
    -p build-image="image-registry.openshift-image-registry.svc:5000/$SN_ICR_NAMESPACE/accounts:1" \
    -w name=pipeline-workspace,claimName=pipelinerun-pvc \
    -s pipeline \
    --showlog
```
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


## Comenzando
### Entorno de Desarrollo
Important: Este proyecto está diseñado para ejecutarse en el IBM Developer Skills Network Cloud IDE con OpenShift.<br>
Ejecute el siguiente comando después de clonar el repositorio (*Nota: NO ejecute este programa como un script bash. Establece variables de entorno y por lo tanto debe ser "sourceado"*):<br>

```bash
source bin/setup.sh
```

Esto instalará Python 3.9, lo hará el predeterminado, modificará el prompt de bash, creará un entorno virtual de Python y lo activará.<br>
Después de "sourcearlo", el prompt debería verse así:<br>


```bash
(venv) theia:project$
```

<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Comandos útiles
Under normal circumstances you should not have to run these commands.<br>
They are performed automatically at setup but may be useful when things go wrong:<br>

#### Activación del entorno virtual de Python
Activate the Python 3.9 environment with:<br>

```bash
source ~/venv/bin/activate
```

#### Instalando dependencias de Python
These dependencies are installed as part of the setup process but should you need to install them again, first make sure that the Python 3.9 virtual environment is activated and then use the `make install` command:<br>

```bash
make install
```

#### Iniciando el contenedor Docker de Postgres
This project uses Postgres running in a Docker container.<br>
If for some reason the service is not available you can start it with:<br>

```bash
make db
```

You can use the `docker ps` command to make sure that postgres is up and running.<br>

<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Dispocisión de Carpeta del Proyecto
El código para el microservicio está contenido en el paquete `service`. Todas las pruebas están en la carpeta `tests`.<br>
El código sigue el patrón **Modelo-Vista-Controlador** con todo el código de la base de datos y la lógica de negocio en el modelo (`models.py`), y toda la ruta RESTful en el controlador (`routes.py`).<br>

```text
├── service         <- microservice package
│   ├── common/     <- common log and error handlers
│   ├── config.py   <- Flask configuration object
│   ├── models.py   <- code for the persistent model
│   └── routes.py   <- code for the REST API routes
├── setup.cfg       <- tools setup config
└── tests                       <- folder for all of the tests
    ├── factories.py            <- test factories
    ├── test_cli_commands.py    <- CLI tests
    ├── test_models.py          <- model unit tests
    └── test_routes.py          <- route unit tests
```

<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Modelo de datos - Cuenta
El modelo de Cuenta contiene los siguientes campos:

| Name | Type | Optional |
|------|------|----------|
| id | Integer| False |
| name | String(64) | False |
| email | String(64) | False |
| address | String(256) | False |
| phone_number | String(32) | True |
| date_joined | Date | False |

<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>
<br>
<br>


### Desarrollo local de Kubernetes
Este repositorio también puede usarse para desarrollo local con Kubernetes.<br>
No se recomienda ejecutar estos comandos en el entorno de Cloud IDE.<br>
El propósito de estos comandos es simular el entorno de Cloud IDE localmente en tu computadora.<br>
<br>
Como mínimo, necesitarás tener instalado [Docker Desktop](https://www.docker.com/products/docker-desktop) en tu computadora.<br>
Para el entorno de desarrollo completo, también necesitarás [Visual Studio Code](https://code.visualstudio.com) con la extensión [Remote Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) del Visual Studio Marketplace.<br>
Todos estos pueden ser instalados manualmente haciendo clic en los enlaces anteriores o puedes usar un gestor de paquetes como **Homebrew** en Mac o **Chocolatey** en Windows.<br>
<br>
Por favor, usa estos comandos únicamente para trabajar de forma independiente en tu propia computadora con el entorno de VSCode Remote Container proporcionado.<br>
<br>
1. Levantar un clúster local de K3D Kubernetes

    ```Bash
    $ make cluster
    ```

2. Instalar Tekton

    ```Bash
    $ make tekton
    ```

3. Instalar los ClusterTasks que tiene el Cloud IDE

    ```bash
    $ make clustertasks
    ```

Ahora puedes realizar el desarrollo de Tekton localmente, tal como en el entorno de laboratorio de Cloud IDE.<br>

<p align="right">(<a href="#readme-top">volver al inicio</a>)</p>
<br>
<br>



## Contacto
Si tienes dudas al respecto no dudes en contactarme: diego_rojas87@hotmail.com<br>
<p align="right">(<a href="#readme-top">Volver al inicio</a>)</p>

