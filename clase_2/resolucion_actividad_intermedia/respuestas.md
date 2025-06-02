# REspuestas punto 4 y 5 

## **4.Enumerar y describir las principales diferencias entre Subversion y Git (no más de 1 carilla).**

| Característica               | **Subversion (SVN)**                                         | **Git**                                                            |
|-----------------------------|---------------------------------------------------------------|--------------------------------------------------------------------|
| **Modelo de control**       | Centralizado: hay un único repositorio central.              | Distribuido: cada usuario tiene una copia completa del repositorio. |
| **Trabajo offline**         | Requiere conexión al servidor para la mayoría de operaciones. | Permite trabajar completamente offline.                            |
| **Velocidad**               | Más lento; depende del servidor para muchas operaciones.      | Muy rápido para operaciones locales (commit, diff, log, etc.).     |
| **Branching y merging**     | Costoso y complejo.                                           | Eficiente y sencillo.                                              |
| **Tamaño del repositorio**  | Crece lentamente, guarda sólo diferencias por versión.        | Guarda el historial completo localmente.                           |
| **Seguimiento de archivos** | Rastrea archivos individualmente.                            | Rastrea el contenido y detecta cambios como renombrados.           |
| **Historial de cambios**    | Lineal, difícil de modificar.                                | Flexible, permite reescribir historial (rebase, squash).           |
| **Colaboración**            | Todos trabajan sobre el repositorio central.                 | Cada usuario trabaja en su copia y luego sincroniza.               |
| **Permisos y seguridad**    | Control granular por archivo/directorio.                     | Control a nivel de repositorio remoto.                             |
| **Curva de aprendizaje**    | Más simple para principiantes.                               | Requiere más aprendizaje inicial, pero ofrece más flexibilidad.    |

## **5.Enumerar y describir las principales diferencias entre Gitlab y Github (no más de 1 carilla).**

| Característica                  | **GitLab**                                                   | **GitHub**                                                 |
|--------------------------------|---------------------------------------------------------------|-------------------------------------------------------------|
| **Propiedad**                  | Desarrollado por GitLab Inc. (open core).                    | Propiedad de Microsoft desde 2018.                         |
| **Alojamiento**                | Puede usarse en la nube o instalarse en servidores propios.   | Principalmente en la nube, aunque existe GitHub Enterprise.|
| **Modelo de CI/CD**            | Integrado por defecto con potentes pipelines personalizables. | GitHub Actions ofrece CI/CD, pero fue añadido más tarde.   |
| **DevOps completo**            | Incluye planificación, gestión de incidencias, monitoreo, etc.| Enfocado más en control de código y colaboración.          |
| **Privacidad y control**       | Mayor control en instalaciones self-hosted.                   | Menos control directo si se usa GitHub en la nube.         |
| **Gestión de proyectos**       | Tableros Kanban, Roadmaps y seguimiento de issues avanzados.  | Boards simples; depende más de integraciones externas.     |
| **Licencia**                   | Código abierto (Community Edition), y versiones comerciales.  | Cerrado, aunque hay herramientas y API accesibles.         |
| **Popularidad y comunidad**    | Muy usado en empresas DevOps; comunidad técnica activa.        | Mayor comunidad global, especialmente en proyectos open source. |
| **Integraciones**              | Soporte nativo para DevOps; pipelines muy configurables.       | Fuerte ecosistema de apps e integraciones vía GitHub Marketplace. |
| **Interfaz y experiencia**     | Más técnica y orientada a flujos DevOps completos.            | Más amigable para desarrolladores y proyectos open source.  |

