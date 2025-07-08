## 👨‍💻 Manual de Usuario

### 🖥️ Pantalla principal

Al iniciar la aplicación, se presenta un **menú principal interactivo**. Este menú permite al usuario navegar hacia diferentes interfaces funcionales, incluyendo:

- **Usuario**
- **Inscripción**

Cada opción abre una nueva ventana con herramientas específicas según la funcionalidad elegida.

---

### 👤 Interfaz: Usuario

La interfaz de **Usuario** permite gestionar información relacionada con las personas registradas en la biblioteca. Desde aquí puedes:

- **Registrar nueva persona:** Se abre un formulario donde se ingresan nombre, apellidos, edad, etc.
- **Editar datos existentes:** Puedes modificar la información de un usuario previamente guardado.
- **Eliminar registros:** Borra de forma permanente a una persona de la base de datos.
- **Buscar usuarios:** Filtra la lista mediante nombre o ID para ubicar rápidamente un registro.

Esta vista es esencial para el manejo del catálogo de usuarios y su mantenimiento actualizado.

---

### 🧯 Solución de problemas comunes

| Problema | Posible causa | Solución |
|---------|----------------|----------|
| `java.sql.SQLException: Access denied` | Usuario o contraseña incorrecta | Revisa `ConexionMySQL.java` |
| Fallo al conectar a la BD | MySQL no se está ejecutando | Inicia el servicio MySQL |
| Error de librerías | Falta el driver JDBC | Añádelo al proyecto manualmente |

---

### 💡 Ejemplos de uso

1. Desde el **menú principal**, haz clic en **Usuario**.
2. Llena el formulario con los datos: nombre, apellidos, edad.
3. Presiona **Guardar** → El usuario se registra en la base de datos.
4. Usa el campo de búsqueda para verificar su ingreso.
