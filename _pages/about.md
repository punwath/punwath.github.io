---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
table {
  border-collapse: collapse;
  border: none;
  margin: 0;
}
table thead {
  display: none;
}
table tr,
table th,
table td {
  border: none !important;
  background: transparent !important;
}
table td {
  padding: 0.75em 0.5em;
  vertical-align: top;
}
.pub-title a {
  text-decoration: none !important;
  color: inherit !important;
  font-weight: bold;
}

  /* Hide the theme toggle button */
.theme-toggle,
.theme-switch,
.palette-toggle,
.color-scheme-toggle,
button[aria-label*="theme" i],
button[aria-label*="palette" i],
button[title*="theme" i],
[id*="theme-toggle"],
[class*="theme-switch"] {
  display: none !important;
}

/* Force light mode regardless of toggle or system preference */
:root,
:root[data-theme],
html[data-theme="dark"],
body[data-theme="dark"],
body.dark-theme {
  --global-bg-color: #ffffff !important;
  --global-text-color: #3f3f3f !important;
  --global-base-color: #555 !important;
  --global-border-color: #f2f3f3 !important;
  --global-text-color-light: #8e8e8e !important;
  --global-link-color: #2f7f93 !important;
  --global-masthead-link-color: #3f3f3f !important;
  background-color: #ffffff !important;
  color: #3f3f3f !important;
}

@media (prefers-color-scheme: dark) {
  :root {
    --global-bg-color: #ffffff !important;
    --global-text-color: #3f3f3f !important;
  }
}
</style>

I am a Ph.D. candidate in Geology and Environmental Science at the University of Pittsburgh, advised by Dr. [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/). My research focuses on satellite remote sensing and machine learning for monitoring water quality across rivers, estuaries, and coastal waters. I work primarily with the multi-decadal Landsat archive (TM, ETM+, OLI, OLI-2) to track suspended sediment dynamics, surface water temperature, and other indicators of environmental change at global scales.

I am a NASA Future Investigator (FINESST) fellow and Ocean Optics Class alumni. My first-author research includes a global analysis of estuarine warming across 1,060 estuaries, published in *Limnology & Oceanography Letters* and recognized with an Early Career Publication Honor.

Before my PhD, I completed a Professional Master of Science at the University of Wisconsin–Madison, with a major in Environmental Observation and Informatics. Prior to graduate school, I spent five years working in GIS and data research in Cambodia, supporting community forestry and conservation stakeholders, for which I received a Civil Society Leadership Award from the Open Society Foundation.

I will graduate in August 2026. I am currently on the postdoctoral job market.

# News

