Llanquihue Tour App - Semana 8
Descripción del Proyecto
Esta versión del sistema de la agencia de turismo Llanquihue Tour integra conceptos avanzados de Programación Orientada a Objetos, incluyendo el uso de interfaces, polimorfismo, colecciones genéricas y una interfaz gráfica de usuario (GUI) básica.


El sistema permite gestionar diversas entidades (Guías Turísticos, Vehículos y Colaboradores Externos) de manera unificada a través de un contrato común, facilitando la administración de recursos de la agencia.

Estructura del Proyecto
El código se organiza en los siguientes paquetes siguiendo el estándar modular:


model: Contiene la interfaz Registrable y la jerarquía de clases (Persona, GuiaTuristico, Vehiculo, ColaboradorExterno).
data: Incluye la clase GestorEntidades, encargada de manejar la colección polimórfica de objetos.
ui: Contiene la clase VentanaPrincipal, que implementa la interfaz gráfica usando JOptionPane.
app: Contiene la clase Main, punto de entrada de la aplicación.

Características Implementadas
Interfaz Registrable: Define el método mostrarResumen(), obligando a todas las entidades a tener un comportamiento común.
Polimorfismo e instanceof: Se utiliza una lista única de tipo ArrayList<Registrable> para almacenar diferentes objetos. Al recorrerla, se utiliza el operador instanceof para aplicar lógica específica según el tipo de entidad.
Interfaz Gráfica (GUI): Se implementó un sistema de menús y formularios visuales mediante cuadros de diálogo, facilitando la interacción del usuario sin necesidad de usar la consola directamente para el ingreso de datos.
Instrucciones de Ejecución
Abra el proyecto en IntelliJ IDEA.
Asegúrese de tener configurado un JDK (versión 17 o superior recomendada).
Navegue hasta la clase src/app/Main.java.
Haga clic derecho y seleccione Run 'Main.main()'.
Siga las instrucciones en las ventanas emergentes para registrar y visualizar las entidades.
Desarrollado para la asignatura de Desarrollo Orientado a Objetos I.
