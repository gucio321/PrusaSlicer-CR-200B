# Creality CR-200B presets for PrusaSlicer

This repository contains a working set of presets for the Creality CR-200B 3D printer, designed for use with PrusaSlicer.

## Why?
Since Creality CR-200B is a relatively old printer, it is not supported by the latest version of a dedicated slicer [Creality Print](https://github.com/CrealityOfficial/CrealityPrint).
The old version of Creality Print that is supposed to support CR-200B has only few features and is completely outdated so it simply cannot be used as a modern slicer.
The @CrealityOfficial team [refused to re-add CR-200B support to the latest slicer version](https://github.com/CrealityOfficial/CrealityPrint/issues/424#issuecomment-3111698503) so I decided to create my own presets, but this time for PrusaSlicer as I know it better than Creality Print.

## How to use

1. Download [configuration file from this repo](./CR-200B_config_bundle.ini)
2. Open PrusaSlicer
3. Go to File -> Import -> Import Config Bundle

## Available presets

### Printers

I added presets for 3 nozzle sizes:
- 0.4 mm (default) (Layer height: 0.1-0.3 mm)
- 0.6 mm (for drafts) (Layer height: 0.15-0.45 mm)
- 0.2 mm (for high quality) (Layer height: 0.05-0.15 mm)

### Print settings presets

- **Draft**:
  - Layer height: 0.45 mm
  - Supported Nozzle: 0.6 mm
- **Normal**:
    - Layer height: 0.3 mm
    - Supported Nozzle: 0.4 mm (recommended), 0.6 mm
    - used for most prints (balanced time and quality)
- **Quality**:
    - Layer height: 0.15 mm
    - Supported Nozzle: 0.2 mm, 0.4 mm (recommended)
    - Enables Ironing and Avoids Crossing Perimeters
- **Absurdly Heigh Quality**:
    - Layer height: 0.05 mm
    - Supported Nozzle: 0.2 mm
    - Enables Ironing and Avoids Crossing Perimeters
    - Used for very, very high quality prints, but takes a whole lot of time
