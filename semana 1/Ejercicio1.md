### Arquitecturas Software para la nube 


## 1. Buscar una aplicación de ejemplo, preferiblemente propia, y deducir qué patrón es el que usa. ¿Qué habría que hacer para evolucionar a un patrón tipo microservicios?

[Intg-IO](https://github.com/Kevincamp/IntgIO.git) es un proyecto hecho encojunto con un compañero por una materia en la carrera de ingeniería de software. Es un sistema de integración para objetos inteligentes, un objeto inteligente es un objeto cotidiano como una lampara, puerta de garaje, etc ... conectado a internet y controlador por una persona mediante su smartphone. El usuario podia ejecutar acciones de dichos objetos mediante el dispositivo. La arquitectura que seguía esta aplicación era conocida como Modelo-Vista-Controladdor(MVC).

Para migrar a una arquitectura basada en microservicios, en este caso el almacenamiento era en un base de datos no relacional, esta base de datos tendria su contenedor, al igual que el dashboard de la aplicación, y el API Core, haciendo independientes a sus componentes.