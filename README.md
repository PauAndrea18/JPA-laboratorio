# Laboratorio JPA
    
## Breve explicación de la anotación 
    $@OneToMany

Esta anotación representa la cardinalidad entre dos entidades, en este caso Competitor y Producto, donde al ser una relación de uno a muchos desde Competitor a Producto quiere decir que un Competitor puede tener muchos Productos, lo anterior se evidencia en el atributo List<Producto>, esta relación esta principalmente relacionada en el mapeo que se realiza entre tablas dentro de una Base de Datos Relacional

