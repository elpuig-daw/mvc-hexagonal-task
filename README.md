
## Exercici:
### Aplicació de Reserva de Llibres de Biblioteca (Patró MVC i Hexagonal)

Crea una aplicació de consola en Java que permeti a un usuari reservar un llibre d’una biblioteca. L’aplicació ha de seguir:  
- L’arquitectura MVC (Model-Vista-Controlador).
- L'arquitectura hexagonal com l'hem vist a classe.

Requisits:
- L’usuari introdueix el seu nom i el títol del llibre que vol reservar per consola.
- L’aplicació mostra un missatge de confirmació amb el nom de l’usuari i el títol del llibre reservat.
- Organitza el teu codi tal com està definit en aquesta plantilla.
- Es necessiten les següents classes com a model de dades o domini:
    - User (emmagatzema les dades de l’usuari).
    - Book (emmagatzema les dades del llibre).
    - Reservation per encapsular la reserva.
- En MVC el paquet view s’encarrega de la interacció amb l’usuari (entrada i sortida).
- En MVC el paquet controller coordina el flux entre la vista i el model.
- Extres:
    - Permet que l’usuari pugui reservar més d’un llibre en una mateixa sessió.
    - En MVC crea un classe ReservationService amb un mètode que faci la reserva del llibre.  
    - En hexagonal implementa també un sortida de les reserva cap a un fitxer amés de la consola.

