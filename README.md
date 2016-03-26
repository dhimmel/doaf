# Extracting disease–gene associations from DOAF

[DOAF](http://doa.nubic.northwestern.edu/pages/search.php) is a resource that extracts functional disease–gene associations from GeneRIF [[ref](http://doi.org/10.1371/journal.pone.0049686 "Xu et al (2012) A Framework for Annotating Human Genome in Disease Context")]. We're [using the resource](http://doi.org/10.15363/thinklab.d94 "Thinklab discussion: Functional disease annotations for genes using DOAF") in rephetio, our network for drug repurposing. This repository extracts associations for the diseases and genes in rephetio.

[`doaf.ipynb`](doaf.ipynb) processes the DOAF downloads and outputs user-friendly TSVs to [`data`](data).

## License

Please contact the DOAF creators for the licensing of any DOAF content or derivatives. All original content in this repository is licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/ "CC0 1.0 Universal: Public Domain Dedication").
