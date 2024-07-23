---
title: "Real-Time Underwater Spectral Rendering"
authors:
- "[Nestor Monzon](#)"
- "[Diego Gutierrez](http://giga.cps.unizar.es/~diegog/)"
- "[Derya Akkaynak](https://www.deryaakkaynak.com/)"
- "[Adolfo Muñoz](https://webdiis.unizar.es/~amunoz)"
date: "2024-05-01"
doi: "https://doi.org/10.1111/cgf.15009"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-01"
 
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ["1", "2"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Graphics Forum* 43 (2) (Eurographics 2024)"
publication_short: "CG Forum (EG 2024)"

abstract: "The light field in an underwater environment is characterized by complex multiple scattering interactions and wavelength-dependent attenuation, requiring significant computational resources for the simulation of underwater scenes. We present a novel approach that makes it possible to simulate multi-spectral underwater scenes, in a physically-based manner, in real time. Our key observation is the following: In the vertical direction, the steady decay in irradiance as a function of depth is characterized by the diffuse downwelling attenuation coefficient, which oceanographers routinely measure for different types of waters. We rely on a database of such real-world measurements to obtain an analytical approximation to the Radiative Transfer Equation, allowing for real-time spectral rendering with results comparable to Monte Carlo ground-truth references, in a fraction of the time. We show results simulating underwater appearance for the different optical water types, including volumetric shadows and dynamic, spatially varying lighting near the water surface."

# Summary. An optional shortened abstract.
summary: "We present a simplification of multiple scattering as a function of depth that allows for real-time underwater spectral rendering."

# tags:
# - Source Themes
featured: true  

links:
# - name: "bibtex"
#   url: 'https://scholar.googleusercontent.com/scholar.bib?q=info:cAoIP-ipQIYJ:scholar.google.com/&output=citation&scisdr=ClHmFgBDEMP81zBi46w:AFWwaeYAAAAAZp5k-6xqvKyy3GmByMw_kl3BAtU&scisig=AFWwaeYAAAAAZp5k--Yg-4Q2f7sa2rDQ4o-MEng&scisf=4&ct=citation&cd=-1&hl=en'
url_pdf: "https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.15009"
# url_code: ''
# url_dataset: ''
# url_poster: ''
url_project: 'https://graphics.unizar.es/projects/EG24Underwater/'
# url_slides: ''
# url_source: ''
url_video: 'https://youtu.be/x6JQNNJBJyA?list=TLGGxu1EqFf3Yp0yMjA3MjAyNA'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

## Bibtex
 ```bibtex
  @article{https://doi.org/10.1111/cgf.15009,
      author = {Monzon, Nestor and Gutierrez, Diego and Akkaynak, Derya and Muñoz, Adolfo},
      title = {Real-Time Underwater Spectral Rendering},
      journal = {Computer Graphics Forum},
      pages = {e15009},
      doi = {https://doi.org/10.1111/cgf.15009},
      url = {https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.15009},
      eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1111/cgf.15009},
  }       
```