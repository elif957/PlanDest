# PlanDest 
PlanDest es un servicio en la nube que recomienda destinos turísticos basados en clima, presupuesto y preferencias del usuario. Se integrará con fuentes de datos en tiempo real y ofrecerá recomendaciones personalizadas con IA.

La arquitectura del Proyecto será la siguiente:
- Backend (API): Aplicación en EC2 (Flask/FastAPI con Python).
- Base de Datos: DynamoDB para almacenar preferencias y búsquedas.
- APIs Externas: Google Places API para lugares.
                  OpenWeatherMap para el clima.
                  DeepSek para el análisis.

  
