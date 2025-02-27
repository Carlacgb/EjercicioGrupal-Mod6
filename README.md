

# ABPro: Implementación Completa de PWA en la Web del Hospital

## Descripción: 
Se implementa una PWA completa para la web del hospital. Se hace uso de ReactJS y aprovecha al máximo las características de PWA, incluyendo almacenamiento web avanzado, estrategias de Service Worker, y análisis de rendimiento y accesibilidad con Lighthouse. A su vez, se integrarán nuevas funcionalidades de uso de periféricos del sistema operativo, accesos a APIs externas, y una estrategia avanzada de despliegue en un servidor.


## 1. Creación del Manifiesto y Configuración Inicial
Se crear el archivo manifes.json dentro de la carpeta public.

## 2. Integración de Service Worker para Gestión Avanzada de Caché
Se implementa el Service Worker en el archivo sw.js

## 3. Acceso a Periféricos del Sistema Operativo
Se crea componenten camara.jsx y este se implementa en el componente Cita.jsx, donde tambien se implementa la geolocalización.


## 4. Consumo de API Externa para Datos Médicos
Se implementa el consumo de la api externa en componenten EquipoMedico y el archivo api-externa.js


## 5. Pruebas de Rendimiento y Optimización con Lighthouse
Se hacen pruebas de rendmiento Lighthouse y da como resultado:
- Perfomance: 59
- Accesibilidad: 98
- Mejores practicas: 93 
- SEO: 83




