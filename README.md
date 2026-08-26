# KDSF 2.1 Full Metadata Schema for DSpace-CRIS (Kerndatensatz Forschung)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22107818.svg)](https://doi.org/10.5281/zenodo.22107818)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Standard: KDSF](https://img.shields.io/badge/Standard-KDSF%202.1%20(143%20Fields)-green.svg)](https://kerndatensatz-forschung.de/)
[![DSpace-CRIS Compatible](https://img.shields.io/badge/DSpace--CRIS-7.x%20%7C%208.x-blue.svg)](https://github.com/4Science/DSpace)

> **Version:** 1.0.0  
> **Release Date:** 2026-08-26  
> **Author:** Oleh Riabtsev  
> **DOI:** [10.5281/zenodo.22107818](https://doi.org/10.5281/zenodo.22107818)  
> **Namespace:** `https://kerndatensatz-forschung.de/kdsf_standard/2.0#`  
> **Prefix:** `kdsf`  
> **Schema File:** `schema/kdsf-metadata-schema-full.xml` (143 Fields)

---

## 🇩🇪 Beschreibung (Deutsch)

Dieses Repository enthält die vollständige, konsolidierte Metadatenschema-Definition des **Kerndatensatz Forschung (KDSF 2.1)** für **DSpace-CRIS 7+ und 8+**. Es umfasst **143 standardisierte Metadatenfelder** über alle 16 Module der KDSF-Spezifikation zur Abbildung von Forschungsaktivitäten, Personal, Projekten, Promotionen und Transferleistungen an deutschen Wissenschaftseinrichtungen.

### Modulabdeckung des KDSF-Vollschemas (143 Felder)

| KDSF-Modul | DSpace-Element | Felder | Beschreibung |
| :--- | :--- | :---: | :--- |
| **KDSF-B-0** | `kdsf.person.*` | 11 | Forschende & Personal (ORCID, GND, Scopus ID, ResearcherID, Stammdaten) |
| **KDSF-B-1** | `kdsf.employment.*` | 13 | Beschäftigungsverhältnisse, Befristung, VZÄ/FTE, Personalkategorien, Tenure Track |
| **KDSF-B-2** | `kdsf.project.*` | 10 | Drittmittel- und Eigenforschungsprojekte, Zweck, Laufzeiten, Fachsystematik |
| **KDSF-B-3** | `kdsf.funding.*` | 6 | Förderungen, Bewilligungssummen, Förderprogramme, Jahreserträge |
| **KDSF-B-4** | `kdsf.externalproject.*` | 3 | Externe Teilprojekte und Partner-Bewilligungssummen |
| **KDSF-B-5** | `kdsf.doctoralprogram.*` | 9 | Strukturierte Promotionsprogramme und Graduiertenschulen |
| **KDSF-B-6** | `kdsf.doctoralprocess.*` | 13 | Promotionsverfahren, Kooperationen, Promotionsstatus, Erstbetreuung |
| **KDSF-B-7** | `kdsf.habilitationprocess.*` | 8 | Habilitationsverfahren und Venia Legendi |
| **KDSF-B-8** | `kdsf.publication.*` | 13 | Publikationen, Open-Access-Status, Lizenzen, Peer-Review, Identifier |
| **KDSF-B-9** | `kdsf.patent.*` | 10 | Patente, IPC-Klassen, Schutzrechtsgebiete, Erteilungsstatus |
| **KDSF-B-10** | `kdsf.otherip.*` | 6 | Sonstiges geistiges Eigentum (Gebrauchsmuster, Marken, Software) |
| **KDSF-B-11** | `kdsf.spinoff.*` | 7 | Akademische Ausgründungen, Spin-Offs, Beteiligungen, NACE-Zweige |
| **KDSF-B-12** | `kdsf.award.*` | 5 | Preise, Ehrungen, Auszeichnungen und Reichweite |
| **KDSF-B-13** | `kdsf.infra.*` | 10 | Forschungsinfrastrukturen, Großgeräte, ROR/MERIL ID, Zugangsarten |
| **KDSF-B-14** | `kdsf.orgunit.*` | 4 | Interne Organisationseinheiten, Fakultäten, Institute (GERiT ID) |
| **KDSF-B-15** | `kdsf.externalorg.*` | 15 | Externe Organisationen, Mittelgeber, Kooperationspartner (ROR, GND, ISNI) |

---

## 🇬🇧 Overview (English)

This repository provides the full, consolidated **KDSF (Kerndatensatz Forschung 2.1)** XML metadata registry schema for **DSpace-CRIS**. Covering **143 granular metadata fields**, it provides complete compliance for institutional research information management.

---

## 📥 Import in DSpace-CRIS

```bash
[dspace]/bin/dspace registry-loader -m schema/kdsf-metadata-schema-full.xml

}
  url          = {[https://doi.org/10.5281/zenodo.22107818](https://doi.org/10.5281/zenodo.22107818)}
  doi          = {10.5281/zenodo.22107818},
  publisher    = {Zenodo},
  year         = 2026,
  title        = {KDSF 2.1 Full Metadata Schema for DSpace-CRIS (143 Fields)},
  author       = {Oleh Riabtsev},
@misc{riabtsev_2026_kdsf_2_1_schema,
Фрагмент коду
🔗 Zitation / Citation

Veröffentlicht unter der MIT License.
📜 Lizenz / License
