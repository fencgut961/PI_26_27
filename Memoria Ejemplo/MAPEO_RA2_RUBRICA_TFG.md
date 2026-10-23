# 📊 Mapeo: RA2 vs. Rúbrica de Moodle vs. Memoria TFG

> **Módulo Profesional:** Proyecto Intermodular / Proyecto Integrado (DAM / DAW / ASIR)  
> **Resultado de Aprendizaje:** RA2 - Diseña proyectos relacionados con las competencias expresadas en el título, desarrollando explícitamente las fases que lo componen.  
> **Fuente de Referencia:** [`2_Memoria.pdf`](https://github.com/fencgut961/PI_26_27/tree/main/Memoria%20Ejemplo)  

---

## 📋 Tabla Consolidada de Mapeo: RA2 y Criterios de Evaluación

| Criterio de Evaluación (RA2) | Requisito Nivel 3 de la Rúbrica (Excelente) | Apartados Mapeados del TFG | Evidencia y Justificación Técnica en la Memoria del TFG |
| :--- | :--- | :--- | :--- |
| **CE.a: Recopilación de información** | Recopila y sintetiza de forma exhaustiva la información técnica, de mercado y normativa (benchmarking, estado del arte, arquitectura existente, tecnologías competidoras, etc.). | Capítulo 1 (1.1, 1.2, 1.3) | Realiza un estudio comparativo del estado del arte entre la virtualización tradicional y la contenerización con Docker/Kubernetes, analizando la plataforma Portainer como solución gráfica de gestión. |
| **CE.b: Estudio de viabilidad técnica** | Evalúa rigurosamente la viabilidad técnica analizando conocimientos del equipo, compatibilidad del stack (lenguajes, frameworks, BD, topología de red, hipervisores, Cloud, etc.) y riesgos técnicos. | Capítulo 2 (2.1, 2.2, 2.4) | Justifica la viabilidad y compatibilidad del stack tecnológico (Docker Compose, Node.js, Go, Python) garantizando la paridad entre el entorno de desarrollo local y la nube. |
| **CE.c: Fases y plazos de ejecución** | Estructura detalladamente las fases (Sprints, hitos de desarrollo, fases de despliegue, pruebas UAT, etc.) estimando plazos de ejecución realistas. | Capítulo 2 (2.2.3); Capítulo 3 (3.1, 3.3) | Estructura el proyecto por fases operativas (desarrollo local, pipelines de CI/CD, aprovisionamiento de infraestructura IaC y despliegue) gestionado mediante Sprints y Gitflow. |
| **CE.d: Objetivos y alcance** | Define meticulosamente objetivos SMART funcionales y técnicos, delimitando de forma precisa los límites del proyecto (backlog inicial, matriz MoSCoW, entregables clave, etc.). | Capítulo 1 (1.4); Capítulo 2 (2.1, 2.5) | Delimita explícitamente el alcance técnico del sistema (arquitectura Monorepo integrada por 3 áreas) fijando objetivos medibles de alta disponibilidad y automatización de despliegue. |
| **CE.e: Actividades del proyecto** | Desglosa exhaustivamente todas las actividades del proyecto (WBS/EDT, tareas de desarrollo/configuración, diseño de BD, seguridad, pruebas, etc.) ordenadas de forma lógica. | Capítulo 2 (2.2); Capítulo 3 (3.1); Capítulo 4 (4.1, 4.3) | Desglosa secuencialmente las actividades de construcción del proyecto: diseño de imágenes multi-stage, configuración de pipelines en GitHub Actions, aprovisionamiento con Terraform y VPC. |
| **CE.f: Recursos materiales y personales** | Cuantifica y asigna con precisión perfiles profesionales (Dev, QA, SysAdmin, DevOps, etc.) y recursos materiales (hardware, licencias, entorno de pruebas, Cloud, etc.). | Capítulo 2 (2.1); Capítulo 4 (4.1, 4.4.3) | Planifica los recursos humanos (6 desarrolladores divididos en Frontend, Backend y DevOps) y materiales (cuotas AWS, nodos de cómputo `t3.small`, redes VPC e instancias EKS). |
| **CE.g: Necesidades de financiación y presupuesto** | Detalla minuciosamente el modelo presupuestario (costes de personal, licencias, servidores/Cloud, amortizaciones, fondo de contingencia, ROI, etc.) y el plan de financiación. | Capítulo 1 (1.4); Capítulo 4 (4.2.2, 4.4.3) | Analiza la viabilidad económica mediante el modelo OPEX de suscripción/consumo Cloud en AWS, aplicando estrategias FinOps de etiquetado global de recursos para control del gasto. |
| **CE.h: Documentación para el diseño** | Elabora una documentación de diseño profesional (SRS, diagramas UML, esquemas E/R, arquitectura de red, prototipos/mockups, etc.) con formato normalizado. | Capítulo 2 (2.1, 2.3, 2.5); Capítulo 4 (4.3) | Genera la documentación técnica de arquitectura: diagramas de bloques del Monorepo, topología de red VPC en AWS con subredes públicas/privadas y esquemas de variables de entorno. |
| **CE.i: Control y garantía de calidad** | Establece un plan de calidad integral (estándares ISO/IEC, pruebas funcionales/de estrés, matriz de riesgos, plan de contingencia, etc.) adaptado al proyecto. | Capítulo 3 (3.3, 3.4); Capítulo 4 (4.4.3) | Define controles de calidad estrictos: revisión de código mediante Pull Requests, escaneo de seguridad de contenedores con Trivy (DevSecOps) y alta disponibilidad con Managed Node Groups. |

---

## 📌 Resumen de Aplicación Pedagógica

La memoria de Jesús Carlos Mora Mesa (`2_Memoria_TFG_JesusMoraMesa.pdf`) satisface plenamente las exigencias del **RA2 (Diseño, Arquitectura y Viabilidad)** alcanzando el **Nivel 3 (Excelente / 10.0)** en la rúbrica de Moodle:

1. **Investigación y Viabilidad (CE.a, CE.b):** Analiza el estado del arte de la contenerización frente a la virtualización tradicional y justifica la viabilidad del stack tecnológico elegido.
2. **Planificación, Alcance y Actividades (CE.c, CE.d, CE.e):** Estructura el trabajo por fases claras (desarrollo, CI/CD, IaC, Cloud), fijando un alcance acotado en arquitectura Monorepo.
3. **Recursos, Presupuesto y Documentación (CE.f, CE.g, CE.h):** Cuantifica los perfiles del equipo, calcula los costes operativos (*OPEX/FinOps*) en AWS y aporta diagramas completos de red y arquitectura.
4. **Garantía de Calidad (CE.i):** Garantiza la calidad técnica mediante validación automatizada de código, análisis de seguridad DevSecOps y estrategias de alta disponibilidad.
