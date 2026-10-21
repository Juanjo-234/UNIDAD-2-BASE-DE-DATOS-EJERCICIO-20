# UNIDAD-2-BASE-DE-DATOS-EJERCICIO-20
Se pide diseñar un Modelo Entidad-Relación (MER) para un espacio de coworking, que permita administrar los espacios físicos, los miembros, las reservas, los accesos al edificio y los consumos adicionales.

El modelo debe contemplar:

- Espacios: registrar código, nombre, capacidad máxima y tarifa por hora o jornada.
- Miembros: almacenar DNI, nombre, empresa, correo electrónico y número de tarjeta RFID.
- Reservas: registrar fecha de uso, hora de inicio y fin, miembro solicitante y espacio reservado.
- Control de acceso: registrar cada entrada o salida del edificio, incluyendo fecha y hora exactas, sentido del movimiento, tarjeta utilizada y miembro validado.
- Consumos adicionales: registrar servicios o productos utilizados, como café, impresiones o alquiler de proyectores, indicando fecha, descripción, cantidad y costo, asociados a la cuenta del miembro.

Finalmente, se deben identificar las entidades, sus atributos, las relaciones y las cardinalidades, considerando que un miembro puede realizar múltiples reservas, registrar numerosos accesos y acumular varios consumos, mientras que cada reserva corresponde a un espacio específico.

<img width="2552" height="1252" alt="EJERCICIO 20 drawio" src="https://github.com/user-attachments/assets/0374f1ab-69f8-45fb-8fdd-34ba1c69fd72" />

