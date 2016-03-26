# Extracting disease–gene associations from DisGeNET

[DisGeNET](http://www.disgenet.org/) is a resource that integrates disease–gene associations from several sources [[ref](http://doi.org/10.1093/database/bav028 "Pinero et al (2015) DisGeNET: a discovery platform for the dynamical exploration of human diseases and their genes")]. We're [using the resource](http://doi.org/10.15363/thinklab.d105 "Thinklab discussion: Processing DisGeNET for disease-gene relationships") in Rephetio, our network for drug repurposing. This repository extracts associations for the diseases and genes in rephetio.

[`disgenet.ipynb`](disgenet.ipynb) processes the DisGeNET downloads and outputs user-friendly TSVs to [`data`](data).

## License

DisGeNET content and derivatives are licensed under the [ODbL 1.0](http://opendatacommons.org/licenses/odbl/summary/ "Open Database License (ODbL) v1.0"). All original content is licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/ "CC0 1.0 Universal: Public Domain Dedication").
