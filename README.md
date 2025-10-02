
# Proyecto Finanzas personales

El proyecto consiste en el desarrollo de un sistema web para la gestión de finanzas 
personales. La aplicación permitirá que un usuario pueda registrar sus ingresos y gastos, 
organizarlos por categorías, y recibir notificaciones de vencimientos (facturas o servicios) a 
las cuales podrá marcar como leídas. Además, se incluirá un módulo de reportes y 
estadísticas que ayudará al usuario a analizar su situación financiera de manera clara y 
sencilla y otro módulo que permitirá a los usuarios crear varias listas de compras 
(personales y compartidas con otros usuarios) para tener un seguimiento de compras 
futuras.

---

## Patrones a utilizar:
### Factory Method
En la generación de reportes, cambiando los parámetros una clase podemos definir como queremos que se genere el reporte, si en pdf o en excel, además se puede extender facilmente en un futuro si se quiere agregar otro formato, por ejemplo csv.

### Adapter
Se adaptan las clases encargadas de usar las librerias para crear pdf y excel en este caso para que puedan ser usadas por el factory method facilmente


### Singleton
Para tener una sola instancia de la base de datos y evitar múltiples conexiones simultaneas

### Facade
Para ejecutar los seeds de manera simple con una sola función


--- 

#### Integrantes
● Cordoba Ismael 
● Baradad Mariana
● Baranovsky Juan
● Folik Hernan