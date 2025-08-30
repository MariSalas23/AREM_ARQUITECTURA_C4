# 🛠️ Taller 3: Arquitectura Actual del Sistema con el Modelo C4

## 🎯 Objetivo

Representar la arquitectura actual del sistema del cliente utilizando las vistas C1 (Contexto) y C2 (Contenedores) del modelo C4, para entender cómo interactúan los actores con el sistema y cómo se distribuyen los componentes principales.

---

## 🚚 Caso base de referencia: RedExpress (Plataforma de Logística)

RedExpress es una empresa nacional de logística y envíos que ha digitalizado la mayoría de sus operaciones. Ofrece una app móvil para usuarios finales, un sistema de gestión de rutas para operadores logísticos, y un dashboard de seguimiento para clientes corporativos. Su arquitectura actual integra servicios en la nube con bases de datos distribuidas, motores de cálculo de rutas y APIs de terceros para notificaciones. Comprender la estructura de sus sistemas y cómo los actores interactúan con ellos es clave para mejorar la eficiencia operativa y escalar a nuevas regiones.

**Contexto:**
- RedExpress es una empresa nacional de logística y transporte que ofrece rastreo en tiempo real de paquetes desde una app móvil y un portal web.
- Cuenta con centros de distribución físicos, sistemas de monitoreo, y servicios de notificación a usuarios y mensajeros.

**Elementos esperados:**

- **C1 (Vista de Contexto):**
  - Actores: Usuario final, Mensajero, Operador logístico
  - Sistemas: App de cliente, Sistema central de logística, API de notificaciones, Web para operadores

- **C2 (Vista de Contenedores):**
  - Contenedores internos: Módulo de gestión de paquetes, Seguimiento GPS, Motor de rutas, Sistema de alertas
  - Infraestructura: Balanceador de carga, base de datos distribuida, integración con proveedores de geolocalización

---

## 🧪 Parte 1: Trabajo en Clase

Durante la clase se espera que el equipo:

- Modele la **vista de contexto (C1)** de RedExpress usando draw.io o Astah UML.
- Bocete la **vista de contenedores (C2)** con los módulos internos y sistemas conectados.
- Identifique puntos críticos de comunicación e interacción.
- Reciba retroalimentación del docente y registre observaciones.

---

## 🧠 Parte 2: Aplicación al Cliente Real

Después de la clase, el equipo debe:

- Modelar las vistas C1 y C2 aplicadas al sistema del cliente real.
- Documentar componentes clave, flujos, roles y debilidades actuales.
- Redactar un informe técnico explicando la estructura actual.
- Investigar ejemplos reales de arquitecturas C4 en el sector del cliente.

---

## 📁 Estructura esperada del repositorio

```
taller-03-arquitectura-c4/
├── README.md
├── clase/
│   ├── c1-contexto-borrador.drawio
│   ├── c2-contenedores-borrador.drawio
│   └── notas.md
├── entrega/
│   ├── c1-contexto-final.drawio
│   ├── c2-contenedores-final.drawio
│   ├── informe.md
│   └── referencias.md
```

---

## 📤 Entregables

- Diagrama C1 y C2 del sistema real del cliente
- Informe técnico explicativo (`informe.md`)
- Referencias técnicas e investigación complementaria (`referencias.md`)

---

## 📊 Rúbrica de Evaluación

| Criterio                            | Excelente (5)                                                         | Aceptable (3) / Insuficiente (1–2)                       |
|-------------------------------------|------------------------------------------------------------------------|-----------------------------------------------------------|
| Vista de contexto (C1)              | Muestra claramente actores, límites del sistema y relaciones externas | Faltan actores o relaciones clave                        |
| Vista de contenedores (C2)          | Módulos definidos, conectados y etiquetados claramente                 | Diagramas confusos o con contenedores mal estructurados  |
| Aplicación al cliente real          | Adaptación clara con explicación de decisiones                        | Copiado o genérico sin relación al cliente               |
| Documentación e investigación       | Informe estructurado y referencias relevantes                         | Informe superficial o sin sustento técnico               |

---

## ✅ Licencia

Este taller hace parte del curso de Arquitectura Empresarial - Universidad de La Sabana. Uso académico bajo licencia MIT.
