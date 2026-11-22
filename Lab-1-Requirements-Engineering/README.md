# Lab 1 – Requirements Engineering

## Overview

Lab 1 focuses on requirements engineering as the first stage of the four-lab software development process. The overall project is to engineer an Internet search engine similar to Google, Bing, or DuckDuckGo, or at least parts of one.

The following labs build on this work and cover system modelling, design patterns, and API design.

## Preparation before the lab

Complete the preparation tasks before attending the lab. Submit **one document** containing the UML use case diagram and textual descriptions for every use case.

### Preparation Task 1 – Use cases

Identify all users of the search engine and how they interact with the system.

- Focus on the users' perspective: **what do users do?**
- Do not describe technical aspects or specify what the system does.
- Draw a UML use case diagram showing the actors and their use cases.

### Preparation Task 2 – Use case descriptions

Write a textual use case description for every use case identified in Preparation Task 1. Use the following fields:

| Field | Description |
| --- | --- |
| Use Case ID / Name | Unique identifier and name of the use case |
| Related requirements | Leave blank during preparation; requirements will be defined in the lab |
| Initiating actor | Actor who starts the use case |
| Actor's goal | What the initiating actor wants to achieve |
| Participating actors | Other actors involved |
| Preconditions | Conditions that must be true before the use case starts |
| Postconditions | Conditions that are true after the use case completes |
| Flow of events – main success scenario | Numbered interaction steps between the actor and the system |
| Flow of events – alternate scenario | Numbered steps describing alternative or exceptional paths |

Use the interaction notation from the lab sheet for the event flows:

- `→` Actor action
- `←` System response

### Preparation submission

Submit one document containing:
1. The UML use case diagram.
2. A textual use case description for every use case.

This document is due **before the lab**.

## Work during the lab

### Lab Task 1 – System requirements and SRS

During the lab, work with the use case model received from another team. Your task is to define the system requirements and other parts of a Software Requirements Specification (SRS).

#### Review and clarification

1. Review the use case material received from the other team.
2. Collect questions and comments that need clarification for the SRS.
3. Discuss these points with the other team.
4. Document changes agreed with the authors.

**Important:** Do not add or change received use cases independently. Obtain permission from their authors before making any changes.

#### Identify system requirements

Identify requirements using both:
- The received use case material.
- The Google Search documentation listed in the resources below.

Specify both:
- Functional requirements.
- Non-functional requirements.

#### Complete the SRS template

Use the SRS template provided for the course. Focus especially on:

- **Chapter 4:** Functional requirements.
- **Chapter 5:** Non-functional requirements.
- **Chapter 6:** Traceability matrix for functional requirements and use cases.

Keep the other SRS chapters short (approximately 1–3 sentences each), as instructed in the lab sheet.

### Lab submission

Submit a **complete SRS based on the given template**.

**Important:** The SRS must be prepared and submitted in **Microsoft Word format (.docx)** because track changes will be used in the following steps.

## Resources

- [Google Search – How Search Works](https://developers.google.com/search/docs/fundamentals/how-search-works)
- [Google Search – How Search Works video playlist](https://www.youtube.com/playlist?list=PLKoqnv2vTMUN83JWBNM6MoBuBcyqhFNY3)

## Deliverables checklist

### Before the lab

- [ ] Identify the users / actors and their goals.
- [ ] Draw the UML use case diagram from the user perspective.
- [ ] Write a textual description for every use case.
- [ ] Leave the related-requirements field blank.
- [ ] Combine the diagram and descriptions into one document.
- [ ] Submit the preparation document before the lab.

### During and after the lab

- [ ] Review the use case model received from the other team.
- [ ] Record clarification questions and comments.
- [ ] Discuss and document agreed changes with the authors.
- [ ] Identify functional requirements.
- [ ] Identify non-functional requirements.
- [ ] Complete the SRS using the course template.
- [ ] Complete the functional-requirement/use-case traceability matrix.
- [ ] Keep other SRS chapters to approximately 1–3 sentences each.
- [ ] Submit the completed SRS in Word (.docx) format.

## Notes

This README summarizes the instructions in the Lab 1 handout. Use the official course SRS template and any additional instructions provided by the instructor. Do not treat example or preliminary requirements elsewhere in this repository as a substitute for the agreed use cases and the course template.
