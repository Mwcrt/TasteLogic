# TasteLogic

## Descripción
TasteLogic es un sistema de gestión de restaurantes con Inteligencia Artificial.  
Permite a los clientes hacer **reservas y pedidos online**, y a los administradores gestionar **mesas, menú, pedidos y estadísticas**.  
Además, integra un módulo de IA que predice la demanda de alimentos según horarios y temporadas.

## Tecnologías
- **Frontend:** React  
- **Backend:** Node.js + Express  
- **Base de Datos:** PostgreSQL  
- **IA/Machine Learning:** Python (Scikit-learn / TensorFlow)  
- **Microservicio de Predicción:** FastAPI  
- **Infraestructura:** GitHub (control de versiones)  

## Estructura de Carpetas

-TasteLogic/
-frontend/ # Interfaz web (clientes y dashboard)
-backend/ # API REST (Node.js + Express)
-ia/ # Microservicio de predicción (Python + FastAPI)
-docs/ # Documentación y diagramas
-README.md # Descripción del proyecto
-.gitignore # Archivos a ignorar en git

## Roles del Equipo
- **Miguel Acosta** → Fullstack + Coordinador  
- **Dacarlos Lora** → Frontend + QA  

## Requerimientos Funcionales

### Cliente
- Registrarse / iniciar sesión.  
- Ver menú actualizado.  
- Hacer pedidos y reservas en línea.  
- Consultar estado de pedidos/reservas.  

### Administrador
- Gestionar mesas, menús y pedidos.  
- Acceder a estadísticas de ventas.  
- Consultar historial de clientes y predicciones.  

### Inteligencia Artificial
- Analizar datos históricos de ventas.  
- Predecir demanda de alimentos.  
- Recomendar cantidades para inventario.  
