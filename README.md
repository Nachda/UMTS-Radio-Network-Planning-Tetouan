# UMTS Radio Network Planning — Tetouan, Morocco

**3G/UMTS radio network planning using Global Mapper and Forsk Atoll.**

[English](README.md) | [Français](README.fr.md)

## Project Overview

This project focuses on the planning of a 3G/UMTS radio network for Tetouan, Morocco. It combines geospatial data preparation, radio link budget analysis, network design, and radio coverage, quality, and capacity simulations.

Global Mapper will be used to prepare geographic data, while Forsk Atoll will be used for radio network design and simulation.

> **Project status:** Initial setup. Data preparation, network design, and simulations have not yet been completed.

## Objectives

- Prepare and organize geographic data for the study area.
- Process terrain and relevant geographic layers using Global Mapper.
- Define radio planning assumptions and calculate the link budget.
- Develop a preliminary UMTS radio network design in Forsk Atoll.
- Evaluate predicted coverage, signal quality, and capacity, depending on the available simulation configuration.
- Document the methodology, assumptions, results, and limitations.

## Tools

| Tool | Purpose |
|---|---|
| Global Mapper | Terrain and geospatial data preparation |
| Forsk Atoll | UMTS radio network design and simulation |
| Git and GitHub | Version control and project documentation |

## Project Structure

```text
UMTS-Radio-Network-Planning-Tetouan/
├── 01_Data/
│   ├── Raw/
│   └── Processed/
├── 02_Atoll_Project/
├── 03_Results/
└── 04_Documentation/
```

## Methodology

The planned workflow consists of the following stages:

1. Define the study area and identify suitable geographic data sources.
2. Prepare terrain and geographic layers.
3. Establish radio planning assumptions and calculate the link budget.
4. Configure the UMTS planning environment and develop the initial network design.
5. Run the available coverage, quality, and capacity predictions.
6. Analyze the results and document limitations and possible improvements.

The methodology may be refined as data availability and software capabilities are confirmed.

## Data and Reproducibility

Data sources, coordinate reference systems, processing steps, simulation assumptions, and relevant software settings will be documented throughout the project.

Large datasets and software-specific project files may be excluded from Git when necessary because of file-size, licensing, or redistribution restrictions.

## Results

Results will be added after the corresponding processing and simulations have been completed. Simulated results will be identified as predictions and will not be presented as field measurements.

## Limitations

The reliability of the results will depend on the quality of the input data, terrain and clutter information, radio parameters, and available simulation configuration. Predicted performance does not replace field measurements.
