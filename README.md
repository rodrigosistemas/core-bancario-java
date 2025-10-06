# 🏦 Core Banking System en Java

Réplica de un sistema bancario básico desarrollada en **Java 21**, aplicando principios sólidos de **Programación Orientada a Objetos (POO)**.  
El proyecto simula las operaciones esenciales de un **core bancario**: gestión de cuentas, transacciones (depósitos, retiros, transferencias) y generación de reportes detallados.

---

## 🧩 Descripción del Proyecto

El objetivo de este proyecto es **modelar la lógica de un banco real** en un entorno controlado, aplicando buenas prácticas de diseño y estructura de clases en Java.  
Está pensado como un proyecto educativo y demostrativo para estudiantes o desarrolladores que deseen entender cómo funcionan los sistemas financieros desde el punto de vista técnico y lógico.

**Características principales:**
- Creación y gestión de diferentes tipos de cuentas (corriente, ahorro, etc.).
- Registro de clientes y vinculación con cuentas.
- Transacciones básicas: depósitos, retiros y transferencias entre cuentas.
- Generación de reportes detallados de movimientos y saldos.
- Validaciones de negocio (saldos insuficientes, límites de operación, etc.).
- Arquitectura modular basada en principios SOLID.

---

## ⚙️ Tecnologías Utilizadas

- **Lenguaje:** Java 21  
- **Paradigma:** Programación Orientada a Objetos (POO)  
- **IDE sugerido:** IntelliJ IDEA / Eclipse / VS Code  
- **Herramientas opcionales:**  
  - JUnit (para pruebas unitarias)  
  - Maven o Gradle (para gestión de dependencias)

---

## 🏗️ Arquitectura del Sistema

El sistema está estructurado bajo un enfoque modular, separando la lógica por capas:
src/
├─ models/ # Clases principales (Cuenta, Cliente, Transacción)
├─ services/ # Lógica de negocio (manejo de operaciones bancarias)
├─ reports/ # Generación de reportes y resúmenes
├─ utils/ # Utilidades generales y validaciones
└─ Main.java # Punto de entrada del sistema

---

## 💵 Funcionalidades Principales

| Módulo | Descripción |
|--------|--------------|
| **Gestión de cuentas** | Creación, búsqueda y administración de cuentas bancarias. |
| **Operaciones financieras** | Depósitos, retiros y transferencias con validación de saldo. |
| **Reportes** | Generación de informes de transacciones y saldos finales. |
| **Clientes** | Registro y vinculación de clientes con múltiples cuentas. |

---
