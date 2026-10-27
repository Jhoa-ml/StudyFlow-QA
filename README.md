# Pruebas Beta - StudyFlow v2.0.0

## Información general y descarga

- **Testers asignados:** David, Belem y Brayan.
- **Versión a revisar:** StudyFlow v2.0.0 (Versión 2 con correcciones de la primera fase de pruebas).
- **Archivo ejecutable:** `StudyFlow-2.0.0.apk`

---

## 🚀 Resumen de Cambios y Correcciones (Release v2.0.0)

Con base en los hallazgos y la retroalimentación de la primera fase de pruebas, se reestructuró la aplicación para ser **100% autodidacta y de autogestión personal**. Ya no es necesario depender de un usuario administrador para la asignación de contenido.

### 1. Autogestión Total del Estudiante (Sin precargas)
- **Mis Materias:** Cada usuario puede crear, consultar y eliminar sus propias materias desde la pantalla *Mis materias*. Las cuentas inician limpias para libre configuración.
- **Mis Tareas:** Se incorporó el botón flotante **`+ Nueva Tarea`** para que el estudiante agregue sus propios pendientes, asignándoles materia, fecha de entrega y prioridad (Alta, Media, Baja). Permite editar, eliminar y marcar entregas completadas.

### 2. Notificaciones Locales Automáticas
- Integración de notificaciones push en la barra de estado del dispositivo al detectar tareas pendientes al iniciar la aplicación o consultar el Home.

### 3. Seguridad y Ajustes de Perfil
- **Validación de Cambio de Contraseña:** Reautenticación obligatoria solicitando la contraseña actual antes de actualizar a una nueva clave por seguridad.
- **Frases Motivacionales:** Traducción y adaptación nativa al español para las frases inspiracionales de la pantalla principal.
- **Notificaciones en Home:** Conexión interactiva del botón de campana en la barra superior.

---

## 📝 Nota importante para los Testers

Al instalar el APK de esta versión 2 e iniciar sesión (o registrar una cuenta nueva):
1. Tu cuenta iniciará desde cero (sin tareas ni materias precargadas).
2. Dirígete primero a la sección **Materias** para dar de alta tus asignaturas.
3. Posteriormente ve a **Tareas** y crea tus actividades para evaluar las notificaciones, filtros y seguimiento académico.

---

## 🐛 Registro e Instrucciones para los Testers

Para mantener un flujo ordenado de QA, los hallazgos pueden registrarse tanto en los archivos personales como mediante **GitHub Issues**:

### Opción A: Crear un Issue en GitHub (Recomendado)
1. Dirígete a la pestaña **Issues** en la barra superior del repositorio.
2. Haz clic en el botón verde **New Issue**.
3. Asigna un título claro (Ejemplo: `[Bug] Error al guardar materia en Android 14`).
4. Describe los pasos exactos para reproducir el problema y adjunta capturas de pantalla si es necesario.
5. Asigna la etiqueta (*label*) correspondiente (`bug`, `enhancement` o `documentation`).

### Opción B: Tabla de Registro en Archivo Personal
Cada tester puede ingresar a su carpeta personal y registrar los hallazgos en la tabla de su `README.md`:

- [Tabla de Registro - David](./David/README.md)
- [Tabla de Registro - Belem](./Belem/README.md)
- [Tabla de Registro - Brayan](./Brayan/README.md)

*Nota: Solo edita tu archivo personal para evitar conflictos de sincronización.*
