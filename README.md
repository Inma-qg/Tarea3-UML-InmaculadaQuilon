 AD-3. Diagramas UML. 
1.	Análisis del problema y requisitos del sistema

¿Quiénes son los actores que interactúan con el sistema? 
Administrador, jugadores y sistema

¿Cuáles son las acciones que cada actor puede realizar? 
Administrador: registro de equipos y jugadores
Jugadores: consulta las listas
Sistema: procesos automáticos

¿Cómo se relacionan entre sí las entidades del sistema? 
Equipo – Jugador: relación de composición.
GestorTorneo – Equipo/Jugador: relación de asociación.
PantallaRegistro/PantallaConsulta – GestorTorneo: relación de dependencia.

2. Identificación de los casos de uso y elaboración del diagrama 

3. Identificación de clases y relaciones
Clases de Entidad: Equipo y Jugador
Clases de Control: GestorTorneo
Clases de Interfaz: PantallaRegistro y PantallaConsulta

Clase origen	   Clase destino	Tipo de relación	Símbolo UML
Equipo	            Jugador	          Composición	         ◆———
GestorTorneo	    Equipo, Jugador	  Asociación		  ———
PantallaRegistro    GestorTorneo	  Dependencia		  ------→
PantallaConsulta    GestorTorneo	  Dependencia		  ------→
