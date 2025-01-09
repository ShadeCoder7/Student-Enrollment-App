# Student Enrollment App

¡Bienvenido a **Student Enrollment App**! Este es un proyecto diseñado para administrar la inscripción de estudiantes, proporcionando una solución robusta y escalable para gestionar datos relacionados con estudiantes, cursos y matriculaciones. El proyecto utiliza tecnologías modernas para garantizar un rendimiento óptimo y un desarrollo eficiente.

## Tecnologías Utilizadas

Este proyecto está desarrollado con las siguientes tecnologías:

- **Java**: Como lenguaje principal para la lógica de negocio.
- **Hibernate**: Para la gestión de la persistencia y el mapeo objeto-relacional (ORM).
- **MySQL**: Como sistema de gestión de bases de datos relacional.

## Características principales

- **Gestión de estudiantes**: Permite añadir, modificar y eliminar registros de estudiantes.
- **Administración de cursos**: Registra la información de los cursos disponibles.
- **Inscripción de estudiantes**: Vincula a los estudiantes con los cursos en los que están inscritos.
- **Consulta y reportes**: Proporciona estadísticas básicas sobre la inscripción de estudiantes.

## Instalación

Sigue estos pasos para configurar y ejecutar el proyecto en tu entorno local:

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/ShadeCoder7/Student-Enrollment-App.git
   ```
2. **Configura la base de datos:**
   - Crea una base de datos MySQL con el nombre `student_enrollment`.
   - Ejecuta el script SQL proporcionado en el archivo `schema.sql` para crear las tablas necesarias.

3. **Configura Hibernate:**
   - Ve al archivo `hibernate.cfg.xml` y actualiza los parámetros de conexión según tu entorno (URL, usuario, contraseña, etc.).

4. **Ejecuta la aplicación:**
   - Compila el proyecto con tu IDE preferido o utiliza la línea de comandos con Maven/Gradle.
   - Inicia la aplicación y verifica el log para asegurarte de que está conectada correctamente a la base de datos.

## Uso

1. Inicia la aplicación y accede a la consola o a la interfaz proporcionada.
2. Crea nuevos estudiantes y cursos a través de las opciones disponibles.
3. Gestiona las inscripciones para vincular estudiantes con los cursos.
4. Consulta el listado de estudiantes inscritos en cada curso y genera reportes básicos.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar esta aplicación, por favor sigue estos pasos:

1. Haz un fork de este repositorio.
2. Crea una rama para tu función o corrección de errores:
   ```bash
   git checkout -b feature/nombre-funcion
   ```
3. Realiza los cambios y realiza un commit:
   ```bash
   git commit -m "Añadir nueva función"
   ```
4. Sube tus cambios a tu fork:
   ```bash
   git push origin feature/nombre-funcion
   ```
5. Abre un pull request en este repositorio explicando tus cambios.

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE). Puedes usarlo, modificarlo y distribuirlo libremente.

---

¡Gracias por visitar este repositorio! Si tienes alguna pregunta o sugerencia, no dudes en abrir un issue o contactarme directamente.

