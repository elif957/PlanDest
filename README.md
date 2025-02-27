# PlanDest 
PlanDest es un servicio en la nube que recomienda destinos turísticos personalizados.

## Características:
Las recomendaciones están basadas en el clima, presupuesto e intereses del usuario. Se integrará con fuentes de datos en tiempo real y ofrecerá recomendaciones personalizadas con IA.

## La arquitectura del Proyecto será la siguiente:
- Backend (API): Aplicación en EC2 (Flask/FastAPI con Python).
- Base de Datos: DynamoDB para almacenar preferencias y búsquedas.
- APIs Externas: Google Places API para lugares.
                  OpenWeatherMap para el clima.
                  DeepSek para el análisis.

  
