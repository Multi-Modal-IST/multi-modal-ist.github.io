# MMIST-Lung

Lung cancer is one of the most prevalent and lethal malignancies worldwide. To support the development and evaluation of multi-modal learning methods under realistic clinical conditions, we curated **MMIST-Lung**, a multi-center, multi-modal, and longitudinal lung cancer dataset comprising **1,365 patients**. The cohort combines data from **CPTAC-LSCC, CPTAC-LUAD, TCGA-LUSC, and TCGA-LUAD**, including 1,026 patients from TCGA and 339 from CPTAC, and covers both Lung Squamous Cell Carcinoma (LUSC/LSCC) and Lung Adenocarcinoma (LUAD). The dataset integrates clinical information, transcriptomic profiles, whole-slide images (WSI), CT and PET scans, as well as longitudinal follow-up and treatment data.

[MMIST-Lung](https://multi-modal-ist.github.io/datasets/Lung/)

### Number of modalities across the Dataset

| Modality | Patients | Missingness | Alive @12 months | Deceased @12 months |
|----------|----------|-------------|------------------|---------------------|
| Clinical | 1365 | 0% | 1169 (86%) | 196 (14%) |
| Transcriptomics | 1284 | 6% | 1107 (86%) | 177 (14%) |
| Follow-up | 880 | 35% | 777 (88%) | 103 (12%) |
| Chemotherapy | 277 | 80% | 245 (88%) | 32 (12%) |
| Radiation Therapy | 923 | 32% | 804 (87%) | 119 (13%) |
| Surgery | 291 | 79% | 250 (86%) | 41 (14%) |
| Immunotherapy | 49 | 96% | 45 (92%) | 4 (8%) |
| WSI | 1359 | 0.4% | 1164 (86%) | 195 (14%) |
| CT | 71 | 95% | 58 (82%) | 13 (18%) |
| PET | 33 | 98% | 26 (79%) | 7 (21%) |

:contentReference[oaicite:1]{index=1}

### Imaging Data

The dataset contains **5,427 whole-slide images**, **482 CT scans**, and **144 PET volumes**. Patients may have multiple imaging instances per modality, reflecting the heterogeneity and longitudinal nature of real-world clinical data. :contentReference[oaicite:2]{index=2}

### Longitudinal Data

Longitudinal follow-up information is available for **880 patients**, comprising **1,431 follow-up records**. The dataset also includes longitudinal treatment information for chemotherapy, radiation therapy, surgery, and immunotherapy, enabling dynamic survival prediction and time-to-event modelling. :contentReference[oaicite:3]{index=3}


#### Institute for Systems and Robotics (ISR-Lisboa)

Curated at [ISR](http://welcome.isr.tecnico.ulisboa.pt/), [IST](http://tecnico.ulisboa.pt/) - [Universidade de Lisboa](http://ulisboa.pt/).


#### Contact Info

[rita.cordeiro@tecnico.ulisboa.pt](mailto:rita.cordeiro@tecnico.ulisboa.pt), [ritaverdelho@tecnico.ulisboa.pt](mailto:ritaverdelho@tecnico.ulisboa.pt)

  
