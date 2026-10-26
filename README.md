
# Powder Characterization of Ti-6Al-4V Alloy 🔬

<p align="center">
  <img src="https://img.shields.io/badge/Hall_Funnel-ASTM_B213-00599C?style=for-the-badge&logo=academia&logoColor=white" alt="Hall Funnel ASTM B213" />
  <img src="https://img.shields.io/badge/Tapping_Apparatus-ASTM_B527-0077B6?style=for-the-badge&logo=databricks&logoColor=white" alt="Tapping Apparatus ASTM B527" />
  <img src="https://img.shields.io/badge/Optical_Microscopy-Microstructure-6A5ACD?style=for-the-badge&logo=opencv&logoColor=white" alt="Optical Microscopy" />
  <img src="https://img.shields.io/badge/SEM-BSE_%26_SE-E87519?style=for-the-badge&logo=electron&logoColor=white" alt="SEM BSE and SE" />
  <img src="https://img.shields.io/badge/SEM--EDS-Elemental_Analysis-C62828?style=for-the-badge&logo=atom&logoColor=white" alt="SEM-EDS" />
  <img src="https://img.shields.io/badge/Python-Scientific_Computing-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Ti--6Al--4V-Titanium_Alloy-008B8B?style=for-the-badge&logo=materialdesign&logoColor=white" alt="Ti-6Al-4V" />
</p>

---

This project characterizes and compares non-spheroidized (gas atomized) and spheroidized (plasma spheroidized) Ti-6Al-4V powders. Key properties analyzed include flowability, apparent and tap density, particle size distribution, particle shape, morphology via SEM, and chemical composition via SEM-EDS.


## 1. Introduction

Powder Characterization and Testing are essential for gaining a thorough understanding of the physical and technological properties of powders, contributing to the optimization of processes and the assurance of quality outcomes. This report investigates key aspects of powders, including flowability, density, morphology, and chemical composition, aiming to provide comprehensive insights into their behavior and performance.

## 2. Objectives

This study aims to conduct a thorough comparison between spheroidized and non-spheroidized powders by analyzing their flowability, tap density, morphology, and chemical composition. Flowability testing will assess the ease of powder flow, while tap density measurements will evaluate packing efficiency. Morphological analysis will examine particle size distribution and shape consistency, utilizing SEM imaging and laser diffraction. Chemical composition will be compared using SEM-EDS to quantify elemental makeup and distribution. This comprehensive approach will provide valuable insights into the physical, morphological, and chemical properties of the powders, aiding in informed decision-making for diverse industrial applications.

## 3. Powder Types and Manufacturing Processes

The two powders studied in this work are non-spheroidized and spheroidized Ti-6Al-4V alloy.

- **Non-spheroidized powder (NS)** was manufactured using Gas Atomization technology. A melted metal alloy forms a melt stream that is impinged by a high-velocity atomization gas, dispersing it into particles. The particles cool as they fall and contact a substrate. This process produces metal powders with controlled characteristics.

- **Spheroidized powder (S)** was produced by Plasma Spheroidization. Starting from gas-atomized powder, the particles are introduced into a high-temperature plasma torch. The extreme heat melts the surface, and surface tension forces reshape the particles into more spherical forms. Rapid cooling freezes the improved spherical morphology. Plasma spheroidization yields high spheroidization ratio, narrow size distribution, and excellent flowability, making it ideal for spherical Ti-6Al-4V powder.

## 4. Flowability

Flowability is a critical property that strongly influences the performance of Additive Manufacturing processes. Good flowability ensures uniform powder spreading and stable part quality. Morphology, particle size distribution, and moisture content are the main factors affecting flowability.

Flowability was measured using a Hall funnel according to ASTM B 213. A 50 g dry sample is placed in the funnel with the orifice blocked. Timing starts when the fingertip is removed and stops when the last particle exits. Results are reported as time in seconds for 50 g to flow (s/50 g).

![Hall funnel for flowability measurement](assets/Hall%20funnel%20for%20flowability%20measurement.jpeg)

**Figure 1**: Hall funnel for flowability measurement

![Flowability measured for Ti-6Al-4V powders (NS and S)](assets/Flowability%20measured%20for%20Ti-6Al-4V%20powders%20(NS%20and%20S).jpeg)

**Figure 2**: Flowability measured for Ti-6Al-4V powders (NS and S)

**Table 1**: Flowability values and measurement error

| Powder              | Flowability (s/50 g) |
|---------------------|----------------------|
| Ti-6Al-4V (NS)      | 37.736 ± 2.935       |

The spheroidized powder shows clearly better flowability (lower time), indicating easier and faster flow through the orifice. This improves handling and process efficiency.

## 5. Apparent and Tap Density

Apparent density is the mass of powder per unit volume (g/cm³), including the voids between particles. It depends strongly on particle size and shape.

