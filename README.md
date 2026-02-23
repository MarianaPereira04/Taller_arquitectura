# Taller Práctico  
## Análisis, Evaluación y Propuesta de Refactorización de Arquitectura Monolítica  

Proyecto: Sistema de Encuestas "Espagueti"  
Asignatura: Arquitectura de Software  

---

## 👥 Integrantes del Grupo

- Juan José Torrejano Rojas  
  jjtorrejano-2032b@corhuila.edu.co  

- Jhon Edinson Marín Tapias  
  jemarin-2032b@corhuila.edu.co  

- Karina Cantillo Plaza  
  kcantillo-2032b@corhuila.edu.co  

- Danay Mariana Pereira Ospina  
  dmpereira-2032b@corhuila.edu.co  

---

## 📅 Fecha de Entrega
23 de febrero de 2026

---

# 📌 Resumen Ejecutivo

El presente taller tuvo como objetivo analizar y evaluar la arquitectura monolítica del sistema “Espagueti de Encuestas”, desarrollado con Spring Boot, Angular y PostgreSQL, con el fin de identificar debilidades estructurales y proponer una refactorización arquitectónica fundamentada en principios modernos de ingeniería de software.

Durante la Fase 1 se realizó el montaje y validación del entorno mediante Docker Compose, garantizando el correcto funcionamiento del frontend, backend y base de datos en un entorno controlado y reproducible.

En la Fase 2 se efectuó un análisis técnico del código fuente, identificando múltiples anti-patrones clasificados en categorías como Seguridad, Arquitectura, SOLID, Clean Code, Manejo de Errores, Tipado y Rendimiento. Se detectaron problemáticas relevantes como inyección SQL, credenciales hardcodeadas, ausencia de separación clara por capas, alta dependencia entre componentes y deficiencias en el control de errores.

En la Fase 3 se planteó una propuesta de mejora estructural que incluye:

  - Aplicación de patrones de diseño como Layered Architecture, Repository Pattern, Service Layer, DTO y manejo global de excepciones.

  - Implementación de mejoras de Clean Code con ejemplos concretos sobre el código original.

  - Rediseño arquitectónico hacia una solución basada en microservicios, con delimitación de bounded contexts, uso de API Gateway y componentes transversales de infraestructura.

  - Elaboración de diagramas C4 (niveles 1 y 2) para representar el estado actual y la arquitectura propuesta.

  - Documentación de decisiones clave mediante ADR (Architecture Decision Records).

Como resultado, la propuesta mejora significativamente la mantenibilidad, escalabilidad, seguridad y resiliencia del sistema, alineándolo con principios SOLID, Clean Code y prácticas modernas de arquitectura distribuida.



