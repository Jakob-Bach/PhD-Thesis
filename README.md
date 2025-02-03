# PhD Thesis of Jakob Bach

This repository contains the dissertation

> Bach, Jakob. "Leveraging Constraints for User-Centric Feature Selection"

at the [Department of Informatics](https://www.informatik.kit.edu/english/index.php) of the [Karlsruhe Institute of Technology](https://www.kit.edu/english/).
The corresponding defense was held on January 20, 2025.
This repository provides the dissertation's LaTeX source code and the final compiled version as PDF (`phd-thesis-jakob-bach.pdf`).
The latter is identical to the official publication on [*KITopen*](https://doi.org/10.5445/IR/1000178649).
You can find the corresponding complete experimental data (inputs as well as results) on [*RADAR4KIT*](https://doi.org/10.35097/4kjyeg0z2bxmr6eh).
The LaTeX source code and PDF for the corresponding defense presentation are available on [*GitHub*](https://github.com/Jakob-Bach/PhD-Defense),
with the PDF additionally backed up on [*KITopen*](https://doi.org/10.5445/IR/1000178247).

The main file of the dissertation is `dissertation.tex`.
It builds on the LaTeX dissertation template of the research group [Software Design and Quality](https://sdq.kastel.kit.edu/) at KIT
(class `sdqdiss.cls`, which we slightly adapted to not use the SDQ logo on the title page).
Individual chapters are in the folder `sections/` and plots are in the folder `plots/`.
We use `biblatex` with the backend `biber` for managing the bibliography, whose source file is `references.bib`.
`dissertation.xmpdata` contains meta-data for the compiled PDF.

Additionally, the dissertation's review version ("vorgelegte Version") needs to contain a CV (`cv.tex`) and list of own publications (`publications.tex`).
Further, these two documents also need to be handed in separately, for which we created the files `cv_standalone.tex` and `publications_standalone.tex`.
For privacy reasons, we anonymized the CV but kept its structure.
The final version ("genehmigte Version") of the dissertation does not need to contain these two sections
(the corresponding `\input` statements are commented in `dissertation.tex`).
