# Trasteros · estado de comercialización

Mapa web de la promoción de 88 trasteros (fases A y B) de Lua Quinver S.L.U.
Cada trastero aparece coloreado según su estado: disponible, reservado o vendido.

## Contenido

| Archivo | Para qué sirve |
|---|---|
| `index.html` | El mapa. Lleva dentro la geometría de los trasteros, generada desde el DXF de la promoción. |
| `ESTADO_TRASTEROS.xlsx` | El estado y los precios. La página lo lee cada vez que se abre. |

## Actualizar el estado

1. Exporta el Excel desde la gestión de trasteros y guárdalo con el nombre **`ESTADO_TRASTEROS.xlsx`**.
2. En GitHub, entra en el repositorio y pulsa **Add file → Upload files**.
3. Arrastra el Excel, pon un comentario (por ejemplo «Estado 25/10/2026») y pulsa **Commit changes**.
4. Espera uno o dos minutos y recarga el mapa.

El Excel tiene que mantener las columnas de siempre:
Fase (A/B), Nº, …, Precio (columna G) y Estado (columna H).
En Estado se pone V para vendido, R para reservado y se deja en blanco si está disponible.
