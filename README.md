# SpeedyWeatherAssets

[![docs](https://img.shields.io/badge/documentation-main-blue.svg)](https://speedyweather.github.io/SpeedyWeatherDocumentation/dev/input_data)

Input data and other assets to run SpeedyWeather.jl. Usage documentation found in the SpeedyWeather documentation [here](https://speedyweather.github.io/SpeedyWeatherDocumentation/dev/input_data),
datasets themselves are described below.

## Boundary conditions

in `data/boundary_conditions`

### Time-constant

- __orography.nc__ (IFS TCO1279 data bilinearly remapped to a 2048x1024 full Gaussian grid ~0.2˚C global resolution, rounded to 7 significant bits, zlib lossless compression)
- Land-sea mask
- Orography
- Vegetation

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
