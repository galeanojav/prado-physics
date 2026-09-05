# Art and Physics at the Museo del Prado
## Supplementary material and Python notebooks
<img width="193" height="20" alt="image" src="https://github.com/user-attachments/assets/c0283c27-09a9-4aa0-b89a-d330be333293" />


This repository contains the supplementary computational and GeoGebra materials for the article:

> Galeano J R (2026) **Art and Physics at the Museo del Prado: A Walk Through Science Hidden in Masterpieces**. In review at *European Journal of Physics*.

---

## Contents

### Python notebooks

| File | Description |
|------|-------------|
| `velazquez_blackbody.ipynb` | Blackbody radiation and Velázquez's *The Forge of Vulcan*. Supports Block 1 (Colour as a thermometer) of Section 4. Calculates the fraction of visible emission from a blackbody at forge temperature, answers the three quantitative questions of the article, and plots the Planck distribution over the visible range. |
| `durer_golden_spiral.ipynb` | Golden spiral and Dürer's *Eve*. Supports the advanced level of Block 3 of Section 5. Superimposes a logarithmic spiral on the image of Eve, calculates the RMSD between the spiral and anatomical landmarks, and compares the golden spiral with non-golden logarithmic spirals. |

### GeoGebra files

| File | Description |
|------|-------------|
| `Eve_proportion.ggb` | Proportional analysis of Dürer's *Eve* (Block 1 of Section 5). Measures the nine-head canon (CE/CD = 9.1) and the golden ratio at the navel (FE/CF = 1.6). |
| `espiral_Durero_Eve.ggb` | Golden spiral construction on Dürer's *Eve* (Block 2 of Section 5). Constructs the golden rectangle IJLK and the three subdivisions, and approximates the golden spiral with circular arcs. |

### Reference images

| File | Description |
|------|-------------|
| `Eve_proportion.jpg` | GeoGebra output: proportional analysis of Eve (Figure 5a in the article). |
| `Durero_espiral.jpg` | GeoGebra output: golden spiral construction on Eve (Figure 5b in the article). |
| `Geogebra_proportions.jpg` | GeoGebra output with Algebra panel: step-by-step proportional analysis. |
| `Geogebra_ratio2.jpg` | GeoGebra output with Algebra panel: golden ratio calculation. |

---

## Requirements

### Python notebooks

The notebooks require Python 3.8 or later and the following packages:

```
numpy
scipy
matplotlib
jupyter
```

Install all dependencies with:

```bash
pip install -r requirements.txt
```

Then launch Jupyter:

```bash
jupyter notebook
```

### Image of Eve (required for `durer_golden_spiral.ipynb`)

The notebook requires the official high-resolution image of Dürer's *Eve* from the Museo del Prado collection website. Download it from:

https://www.museodelprado.es/coleccion/obra-de-arte/eva/930c0fdf-fcfc-47df-b216-e375f5719084

Save it as `Eva.jpg` in the same folder as the notebook before running it.

### GeoGebra files

Open the `.ggb` files with GeoGebra Geometry (free, online or desktop):

https://www.geogebra.org/geometry

The GeoGebra files do **not** include the image of Eve for copyright reasons. To use them, open the file in GeoGebra and import the image of Eve manually via *Insert → Image*.

---

## Step-by-step guides

Detailed step-by-step instructions for the GeoGebra activities are provided in **Supplementary Material S1** of the article:

- **S1.1** — Block 1: Proportional analysis (nine-head canon and golden ratio)
- **S1.2** — Block 2: Golden spiral construction

The distance modulus activity (Rubens, Section 7) is described in **Supplementary Material S2**.

---

## Funding

This work was supported by the Universidad Politécnica de Madrid (UPM) through the Educational Innovation Project *Explorando la ciencia en el arte: Aprendizaje basado en investigación a través del Museo del Prado* (Project code IE26.2004).

---

## How to cite

If you use these materials in your teaching or research, please cite the article:

```
Galeano J R (2026) Art and Physics at the Museo del Prado: A Walk Through 
Science Hidden in Masterpieces. European Journal of Physics. 
Manuscript reference: EJP-110803.
```

And the repository:

```
Galeano J R (2026) Art and Physics at the Museo del Prado: 
Supplementary Python notebooks and GeoGebra files [Software].
GitHub. https://github.com/jgaleano/prado-physics
```

---

## Licence

The code and GeoGebra files in this repository are released under the
[Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

The images (`Eve_proportion.jpg`, `Durero_espiral.jpg`, `Geogebra_proportions.jpg`, `Geogebra_ratio2.jpg`) are screenshots of GeoGebra constructions performed on the official Museo del Prado image of Dürer's *Eve* (public domain). The underlying painting is in the public domain.

---

## Contact

Javier R. Galeano  
Complex System Group  
Universidad Politécnica de Madrid  
javier.galeano@upm.es
