# 📊 Mapeo: RA1 vs. Rúbrica de Moodle vs. Memoria TFG

> **Módulo Profesional:** Proyecto Intermodular / Proyecto Integrado (DAM / DAW / ASIR)  
> **Resultado de Aprendizaje:** RA1 — Estudio del entorno productivo empresarial y demandas del mercado  
> **Fuente de Referencia:** [`2_Memoria.pdf`](https://github.com/fencgut961/PI_26_27/tree/main/Memoria%20Ejemplo)  

---

## 📋 Tabla de Correspondencia Completa

| Criterio de Evaluación (RA1) | Requisito Nivel 3 de la Rúbrica (Excelente - 3 pts) | Apartados Mapeados del TFG | Evidencia y Justificación Técnica en la Memoria |
| :--- | :--- | :--- | :--- |
| **CE.a: Clasificación de empresas** | Clasifica rigurosamente empresas del sector (software, web, microservicios, consultoría, sistemas, ciberseguridad, MSP, etc.) según modelo (B2B, B2C, SaaS, IaaS, etc.). | Capítulo 1 (1.1, 1.4); Capítulo 2 (2.1) | Analiza la transformación del sector TIC desde la virtualización tradicional a la contenerización Cloud-Native, evaluando modelos IaaS/PaaS en la nube y arquitecturas de microservicios. |
| **CE.b: Organigrama y departamentos** | Identifica con precisión la estructura organizativa y los roles del equipo (Dev, Frontend/Backend, SysAdmin, DevOps, SecOps, DBA, etc.) y sus relaciones. | Capítulo 2 (2.1); Capítulo 3 (3.3) | Describe la organización real de un equipo multidisciplinar de 6 integrantes (2 Frontend, 3 Backend y 1 SysAdmin/DevOps) coordinados bajo arquitectura Monorepo y flujo Gitflow. |
| **CE.c: Identificación de necesidades** | Prioriza necesidades del mercado (apps móviles, plataformas web, migración Cloud, alta disponibilidad, seguridad en redes, automatización, etc.) con criterio técnico. | Capítulo 1 (1.1, 1.2, 1.4) | Justifica técnicamente la demanda empresarial de orquestación con Kubernetes, alta disponibilidad, aislamiento de servicios en contenedores y control de accesos RBAC. |
| **CE.d: Valoración de oportunidades** | DAFO exhaustivo detectando nichos emergentes (PWA, SaaS, IoT, virtualización, infraestructura híbrida, cumplimiento ENS/RGPD, etc.) y barreras reales. | Capítulo 1 (1.4); Capítulo 4 (4.4.3) | Identifica la oportunidad de negocio al migrar arquitecturas monolíticas a microservicios orquestados y optimizar los costes de cómputo Cloud (estrategia FinOps en AWS). |
| **CE.e: Selección del tipo de proyecto** | Justifica minuciosamente el tipo de proyecto (desarrollo de software, implantación/despliegue de infraestructura, solución integrada, etc.). | Capítulo 1 (1.3); Capítulo 2 (2.1, 2.5) | Argumenta la idoneidad de un proyecto de infraestructura Cloud-Native e integración continua (Monorepo + Docker + Kubernetes + gestión visual con Portainer). |
| **CE.f: Características específicas** | Define completamente el valor añadido, la viabilidad técnica/económica y el stack tecnológico (lenguajes, frameworks, BD, topología de red, hipervisores, Cloud, etc.). | Capítulo 2 (2.2, 2.4); Capítulo 4 (4.1, 4.3, 4.4) | Especifica completamente el stack tecnológico: imágenes multi-stage en Docker, aprovisionamiento con Terraform, VPC con subredes públicas/privadas y clúster Amazon EKS. |
| **CE.g: Marco legal, fiscal y PRL** | Detalla exhaustivamente RETA, Hacienda, IS, cotizaciones, plan de PRL y leyes específicas (RGPD/LOPDGDD, LSSI-CE, Esquema Nacional de Seguridad/ENS, etc.). | Capítulo 2 (2.3); Capítulo 3 (3.2, 3.4) | Aplica normativas de ciberseguridad y protección de datos mediante aislamiento de credenciales en `.env` y `.gitignore`, GitHub Secrets y escaneo proactivo con Trivy (DevSecOps). |
| **CE.h: Ayudas y financiación** | Especifica convocatorias y programas reales (Kit Digital, ICO, FEDER, deducciones I+D+i, ENISA, etc.) aplicables al proyecto. | Capítulo 1 (1.4); Capítulo 4 (4.2.2, 4.4.3) | Aborda la viabilidad económica mediante el control del gasto operativo (OPEX) en AWS, etiquetado global de recursos para auditoría y selección de instancias eficientes `t3.small`. |
| **CE.i: Guión de trabajo de la memoria** | Planificación clara de la memoria estructurada por fases (Sprints de desarrollo, fases de despliegue/administración, etc.) con entregables definidos. | Capítulo 2 (2.2.3); Capítulo 3 (3.1, 3.3) | Establece la planificación ágil del proyecto mediante scripts de automatización (`make.bat`), pipelines de integración continua en GitHub Actions y estrategia de ramas por Sprints. |

---
