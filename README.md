# EDUTRAK

## Plataforma Web de Seguimiento Académico y Acompañamiento Tutorial

**Universidad:** Universidad Tecnológica de Torreón  
**Programa educativo:** Ingeniería en Desarrollo y Gestión de Software  
**Proyecto:** EDUTRAK  
**Asignatura:** Desarrollo Web Profesional  
**Docente:** MCC. Jesús Del Toro Robledo

---

## 1. Descripción general

EDUTRAK es una plataforma web diseñada para centralizar los procesos de seguimiento académico y acompañamiento tutorial de los estudiantes.

El proyecto busca facilitar la administración de información relacionada con asistencia, calificaciones, justificaciones, grupos, horarios e indicadores académicos.

La plataforma contempla controles de acceso por roles, trazabilidad de operaciones y herramientas para apoyar la toma de decisiones del personal académico.

## 2. Objetivo general

Desarrollar una plataforma web de seguimiento académico y acompañamiento tutorial que permita centralizar información escolar, gestionar asistencias y calificaciones, administrar justificaciones y proporcionar indicadores para el seguimiento oportuno de los estudiantes.

### Objetivos específicos

- Centralizar la información académica.
- Facilitar el registro y consulta de asistencias.
- Gestionar calificaciones por unidades académicas.
- Digitalizar las solicitudes de justificación.
- Proporcionar herramientas de seguimiento tutorial.
- Implementar permisos y controles de seguridad.
- Organizar el desarrollo mediante una arquitectura modular y control de versiones.

## 3. Roles del sistema

| Rol | Responsabilidades |
|---|---|
| Administrador | Gestión de usuarios, cuentas y credenciales |
| Director | Administración académica de periodos, grupos, materias y asignaciones |
| Profesor | Registro de asistencia, calificaciones y revisión de justificantes |
| Tutor | Seguimiento de estudiantes, revisión de justificantes e indicadores |
| Alumno | Consulta de información académica y solicitud de justificaciones |

## 4. Arquitectura y tecnologías

EDUTRAK utiliza un **monolito modular con Arquitectura Hexagonal** para organizar los componentes del backend.

Cada módulo se estructura mediante capas de dominio, aplicación, puertos y adaptadores, favoreciendo la separación de responsabilidades y la mantenibilidad.

| Tecnología | Función |
|---|---|
| Angular | Desarrollo de la interfaz web |
| Go | API REST y lógica de negocio |
| PostgreSQL | Base de datos relacional |
| Git | Control de versiones |
| GitHub | Repositorios, Pull Requests y colaboración |
| GitHub Actions | Integración continua y verificaciones automatizadas |
| Figma | Diseño y prototipado de interfaces |
| Jira | Organización y seguimiento de tareas |

Los módulos contemplados incluyen identidad, administración académica, calificaciones, asistencia, justificaciones, tutoría, analítica y auditoría.

## 5. Documentación académica

La documentación general del proyecto se organiza en dos unidades.

### Unidad 1 — Planeación, análisis y diseño

Contiene los fundamentos, objetivos, alcance y decisiones iniciales del proyecto.

Incluye:

- Problemática y justificación.
- Objetivo general y objetivos específicos.
- Alcance y funcionalidades del MVP.
- Requisitos funcionales y no funcionales.
- Análisis y gestión de riesgos.
- Metodología y responsabilidades del equipo.
- Planificación de actividades y cronograma.
- Arquitectura del sistema y tecnologías seleccionadas.
- Patrones de diseño.
- Wireframes y validaciones de información.
- Propuesta visual de interfaces.

La documentación contempla **25 requisitos funcionales, 12 no funcionales, 15 riesgos y 26 tareas de planificación**.

**[Consultar documentación completa de la Unidad 1](docs/UNIDAD_1.md)**

**[Consultar diagramas e imágenes de la Unidad 1](docs/assets/unidad1/)**

### Unidad 2 — Control de versiones, prototipado, diagramas y modelo de datos

Desarrolla la documentación técnica y colaborativa del proyecto.

Incluye:

- Control de versiones mediante Git y GitHub.
- Organización de ramas y convenciones de commits.
- Flujo de colaboración y Pull Requests.
- Diseño y prototipado de interfaces.
- Diagramas del sistema.
- Arquitectura y distribución de componentes.
- Modelo entidad-relación.
- Diccionario de datos de 23 tablas.
- Restricciones y relaciones de la base de datos.
- Estrategia de pruebas e integración continua.
- Evidencias de colaboración y desarrollo.

**[Consultar documentación completa de la Unidad 2](docs/UNIDAD_2.md)**

**[Consultar diagramas de la Unidad 2](docs/assets/unidad2/)**

## 6. Evidencias de diseño de interfaces

Las evidencias de diseño documentan la evolución de las pantallas y componentes de EDUTRAK.

Se incluyen capturas correspondientes a:

