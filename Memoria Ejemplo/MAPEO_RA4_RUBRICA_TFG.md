# 📊 Mapeo: RA4 vs. Rúbrica de Moodle vs. Memoria TFG

> **Módulo Profesional:** Proyecto Intermodular / Proyecto Integrado (DAM / DAW / ASIR)  
> **Resultado de Aprendizaje:** RA4 — Define los procedimientos para el seguimiento y control en la ejecución del proyecto, justificando la selección de variables e instrumentos empleados.  
> **Fuente de Referencia:** `2_Memoria_TFG_JesusMoraMesa.pdf`  
> **Criterio de Evaluación de la Rúbrica:** Nivel 3 (Excelente — 3 Puntos / Máximo 21 Puntos)

---

### 📋 Tabla de Mapeo de Trazabilidad (RA4)

| Criterio de Evaluación (RA4) | Requisito Nivel 3 de la Rúbrica (Excelente) | Apartados Mapeados del TFG | Evidencia y Justificación Técnica en el TFG |
| :--- | :--- | :--- | :--- |
| **CE.a: Evaluación de actividades e intervenciones** | Establece un sistema riguroso de seguimiento continuo (*reuniones de seguimiento, revisiones de Sprint/Sprint Review, hitos de control, informes de progreso, etc.*). | Capítulo 3 (3.1, 3.3) | Control de progreso mediante ejecución automatizada de pipelines de CI en cada Pull Request y revisiones de código entre pares antes de la integración en la rama principal (`main`). |
| **CE.b: Indicadores de calidad** | Establece KPIs y métricas de calidad formales (*estándares ISO/IEC 25010, cobertura de pruebas, rendimiento, tiempo de respuesta, uptime, MTTR, etc.*). | Capítulo 3 (3.3, 3.4); Capítulo 4 (4.4.3) | Aplica métricas de calidad formales: reglas de Linting, escaneo de vulnerabilidades de imágenes y dependencias con Trivy (DevSecOps) y alta disponibilidad con auto-healing en AWS EKS. |
| **CE.c: Registro y evaluación de incidencias** | Diseña un sistema integral de gestión de incidencias (*herramientas de issue tracking como Jira/GitHub Issues, clasificación por prioridad/severidad, SLA de atención, etc.*). | Capítulo 3 (3.1, 3.3); Capítulo 4 (4.4.3) | Trazabilidad y registro de incidencias en la integración mediante GitHub Issues y logs de ejecuciones fallidas en GitHub Actions, clasificando errores de compilación, test o seguridad. |
| **CE.d: Solución de incidencias** | Protocoliza detalladamente el ciclo de vida de resolución (*asignación de responsables, parches/hotfixes, pruebas de regresión, análisis causa raíz/post-mortem, etc.*). | Capítulo 3 (3.1, 3.3, 3.4); Capítulo 4 (4.4.3) | Protocolo de resolución mediante ramas de corrección rápida (`hotfix`/`bugfix`), validación automática por reejecución de pipelines de CI/CD y redespliegue sin interrupción del servicio. |
| **CE.e: Gestión y registro de cambios** | Define un sistema riguroso de control de cambios (*solicitud de cambio/CR, análisis de impacto en WBS y presupuesto, control de versiones, trazabilidad, etc.*). | Capítulo 2 (2.1); Capítulo 3 (3.2, 3.3) | Control de cambios centralizado mediante Git/GitHub bajo arquitectura Monorepo, trazabilidad histórica de commits, Pull Requests documentados y control de variables con GitHub Secrets. |
| **CE.f: Evaluación de usuarios y documentos** | Implementa un plan completo de validación por el usuario (*pruebas de aceptación/UAT, encuestas de satisfacción, formularios de feedback, actas de conformidad, etc.*). | Capítulo 1 (1.3); Capítulo 2 (2.5); Capítulo 4 (4.5) | Validación funcional de la infraestructura mediante la interfaz gráfica Portainer y paneles de control visuales, permitiendo al usuario/administrador comprobar la salud de los microservicios. |
| **CE.g: Cumplimiento del pliego de condiciones** | Diseña un sistema de auditoría y trazabilidad riguroso (*matriz de trazabilidad de requisitos, verificación de pliego técnico/administrativo, auditorías de entregables, etc.*). | Capítulo 2 (2.5); Capítulo 4 (4.1, 4.3, 4.4, 4.5) | Auditoría y verificación final del cumplimiento de los requisitos del proyecto (despliegue en AWS EKS, aislamiento de red VPC con subredes públicas/privadas y alta disponibilidad). |

---

### 📌 Resumen de Cobertura Pedagógica del RA4

1. **Control de Calidad y DevSecOps (CE.a, CE.b):** Se garantiza mediante la combinación de integración continua (GitHub Actions), análisis estático de código y escaneo de vulnerabilidades con Trivy.
2. **Gestión de Incidencias y Cambios (CE.c, CE.d, CE.e):** Se canaliza mediante la metodología Gitflow (ramas `feature` y `hotfix`), auditoría de Pull Requests y trazabilidad completa de commits en un repositorio único (Monorepo).
3. **Evaluación de Usuarios y Verificación del Pliego (CE.f, CE.g):** Se valida a través del panel de administración de Portainer y la verificación en vivo de la infraestructura en la nube de AWS EKS.
