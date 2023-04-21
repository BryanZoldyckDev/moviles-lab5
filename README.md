# ¿Qué diferencia existe entre navegar dentro de la aplicación utilizando Navigation Component o hacer uso de intents?



###### La principal diferencia entre Navigation Component e Intents es que Navigation Component es una biblioteca diseñada específicamente para la navegación dentro de una aplicación Android, mientras que Intents se utilizan para iniciar actividades, servicios y broadcast receivers en la plataforma Android.

# Menciona los componentes fundamentales de Navigation 
- NavHost: El NavHost es un contenedor que aloja los fragmentos de una aplicación y gestiona la navegación entre ellos. Es el componente principal de Navigation.
- NavGraph: El NavGraph es un gráfico de navegación que define la estructura y los destinos (fragmentos y acciones) de la navegación de una aplicación.
- Destinos (Destinations): Los destinos son los puntos de la navegación que el usuario puede alcanzar. En Navigation, los destinos pueden ser fragmentos, actividades o acciones.
- Acciones (Actions): Las acciones son eventos que definen cómo se puede navegar desde un destino a otro. Una acción puede llevar a un usuario a otro destino y especificar un conjunto de argumentos que se deben pasar al nuevo destino.
- Argumentos (Arguments): Los argumentos son datos que se pueden pasar de un destino a otro a través de una acción. Los argumentos son opcionales y se pueden utilizar para proporcionar datos adicionales a un destino o para obtener datos de un destino.
- Safe Args: Safe Args es una biblioteca que permite definir argumentos seguros y evitar errores de compilación en tiempo de ejecución. Safe Args genera clases de argumentos seguras que se pueden utilizar para pasar argumentos entre destinos.
- NavController: El NavController es un objeto que se utiliza para navegar entre los destinos de un NavGraph. El NavController gestiona el historial de navegación y proporciona métodos para navegar hacia delante, hacia atrás y para navegar a destinos específicos.



# Mencione algunas de las ventajas del Navigation Graph

- Diseño visual: El Navigation Graph ofrece una vista visual de la estructura de navegación de la aplicación, lo que facilita la comprensión de la relación entre los fragmentos y las acciones de navegación.

- Modularidad: El Navigation Graph permite definir la navegación para cada módulo o característica de la aplicación de forma independiente. Esto facilita la integración de diferentes componentes y la reutilización de los mismos.

- Gestión del historial de navegación: El Navigation Graph maneja automáticamente el historial de navegación de la aplicación, lo que hace que sea fácil navegar hacia adelante y hacia atrás a través de las pantallas visitadas previamente.

- Safe Args: El Navigation Graph trabaja en conjunto con la biblioteca Safe Args, lo que permite pasar argumentos de forma segura entre los fragmentos y acciones de navegación. Esto evita errores de tiempo de ejecución y hace que sea más fácil mantener y depurar la aplicación.

- Compatibilidad con otros componentes de Android: El Navigation Graph funciona bien con otros componentes de Android, como ViewModel y LiveData. Esto permite una comunicación más fluida entre diferentes componentes de la aplicación y facilita la implementación de patrones de arquitectura como el patrón MVVM.

- Facilidad de prueba: Al separar la navegación de la lógica de negocio, el Navigation Graph facilita la escritura de pruebas unitarias y de integración, lo que mejora la calidad de la aplicación y reduce el tiempo necesario para detectar y corregir errores.