* **2026-04** Our paper [Extent of sediment concentration trends associated with climate and human factors across global rivers](https://doi.org/10.1038/s41598-026-47267-2) (Prajapati, Gardner, & Prum) is published in *Scientific Reports*.
* **2026-03** Our paper [Operational near real-time global riverine sediment flux estimates from space](https://doi.org/10.1029/2025GL120407) (Lucchese et al.) is published in *Geophysical Research Letters*.
* **2026-02** Submitted manuscript on harmonizing Landsat TM, ETM+, OLI, and OLI-2 surface reflectance for long-term water quality monitoring.
* **2025-12** Presented at AGU Fall Meeting on harmonizing Landsat surface reflectance for long-term understanding of water quality in rivers.
* **2025** Attended the Ocean Optics summer school; processed NASA PACE OCI hyperspectral data using SeaDAS.
* **2025** Awarded the NASA Future Investigators in Earth and Space Science and Technology (FINESST) Fellowship (2025–2027).
* **2025** Our paper on [Improving Satellite Imagery Masking Using Multitask and Transfer Learning](https://doi.org/10.1109/JSTARS.2025.3551620) (Daroya et al.) is published in *IEEE JSTARS*.
* **2024-12** Presented at AGU Fall Meeting on Landsat harmonization for river water quality.
* **2024-06** Presented at the ASLO Summer Meeting on building a global suspended sediment concentration database with Landsat.
* **2024** Our paper [Widespread warming of Earth's estuaries](https://doi.org/10.1002/lol2.10389) (Prum, Harris, & Gardner) is published in *Limnology & Oceanography Letters*.
* **2024** Awarded the Andrew Mellon Predoctoral Fellowship, University of Pittsburgh.
* **2024** Awarded the Hydroinformatics Innovation Fellowship, Consortium of Universities for the Advancement of Hydrologic Science (CUAHSI).
* **2024** Awarded the Christopher Hapke Memorial Planetary Award, University of Pittsburgh.
* **2022** Received the *L&O Letters* Early Career Publication Honor from the Association for the Sciences of Limnology and Oceanography.
* **2021** Started Ph.D. at the University of Pittsburgh.

# Publications

|     |     |
| --- | --- |
| ssc-trends | <span class="pub-title">[**Extent of sediment concentration trends associated with climate and human factors across global rivers**](https://doi.org/10.1038/s41598-026-47267-2)</span><br>Rajaram Prajapati, [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/), **Punwath Prum**<br>*Scientific Reports* 2026<br>Leveraging more than 88 million satellite-derived suspended sediment estimates across more than 200,000 river segments globally, we found significant trends in one-third of rivers over a 38-year period, with declines concentrated in temperate and arid basins and increases in tropical basins. |
| ssc-deep-learning | **Towards global estimation of riverine suspended sediment flux using deep learning**<br>Pratiman Devkota, [Dongmei Feng](https://researchdirectory.uc.edu/p/fengdi), Anika Gupta, [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/), [Luisa Lucchese](https://www.luisalucchese.com/), **Punwath Prum**<br>*In review* 2026<br>A Long Short-Term Memory (LSTM) deep learning approach for quantifying riverine suspended sediment flux globally, trained on more than 100,000 in-situ measurements from 824 sites between 1984 and 2019. |
| sediment-flux | <span class="pub-title">[**Operational near real-time global riverine sediment flux estimates from space**](https://doi.org/10.1029/2025GL120407)</span><br>[Luisa Lucchese](https://www.luisalucchese.com/), [Rangel Daroya](https://rangeldaroya.github.io/), Travis Simmons, Punwath Prum, Nikki Tebaldi, [Tamlin Pavelsky](https://uncglobalhydrology.org/tamlin/), [Subhransu Maji](https://people.cs.umass.edu/~smaji/), [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/), [Colin Gleason](https://www.umass.edu/engineering/about/directory/colin-gleason)<br>*Geophysical Research Letters* 2026<br>We present global estimates of riverine sediment flux using the Harmonized Landsat Sentinel (HLS) and Surface Water and Ocean Topography (SWOT) products, providing 30 million estimates of suspended sediment flux between April 2023 and May 2025. |
| harmonization | **Harmonizing Landsat TM, ETM+, OLI, and OLI-2 surface reflectance data for long-term surface water quality monitoring**<br>**Punwath Prum**, Sam Sillen, Bennett Steele, [Xiao Yang](https://www.smu.edu/dedman/academics/departments/earth-sciences/people/faculty/xiao-yang), [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/)<br>*In review* 2026<br>Band-by-band adjustment models harmonize surface reflectance across four generations of Landsat sensors, trained on 9,555 overlapping observations and reducing inter-sensor bias from as high as 24% to under 5% across optical water types. |
| ssc-model | **Global model for riverine suspended sediment concentration from Landsat**<br>**Punwath Prum**, [Luisa Lucchese](https://www.luisalucchese.com/), [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/)<br>*In review* 2025<br>A global machine learning model for estimating riverine SSC from multiple Landsat satellites (TM, ETM+, OLI), trained on the largest global matchup database recorded with 240,000 paired in-situ SSC and surface reflectance observations. |
| masking | <span class="pub-title">[**Improving Satellite Imagery Masking Using Multitask and Transfer Learning**](https://doi.org/10.1109/JSTARS.2025.3551620)</span><br>[Rangel Daroya](https://rangeldaroya.github.io/), [Luisa Lucchese](https://www.luisalucchese.com/), Travis Simmons, **Punwath Prum**, [Tamlin Pavelsky](https://uncglobalhydrology.org/tamlin/), [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/), [Colin Gleason](https://www.umass.edu/engineering/about/directory/colin-gleason), [Subhransu Maji](https://people.cs.umass.edu/~smaji/)<br>*IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing* 2025<br>A unified multitask masking model that predicts water, cloud, cloud shadow, terrain shadow, and snow/ice from harmonized Landsat–Sentinel imagery, achieving a 30× speedup with reduced SSC estimation error. |
| estuarine-warming | <span class="pub-title">[**Widespread warming of Earth's estuaries**](https://doi.org/10.1002/lol2.10389)</span><br>**Punwath Prum**, [Lora Harris](https://www.umces.edu/lora-harris), [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/)<br>*Limnology & Oceanography Letters* 2024 (Early Career Publication Honor)<br>Using Landsat 5, 7, and 8 imagery from 1985 to 2022, I generated surface water temperature data over 1,060 estuaries globally and found that 47% of Earth's estuaries are warming, with the most rapid warming at higher latitudes. |
| ecph-perspectives | <span class="pub-title">[**Just hit submit—Perspectives and advice from L&O Letters Early Career Publication Honor awardees**](https://doi.org/10.1002/lob.10658)</span><br>Renny Barton et al. (incl. **Punwath Prum**)<br>*Limnology and Oceanography Bulletin* 2024<br>Twelve early career researchers awarded the 2022 L&O Letters Early Career Publication Honor share experiences and advice for future applicants. |

# Work in Progress

|     |     |
| --- | --- |
| estuary-trends | **Trends in suspended sediment concentration in global estuaries from 1984 to 2024**<br>**Punwath Prum**, [Anna Braswell](https://ffgs.ifas.ufl.edu/faculty/braswell-anna/), [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/)<br>*In preparation* 2026<br>Quantifying spatial and temporal patterns of suspended sediment concentration across more than 1,000 global estuaries from 1984 to 2024 and identifying the climatic and anthropogenic drivers shaping coastal sediment dynamics. |
| cyano-blooms | **Integrating Harmonized Landsat–Sentinel-2 imagery and climate drivers for CONUS-scale detection of riverine cyanobacteria blooms**<br>**Punwath Prum**, [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/)<br>*In preparation* 2026<br>Combining Harmonized Landsat–Sentinel-2 imagery with climate drivers to detect and characterize riverine cyanobacteria blooms at the CONUS scale. |
| cross-validation | **Random cross-validation inflates satellite-derived suspended sediment retrieval accuracy**<br>**Punwath Prum**, [John Gardner](https://emes.unc.edu/people-indiv/john-gardner/)<br>*In preparation* 2026<br>Methodological investigation showing that random cross-validation overestimates the accuracy of satellite-based suspended sediment retrieval models, with implications for honest evaluation of geospatial machine learning. |
