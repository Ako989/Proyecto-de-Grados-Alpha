# Entrega final del proyecto de grados

# Alpha: Un rpg con base en un sistema de moralidad
### Descripcion
Crear un rpg (role playing game), donde la toma de elecciones del jugador cambiara su experiencia, progreso y final.
El objetivo es comprender los requerimientos que necesita crear una experiencia unica para cada persona. Donde el reto sera poder captar requisitos para 
crear emociones, cubrir necesidades y demandas de los steakholders y sobre todo hacer algo divertido que engache al jugador(es).

______________________________________________________________________________________________________________________________________________________________
## Requisitos funcionaes y no funcioanes
___________
### Funcionales:
- carga de dailogos/musica
- registro interno: "karma"/"Ruta"
- feedback: dependiendo de las acciones
- nucleo: seran las elecciones, seguidas de causa/efecto y moral (Karma)

### No funcionales: 
- coherencia de tono y atmosfera que dependen del camino recorrido
- responsividad: adaptar las mecanicas PvN para que la habilidad del jugador sea el factor critico
- Narrativa: las acciones y reacciones del juego deben estar en coherencia con las elecciones tomadas


______________________________________________________________________________________________________________________________________________________________

## Tecnologias utilizadas
### MySQL o JSON: 
Para base de datos, ya sea para guardar record, elecciones o la ruta que se sigue, inventario, etc
### Framewoerk: 
godot, enfocado en el 2D
### Arte/Diseño:
- Asepite para un diseño con pixeles
- Control de versioens: Git





<img width="6561" height="2026" alt="deepseek_mermaid_20251106_1b7a2b" src="https://github.com/user-attachments/assets/ef168156-288f-4844-949a-b4250b7b35f4" />


# Diagrama ishikawa
 
<img width="1528" alt="Diagrama Ishikawa" src="https://github.com/user-attachments/assets/42a7c85e-6a81-4085-9d8e-95a8046bef27" />
 
# Validacion y verificacion

|Verificacion: "Are we building the product right?"| validacion: "Are we building the right product?"|
|----------------------------------------------------|--------------------------------------------------|
|1. unicamente los usuarios registrados podran ingresar|1. la pagina principal tambien necesitara registrarse para ver el contenido?|
|2. la ruta podra cambiar dependiendo de las acciones del personajes|2. en caso de una reaccion en cadena, el karma sera de la accion inicial o el resultado?|
|3. los consumibles deben tener limite|3. tendra limite de consumo y el limite bajara si se consumen varios al mismo tiempo?|
|4. las tiendas deben tener tiempos de restok|4. los restok de las tiendas seran individuales o unicos? manejaran diferentes horarios?|
