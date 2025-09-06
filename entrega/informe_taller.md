# 📄 Informe Técnico del Taller

## 🔖 ARQUITECTURA C4
_Taller C4_

## 👥 Integrantes del equipo
- Juan David Cetina Gómez (juancego@unisabana.edu.co)
- Ana Lucía Quintero Vargas (anaquiva@unisabana.edu.co)
- Mariana Salas Gutiérrez (marianasalgu@unisabana.edu.co)

## 🧠 Descripción general del trabajo
Describa brevemente el objetivo del taller y cómo se desarrolló la actividad.

## 🔧 Proceso de desarrollo
Explique cómo realizaron el trabajo: qué decisiones tomaron, qué herramientas utilizaron, qué aspectos modelaron primero y cómo lo fueron ajustando.

## 🧩 Análisis del modelo propuesto
Incluya un análisis sobre:
- Cómo se estructura el modelo entregado
- Cómo representa las necesidades del cliente
- Qué supuestos se tomaron

## 📈 Diagrama final entregado
> (Inserte aquí una imagen o enlace al modelo-final.drawio / .asta / PDF)

## 📋 Tabla de actores, entidades o componentes (si aplica)

| Nombre del elemento | Tipo | Descripción | Responsable |
|---------------------|------|-------------|-------------|
| Cliente        | Actor (Person) | Persona o empresa (ej. bancos, entidades de crédito) que consulta información y solicita scores. | Cliente |
| Operador        | Actor (Person) | Personal interno encargado de crear clientes, gestionar usuarios y administrar la plataforma. | Zajana |
| Fuente        | Componente (External Software System) | Sistemas externos que proveen información utilizada por Zajana (ej. registros, bases de datos). | Externo |
| Página web        | Componente (Software System) | Interfaz que permite al cliente acceder al servicio, realizar consultas y recibir respuestas. | Zajana |
| Portal de operaciones        | Componente (Software System) | Plataforma interna que usan los operadores para crear y administrar clientes y usuarios. | Zajana |
| API de consulta cliente        | Componente (Software System) | SPunto de entrada para solicitudes de clientes hacia Zajana (consultas de scores, datos). | Zajana |
| API de fuentes       | Componente (Software System) | Conector entre Zajana y los sistemas externos (Fuentes) para obtener datos necesarios. | Zajana |
| API de facturación       | Componente (Software System) | Registra el consumo de consultas y operaciones hechas en Zajana, base para facturación a clientes. | Zajana |
| API de notificaciones | Componente (External Software System) | Servicio que envía notificaciones por correo a clientes, informando sobre la disponibilidad de scores, cambios en el estado de consultas o similares. | Externo |

## 🔍 Investigación complementaria
### Tema investigado:
Comparación TOGAF vs C4

### Resumen:
Describa en 2–3 párrafos lo investigado, citando fuentes cuando sea necesario. Incluya cómo se relaciona con el taller.

## 📚 Referencias
- [1] Apellido, Nombre. *Título*. Año. URL o DOI.
- [2] Fuente oficial BPMN: https://www.omg.org/spec/BPMN/

---

_Este documento hace parte de la entrega del taller C4 del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
