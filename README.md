# GenAI Challenge — ACMW Challenge

This repository contains three generative AI challenge notebooks created for the ACMW competition. The projects cover image repair, creative fashion generation, and poster design refinement.

## Repository Contents

- `Challenge_1/` — Image Repair + Style Transformation
- `Challenge_2/` — AI Fashion Designer (Digital Garden theme)
- `Challenge_3/` — Poster Design & Refinement

## Challenge 1: Image Repair + Style Transformation

**Objective**
Repair an intentionally degraded image using a generative reconstruction model, then apply a new visual style while preserving the original structure.

**Included in `Challenge_1/Challenge 1 - Team S2.ipynb`**
- Small image dataset selection and preprocessing
- Degradation method applied to the input image (blur, noise, or corruption)
- Generative reconstruction using an autoencoder / VAE approach
- Style transformation applied to the repaired image
- Visual examples of degraded input, repaired output, and final stylized version
- Explanation of method and design decisions

**Deliverables covered**
- Degraded input image
- Repaired image
- Final stylized image
- Short explanation of the model, degradation method, and style design

## Challenge 2: AI Fashion Designer — Digital Garden

**Objective**
Train a generative model on a fashion dataset and create a coherent mini-collection. Explore the latent space and generate multiple fashion designs.

**Theme: Digital Garden**
- Color palette: bright green, pink, lavender, sky blue
- Style direction: dresses inspired by flowers, leaves, butterflies, and vines

**Included in `Challenge_2/Challenge 2 - Team S2.ipynb`**
- Fashion dataset preparation and modeling details (Fashion-MNIST used for fast experimentation)
- Generative model training for fashion output
- Latent space exploration through sampling and interpolation
- Creation of 3 to 5 visually consistent outfit designs
- Mood board or style sheet that supports the theme
- Short explanation of the creative process

**Deliverables covered**
- 5 generated outfit images
- Mood board / style sheet
- Creative process summary

## Challenge 3: Poster Design & Refinement

**Objective**
Use generative AI to produce initial poster concepts, then refine them into a polished final poster suitable for a fictional concept.

**Included in `Challenge_3/Challenge 3 - Team S2.ipynb`**
- Defined poster concept and visual mood
- Initial AI-generated concepts (2 to 3 variations)
- Iterative refinement using design tools and layout decisions
- Final polished poster output
- Short rationale describing the design choices

**Deliverables covered**
- 3 initial poster concepts
- 1 final poster image
- Short design rationale

## How to Use This Repository

1. Open the notebook for the challenge you want to explore.
2. Run the cells in order and follow the notebook instructions.
3. Check the output folders and notebook cells for example results and saved assets.

## Notes

- The notebooks are designed for Jupyter or Google Colab.
- Some datasets and checkpoints may require downloading externally, as noted in the notebooks.
- Use `requirements.txt` to install the Python dependencies for running the notebooks.

## Colab Access

To open these notebooks in Google Colab:

1. If this repository is hosted on GitHub, use Colab's `File > Open notebook > GitHub` option and enter the repo URL.
2. Alternatively, download the `.ipynb` file locally and upload it directly in Colab.
3. Install dependencies in Colab with:

```bash
!pip install -r requirements.txt
```

## Direct Notebook Links

- [Challenge 1 — Image Repair + Style Transformation](Challenge_1/Challenge 1 - Team S2.ipynb)
- [Challenge 2 — AI Fashion Designer (Digital Garden)](Challenge_2/Challenge 2 - Team S2.ipynb)
- [Challenge 3 — Poster Design & Refinement](Challenge_3/Challenge 3 - Team S2.ipynb)

## Setup

From the repository root, install dependencies with:

```bash
pip install -r requirements.txt
```

## Conclusion

This repository presents three distinct generative AI projects aligned with the ACMW challenge requirements: image repair and stylization, fashion generation with a Digital Garden theme, and poster concept design with refinement.

Thank you for reviewing this work — feel free to explore the notebooks, run the experiments, and build on these creative AI solutions.

