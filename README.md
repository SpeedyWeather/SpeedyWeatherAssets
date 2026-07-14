# SpeedyWeatherAssets

[![docs](https://img.shields.io/badge/documentation-main-blue.svg)](https://speedyweather.github.io/SpeedyWeatherDocumentation/dev/input_data)

Input data and other assets to run SpeedyWeather.jl. Usage documentation found in the SpeedyWeather documentation [here](https://speedyweather.github.io/SpeedyWeatherDocumentation/dev/input_data),
datasets themselves are described below.

## Boundary conditions

in `data/boundary_conditions`

### Time-constant

- __orography.nc__: Orographic height (IFS TCO1279 data bilinearly remapped to a 2048x1024 full Gaussian grid ~0.2˚C global resolution, rounded to 7 significant bits, zlib lossless compression)
- __land-sea_mask.nc__: Binary land-sea mask (0.25˚ from ERA5, losslesss compression)
- __vegetation.nc__: Vegetation (low and high cover, leaf area index, 0.25˚ from ERA5, rounded to 2 significant digits, lossless compression)

### Climatologies

Monthly data with a seasonal cycle

- Albedo
- Sea ice
- Sea surface temperature
- Soil moisture
- Soil temperature

## Neural network weights

### Land

- Surface roughness
