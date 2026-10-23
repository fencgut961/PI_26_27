# 📊 Mapeo: RA3 vs. Rúbrica de Moodle vs. Memoria TFG

> **Módulo Profesional:** Proyecto Intermodular / Proyecto Integrado (DAM / DAW / ASIR)  
> **Resultado de Aprendizaje:** RA3 — Planifica la ejecución del proyecto, determinando el plan de intervención y la documentación asociada.  
> **Fuente de Referencia:** [`2_Memoria.pdf`](https://github.com/fencgut961/PI_26_27/tree/main/Memoria%20Ejemplo)  

---

## 📋 Mapeo de Criterios de Evaluación (RA3)

| Criterio de Evaluación (RA3) | Requisito Nivel 3 de la Rúbrica (Excelente - 3 pts) | Apartados Mapeados del TFG | Evidencia y Justificación Técnica en el TFG |
| :--- | :--- | :--- | :--- |
| **CE.a: Secuenciación de tareas** | Secuencia minuciosamente las tareas identificando dependencias, hitos y camino crítico (*diagramas Gantt/PERT, sprints/Scrum, WBS, etc.*). | Capítulo 2 (2.2, 2.2.3); Capítulo 3 (3.1, 3.3) | Secuencia el desarrollo local con Docker Compose, automatiza flujos recurrentes con scripts (`make.bat`), y estructura la entrega mediante pipelines de CI/CD en GitHub Actions y estrategia Gitflow. |
| **CE.b: Recursos y logística por tarea** | Detalla los recursos materiales/técnicos y la logística de cada tarea (*entornos de desarrollo, servidores, licencias, despliegue, redes, etc.*). | Capítulo 2 (2.2, 2.4); Capítulo 4 (4.1, 4.3) | Planifica los entornos aislados con Docker, el aprovisionamiento automatizado con Terraform y la logística de red en AWS (VPC, subredes públicas/privadas y clúster EKS). |
| **CE.c: Permisos y autorizaciones** | Identifica y gestiona con precisión todos los permisos y licencias (*RGPD/LOPDGDD, dominios, certificados SSL/TLS, licencias de software, permisos de red/firewall, etc.*). | Capítulo 2 (2.3); Capítulo 3 (3.2); Capítulo 4 (4.2, 4.4.1) | Gestiona credenciales y permisos de acceso mediante variables de entorno (`.env`), GitHub Secrets cifrados, políticas IAM de mínimo privilegio en AWS y credenciales de acceso al clúster EKS. |
| **CE.d: Procedimientos de ejecución** | Define procedimientos de ejecución normalizados (*flujos Gitflow/CI-CD, guías de estilo, protocolos de despliegue, scripts de instalación, etc.*). | Capítulo 2 (2.2.3); Capítulo 3 (3.1, 3.3, 3.4) | Protocoliza los procedimientos de ejecución con reglas de Linting, ejecución de tests automatizados, integración mediante Pull Requests y escaneo de seguridad con Trivy (DevSecOps). |
| **CE.e: Riesgos, prevención y medios** | Diseña un plan de gestión de riesgos y contingencias exhaustivo (*matriz de riesgos, copias de seguridad/backups, seguridad lógica/física, PRL, etc.*). | Capítulo 2 (2.3); Capítulo 3 (3.2, 3.4); Capítulo 4 (4.4.3) | Previene fuga de secretos mediante `.gitignore`, mitiga fallos en construcción cancelando pipelines con errores y garantiza alta disponibilidad con grupos de nodos administrados en AWS. |
| **CE.f: Asignación temporal de recursos** | Nivel y optimiza temporalmente la carga de trabajo de recursos humanos y materiales (*cuadrante de dedicación, disponibilidad de perfiles, uso de infraestructura Cloud, etc.*). | Capítulo 2 (2.1); Capítulo 3 (3.3); Capítulo 4 (4.4.3) | Distribuye temporalmente las tareas entre perfiles (Frontend, Backend, DevOps), gestiona la dedicación en ramas/Sprints y optimiza el escalado dinámico de nodos de cómputo Cloud. |
| **CE.g: Valoración económica de la ejecución** | Realiza un desglose económico riguroso de la ejecución (*costes hora/hombre, consumo de infraestructura/Cloud, licencias en producción, imprevistos, etc.*). | Capítulo 1 (1.4); Capítulo 4 (4.2.2, 4.4.3) | Controla la ejecución presupuestaria bajo modelo OPEX en AWS, implementando etiquetado global de recursos (*FinOps*) para auditoría de costes e instancias eficientes `t3.small`. |
| **CE.h: Documentación para la ejecución** | Genera una documentación de ejecución completa y profesional (*manuales de instalación/despliegue, documentación de API/código, cuadernos de bitácora, guías de usuario, etc.*). | Capítulo 2 (2.5); Capítulo 3 (3.1, 3.4); Capítulo 4 (4.5) | Elabora la documentación técnica de ejecución: archivos de especificación (`docker-compose.yml`, `main.tf`), manifiestos de despliegue en Kubernetes y guía de verificación final. |

---

## 📌 Resumen de Aplicación Pedagógica
La memoria de Jesús Carlos Mora Mesa satisface de forma completa los **8 Criterios de Evaluación del RA3**, alcanzando el **Nivel 3 (Excelente)** en la rúbrica de Moodle al combinar la planificación rigurosa con la automatización práctica del despliegue y la gestión de riesgos.
