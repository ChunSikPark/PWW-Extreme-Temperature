# Extreme Temperature Events with PWW Weather Data

Resources for **"A Flexible Method for Identifying Electric Grid Extreme Temperature Events as Per NERC TPL-008"**
(S. Lee, K. Zhgun, R. Badawi, F. Safdarian, T. J. Overbye, J. D. Weber), North American Power Symposium (NAPS) 2026, Houghton, MI.

The paper presents the **Power Weather Outlier Method (PWOM)**: it reads hourly historical weather (1940 to present) from PoWer Weather (`.pww`) files, averages it over any part of a grid weighted by load and/or generation, and ranks extreme heat and cold events over any time window, including the 3-day period in NERC TPL-008-1 R2.

## Links

| What | Where |
|---|---|
| PWW weather data (hourly ERA5, `.pww` format) | [Google Drive](https://drive.google.com/drive/folders/1-nsEIuzKt5XHJlCfNFivuOzBF-BnHpfS) |
| Potential NERC TPL-008 scenarios: application video and `.pww` files | [Google Drive](https://drive.google.com/drive/folders/1qDXPh1yu5XpzJPWFKBDDawdpcktXhA7V) |
| `TeamOverbyeWeather`: Python client to download and automate `.pww` files | [PyPI](https://pypi.org/project/TeamOverbyeWeather/) · [Docs](https://chunsikpark.github.io/TeamOverbyeWeather/) · [Web portal](https://weather-data-gui.pages.dev) |
| Synthetic test grids used in the paper (2K, 23.6K, 82K bus) | [TAMU Electric Grid Test Case Repository](https://electricgrids.engr.tamu.edu/) |
| PowerWorld Simulator 25 (includes a PWOM implementation) | [powerworld.com](https://www.powerworld.com) |

## Contact

SeungJun (Brian) Lee, Texas A&M University: sl47745@tamu.edu

This work was supported by the U.S. Department of Energy's Office of Cybersecurity, Energy Security, and Emergency Response (CESER) under award DE-CR0000067.