Tap density is the density obtained after tapping the powder under controlled conditions (ASTM B 527). It is always higher than apparent density and reflects packing efficiency.

Apparent density was measured with a Hall funnel (ASTM B 212) by pouring 50 g into a 100 cm³ graduated cylinder. Tap density was measured by placing the same cylinder in a tapping apparatus and recording volume after successive taps up to 3000 taps.

The density is calculated as:

<img src="https://latex.codecogs.com/svg.latex?TD%3D%5Cfrac%7BM%7D%7BV%7D" alt="TD = M/V" />

![Tapping apparatus for measuring tap density](assets/Tapping%20apparatus%20for%20measuring%20tap%20density.jpeg)

**Figure 3**: Tapping apparatus for measuring tap density

![Tap density measured for Ti-6Al-4V powders (NS and S)](assets/Tap%20density%20measured%20for%20Ti-6Al-4V%20powders%20(NS%20and%20S).jpeg)

**Figure 4**: Tap density measured for Ti-6Al-4V powders (NS and S)

**Table 2**: Apparent density, tap density and packing factors

| Powder              | Apparent density (g/cm³) | Tap density (g/cm³) | Carr’s index (%) | Hausner ratio | Flowability |
|---------------------|---------------------------|---------------------|------------------|---------------|-------------|
| Ti-6Al-4V (NS)      | 2.131 ± 0.037            | 2.489 ± 0.016      | 14.37            | 1.17          | Good        |
| Ti-6Al-4V (S)       | 2.440 ± 0.000            | 2.753 ± 0.029      | 11.38            | 1.13          | Good        |

Both powders show “Good” flowability according to Carr’s index and Hausner ratio. The spheroidized powder has higher density and better packing efficiency due to its more regular shape.

## 6. Morphology

Particle image analysis was performed to measure size and shape. A controlled amount of powder was deposited on the microscope stage and uniformly spread using a vacuum system to avoid agglomeration.

![Vacuum system and Microscope](assets/a%29%20Vacuum%20system%20for%20particle%20uniform%20spreading%20b%29%20Microscope%20for%20particle%20image%20analysis.jpeg)

**Figure 5**: a) Vacuum system for particle uniform spreading b) Microscope for particle image analysis

### Particle Size Distribution

Particle size was evaluated using the area-equivalent diameter. Both powders showed a size range of approximately 5–115 µm with a mean size around 35 µm. About 50 % of the particles in both powders were smaller than 40 µm. The spheroidized powder exhibited smaller error bars, indicating higher measurement consistency due to more regular particle shapes.

![Diameter size distribution for gas atomized powder (NS)](assets/Diameter%20size%20distribution%20for%20gas%20atomized%20powder%20(NS).jpeg)

**Figure 6**: Diameter size distribution for gas atomized powder (NS)

![Diameter size distribution for spheroidized powder (S)](assets/Diameter%20size%20distribution%20for%20spheroidized%20powder%20(S).jpeg)

**Figure 7**: Diameter size distribution for spheroidized powder (S)

### Particle Shape

The main shape descriptors used were:

- **Aspect Ratio** = Feret min / Feret max (0 < AR ≤ 1)
- **Circularity** – how closely the particle projection resembles a perfect circle

NS powder showed circularity values ranging from 40 % to 100 %, with more than 50 % of particles above 90 %.  
S powder showed a narrower range (50–100 %) with more than 95 % of particles above 90 % circularity and significantly smaller scatter.

![Shape distributions for gas atomized powder (NS)](assets/Shape%20distributions%20for%20gas%20atomized%20powder%20(NS).jpeg)

**Figure 8**: Shape distributions for gas atomized powder (NS)

![Shape distributions for spheroidized powder (S)](assets/Shape%20distributions%20for%20spheroidized%20powder%20(S).jpeg)

**Figure 9**: Shape distributions for spheroidized powder (S)

## 7. Material Characterization

### Identification of Powder Type (SEM)

SEM images (500×) in both Back-Scattered Electron (BSE) and Secondary Electron (SE) modes clearly distinguish the two powders. The non-spheroidized powder contains numerous small satellite particles attached to larger ones, while the spheroidized powder is largely free of satellites and appears much more spherical.

![Microscopic view of powder sample NS](assets/Microscopic%20view%20of%20powder%20sample%20NS%20a%29%20BSE%20b%29%20SE.jpeg)

**Figure 10**: Microscopic view of powder sample NS a) BSE b) SE

![Microscopic view of powder sample S](assets/Microscopic%20view%20of%20powder%20sample%20S%20%20c%29%20BSE%20d%29%20SE%20.jpeg)

**Figure 11**: Microscopic view of powder sample S c) BSE d) SE

