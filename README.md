# BT&Airways — Modelo Entidad-Relación (MER)

Experiencia 1, Semana 2 — **Modelamiento de Bases de Datos (PRY2204)**
Duoc UC · Analista Programador · Grupo 13

**Integrantes:** Rodolfo Delgado · Alex Lorca

## El caso

BT&Airways es una aerolínea con más de 25 años de operación que necesita rediseñar
el módulo de registro de venta de vuelos. Este repositorio contiene el modelo
conceptual de datos construido a partir de sus reglas de negocio.

## El modelo

Seis entidades: **AVION**, **VUELO**, **RESERVA**, **PASAJERO**, **EMPLEADO** y
**EQUIPAJE**, esta última como entidad débil identificada por su dueño.

Seis relaciones, entre ellas una identificadora (PASAJERO — EQUIPAJE) y una de
muchos a muchos (RESERVA — EQUIPAJE), que al pasar al modelo relacional se
resuelve con la tabla puente `RESERVA_EQUIPAJE`.

## Archivos

| Archivo | Contenido |
|---|---|
| `PRY2204_Exp1_S2_Formato respuesta_Grupo13_Delgado_Lorca.docx` | Documento de entrega con las capturas del MER en notación Barker y del modelo en notación Bachman / Ingeniería de la Información |
| `Exp1_S2_Nuevo_Grupo13.zip` | Diseño de Oracle SQL Developer Data Modeler: archivo `.dmd` y su subcarpeta |
| `captura_MER.png` | Modelo Entidad-Relación en notación Barker |
| `captura_banchman.png` | Modelo en notación Bachman con los tipos de datos |

## Herramienta

Oracle SQL Developer Data Modeler 24.3. Para abrir el diseño, descomprimir el ZIP
y abrir `BTAirways_Semana2.dmd` — el archivo `.dmd` necesita su subcarpeta del
mismo nombre en la misma ubicación.
