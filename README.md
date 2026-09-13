# Gestor de Colección Musical

Proyecto final de Fundamentos de Programación en C++. Sistema de consola que administra una colección de hasta 20 álbumes musicales.

## Conceptos aplicados

- `struct` de siete campos: título, artista, año, género, duración, calificación, precio y formato.
- Arreglo estático de estructuras con validación de cada entrada del usuario.
- Matriz bidimensional de conteo por género y década para el análisis estadístico.
- `vector` dinámico para almacenar los resultados de los filtros.
- Ordenamiento burbuja ascendente y descendente por año de lanzamiento.

## Funcionalidades

1. Registrar álbum con validación campo por campo.
2. Mostrar la colección en formato de tabla.
3. Modificar calificación y precio de un álbum existente.
4. Eliminar un álbum reorganizando el arreglo.
5. Buscar por coincidencia parcial en el título.
6. Ordenar por año de lanzamiento.
7. Mostrar el álbum mejor calificado.
8. Análisis estadístico: matriz género por década y promedio de calificación por género.
9. Filtrar por género, rango de años, calificación mínima o formato.

## Compilación y ejecución

```
g++ "Proyecto programacion F .cpp" -o coleccion
./coleccion
```

## Autores

Paúl Guerra e Israel Ferigra.

---

**Paúl Andrés Guerra Vicuña** · Fundamentos de Programación · Ingeniería en Ciencias de Datos e Inteligencia Artificial · Universidad Nacional de Chimborazo (UNACH)
