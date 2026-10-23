# Digital Forensics Investigation

**Windows Laptop & iPhone Evidence Analysis | Academic Case Study**

![Status](https://img.shields.io/badge/Project-Academic%20Simulation-blue) ![Focus](https://img.shields.io/badge/Focus-Digital%20Forensics-informational)

## Overview

This repository documents a **simulated digital forensic investigation** completed during my BSc (Hons) Cybersecurity degree at Coventry University London. The university exercise concerned a fictional counterfeit-currency investigation and involved a staged crime scene and university-supplied USB media containing laptop and iPhone forensic datasets.

My work covered evidence identification, forensic acquisition, analysis of Windows and iPhone artefacts, correlation of findings, chain-of-custody documentation, and an expert-witness-style report. **This was an academic exercise, not a real criminal case, police appointment, or professional expert-witness engagement.**

## Investigation objectives

- Identify and document relevant digital exhibits in the simulated scene.
- Preserve evidence and create forensic copies of the supplied media.
- Verify acquired evidence integrity using recorded cryptographic hashes.
- Examine laptop and iPhone artefacts for relevant activity and connections.
- Correlate communications, locations, timestamps, and device artefacts.
- Produce a traceable report with supporting screenshots and evidence records.

## Tools and techniques

| Tool / technique | Use in this project |
|---|---|
| **SafeBlock** | Write-blocking during handling of the supplied USB evidence |
| **FTK Imager** | Evidence acquisition, E01 imaging, and hash verification |
| **Autopsy** | Examination of the laptop forensic dataset |
| **iLEAPP** | Extraction and review of iPhone artefacts |
| **MD5 / SHA-1** | Recorded checks for forensic image integrity |
| **Chain of custody / audit trail** | Documentation of evidence handling and analysis steps |

## Investigation workflow

### 1. Simulated scene and evidence preservation

I helped document a staged crime scene, identify potentially relevant items, and record evidence handling. Two USB drives supplied by the university were used for the laptop and iPhone datasets.

**Evidence image:** _To add after reviewing publication permissions and redacting personal information._

### 2. Forensic acquisition

I followed a write-blocking workflow using SafeBlock, then used FTK Imager to create E01 forensic images of the supplied media. I recorded evidence metadata and MD5/SHA-1 hash values as part of the acquisition and verification process.

**Evidence images to add:** write-blocking setup, FTK Imager acquisition settings, and hash verification output.

### 3. Laptop examination — Autopsy

I examined the laptop dataset for user and file-system activity. The report documents findings including:

- A user profile associated with the fictional subject.
- A concealed encrypted virtual-disk artefact (`vault.vhdx`).
- Printer-related artefacts associated with the case scenario.
- Communications and timestamps relevant to the simulated investigation.

**Evidence images to add:** selected Autopsy views with brief captions explaining what each artefact establishes.

### 4. iPhone examination — iLEAPP

I used iLEAPP to review mobile artefacts, including account information, messaging activity, application records, and location-related data. The report discusses how these records helped connect events in the fictional case.

**Evidence images to add:** selected, redacted iLEAPP output and supporting location or application artefacts.

### 5. Correlation and reporting

I compared artefacts across the laptop and iPhone datasets, considering how timestamps, communications, locations, and device activity related to the investigation questions. I documented my methods and conclusions in an expert-witness-style academic report, supported by an activity log, evidence forms, and chain-of-custody records.

**Important distinction:** The findings and conclusions relate to the **provided fictional case dataset**; they are not findings about real individuals.

## Skills demonstrated

- Forensic evidence handling and acquisition
- Write-blocking and image-integrity checks
- Windows and mobile forensic artefact examination
- Cross-device evidence correlation
- Chain-of-custody and audit-trail documentation
- Technical reporting and evidence-based reasoning

## Repository contents

```text
digital-forensics-investigation/
├── README.md
├── screenshots/             # Curated, authorised and redacted evidence images
├── documentation/           # Sanitised report or case-study PDF (if cleared for release)
└── methodology.md           # Optional detailed workflow and analysis notes
```

> **Publication note:** The original university-supplied forensic images and extracted datasets are **not included** in this repository. Screenshots and documents will be published only where redistribution is permitted, with credentials, personal data, identifiable classmates, and other sensitive material removed. Any simulated warrant, investigator credential, or certificate must be labelled as an academic prop, not a genuine professional credential.

## Standards referenced in the academic report

The report discusses the ACPO Good Practice Guide for Digital Evidence (2012), ISO/IEC 27037:2012, NIST SP 800-86, the Police and Criminal Evidence Act 1984, and the Forensic Science Regulator's Code of Practice. These are **frameworks referenced in the coursework**, not a claim of external accreditation or independent validation.

## Author

**Ebuka Fidelis**  
BSc (Hons) Cybersecurity, First Class Honours  
CompTIA A+ Certified  
[LinkedIn](https://www.linkedin.com/in/ebukafidelis)
