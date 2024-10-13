# Taller de Base de Datos - Pokémon

**Trabajo:** Base de datos Pokémon  
**Integrantes:**  
- Leonardo Farías  
- Javier Nanco  
- Nicolás Pozo  
**Profesor:** Jonathan Sepúlveda  
**Fecha de creación:** 29/06/2023  
**Última modificación:** 04/07/2023  
**Fecha de entrega:** 06/07/2023  

## Descripción

Ash Ketchum necesita una base de datos detallada sobre las ciudades que visita, para evitar sorpresas inesperadas y mejorar su desempeño en los gimnasios. Este proyecto tiene como objetivo crear una base de datos que almacene toda la información relevante sobre las ciudades, gimnasios, centros Pokémon y tiendas que Ash encontrará en su viaje.

## Requisitos del Proyecto

El sistema debe incluir los siguientes elementos:

### Ciudades
- **Mínimo 20 ciudades**: Cada ciudad debe tener un nombre, un código único y estar relacionada con su respectivo gimnasio, centro Pokémon y tienda.
  
### Centros Pokémon
- **Información de las enfermeras**: Cada centro debe registrar el nombre de la enfermera a cargo.
- **Pokémon atendidos**: Cada centro debe almacenar detalles de los últimos 151 Pokémon atendidos (sin repetir nombres), con los siguientes atributos:
  - Nombre del Pokémon
  - Tipo primario y tipo secundario
  - HP, Ataque, Defensa, Tipo de Ataque
  - Posición en el Pokédex (número)

### Tiendas
- Cada tienda debe vender **objetos con un código específico**, y se debe almacenar el siguiente detalle:
  - Nombre del objeto
  - Tipo de objeto (Pokéball o Soporte)
  - Stock disponible
  - Precio

#### Tipos de Pokéballs:
- Pokéball
- Superball
- Ultraball
- Masterball

#### Tipos de objetos de soporte:
- Poción
- Poción Máxima
- Revivir
- Revivir Máximo
- Caramelo, entre otros

La tienda debe tener un **mínimo de 30 objetos diferentes**.

### Gimnasios
Cada ciudad tiene un gimnasio, y se debe registrar la siguiente información:
- **Nombre del líder de gimnasio**
- **Especialidad**: Tipo de Pokémon que maneja (agua, planta, siniestro, etc.)
- **Medalla**: Nombre de la medalla que otorga al derrotar al líder.

Debe incluir un **mínimo de 20 líderes de gimnasio** distintos.

## Objetivo del Proyecto

Este proyecto está diseñado para proporcionar a Ash una herramienta robusta para planificar mejor sus viajes, conocer las características de las ciudades y sus gimnasios, así como gestionar los recursos disponibles en las tiendas y centros Pokémon, ayudando a mejorar su desempeño como entrenador Pokémon.


