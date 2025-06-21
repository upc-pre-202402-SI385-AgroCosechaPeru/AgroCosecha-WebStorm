### 5.2.2. Sprint 3

#### 5.2.2.1. Sprint Planning 3

| **Sprint #**                        | 3                                                                                              |
|-----------------------------------|------------------------------------------------------------------------------------------------|
| **Date**                           | 20/06/2025                                                                                   |
| **Time**                           | 13:30 PM                                                                                       |
| **Location**                       | Zoom Meetings                                                                                  |
| **Prepared By**                    | Jhon Huamani                                                                                  |
| **Attendees (to planning meeting)**|Jhon Huamani, Melina Santillan|

**Introducción:**

El equipo se reunió para planificar el Sprint 3 del proyecto, cuyo enfoque principal es la implementacion del backend y actualizaciones en el frontend.

**Sum of Story Points:**  
El equipo ha asignado un total de **X puntos** distribuidos en **X User Stories**.

#### 5.2.2.2. Sprint Backlog 3

**Objetivo del Sprint**
Implementar el módulo de creación y consulta de distancias entre rutas, permitiendo registrar rutas con origen, destino y distancia, y consultarlas por distintos criterios utilizando el patrón CQRS.


| **Sprint #** | **Sprint 3** |
|--------------|--------------|

| **User Story** | **Work-Item / Task** |
|--------------|--------------|

| **ID** | **Title**                               | **Id**  | **Title**                                        | **Description**                                                                 | **Estimation (Hours)** | **Assigned To**     | **Status**    |
|--------|-----------------------------------------|---------|--------------------------------------------------|----------------------------------------------------------------------------------|------------------------|----------------------|---------------|
| 4      | Backend – Distancias de Rutas           | T004    | Crear entidad y configuración EF                | Definir la clase `RouteDistance` y mapearla con EF Core en `OnModelCreating`.    | 3                      | Melina Santillan          | Done          |
| 5      | Backend – Distancias de Rutas           | T005    | Implementar comandos y servicios (CQRS – Write) | Crear `CreateRouteDistanceCommand`, `IRouteDistanceCommandService` y su servicio.| 4                      | Jhon Huamani         | Done          |
| 6      | Backend – Distancias de Rutas           | T006    | Implementar queries y servicios (CQRS – Read)   | Crear queries para búsqueda por ID, API key y puntos; definir `IRouteDistanceQueryService`. | 4              | Jhon Huamani         | In Progress    |
| 7      | Backend – Distancias de Rutas           | T007    | Implementar repositorio                         | Definir `RouteDistanceRepository` con métodos de acceso a datos.                 | 3                      | Melina Santillan         | Done          |



#### 5.2.X.3. Development Evidence for Sprint Review
En esta seccion se busca detallar el proceso por la cual se trabajo el Sprint 3 indicando el repositorio en la cual se trabajo las ramas que se usaron dentro de dicho repositorio, el id con su mensaje y la fecha en la que se realizo de esta manera tener un registro del avance de los task planteados.

| Repository          | Branch            | Commit Id | Commit Message           | Commit Message Body            | Committed on (Date) |
|---------------------|-------------------|-----------|--------------------------|--------------------------------|---------------------|
| https://github.com/AplicacionesWebGrupo1/CicloVia-Backend  |  | 5d9df57242224132e812e6d1df04444a1f      |       | -- | 20/05/2025  |
| https://github.com/AplicacionesWebGrupo1/CicloVia-Backend  |  | 5d9df57242224132e812eac9ff04444a1f      |       | -- | 20/05/2025  |
| https://github.com/AplicacionesWebGrupo1/CicloVia-Backend  |  | 5d9df57242224136d1d08ac9ff04444a1f      |       | -- | 20/05/2025  |
| https://github.com/AplicacionesWebGrupo1/CicloVia-Backend  |  | 5d9df57242224132e812e6d1d08a444a1f      |       | -- | 20/05/2025  |
| https://github.com/AplicacionesWebGrupo1/CicloVia-Backend  |  | 5d9df57242224132e812e6d1d08ac44a1f      |       | -- | 20/05/2025  |
| https://github.com/AplicacionesWebGrupo1/CicloVia-Backend  |  | 5d9df57242224132e812e6d1ff04444a1f      |       | -- | 20/05/2025  |


#### 5.2.1.4. Testing Suite Evidence for Sprint Review


#### 5.2.1.5. Execution Evidence for Sprint Review

En este Sprint, se logro desarrollar el frontend web application del proyecto, el cual cuenta con el proposito de ser un
producto facil de utilizar por nuestros usuarios.


#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Se trabajo netamente en el Front End de la aplicación. 

#### 5.2.1.7. Software Deployment Evidence for Sprint Review


#### 5.2.X.8. Team Collaboration Insights during Sprint
Durante este Sprint, el equipo ha colaborado activamente en la implementación del módulo backend para gestión de distancias entre rutas, aplicando principios de Domain-Driven Design (DDD). Se estructuraron claramente los componentes de dominio, comandos, consultas, servicios y repositorios, lo que permitió una separación de responsabilidades limpia y escalable.

A continuación, se presentan capturas de los informes de colaboración en GitHub, donde se puede observar la participación de cada integrante en cuanto a commits y contribuciones.


### 6. Conclusiones

#### TB1:

1. Este proyecto nos enseña a estructurar de manera clara y organizada un proyecto para trabajos futuros.

2. A partir del análisis del contexto, detectamos que la falta de rutas seguras, infraestructura adecuada y una comunidad conectada limita significativamente la experiencia y seguridad del ciclista. Esta problemática es diaria, constante y afecta a un segmento creciente de la población.

3. Nuestra aplicación busca resolver la planificación de las rutas de los cicilistas asi como los problemas que puedan haber, para poder fomentar un ciclismo seguro en el País.

#### TP1:

1. Aprendimos la importancia de saber las necesidades de los usuarios objetivos al momento de realizar alguna aplicación.

2. El trabajo colaborativo fue esencial para construir una solución. Al integrar diferentes puntos de vista del equipo, logramos una visión más completa del problema y una solución más robusta.

3. Este proyecto nos permitió aplicar conceptos aprendidos en clase a una problemática real.

#### TB2:
1. Se ha estructurado correctamente el bounded context Routes siguiendo principios DDD y CQRS.
   
2. El diseño es extensible y alineado con buenas prácticas de arquitectura limpia.
   
3. se separaron claramente comandos, queries, entidades, servicios y repositorios.
