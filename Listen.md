# APIS Banxico

------------------------

## Descripción
Repositorio en el cual se guardan los códigos para la consulta de información vía API de Banxico.

Inicialmente se cuenta con información para la descarga de Remesas a nivel estatal y municipal (se ampliará de forma contínua), sin embargo, queda abierta la invitación para ampliar el catálogo de APIS.

## Actualizaciones
- 31/08/2021: Creación y APIS iniciales.

## Notas
- El número máximo disponible para consulta son 100 series (para consulta masivo como es el caso de remesas municipales, se sugiere hacer  'splits' del dataframe original).
- Se omiten algunas secciones disponibles debido a su poca importancia o poca utilidad debido a su presentación vía API (la presentación y posterior manipulación de algunas encuestas puede resultar complicada y poco práctica, se sugiere consultar las bases [integrales](https://www.banxico.org.mx/publicaciones-y-prensa/encuestas-economia-banco-mexi.html)).

## APIS disponibles para consulta
### Completos
1. Remesas por entidad federativa

![Remesas por entidad](/Ejemplos/rpe.png)

2. Remesas municipales

![Remesas por municipio](/Ejemplos/rpm.png)

### Pendientes

5. Banco de México
6. Tipos de cambio y resultados históricos de las subastas
7. Información histórica del mercado cambiario y de valores
8. Tasas y precios de referencia
9. Subastas y colocación de valores
10. Valores en circulación
11. Agregados monetarios y activos financieros internos
12. Financiamiento e información financiera de intermediarios financieros
13. Billetes y monedas
14. Finanzas públicas
15. Índices de Precios al Consumidor y UDIS
16. Índices de Precios Productor y de Comercio Exterior
17. Laboral
18. Balanza de pagos
19. Sistemas de pago
20. Sistemas de pago de bajo valor
22. Fondo Mexicano del Petróleo (Banxico como Fiduciario)

## Documentación externa

Para más información tal como límites de consulta y catálogo completo de APIS:

- [Banxico](https://www.banxico.org.mx/SieAPIRest/service/v1/)
