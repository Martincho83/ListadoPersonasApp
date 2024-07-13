# 📋 ListadoPersonasApp

## 📖 Descripción
ListadoPersonasApp es una aplicación de consola que permite gestionar una lista de personas. Puedes agregar personas a la lista y mostrar todas las personas almacenadas en ella.

## 🌟 Características
- 👤 **Agregar Persona**: Añade una nueva persona a la lista proporcionando nombre, teléfono y email.
- 📜 **Listar Personas**: Muestra todas las personas en la lista.
- 🚪 **Salir**: Opción para salir de la aplicación.

## 📝 Código Principal

### 📂 Persona.java
Define una clase `Persona` con los siguientes atributos y métodos:
- **Atributos**: `id`, `nombre`, `tel`, `email`
- **Métodos**:
  - Constructores: uno vacío y otro con parámetros `nombre`, `tel`, `email`
  - Getters y Setters para cada atributo
  - `toString()`: para una representación en cadena del objeto `Persona`

### 📂 ListadoPersonasApp.java
Define una clase `ListadoPersonasApp` que gestiona una lista de personas con las siguientes características:
- **Menú Principal**:
  - `1. Agregar`: Permite agregar una nueva persona proporcionando `nombre`, `tel`, `email`.
  - `2. Listar`: Muestra todas las personas almacenadas en la lista.
  - `3. Salir`: Sale de la aplicación.
- **Métodos**:
  - `mostrarMenu()`: Muestra el menú principal.
  - `ejecutarOperacion()`: Ejecuta la operación seleccionada del menú.

## ⚙️ Requisitos
- Java 8 o superior
- IDE recomendado: IntelliJ IDEA o Eclipse

## 🚀 Ejecución
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/ListadoPersonasApp.git
2. Importa el proyecto en tu IDE preferido.
3. Ejecuta la clase `ListadoPersonasApp` para iniciar la aplicación.

## 🤝 Contribuciones
Si deseas contribuir a este proyecto, por favor realiza un fork del repositorio y crea un pull request con tus cambios.

## 👨‍💻 Autor
Martín - Desarrollador Principal - [Martincho83](https://github.com/Martincho83)
