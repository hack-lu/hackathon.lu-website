---
title: Projects at hackathon.lu
description: Team and Projects at hackathon.lu 2026
toc: true
---

## Projects and Team at hackathon.lu 2026

The following open-source projects will be at the hackathon. If you'd like to include your project, feel free to [contact us](https://hackathon.lu/practical/)!

### MISP Project

![](/images/projects/misp-logo.png)

[MISP](https://www.misp-project.org/), the open source threat sharing platform.

### AIL Project

![](/images/projects/ail-logo.png)

[AIL Project](https://www.ail-project.org/) is an open source framework composed of different modules to collect, crawl, dig and analyse unstructured data. AIL includes an extensible Python-based framework for analysis of unstructure information collected via an advanced Crawler manager or from different feeders (such as Twitter, Discord, Telegram Stream providers) or custom feeders.

### Kunai

![](/images/projects/kunai-logo.png)

[Kunai](https://why.kunai.rocks/): bring your Linux Threat-Hunting capabilities to the next level.

### Flowintel

![](images/projects/flowintel-logo.png)

[Flowintel](https://github.com/flowintel/flowintel) is an open-source platform designed to assist analysts in organizing their cases and tasks. It features a range of tools and functionalities to enhance workflow efficiency.

### Rulezet

![](/images/projects/rulezet-logo.png)

[Rulezet](https://rulezet.org/) Rulezet is an open-source web platform for sharing, evaluating, improving, and managing cybersecurity detection rules (YARA, Sigma, Suricata, etc). It aims to foster collaboration among professionals and enthusiasts to improve the quality and reliability of detection rules.

### Lacus

![](/images/projects/lacus-logo.png)

[Lacus](https://github.com/ail-project/lacus): A capturing system using playwright, as a web service.

### Lookyloo

![](/images/projects/lookyloo-logo.png)

[Lookylooo](https://github.com/Lookyloo/) is a web interface that captures a webpage and then displays a tree of the domains, that call each other.

### Pandora

![](/images/projects/pandora-logo.png)

[Pandora](https://github.com/pandora-analysis/pandora) is an analysis framework to discover if a file is suspicious and conveniently show the results.

### Vulnerability-Lookup

![](/images/projects/vulnerability-lookup-logo.jpg)

[Vulnerability-Lookup](https://www.vulnerability-lookup.org) facilitates quick correlation of vulnerabilities from various sources, independent of vulnerability IDs, and streamlines the management of Coordinated Vulnerability Disclosure (CVD).

### GCVE

![](https://gcve.eu/logos/gcve.png)

The Global CVE (GCVE) allocation system is a new, decentralized approach to vulnerability identification and numbering, designed to improve flexibility, scalability, and autonomy for participating entities.

### VulnTrain

[VulnTrain](https://github.com/vulnerability-lookup/VulnTrain) is a tool for generating diverse datasets and models using vulnerability data from Vulnerability-Lookup.

It leverages all vulnerability advisory sources supported by Vulnerability-Lookup to train models, utilizing over one million JSON records.
Additionally, data from the `vulnerability-lookup:meta` container, including enrichment sources such as `vulnrichment` and `Fraunhofer FKIE`, is incorporated to enhance model quality.

Various models are already [available on Hugging Face](https://huggingface.co/CIRCL) and we are always interested in new ideas (datasets, trainers, integration with Vulnerability-Lookup, ...)!

### MISP Workbench

![](/images/projects/misp-workbench-hori-color.jpg)

[MISP Workbench](https://github.com/MISP/misp-workbench) is an analyst-focused threat intelligence platform built to handle large-scale indicator data without the overhead of a full MISP deployment. It ingests feeds from multiple sources — MISP instances, CSV, JSON, and freetext — consolidates them into a unified OpenSearch-backed workspace, and gives analysts the tools to query, correlate, enrich, and hunt across the full corpus from one place.

Built for speed and practicality: run Lucene queries across millions of indicators, schedule recurring hunts for persistent monitoring, enrich IOCs via misp-modules, and push curated results back to MISP or downstream consumers — all without writing one-off scripts or jumping between tools.


### OISF and Suricata

![](/images/projects/oisf-logo.png)
![](/images/projects/suricata-logo.jpg)

[Suricata](https://suricata.io/) is a high performance, open source network analysis and threat detection software used by most private and public organizations, and embedded by major vendors to protect their assets.

### HOPLITE

![](https://hoplite-project.eu/_astro/hoplite_full_no_word.BTCVXS3D_T2kPC.webp)

[AI-Powered Data Analysis for LEAs - HOPLITE](https://hoplite-project.eu/) enables law enforcement agencies to identify and prioritise online threats in real time.

### cocktailparty

![](/images/projects/logo-cocktail-party-horizontal-coul.png)

[cocktailparty](https://github.com/flowintel/CocktailParty) is a websocket data brocker system based on the [phoenix framework](https://www.phoenixframework.org/).

### Mercator

![](/images/projects/logo4c.png)

[Mercator](https://github.com/dbarzin/mercator) is a powerful and versatile open-source web application designed to facilitate the mapping of information systems, as outlined in the [Mapping The Information System Guide](https://cyber.gouv.fr/en/publications/mapping-information-system) by [ANSSI](https://cyber.gouv.fr/en). Whether you're an operator of vital importance or part of a broader IT governance framework, Mercator is an essential tool for gaining visibility, control, and ensuring the resilience of your information systems.

### sysdiagnose analysis framework

![](/images/projects/sysdiagnose-logo.png)

[sysdiagnose](https://github.com/EC-DIGIT-CSIRC/sysdiagnose) is an open-source framework developed to facilitate the analysis of the Apple sysdiagnose files and especially the one generated on mobile devices (iOS / iPadOS). In the light of targeted attacks against journalists, activist, representatives from the civil society and politicians, it empowered incident response team to review device behaviour and ensure their integrity. This tool is initially the result of a joint effort between EC DIGIT CSOC (European Commission DG DIGIT) and CERT-EU (https://cert.europa.eu/).

### IAMI (Identity & Access Management Integrations)

![IAMI (Identity & Access Management Integrations)](/images/projects/IAMI.svg)

[IAMI](https://codeberg.org/icrc-global-cyber-hub/iami) is a Work in Progress Open Source platform that integrates identity and access management to several tools in an automated way (as much as possible). All user-facing applications use Keycloak for single sign-on, and users only need one account to access everything depending on their rights.

The main entry point to the platform is Portal (portal) where users can see all available services and request access to them. Keycloak (id) handles authentication, authorization (via custom made keycloak `group-auth` plugin) and user management. Comprehensive monitoring (Grafana, Loki, Prometheus and Alloy) and analytics using Matomo.

The platform uses official Kubernetes Helms or manifests and is deployed using ArgoCD while custom images are hosted in a privately deployed registry using Harbor. This tool was initially developed by the International Committee of the Red Cross (ICRC) in collaboration with Cortex Security S.A.

### IDPS-ESCAPE

![IDPS-ESCAPE logo](/images/projects/idps-escape-logo.png)

[IDPS-ESCAPE](https://github.com/AbstractionsLab/idps-escape) (Intrusion Detection and Prevention Systems for Evading Supply Chain Attacks and Post-compromise Effects), part of project [CyFORT](https://abstractionslab.com/index.php/research-and-development/cyfort/), is an open-source SOAR system powered by a dedicated anomaly detection toolbox (**ADBox**), integrated with open-source software such as Wazuh and Suricata. The ADBox provides an extensible framework for integrating different AD algorithms and currently includes an implementation of MTAD-GAT, a Multivariate Time-series Anomaly Detection (MTAD) algorithm relying on Graph Attention Networks (GAT).

### SATRAP

![SATRAP logo](/images/projects/satrap-logo.png)

[SATRAP](https://github.com/AbstractionsLab/satrap-dl) (Semi-Automated Threat Reconnaissance and Analysis Platform) part of project [CyFORT](https://abstractionslab.com/index.php/research-and-development/cyfort/), is an open-source, cross-platform software aimed at supporting computer-aided analysis of cyber threat intelligence (CTI) by leveraging automated reasoning and inference. At its core, SATRAP implements a knowledge representation system (KRS) consisting of a CTI knowledge base coupled with a reasoning engine for inferring new knowledge, built on top of TypeDB. The KRS grounds SATRAP into formal underpinnings, enabling the introduction of semantics into the storage, processing, and analysis of CTI.

### MISPERER

![MISPerer logo](/images/projects/MISPerer_logo.png)
[MISPerer](https://github.com/Eacus/misp-mcp) MISPerer implements Anthropics's Model Context Protocol (MCP) to enable Large Language Models (LLMs) to interact directly with the MISP threat intelligence platform. This allows users and automated systems to query and analyze MISP data using natural language prompts.

### Range42

![range42 logo](/images/projects/range42-logo.png)
[Range42](https://github.com/range42) is a modular cyber range platform designed for real-world readiness. We build, deploy, and document offensive, defensive, and hybrid cyber training environments using reproducible, infrastructure-as-code methodologies.

### Monarc

![monarc logo](/images/projects/monarc-logo.png)
[Monarc](https://github.com/monarc-project) is an open-source tool and a method based on ISO/IEC 27005 that helps conduct an optimised, precise, and repeatable risk assessment. The code is based on php/Laminas backend, Angularjs frontend and MariaDB database. It also has some related services based on Python/Flask and Postgresql. The official website is available <a href="https://monarc.lu" target="_blank" rel="noopener">here</a>.

### Misp-ghidra and BSimVis

[Misp-ghidra](https://github.com/MISP/misp-ghidra) is a python library and scripts to extend Ghidra for exporting ghidra decompilation indicators (functions names, FID hashes, BSIM vectors) to MISP Objects.

[BSimVis](https://github.com/MISP/BSimVis) is a tool to analyze similarities across a collection of binaries, based on Ghidra analyzers and the BSim (Behavioral Similarity) plugin. It provides an API and Web interface to upload large quantities of decompiled binaries and BSim feature vectors to a Kvrocks database for similarity analysis, function diffing, and family clustering.