| Evidencia | Archivo |
|---|---|
| Navegación y administración de periodos | [Ver imagen](docs/assets/unidad2/avances/avance-01-periodos.png) |
| Indicadores académicos de grupos | [Ver imagen](docs/assets/unidad2/avances/avance-02-indicadores.png) |
| Configuración de horarios | [Ver imagen](docs/assets/unidad2/avances/avance-03-configuracion-horarios.png) |
| Modal para agregar clases | [Ver imagen](docs/assets/unidad2/avances/avance-04-agregar-clase.png) |
| Diseño del horario semanal | [Ver imagen](docs/assets/unidad2/avances/avance-05-horario-semanal.png) |

Las propuestas incluyen mejoras de navegación, visualización de horarios, indicadores y componentes de interfaz relacionados con asistencia y tutoría.

**[Consultar documento de avances de interfaces](https://docs.google.com/document/d/1QPtZunHHS7UZCLLVmPyzd5itvmhEk914QFiot2mfnyE/edit)**

Estas capturas representan evidencias de diseño y avances de interfaz, sin sustituir la validación del maquetado funcional.

## 7. Modelo de datos

EDUTRAK utiliza PostgreSQL como sistema de persistencia.

El diseño relacional contempla **23 tablas** para representar usuarios, sesiones, estructura académica, grupos, inscripciones, calificaciones, asistencias, justificaciones, seguimientos tutoriales, alertas y auditoría.

El diccionario de datos de la Unidad 2 documenta los campos, tipos, relaciones, claves y restricciones de las entidades.

**[Consultar el diccionario de datos en la Unidad 2](docs/UNIDAD_2.md)**

## 8. Control de versiones y colaboración

El desarrollo se administra mediante Git y GitHub.

El proyecto utiliza repositorios independientes para frontend y backend, con ramas de trabajo, commits y Pull Requests sujetos a revisión.

El proceso contempla:

1. Crear una rama de trabajo.
2. Desarrollar o documentar los cambios correspondientes.
3. Registrar commits descriptivos.
4. Crear un Pull Request.
5. Ejecutar las comprobaciones automatizadas disponibles.
6. Solicitar revisión de otro integrante.
7. Integrar los cambios una vez aprobados.

### Evidencias de colaboración

El repositorio del backend contiene Pull Requests aprobados y fusionados correspondientes al desarrollo de sus módulos.

**[Consultar Pull Requests del backend](https://github.com/EDUTRAKMX/EDUTRAK_BACKEND/pulls?q=is%3Apr+is%3Aclosed)**

### Integración continua

El backend dispone del flujo `backend-ci`, mediante GitHub Actions.

La ejecución verificada #17 finalizó exitosamente, incluyendo comprobaciones de formato, dependencias, análisis estático, compilación, pruebas, migraciones y construcción Docker.

**[Consultar ejecución de GitHub Actions #17](https://github.com/EDUTRAKMX/EDUTRAK_BACKEND/actions/runs/4415931510)**

## 9. Repositorios del proyecto

| Repositorio | Propósito |
|---|---|
| [EDUTRAK_BACKEND](https://github.com/EDUTRAKMX/EDUTRAK_BACKEND) | API REST, módulos Go, PostgreSQL y pruebas del backend |
| [EDUTRAK_FRONTEND](https://github.com/EDUTRAKMX/EDUTRAK_FRONTEND) | Aplicación web Angular y componentes de interfaz |
| [EDUTRAKMX/.github](https://github.com/EDUTRAKMX/.github) | Documentación general y recursos organizacionales |

La documentación académica compartida del proyecto se centraliza en este repositorio organizacional, mientras que cada repositorio de aplicación conserva su documentación técnica específica.

## 10. Alcance y evolución del sistema

El proyecto contempla el desarrollo progresivo de sus funcionalidades, integraciones e interfaces.

El registro mediante QR y la captura manual forman parte del diseño de asistencia del backend. NFC se contempla como alternativa de evolución y no se presenta como una integración funcional completa.

Las evidencias de interfaz documentan avances de diseño; la funcionalidad del frontend debe verificarse en su implementación correspondiente.

Las reglas académicas que requieren validación institucional se distinguen de las decisiones técnicas adoptadas para el desarrollo.

## 11. Organización de la documentación

| Documento o recurso | Ubicación |
|---|---|
| Documentación Unidad 1 | `docs/UNIDAD_1.md` |
| Documentación Unidad 2 | `docs/UNIDAD_2.md` |
| Imágenes y diagramas Unidad 1 | `docs/assets/unidad1/` |
| Imágenes y diagramas Unidad 2 | `docs/assets/unidad2/` |
| Evidencias de interfaces | `docs/assets/unidad2/avances/` |
| Presentación pública de la organización | `profile/README.md` |

## 12. Conclusión

EDUTRAK reúne la planeación, el análisis, el diseño y la organización técnica de una plataforma orientada al seguimiento académico y tutorial.

La documentación de las Unidades 1 y 2 establece los fundamentos del proyecto, su arquitectura, el modelo de información, las decisiones de diseño y la metodología colaborativa utilizada durante el desarrollo.

La separación entre la documentación general de la organización y los repositorios de implementación permite mantener una estructura clara, verificable y preparada para la evolución del sistema.