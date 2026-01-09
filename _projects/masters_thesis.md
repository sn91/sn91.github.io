---
layout: page
title: Traceability and Impact Analysis for Airborne Software
description: Master's Thesis at DLR Braunschweig on DO-178C compliance in DevOps
img: 
importance: 1
category: Major
---

## Project Overview

**Master's Thesis** conducted at the German Aerospace Center (DLR), Braunschweig, focusing on **traceability and impact analysis** for DevOps-based airborne software development compliant with **DO-178C** standards.

**Duration**: 2024 – 2025  
**Institution**: DLR Braunschweig & TU Clausthal

## Problem Statement

Airborne software development requires strict compliance with DO-178C certification standards, which demand comprehensive traceability between requirements, design, code, and tests. Traditional manual traceability approaches don't scale well in modern DevOps CI/CD environments.

## Solution Approach

### Model and Ontology Development
- Built a formal model for DO-178C traceability relationships
- Designed ontologies to represent artifacts and their connections
- Ensured compliance with certification requirements

### Tooling Development
- Developed **Python-based tooling** for automated traceability analysis
- Integrated with **graph databases** for relationship storage and querying
- Enabled automated test and requirement impact analysis

### CI/CD Integration
- Integrated the approach into existing **CI pipelines**
- Automated change-impact assessments for airborne software artifacts
- Provided real-time feedback on traceability completeness

## Technical Stack

- **Programming**: Python
- **Database**: Neo4j (Graph Database)
- **CI/CD**: Jenkins, Git
- **Standards**: DO-178C, ASPICE
- **Modeling**: UML, SysML

## Key Contributions

1. **Automated Traceability**: Reduced manual effort in maintaining requirement-to-test mappings
2. **Impact Analysis**: Enabled rapid assessment of change impacts across the artifact hierarchy
3. **CI Integration**: Provided continuous validation of traceability in DevOps workflows
4. **Certification Support**: Facilitated DO-178C compliance evidence generation

## Architecture

```
┌─────────────────────────────────────────────────────────┐
│                    CI/CD Pipeline                        │
├─────────────────────────────────────────────────────────┤
│  Git Push ──▶ Build ──▶ Traceability Check ──▶ Deploy   │
│                              │                           │
│                              ▼                           │
│                    ┌─────────────────┐                   │
│                    │  Graph Database │                   │
│                    │     (Neo4j)     │                   │
│                    └────────┬────────┘                   │
│                              │                           │
│         ┌────────────────────┼────────────────────┐     │
│         ▼                    ▼                    ▼     │
│  ┌─────────────┐    ┌─────────────┐    ┌─────────────┐  │
│  │Requirements │    │   Design    │    │    Tests    │  │
│  │  Artifacts  │    │  Artifacts  │    │  Artifacts  │  │
│  └─────────────┘    └─────────────┘    └─────────────┘  │
└─────────────────────────────────────────────────────────┘
```

## Impact

- Streamlined DO-178C compliance verification process
- Reduced time for impact analysis from hours to minutes
- Improved confidence in software changes through automated checks

