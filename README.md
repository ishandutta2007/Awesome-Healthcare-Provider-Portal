# Awesome-Healthcare-Provider-Portal

# Top Healthcare Provider Portal Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Patient Engagement, Clinical Data Access & Self-Service Healthcare*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Healthcare Provider Portals**. These tools enable patients to access their medical records, schedule appointments, communicate with care teams, and manage their health journey—while giving providers a secure channel for engagement, telehealth, and care coordination.

**Examples** include ServiceNow Provider Portal, Epic MyChart, Cerner HealtheLife, Athenahealth Patient Portal, NextGen Patient Portal, eClinicalWorks, Allscripts FollowMyHealth, Meditech Expanse, Kareo Patient Portal, and AdvancedMD Patient Portal (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted patient portals, FHIR-based record aggregation, and open EHR platforms with patient-facing modules—ideal for clinics, health systems, and developers building sovereign healthcare engagement infrastructure without per-patient licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Provider Portal](https://www.servicenow.com/)**  
  Healthcare provider portal capabilities on the Now Platform for patient access, care coordination, and clinical workflows; integrates with EHR systems and supports HIPAA-compliant patient engagement.

- **[Epic MyChart](https://www.epic.com/)**  
  The most widely adopted patient portal in the US, integrated with Epic EHR; provides appointment scheduling, test results, medication refills, secure messaging, and telehealth access for millions of patients.

- **[Cerner HealtheLife](https://www.oracle.com/health/)**  
  Oracle Cerner's patient portal for accessing health records, scheduling, messaging, and health management tools; integrated with Cerner Millennium EHR.

- **[Athenahealth Patient Portal](https://www.athenahealth.com/)**  
  Patient portal within the athenahealth network for appointment requests, prescription refills, test results, and secure communication with providers.

- **[NextGen Patient Portal](https://www.nextgen.com/)**  
  Patient engagement portal integrated with NextGen Enterprise EHR/PM; supports scheduling, records access, messaging, and telehealth.

- **[eClinicalWorks](https://www.eclinicalworks.com/)**  
  EHR/PM platform with a patient portal (healow) for appointment scheduling, records access, and health tracking across mobile and web.

- **[Allscripts FollowMyHealth](https://www.allscripts.com/)**  
  Patient portal (now Veradigm) for health record access, appointment management, and provider communication across Allscripts/Veradigm EHR clients.

- **[Meditech Expanse](https://www.meditech.com/)**  
  EHR platform with patient portal capabilities for record access, scheduling, and communication within Meditech's Expanse web-based system.

- **[Kareo Patient Portal](https://www.kareo.com/)**  
  Patient portal for small practices using Kareo EHR/PM; supports appointment requests, messaging, and basic record access.

- **[AdvancedMD Patient Portal](https://www.advancedmd.com/)**  
  Patient engagement portal integrated with AdvancedMD EHR/PM for scheduling, intake forms, messaging, and records access.

## Open-Source GitHub Projects

- **[Mere Medical](https://github.com/cfu288/mere-medical)**  
  Open-source personal health record (PHR) aggregator (MIT, ~250 GitHub stars) built on HL7 FHIR; uses SMART on FHIR standalone launch to authenticate directly to Epic MyChart, Cerner, Allscripts, and DrChrono/OnPatient; aggregates records from multiple EHRs into a unified health timeline with local-first architecture—data stored on the patient's device, not third-party servers; named a finalist in AMIA's 2025 HL7 FHIR App Competition .

- **[OpenEMR Patient Portal](https://github.com/openemr/openemr)**  
  The patient portal module within OpenEMR, the most mature open-source EHR with strong HIPAA-oriented safeguards ; provides patients access to records, appointment scheduling, secure messaging, and prescription requests; OpenEMR 8.5.0 demo includes patient portal login credentials for testing ; partnership with Opal Health Informatics Group adds real-time patient-in-the-loop data access .

- **[Ottehr Patient Portal](https://github.com/masslight/ottehr)**  
  Modular, production-ready open-source EHR stack with a dedicated patient portal component (MIT); patient-facing registration website for appointment creation, telemedicine calls, rescheduling, check-in, intake chatbot, and appointment listing; requires a free Oystehr account for backend hosting; designed for developers to fork, white-label, and build new health-tech products .

- **[PulsePortal](https://github.com/shads-01/PulsePortal)**  
  Smart hospital portal with AI-powered patient engagement (Laravel/React); features Jitsi teleconsultations, AI health chatbot, AI specialist recommendation, AI patient history summarization, medicine autocomplete, prescription PDF generation, real-time notifications, room admission management, and role-based access control for patients, doctors, and admins .

- **[Portail Patient](https://github.com/SaamNoLimits/HealthCare)**  
  Modern patient portal (Next.js/TypeScript/Tailwind) with dashboard, appointment management, medical records (allergies, treatments), personalized health recommendations, dark/light mode, and responsive accessibility-focused design; uses mocked data ready for integration with real healthcare APIs .

- **[GNU Health](https://github.com/gnuhealth)**  
  Free/Libre hospital and health information system (GPLv3) declared a Digital Public Good by the DPGA; includes patient management, appointments, medical encounters, prescriptions, and reporting; Suriname adopted GNU Health for its national public healthcare system alongside a Patient Portal and My Health App ; however, security benchmarking notes limited native authentication capabilities (no native MFA) and reliance on organizational configuration for HIPAA/GDPR compliance .

### Additional Strong Open-Source Options

- **OpenMRS** — Open-source EHR platform with modular architecture and FHIR support via modules; provides a foundation for building patient-facing portals through community modules; security benchmarking rates it moderate for compliance readiness, with strong HL7/FHIR interoperability security .
- **Bahmni** — Open-source EHR/HMIS built on OpenMRS and Odoo; includes patient-facing capabilities and strong HL7/FHIR support; rated moderate for regulatory compliance with comprehensive audit trails .
- **OSCAR EMR** — Canadian open-source EHR with strong HIPAA-oriented safeguards and native two-factor authentication; patient portal capabilities available through community add-ons .
- **FHIR Patient Portal Components** — React component library (`@symbionix/patient-portal`) for building FHIR-compatible patient portal interfaces with authentication, patient search, and listing components (MIT) .
- **Canvas Medical Mobile Patient App** — FHIR-based cross-platform mobile app for patients supporting scheduling, messaging, payments, and medical records; forkable and customizable (TypeScript) .

**Frameworks for building custom systems**: Combine **OpenEMR** for a complete EHR with integrated patient portal and HIPAA-oriented safeguards, **Mere Medical** for FHIR-based multi-EHR record aggregation with local-first privacy, **Ottehr** for a modular headless EHR stack with patient portal and telemedicine, and **PulsePortal** for AI-augmented patient engagement in a self-hosted healthcare provider portal stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Healthcare provider portals handling protected health information (PHI) must comply with applicable regulations (HIPAA in the US, GDPR in the EU, and local health data laws); security benchmarking of open-source EHRs notes universal gaps in native application-level encryption for data at rest and message-level encryption for HL7/FHIR exchanges .
- Self-hosted open-source solutions vary significantly in maturity—OpenEMR provides the most comprehensive HIPAA-oriented foundation, while Mere Medical focuses on patient-owned record aggregation rather than provider-side clinical workflows; full provider portal deployments require substantial security hardening and compliance validation.
- Verify license terms for commercial use; Mere Medical uses MIT , OpenEMR uses GPL-2.0, Ottehr uses MIT , and GNU Health uses GPLv3 .

---

**Made for healthcare CIOs, clinical informatics teams, patient engagement leaders, and health-tech developers.**  
Let's make healthcare provider portals more open, patient-centered, and interoperable.
