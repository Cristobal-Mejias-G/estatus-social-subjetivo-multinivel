# Estatus Social Subjetivo en la Región Metropolitana

### Un análisis multinivel de los factores individuales y comunales que moldean la autopercepción de posición social

**Cristóbal Mejías & Victoria Arias** · Análisis de Datos Multinivel · FACSO, Universidad de Chile · Profesor: Juan Carlos Castillo · Ayudante: Kevin Carrasco

<p align="center">
  <img src="https://img.shields.io/badge/Estado-Terminada-4CAF50?style=for-the-badge" alt="Terminada"/>
  <img src="https://img.shields.io/badge/Modelos_Multinivel-7B1FA2?style=for-the-badge&logoColor=white" alt="Modelos Multinivel"/>
  <img src="https://img.shields.io/badge/2025-555?style=for-the-badge" alt="2025"/>
</p>

---

## Abstract

El estatus social subjetivo ha sido un tema poco explorado en América Latina, por lo que esta investigación se propone analizar los factores individuales y contextuales asociados a esta variable en la Región Metropolitana. Para ello, se emplea una metodología multinivel que permite estimar los efectos tanto de las características personales como del entorno comunal en la autopercepción de la posición social. El estudio se basa en datos de la sexta ola del Estudio Longitudinal Social de Chile (ELSOC), complementados con información comunal sobre el índice de pobreza multidimensional, calidad ambiental y seguridad, provenientes de fuentes secundarias En total, se analizan 767 personas y 42 comunas de la Región Metropolitana. Los resultados indican que las variables que inciden significativamente en el estatus social subjetivo son el estatus social subjetivo de origen familiar, el ingreso total del hogar y el nivel de pobreza multidimensional de las comunas. En consecuencia, se evidencia una fuerte influencia del contexto familiar y de la variable socioeconómica, tanto a nivel individual como contextual, en la autopercepción del estatus social.

## 
<p align="center">
  <a href="https://cristobal-mejias-g.github.io/estatus-social-subjetivo-multinivel/documento.html" style="font-size: 50px;" >
    <strong> Ver Investigación</strong>
  </a>
</p>


---

## Estructura del repositorio

```
.
├── input/
│   ├── data/                          # Datos de entrada
│   ├── img/                           # Imágenes de entrada
│   └── Codebook_ELSOCxlsx             # Codebook de ELSOC
├── proc/
│   └── proc_data.R                    # Procesamiento de datos
├── output/
│   ├── data_proc.Rdata                # Datos procesados
│   └── graf  
├── documento.qmd                      # Documento principal (Quarto)
├── multinivel_informe.scss            # Estilos del informe
└── README.md
```

---

## Requisitos

Este proyecto usa **R** con Quarto. Las principales librerías son:

`lme4` · `lmerTest` · `sjPlot` · `ggplot2` · `tidyverse` · `gt` · `influence.ME`

Para instalar todas las dependencias:

```r
install.packages("pacman")
pacman::p_load(lme4, lmerTest, sjPlot, ggplot2, tidyverse, gt, influence.ME, ...)
```

---

## Contexto académico

Este trabajo fue desarrollado en el marco del curso **Análisis de Datos Multinivel** de la Facultad de Ciencias Sociales (FACSO), Universidad de Chile.

Repositorio original del curso: [multinivel-facso](https://github.com/multinivel-facso)

Repositorio original del proyecto: [grupo 6](https://github.com/multinivel-facso/trabajo1-grupo-6)



---

## Autores

**Cristóbal Mejías** · **Victoria Arias**  
Facultad de Ciencias Sociales, Universidad de Chile
