# 8. Modelo de Datos

# Punto de interés

- Padre[]
- -Dueño: Perfil
- Localización
- Orden*
- Actividad: Actividad del punto de interés
- Descripción
- Contacto
- -Icono
- -Banner
- Multimedia[]
- -Historia**
- -Curiosidades
- Reconocimiento[]:
    - Tipo de reconocimiento: BIC, Patrimonio histórico…
    - Fecha de declaración
- -Info. accesibilidad
- Valoración[]

* Por ejemplo, el Parque de María Luisa tiene mayor orden que otros puntos que estén dentro (que en este caso son sus hijos). Desde una vista más general solo se vería un globo del parque, no sus hijos. Aplica también a barrios, etc. → comunidades/comarcas/municipios/barrios/parques-centros/detalles…

** Será imprescindible bibliografía y fuentes fiables. Revisadas oficialmente antes de ser publicadas. Se podrán alojar en el propio sistema entrevistas en audio o vídeo a residentes locales.

## Visitable: Punto de interés

- Horario
- Tiempo estimado
- Acceso libre
- Entradas
- Idioma[]

## Elemento arquitectónico: Punto de interés

- Estilo
- Arquitecto
- Rango de fechas de construcción
- Fecha de inauguración

**Otros posibles subtipos de Punto de interés:** 

- Edificio Arquitectónico: Elemento arquitectónico
    - Vivienda
    - Iglesia
- Plaza: Elemento arquitectónico
- Parque: Elemento arquitectónico
    - Parque Nacional
    - Jardín Botánico
    - Reserva Natural
    - Parque Urbano
    - Parque de Aventura (con actividades como tirolinas)
- Fuente: Elemento arquitectónico
- Puente: Elemento arquitectónico
- Cerámica: Elemento arquitectónico
- Pieza de arte
    - Arte urbano
- Patrimonio natural
    - Planta
        - Árbol (con sus subtipos)
    - Cueva
    - Montaña
        - Pico
        - Cordillera
        - Volcán
    - Lago/río
        - Cascada
        - Estanque
        - Arroyo

## *Tipos de actividad*

- Museo
- Cine
- Teatro
- Ópera
- Restaurante
- Artesanal
- Ropa
    - Segunda Mano
    - Vintage
    - Artesanal
- Frutería / Verduras
- Panadería
- Pasteles
- …

---

# Ruta

- Tipo: ESTRATÉGICA/TURÍSTICA/CREATIVA
- Parada[]
    - Punto de interés
    - Descripción por páginas/puntos
- Descripción
- Banner
- Valoración[]

## Ruta estratégica: Ruta

## Ruta turística: Ruta

- Dueño: Agencia de turismo
- Precio autoguiada
- Ruta con guía:
    - -Disponibilidades/reservas
    - -Enlace
    - Precio

## Ruta creativa: Ruta

- Dueño: Perfil

---

# Evento

- -Dueño: Perfil
- Inicio
- Fin
- Descripción
- Publicación[]
- Contacto
- -Icono
- -Banner
- Punto de interés[]
- Ruta[]
- Multimedia[]
- Valoración[]

### Visitable: Evento

- Horario
- Tiempo estimado
- Acceso libre
- Entradas

---

# Perfil

- -Imagen
- -Banner
- Publicación[]

## Mapper: Perfil

- Siguiendo: Perfil[]

## Cliente: Perfil

- Info. de contacto

### Comercio: Cliente

- Actividad[]

### Agencia de turismo: Cliente

