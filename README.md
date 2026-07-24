# Beyond-Gut vCurrent - clinical screening tool 2026

> **Beyond-Gut is an offline HTML application for browser-based clinical gut health screening. The current release combines questionnaire-led assessment, pattern recognition, and clinical routing support.**

[![Platform](https://img.shields.io/badge/Platform-HTML%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vCurrent-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ryan-kingbsz8456/beyond-gut-routing-tool?style=flat-square)](https://github.com/ryan-kingbsz8456/beyond-gut-routing-tool)

---

<p align="center">
  <a href="https://ryan-kingbsz8456.github.io/beyond-gut-routing-tool/">
    <img src="https://img.shields.io/badge/Download-Beyond--Gut%20Latest-brightgreen?style=for-the-badge" alt="Download Beyond-Gut">
  </a>
</p>

> **[Download Beyond-Gut vCurrent](https://ryan-kingbsz8456.github.io/beyond-gut-routing-tool/)**

---

[Download Latest Build](https://ryan-kingbsz8456.github.io/beyond-gut-routing-tool/)

---

## Overview

Beyond-Gut provides a browser-based aid for reviewing gut health in clinical environments. It supports a consistent intake process and pattern-focused screening while remaining usable without an internet connection, making it suitable for offline workflows in primary care and gastroenterology.

The application combines patient questionnaire answers with holistic screening axes and routing logic to help structure information for follow-up. Clinicians can also use specialty-oriented investigation lists and export the collected data for subsequent analysis or transfer.

---

## What It Includes

- A 15-item GSRS core symptom questionnaire for consistent symptom collection
- Six holistic screening axes that extend assessment beyond one symptom group
- Twelve pattern detection engines for pattern-based interpretation
- Four clinical routing tiers to organize possible next steps
- Investigation lists tailored to primary care and gastroenterology
- An offline-first, single-file HTML application that runs directly in a browser
- CSV import and export for handling and transferring records
- Distinct patient and clinician views for separate screening needs

---

## Getting Started

1. Download the repository or clone it locally.
2. Open the primary HTML file with a modern browser.
3. Use the application directly; ordinary offline operation does not require a server.

To clone the project:

`git clone https://github.com/ryan-kingbsz8456/beyond-gut-routing-tool.git

You can start the tool by opening the HTML application locally, or use the download link provided above.

---

## Using the Application

The basic screening flow is:

1. Launch the application in a browser.
2. Select the view that matches the current session.
3. Provide the questionnaire answers and other screening information.
4. Examine the detected patterns and routing results.
5. Export the session as CSV when the record needs to be archived or shared.

When working with an existing record, import its CSV file first. The interface can then display the patient information and clinician guidance derived from that data.

---

## Configuration and Data Handling

Beyond-Gut is packaged as one HTML file, meaning its main behavior is managed within the application rather than through a separate configuration folder.

Where a deployment supports configuration or stored data, place the associated files next to the HTML application. CSV import and export can be used to move data between sessions.

---

## System Requirements

- A current HTML-compatible browser
- JavaScript enabled
- Permission to open local files for offline operation
- Optional CSV capability for import and export workflows

The extracted project metadata does not list any additional runtime requirement.

---

## Frequently Asked Questions

**Can Beyond-Gut be used without an internet connection?**  
Yes. It is described as an offline-first HTML application.

**Which users and settings is it intended for?**  
The tool is intended for clinical screening, with particular relevance to primary care and gastroenterology workflows.

**Does the application support data transfer?**  
Yes. Records can be imported from and exported to CSV.

**Are separate user views available?**  
Yes. Beyond-Gut provides patient and clinician views.

**How can I find the newest version?**  
Follow the download link above or review the repository for the latest build and project updates.

**What should I check if the application does not display properly?**  
Use a modern browser, verify that JavaScript is enabled, and reopen the single HTML file from the local system.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
