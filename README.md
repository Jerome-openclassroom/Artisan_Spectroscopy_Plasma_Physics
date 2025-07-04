# README – Artisan Spectroscopy and Plasma Analysis (Low-tech + AI)

## 🔬 Scientific Interest

Spectroscopy is a cornerstone tool in both physics and astronomy. It enables the decomposition of light emitted or absorbed by a source to analyze its chemical composition, physical state, or temperature. In this project, spectroscopy is applied to various light sources, ranging from the Sun to a synthetic plasmoid, with a hands-on, frugal, and AI-assisted methodology.

Notably, **plasma** represents **over 99% of the observable matter in the universe**, including stars, nebulae, and interstellar clouds. On Earth, plasma appears naturally in phenomena such as **auroras** and **lightning**. Understanding plasma spectra therefore bridges terrestrial and astrophysical physics.

## 🧰 Spectroscope Construction

A spectroscope was assembled using salvaged components:

- Lenses from an old binocular set
- Plössl-type telescope eyepiece
- Adjustable slit made from two razor blades
- 100 lines/mm diffraction grating
- Materials: PVC tubing, wood, screws

Observations were recorded through:

- Direct visual inspection
- Digiscopy (digital camera aligned with eyepiece)
- Webcam with an adapter

## 💡 Observed Sources

1. **Mercury discharge tube** (“neon” tube)
2. **Compact fluorescent lamp** (Hg vapor variant)
3. **High-pressure sodium streetlamp (Na + Hg)**
4. **Homemade plasmoid in glass globe**
5. **Sunlight diffused through magnesium carbonate pellet (MgCO₃)**

## ⚙️ The Carbon Plasmoid (Microwave-based)

A graphite rod was inserted into a glass globe and exposed inside a kitchen microwave. The electromagnetic field heated the rod, causing carbon vaporization and the formation of a luminous, unstable plasma — resembling a confined ball lightning.

This experiment visually recreates what is hypothesized in plasma physics as auto-sustained confined discharges, akin to phenomena still not fully explained in the lab.

## 🤖 Spectral Analysis with LLM

The plasmoid’s spectrum was analyzed using a large language model (GPT-4 / Grok):

- **Thermal continuum in orange** (\~590–610 nm), consistent with blackbody emission at 2500–3000 K
- **C₂ Swan bands** in the green (510–560 nm)
- Likely **CN violet bands** (385–420 nm), though partially attenuated due to camera sensor limitations

A Bayesian inference based on known reference spectra yielded a >93% probability of molecular band presence.

## ☀️ Solar Observation (Fraunhofer lines)

With safe indirect solar observation, the following absorption lines were visually identified:

- **Hα (656 nm)**
- **Na doublet (589.0 & 589.6 nm)**
- **Mg triplet (\~517 nm)**
- **Fe absorption lines (\~527–540 nm)**
- **Hβ (486 nm)**

⚠️ Never observe the Sun directly without proper safety filters. Here, a **MgCO₃ pellet** was used to safely diffuse sunlight.

## 📊 Software Workflow

- Outdated spectrometry software being non-functional, the entire analysis pipeline was rebuilt using:
  - **ImageJ**: spectral profile extraction
  - **Excel**: wavelength calibration (using known peaks) and charting

## 📁 Repository Structure

```
spectroscope/
adjustable_slit.JPG
→ Close-up of the entrance slit, built using two razor blades;
manually adjustable for optimal resolution and light throughput.

Fraunhofer_spectrum_digiscopy.JPG
→ Solar spectrum captured via digiscopy, showing prominent Fraunhofer absorption lines.

setting_day.JPG
→ Daytime setup for solar observation, using a magnesium carbonate pellet
as a white diffuser to safely project the Sun’s spectrum.

setting_night.JPG
→ Nighttime configuration with webcam, adapter, laptop and spectroscope;
used to capture streetlamp spectra (e.g. sodium vapor lamp).

webcam.JPG
→ Philips SPC900 webcam fitted with a 31.75 mm (1.25 inch) eyepiece adapter.

results/
Lamp_Hg_2.JPG
→ Spectrum from a compact fluorescent mercury vapor lamp (with phosphor coating).

Sodium_lamp.JPG
→ Spectrum from a high-pressure sodium streetlamp.

tube_Hg.JPG
→ Photograph of a low-pressure mercury discharge tube ("neon"-type).

plasmoid.PNG
→ Annotated spectrum of the microwave-induced carbon plasmoid.

spectre_lampe_Hg.JPG
→ Calibrated spectrogram of a mercury vapor lamp.

spectre_lampe_Na.JPG
→ Calibrated spectrogram of a sodium vapor streetlamp.
```

---

**Author:** Jérôme / Lyra Project 2025\
**License:** Open Science – free for pedagogical and scientific use

## 🔗 Related Repositories
[Main GitHub profile](https://github.com/Jerome-openclassroom)  
- [Related project: AI applied to Astrophysics](https://github.com/Jerome-openclassroom/AI_Astrophysics)  
- [Related project: VLTI Mirror Curvature Modeling (VBA, 2005)](https://github.com/Jerome-openclassroom/VLTI_Mirror_Curvature_Model_C_VBA_2005)
- [Related project: Lyra SunTrack](https://github.com/Jerome-openclassroom/Lyra_SunTrack)  


