---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Learning
description: "FHIR® Lab supports learning and capacity development for health data interoperability and standards, including HL7® FHIR®, SNOMED CT and LOINC. Through hands-on activities, use cases and guided walkthroughs, policymakers, stakeholders and implementers can experience the real-world value of interoperability using standards-based digital health tools."

# Micro navigation
micro_nav: true

# Page navigation
# page_nav:
#   prev:
#        content: Learning
#        url: '#'
#    next:
#        content: Testing
#        url: '/services'

---

# Overview

**Accelerating the adoption of digital health standards and interoperability.**

FHIR Lab provides a simulated, fully functional environment that demystifies digital health interoperability. Through real-world healthcare use cases and interactive walkthroughs, decision-makers and implementers can see how interoperability improves patient care, health system performance and data-driven decision-making.

# Who is it for?

- Policymakers and health system leaders
- Healthcare workers
- Health IT implementers and developers
- Educators and trainers in digital health
- Development partners and donors

# Learning activities

FHIR Lab resources make it easy to explore the practical applications of digital health standards and interoperability. You can explore the tools freely and set up your own workflows to support adoption in your setting.

To help you get started, we have curated the activities below, showing how different users can work with the tools currently available in the sandbox.

## 1. Understand the foundations

Learn the foundational concepts of FHIR and clinical terminology, and why they matter.

### Activity 1.1: Terminology services

See core terminology concepts in action, including code systems (such as SNOMED CT and LOINC) and mappings, or create your own ValueSets for demonstration.

1. Open [FHIR Lab Ontoserver](https://tx.fhirlab.net/){:target="_blank"}. No username or password is required.
2. Use the **Shrimp** browser to explore code systems, ValueSets and concepts. Try finding a SNOMED CT or LOINC concept you use in practice.
3. Open the **Snapper** authoring tool and [create a new CodeSystem, then add ValueSets and concepts](https://ontoserver-wp.csiro.au/technical-documentation/snapper-documentation/snapperauthor-guide/add-a-new-fhir-resource/create-a-new-codesystem/){:target="_blank"}.
4. Use [Postman](https://www.postman.com/downloads/){:target="_blank"} or another API testing tool to try simple operations, such as looking up a concept or expanding a ValueSet.
5. To get started quickly, use the [example Ontoserver Postman collection](https://www.postman.com/jimsteel/ontoserver/collection/k4gv6q6/ontoserver-6-example-fhir-terminology-requests){:target="_blank"}. Set the base URL to the FHIR Lab Ontoserver API endpoint: `https://tx.fhirlab.net/fhir`

### Activity 1.2: FHIR resources

Learn what FHIR resources are, explore common resources on the HAPI FHIR server and understand how health data is represented in FHIR. Then create your first FHIR resource using the HAPI web interface or Postman.

1. Open the FHIR server web interface at [cdr.fhirlab.net](https://cdr.fhirlab.net/){:target="_blank"}, or use the FHIR API endpoint `https://cdr.fhirlab.net/fhir` in Postman. No authentication is required.
2. Query the server to explore existing resources and understand how FHIR data is structured.
3. Add a new resource to the server. Don't worry about making mistakes: FHIR Lab is designed for you to experiment freely.

**Need a head start?** Try the [example Postman collections](https://github.com/upmsilab/2025JuneFHIRConnectathon?tab=readme-ov-file#sample-postman-collections-and-data){:target="_blank"} from our recent FHIR Connectathon.

## 2. Demonstrate standards in action

Showcase standards in action with real-world healthcare examples using synthetic patient data.

### Activity 2.1: FHIR Questionnaires and forms

Explore the basics of FHIR Questionnaires, and convert paper forms into standardised FHIR Questionnaires for data capture and exchange across multiple applications. A single standardised form can be reused across different EMRs and mobile applications, which standardises data entry and improves data quality.

This activity uses the Aidbox FHIR platform available in FHIR Lab. You can also use other standards-based tools, such as the NLM Form Builder, for training and practice.

1. Request access to the FHIR Lab Aidbox instance. Access is free for FHIR Lab users.
2. Log in to Aidbox and open the **Forms** module.
3. Upload a paper form and convert it into a FHIR Questionnaire, either with AI assistance or manually.
4. Bind FHIR ValueSets to form fields to capture coded data.

New to Aidbox Forms? Watch this [introductory tutorial](https://youtu.be/20bprWplCDo?si=J4xvTymjAWG2E0UC){:target="_blank"}.

### Related FHIR Lab resources

- **Bahmni / OpenMRS:** explore pre-designed clinical workflows to see how structured, standardised data can be captured at the point of care using terminologies and synthetic patient data.
- **Ontoserver:** understand terminology concepts, mappings and standard code usage (such as SNOMED CT and LOINC).
- **OpenMRS integration:** explore how ValueSets from a FHIR terminology server can be integrated into a local EMR as interface terminology.

# Tools available in FHIR Lab

| Tool | Description |
| --- | --- |
| **HAPI FHIR Server** | Open-source FHIR R4 server to store and query clinical data. |
| **Ontoserver** | FHIR terminology server supporting SNOMED CT, LOINC and custom ValueSets. |
| **OpenMRS** *(coming soon)* | Integrated EMR environment to simulate structured data capture and transformation into FHIR. |

---

**Let's make interoperability real, together.**
