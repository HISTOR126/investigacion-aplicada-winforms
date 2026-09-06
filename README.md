# investigacion aplicada

WinForms: Permite crear aplicaciones de Windows de forma rápida mediante un diseñador visual de "arrastrar y soltar". Es ideal para interfaces sencillas y proyectos escolares.

WPF: Separa el diseño gráfico de la lógica usando XAML. Soporta estilos avanzados, animaciones y aceleración por hardware mediante el patrón MVVM.

.NET MAUI: Es la alternativa moderna y multiplataforma. Permite desarrollar para Windows, macOS, Android e iOS utilizando un solo código base.

2. Arquitectura Basada en Eventos

Bucle de Mensajes (Message Loop): Proceso en segundo plano que escucha de forma continua las acciones del usuario (clics, teclas) o del sistema operativo.

Manejador de Eventos (Event Handler): Código en C# que se ejecuta automáticamente cuando ocurre una acción (por ejemplo, el método btnBuscar_Click() al presionar un botón).

Hilo de la UI (UI Thread): Hilo principal encargado de renderizar la pantalla. Si realiza tareas pesadas sin asincronía, la interfaz se congela.

3. Ventajas y Limitaciones: Escritorio vs. Web (ASP.NET)

Ventajas del escritorio: Acceso directo a recursos del hardware local (impresoras, archivos), capacidad de funcionar sin conexión a Internet (offline) y respuesta inmediata de la interfaz.

Limitaciones del escritorio: Requiere instalar el programa en cada equipo, las actualizaciones son manuales equipo por equipo y (en el caso de WinForms) se limita únicamente a Windows.
