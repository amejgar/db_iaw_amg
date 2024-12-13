# db_iaw_amg
Este proyecto es un sistema de gestión desarrollado con PHP, MariaDB y Apache2, diseñado para administrar información mediante una interfaz web responsiva y funcionalidades avanzadas. Está optimizado para proporcionar una experiencia profesional gracias al uso de estilos mejorados basados en Bootstrap.

Características principales
    Base de Datos:
        Creada en MariaDB, bajo el control de un usuario propietario con todos los privilegios necesarios para su gestión.
        El acceso a la base de datos solo está permitido desde la máquina local (localhost) para garantizar la seguridad.
        Estructura optimizada para almacenar información con restricciones y validaciones adecuadas.

    Funciones Incluidas:
        Añadir registros: Permite insertar nuevos datos con validaciones para evitar duplicados (por ejemplo, en correos electrónicos o números de teléfono).
        Listar registros: Muestra todos los registros almacenados en un formato tabular.
        Búsqueda: Permite localizar registros específicos según distintos criterios.
        Modificar registros: Opción para editar los datos existentes.
        Borrar registros: Permite eliminar registros individuales o múltiples a la vez.
        Borrar toda la base de datos: Función para reiniciar la base de datos eliminando todos los datos.
        Exportación a CSV: Genera un archivo CSV con los datos almacenados.
        Validaciones avanzadas: Impide la introducción de datos similares en campos sensibles, como números de teléfono o correos electrónicos.

    Diseño y Estilo:
        Uso de Bootstrap para lograr un diseño responsivo y profesional.
        Interfaz clara y moderna, adaptada para dispositivos de diferentes tamaños (móviles, tabletas, ordenadores).

    Infraestructura instalada:
        El servidor web (Apache2), PHP, y MariaDB están configurados en la misma máquina local (localhost).
        Bibliotecas PHP necesarias instaladas, como mysqli o PDO, para realizar consultas a la base de datos.

    Organización del Proyecto:
        Estructura modular con carpetas dedicadas para CSS, PHP, y scripts SQL.
        Código organizado para facilitar el mantenimiento y la escalabilidad.

        