### Chemical Composition (SEM-EDS)

#### Non-Spheroidized Powder (NS)

![Identification of Zones 8 and 9](assets/%28a%29%20Identification%20of%20Zones%20%28b%29%20Material%20Characterization%20graph%20Zone%208%20%28c%29%20Material%20characterization%20graph%20Zone%209.jpeg)

**Figure 12**: (a) Identification of Zones (b) Material Characterization graph Zone 8 (c) Material characterization graph Zone 9

![Material Characteristic data comparison between Zone 8 and Zone 9](assets/Material%20Characteristic%20data%20comparison%20between%20Zone%208%20and%20Zone%209.jpeg)

**Figure 13**: Material Characteristic data comparison between Zone 8 and Zone 9

**Table 3**: Chemical composition parameters (NS)

| Element              | Atomic No. | Netto  | Mass (%) | Mass Normal (%) | Atom (%) | Abs error (%) (1σ) | Rel. error (%) (1σ) |
|----------------------|------------|--------|----------|-----------------|----------|--------------------|---------------------|
| Titanium (Z8)        | 22         | 135150 | 83.12    | 90.73           | 87.49    | 2.34               | 2.81                |
| Aluminum (Z8)        | 13         | 9506   | 4.68     | 5.11            | 8.74     | 0.26               | 5.64                |
| Vanadium (Z8)        | 23         | 5776   | 3.81     | 4.16            | 3.77     | 0.19               | 4.96                |
| Titanium (Z9)        | 22         | 137800 | 81.44    | 90.49           | 86.77    | 2.29               | 2.81                |
| Aluminum (Z9)        | 13         | 9131   | 5.24     | 5.82            | 9.90     | 0.29               | 5.59                |
| Vanadium (Z9)        | 23         | 5186   | 3.32     | 3.69            | 3.32     | 0.18               | 5.34                |

#### Spheroidized Powder (S)

![Identification of Zones 10 and 11](assets/%28a%29%20Identification%20of%20zones%2C%20%28b%29%20Material%20Characterization%20graph%20Zone%2010%2C%20%28c%29%20Material%20characterization%20graph%20Zone%2011.jpeg)

**Figure 14**: (a) Identification of zones (b) Material Characterization graph Zone 10 (c) Material characterization graph Zone 11

![Material Characteristic data comparison between Zone 10 and Zone 11](assets/Material%20Characteristic%20data%20comparison%20between%20Zone%2010%20and%20Zone%2011.jpeg)

**Figure 15**: Material Characteristic data comparison between Zone 10 and Zone 11

**Table 4**: Chemical composition parameters (S)

| Element              | Atomic No. | Netto  | Mass (%) | Mass Normal (%) | Atom (%) | Abs error (%) (1σ) | Rel. error (%) (1σ) |
|----------------------|------------|--------|----------|-----------------|----------|--------------------|---------------------|
| Titanium (Z10)       | 22         | 132057 | 79.5     | 89.7            | 85.8     | 2.24               | 2.82                |
| Aluminum (Z10)       | 13         | 11114  | 5.5      | 6.2             | 10.5     | 0.30               | 5.51                |
| Vanadium (Z10)       | 23         | 5866   | 3.7      | 4.2             | 3.7      | 0.18               | 4.94                |
| Titanium (Z11)       | 22         | 133182 | 76.8     | 89.4            | 85.5     | 2.16               | 2.82                |
| Aluminum (Z11)       | 13         | 10317  | 5.3      | 6.2             | 10.6     | 0.30               | 5.55                |
| Vanadium (Z11)       | 23         | 5984   | 3.7      | 4.4             | 3.9      | 0.18               | 4.89                |

Slight local variations in Ti, Al and V content were observed between zones, but absolute errors remained low, confirming reliable measurements.

## 8. Conclusions

- Plasma spheroidization produces more spherical particles with fewer satellites compared to gas atomization.
- Spheroidized powder showed better flowability and higher apparent/tap density than the non-spheroidized powder.
- Particle size distributions of both powders were similar (mean ≈ 35 µm), but the spheroidized powder exhibited higher shape uniformity and lower measurement variability.
- SEM clearly distinguishes the two powders by the presence/absence of satellite particles.
- SEM-EDS confirmed the expected Ti-6Al-4V composition with only minor local variations between measurement zones.
- Overall, spheroidization improves packing efficiency, flow behavior and morphological consistency, which is highly beneficial for additive manufacturing and other powder-based processes.

## Tools & Methods Used

- Hall Funnel (ASTM B 213 / ASTM B 212)
- Tapping apparatus (ASTM B 527)
- Optical microscopy + vacuum spreading system
- Scanning Electron Microscopy (SEM) – BSE & SE modes
- SEM-EDS chemical analysis
- Python (data analysis, box plots, error bars)
```
