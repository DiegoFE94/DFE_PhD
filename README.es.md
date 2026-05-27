# Análisis computacional del microbioma humano como fuente de biomarcadores clínicos

**Computational Analysis of the Human Microbiome as a Source of Clinical Biomarkers**

[🇬🇧 English version](README.md)

> **Tesis Doctoral** · [Universidade da Coruña (UDC)](https://www.udc.es) · Octubre 2025  
> Programa de Doctorado en Tecnologías de la Información y las Comunicaciones  

---

<p align="center">
  <img width="90%" src="img/results/GA.png" alt="Resumen gráfico">
</p>

---

## Resumen

El estudio del microbioma humano ha avanzado de forma acelerada gracias a la caída del coste de la secuenciación y a la disponibilidad de grandes repositorios públicos. Este progreso ha confirmado asociaciones entre perfiles microbianos y múltiples patologías, pero también ha puesto de relieve retos persistentes: la naturaleza composicional de los datos procedentes del microbioma, el ruido técnico y la variabilidad interindividual. En este contexto, los enfoques de *Machine Learning* brindan una ventaja sustancial para detectar señales complejas con posible significado biológico y estimar con rigor el valor predictivo de los perfiles microbianos en entornos clínicos.

Esta Tesis Doctoral responde a dichos desafíos adoptando un enfoque computacional estandarizado y reproducible, desde el procesado de lecturas 16S rRNA hasta la aplicación de modelos de *Machine Learning* para el análisis de estos datos. Bajo este enfoque computacional, se identifican patrones microbianos que distinguen de forma consistente distintos estados clínicos en enfermedades metabólicas (síndrome metabólico y diabetes tipo 2); se obtienen modelos predictivos para diabetes tipo 1 sustentados en un conjunto acotado de taxones con alta relevancia biológica; y, en vaginosis bacteriana, se propone un subtipado alternativo del microbioma vaginal que añade información complementaria no recogida por otros métodos de estratificación, y puede apoyar la predicción de la respuesta terapéutica. Estos resultados se presentan en un compendio de tres publicaciones científicas.

En conjunto, esta Tesis Doctoral ofrece evidencia de que los perfiles microbianos permiten la caracterización de estados clínicos y ofrece un marco metodológico reproducible que facilita su evaluación comparativa entre cohortes.

---

## Principales Aportaciones

Esta tesis se estructura como un **compendio de tres publicaciones**, abordando cada una un escenario clínico diferente:

### 📄 Publicación I — Síndrome Metabólico y Diabetes Tipo 2
> *Fecal microbiome analysis in patients with metabolic syndrome and type 2 diabetes*  
> Sinisterra-Loaiza L.I., **Fernández-Edreira D.**, Liñares-Blanco J., Cepeda A., Cardelle-Cobas A., Fernandez-Lozano C.  
> **PeerJ**, 13, e19108 (2025)

A partir de una cohorte de 79 pacientes con riesgo de sufrir DT2, se demuestra que, a nivel de filo, el ratio Bacteroidetes/Firmicutes varía a lo largo de la progresión del síndrome metabólico (SM) y de la DT2. A niveles más específicos, se revela que taxones de los géneros *Blautia*, *Tyzzerella* y *Dorea* están enriquecidos en el perfil microbiano de pacientes con SM. Por otro lado, el perfil microbiano de pacientes con DT2 se caracteriza por una mayor abundancia de *Dorea*, *Prevotella* y *Dialister*.

---

### 📄 Publicación II — Diabetes Tipo 1 (pediátrica)
> *Machine Learning analysis of the human infant gut microbiome identifies influential species in type 1 diabetes*  
> **Fernández-Edreira D.**, Liñares-Blanco J., Fernandez-Lozano C.  
> **Expert Systems with Applications**, 185, 115648 (2021)

Se obtiene una firma metagenómica compuesta por 25 especies capaz de identificar a pacientes diagnosticados con DT1. Destacan, por su importancia, taxones de los géneros *Bacteroides* y *Prevotella* como potenciales biomarcadores. Un modelo de Random Forest entrenado con dichas especies tiene un poder predictivo capaz de clasificar a los pacientes en sanos, seroconvertidos y afectados por DT1.

---

### 📄 Publicación III — Vaginosis Bacteriana
> *VIBES: A consensus subtyping of the vaginal microbiota reveals novel classification criteria*  
> **Fernández-Edreira D.**, Liñares-Blanco J., Vázquez-Ucha P., Fernandez-Lozano C., et al.  
> **Computational and Structural Biotechnology Journal**, 23, 148–156 (2024)

Se propone un nuevo enfoque de estratificación de pacientes con vaginosis bacteriana (VB) a partir de datos metagenómicos. Este subtipado presenta información complementaria respecto a otros métodos del estado del arte y, en el contexto de VB, mejora la predicción de la respuesta al tratamiento con metronidazol.

---

## Contenido del Repositorio

Este repositorio contiene el **código fuente LaTeX** completo de la tesis doctoral, compilado con una plantilla personalizada de la UDC.

```
.
├── udc-phd-template.tex    # Punto de entrada del documento principal
├── cleanthesis.sty         # Paquete de estilo de la tesis
├── bibliography.bib        # Referencias bibliográficas (BibTeX)
├── front/                  # Páginas preliminares (resumen, agradecimientos, etc.)
├── body/                   # Capítulos de la tesis
│   ├── 01_introduccion.tex
│   ├── 02_objetivos.tex
│   ├── 03_metodologia.tex
│   ├── 04_discusion.tex
│   ├── 05_conclusiones.tex
│   └── 06_futuro.tex
├── back/                   # Páginas finales
└── img/                    # Figuras e imágenes
```

---

## Metadatos de la Tesis

| Campo | Detalles |
|---|---|
| **Autor** | Diego Fernández Edreira |
| **Título** | Análisis computacional del microbioma humano como fuente de biomarcadores clínicos |
| **Universidad** | Universidade da Coruña (UDC) |
| **Programa de doctorado** | Tecnologías de la Información y las Comunicaciones (TIC) |
| **Directores** | Dr. Carlos Fernández Lozano · Dr. Jose Liñares Blanco |
| **Fecha de defensa** | 27 de marzo de 2026 |
| **Grupo de investigación** | [MALL-Lab](https://mall-lab.github.io/) |

---

## Cómo Citar

```bibtex
@phdthesis{fernandez-edreira2025,
  author  = {Fern{\'a}ndez-Edreira, Diego},
  title   = {An{\'a}lisis computacional del microbioma humano como fuente
             de biomarcadores cl{\'i}nicos},
  school  = {Universidade da Coru{\~n}a},
  year    = {2025},
  url     = {https://ruc.udc.es/entities/publication/a66198bc-faf3-4340-84bb-196d837556da}
}
```

---

## Enlaces

| Recurso | URL |
|---|---|
| 📚 Repositorio Institucional UDC | [ruc.udc.es](https://ruc.udc.es/entities/publication/a66198bc-faf3-4340-84bb-196d837556da) |
| 🗄️ TESEO (Base de datos nacional de tesis) | [aplicaciones.ciencia.gob.es/teseo](https://aplicaciones.ciencia.gob.es/teseo/#/tesis/325807/detalle) |
| 📖 Publicación I — PeerJ 2025 | [doi.org/10.7717/peerj.19108](https://doi.org/10.7717/peerj.19108) |
| 📖 Publicación II — Expert Syst. Appl. 2021 | [doi.org/10.1016/j.eswa.2021.115648](https://doi.org/10.1016/j.eswa.2021.115648) |
| 📖 Publicación III — CSBJ 2024 | [doi.org/10.1016/j.csbj.2023.11.052](https://doi.org/10.1016/j.csbj.2023.11.052) |

---

## Licencia

El código fuente LaTeX de esta tesis se comparte con fines de referencia académica.  
© 2025 Diego Fernández Edreira — Universidade da Coruña.  
Todos los derechos reservados salvo indicación contraria.
