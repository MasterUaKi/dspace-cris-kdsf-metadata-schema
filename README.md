<!--
  ====================================================================
  KDSF 2.1 Metadata Schema for DSpace-CRIS (Documentation)
  Version: 2.0.0
  Date: 2026-08-27
  Author: Oleh Riabtsev
  ====================================================================
-->

# KDSF 2.1 Complete Metadata Schema for DSpace-CRIS

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.placeholder.svg)](https://doi.org/10.5281/zenodo.22127927)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DSpace-CRIS](https://img.shields.io/badge/DSpace--CRIS-7%20%7C%208-blue.svg)](https://wiki.lyrasis.org/display/DSPACECRIS)

A standardized, complete metadata schema implementation for **DSpace-CRIS** based on the official specification of the **Kerndatensatz Forschung (KDSF)** version 2.1 (Commission for Research Information in Germany - KFiD).

## Overview

* **Standard:** Kerndatensatz Forschung (KDSF) 2.1
* **Version:** 2.0.0
* **Release Date:** 2026-08-27
* **Author:** Oleh Riabtsev
* **Namespace:** `https://kerndatensatz-forschung.de/index.php?id=kdsf_standard_main`
* **Prefix:** `kdsf`
* **Total Metadata Fields:** 513 fields

## Covered Core & Extended Entities (18 Blocks)

| Entity / Block ID | DSpace Element | Description | Fields Count |
| :--- | :--- | :--- | :--- |
| **KDSF-B-0** | `person` | Person (Academic staff, researchers, creators) | 67 |
| **KDSF-B-1** | `employment` | Employment details (Beschäftigungsverhältnis) | 45 |
| **KDSF-B-2** | `project` | Research projects & consortium structures | 32 |
| **KDSF-B-3** | `funding` | Grants, funding programs & financial volumes | 21 |
| **KDSF-B-4** | `externalproject` | External subprojects & consortium partners | 7 |
| **KDSF-B-5** | `doctoralprogram` | Structured doctoral programs | 16 |
| **KDSF-B-6** | `doctoralprocess` | Doctoral procedures & supervisions | 27 |
| **KDSF-B-7** | `habilitationprocess` | Habilitation procedures | 5 |
| **KDSF-B-8** | `publication` | Publications, journals, proceedings & book chapters | 106 |
| **KDSF-B-9** | `patent` | Patents, applications & priority claims | 25 |
| **KDSF-B-10** | `otherip` | Non-patent IP rights (Gebrauchsmuster, brands) | 16 |
| **KDSF-B-11** | `spinoff` | Research spin-offs (Ausgründungen) | 10 |
| **KDSF-B-12** | `award` | Academic awards, prizes & honors | 16 |
| **KDSF-B-13** | `infra` | Research infrastructures & core facilities | 40 |
| **KDSF-B-14** | `orgunit` | Organizational units, faculties & institutes | 18 |
| **KDSF-B-15** | `externalorg` | External organizations, funders & corporations | 43 |
| **KDSF-B-16** | `competencespinoff` | Competence-based spin-offs (Transfer) | 8 |
| **KDSF-B-17** | `startupproject` | Academic startup projects & pre-founding | 11 |

## Installation in DSpace-CRIS

### 1. Import Schema Registry
Copy `kdsf-metadata-schema-full.xml` to your DSpace server and load it via `registry-loader`:

```bash
/dspace/bin/dspace registry-loader -metadata /path/to/kdsf-metadata-schema-full.xml