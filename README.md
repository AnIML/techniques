# AnIML Technique Definitions

This repository hosts AnIML technique definitions. Feel free to contribute by submitting a pull request.

## About AnIML

AnIML (Analytical Information Markup Language) is an open standard for storing and exchanging analytical chemistry data. It provides a vendor-neutral format for representing analytical data and metadata.

For more information about AnIML:
* Official website: [https://www.animl.org/](https://www.animl.org/)
* AnIML schemas repository: [https://github.com/AnIML/schemas](https://github.com/AnIML/schemas)

## Technique Definitions

This repository contains technique definition files (`.atdd` format) for various analytical methods:

### Chromatography
* **chromatography.atdd** - General chromatography technique definition for separation methods (HPLC, GC, etc.)
* **chromatography-peak-table.atdd** - Peak table data structure for chromatographic separations

### Chromatography Detectors
* **ecd-trace.atdd** - Electron Capture Detector (ECD) trace data for halogenated compounds detection
* **elsd-trace.atdd** - Evaporative Light Scattering Detector (ELSD) trace for compounds without chromophores
* **fid-trace.atdd** - Flame Ionization Detector (FID) trace for organic compound detection
* **fpd-trace.atdd** - Flame Photometric Detector (FPD) trace for sulfur and phosphorus compounds
* **npd-trace.atdd** - Nitrogen-Phosphorus Detector (NPD) trace for nitrogen/phosphorus-containing compounds
* **rid-trace.atdd** - Refractive Index Detector (RID) trace for bulk property detection
* **tcd-trace.atdd** - Thermal Conductivity Detector (TCD) trace for universal detection

### Mass Spectrometry
* **mass-spec.atdd** - Mass spectrometry technique definition for molecular mass analysis
* **ms-trace.atdd** - Mass spectrometry trace data
* **ms-annotation.atdd** - Mass spectrum annotation data

### UV-Vis Spectroscopy
* **uv-vis.atdd** - General UV-Vis spectroscopy technique definition
* **uv-vis spectrum.atdd** - UV-Vis absorption spectrum data
* **uv-vis dispersive spectrum.atdd** - UV-Vis dispersive spectrometer data
* **uv-vis ft spectrum.atdd** - UV-Vis Fourier-transform spectrum data
* **uv-vis interferogram.atdd** - UV-Vis interferogram data for FT spectroscopy
* **uv-vis-trace.atdd** - UV-Vis detector trace data
* **uv-vis-peaktable.atdd** - UV-Vis peak table data

### Other Techniques
* **indexing.atdd** - Indexing technique for data organization
* **microplate-read.atdd** - Microplate reader data for high-throughput screening

## Getting Help

For questions, issues, or contributions, please use GitHub:
* Open an [issue](https://github.com/AnIML/techniques/issues) to report problems or request features
* Submit a [pull request](https://github.com/AnIML/techniques/pulls) to contribute improvements
