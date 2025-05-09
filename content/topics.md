---
title: Topics at hackathon.lu
description: Topics at hackathon.lu 2025
toc: true
---

## Topics and Projects at hackathon.lu 2025

A series of topics are available for Hackathon 2025, along with potential task ideas. This list will be regularly updated based on feedback and the [projects](/projects/) joining the event.

### Cyber Threat Intelligence

Explore innovative ways to collect, analyze, and share threat intelligence to enhance cyber defenses and facilitate proactive responses to evolving threats.

#### Task - Improve the visualisation of MISP taxonomies and galaxies and make it accessible to a larger community.

| Task CTI-VIS-INFO|
| :--|
|Improve the visualisation of MISP taxonomies and galaxies and make it accessible to a larger community.|
| Task Lead
 **MISP Project**  - taxonomies and galaxy maintainers.|
| References<br> - [https://www.misp-galaxy.org/](https://www.misp-galaxy.org/)<br>- [https://github.com/MISP/misp-galaxy/](https://github.com/MISP/misp-galaxy/)<br>- [https://github.com/MISP/misp-taxonomies](https://github.com/MISP/misp-taxonomies) | 

#### Task - Add MISP workflow action to send messages to nextcloud chat
| Task MISP-WORKFLOW-NEXTCLOUD-CHAT|
| :--|
| Task Lead: **Jeroen Pinoy**  - MISP contributor|
| References<br> - [Nexctcloud chat API doc](https://nextcloud-talk.readthedocs.io/en/latest/chat/) | 

#### Task - Add functionality to MISP modules and/or MISP, to keep an audit record of the usage of modules (timestamps + user)
| Task MISP-MODULES-AUDIT|
| :--|
| Task Lead: |
| References<br> - [MISP modules repo](https://github.com/MISP/misp-modules) |

#### Task - Review and update the MISP OpenAPI documentation (especially the allowed arguments), using the real MISP documentation
| Task MISP-OPENAPI-DOC|
| :--|
| Task Lead: **Jeroen Pinoy**  - MISP contributor|

#### Task - Build a set of examples of common cyber threat intelligence sharing scenarios (e.g. malware sample executed by cron job), with resulting MISP encoded version of the scenario data, along with explanations.
| Task MISP-CTI-ENCODING-SCENARIO-SAMPLES|
| :--|
|Build a set of examples of common cyber threat intelligence sharing scenarios (e.g. malware sample executed by cron job), with resulting MISP encoded version of the scenario data, along with explanations.|
| Task Lead: **Jeroen Pinoy**  - MISP contributor|
| References<br> - [https://www.misp-project.org/misp-training/b.1-best-practices-in-threat-intelligence.pdf](https://www.misp-project.org/misp-training/b.1-best-practices-in-threat-intelligence.pdf) <br> - [https://www.circl.lu/doc/misp/best-practices/](https://www.circl.lu/doc/misp/best-practices/) |

#### Task - Create MISP incident response playbooks / guidelines
| Task MISP-IR-PLAYBOOKS|
| :--|
| The goal is to create documentation for what to look at when trying to answer "Is the user activity of user X on MISP suspicious?". The doc should contain information on how to interpret logs, audit info... This falls under larger umbrella of how to detect and analyze potential abuse on a MISP instance.|
| Task Lead: |

#### Task - Review and update the MISP generated Suricata rules
| Task MISP-SURICATA-RULES|
| :--|
| Review and update the way MISP generated Suricata rules possibly using datasets feature of stable Suricata versions|
| Task Lead: **Eric Leblond**  - Suricata contributor|

#### Task - Connect Suricata 8 dataset in JSON format feature with MISP
| Task MISP-SURICATA-DATAJSON|
| :--|
| Review and update the way MISP generated Suricata rules possibly using datasets feature of stable Suricata versions|
| Reference<br> - [Dataset with JSON format support PR](https://github.com/OISF/suricata/pull/12863)
| Task Lead: **Eric Leblond**  - Suricata contributor|

#### Task - Distribute Certificate transparency logs with Cocktailparty
| Task COCKTAILPARTY-CERTSTREAM|
| :--|
| Integrate calidog's certstream watcher/parser in cocktailparty as a new connection/source. Allow for collection from additional log_lists |
| Reference<br> - [https://github.com/CaliDog/certstream-server](https://github.com/CaliDog/certstream-server)
| Task Lead: **Jean-Louis Huynen**  - Cocktailparty contributor|

#### Task - Create admin-defined filters in Cocktailparty
| Task COCKTAILPARTY-ADMINFILTERS|
| :--|
| Create admin-defined filters to apply on sources before dispatching to channels. |
| Reference<br> - [https://github.com/flowintel/cocktailparty](https://github.com/flowintel/cocktailparty)
| Task Lead: **Jean-Louis Huynen**  - Cocktailparty contributor|

#### Task - Create user-defined filters in Cocktailparty
| Task COCKTAILPARTY-USERFILTERS|
| :--|
| Create user-defined filters to apply on channels, before pushing into the websocket. |
| Reference<br> - [https://github.com/flowintel/cocktailparty](https://github.com/flowintel/cocktailparty)
| Task Lead: **Jean-Louis Huynen**  - Cocktailparty contributor|

#### Task - Improve realtime-py for cocktailparty stream consumption
| Task COCKTAILPARTY-PYTHON-LIB|
| :--|
| Upstream realtime-py significantly diverged from flowintel's current fork. The task consists of reviewing the current code, remove supabase-related parts, play with the library or write tests, and most importantly find a new name =) |
| References<br> - [https://github.com/flowintel/realtime-py](https://github.com/flowintel/realtime-py)<br> - [PR dating before upstream refacto](https://github.com/supabase/realtime-py/pull/68)
| Task Lead: **Jean-Louis Huynen**  - Cocktailparty contributor|

#### Task - Integrate MISP modules into AIL
| Task AIL-MISP-Module |
| :--|
| Task Lead: |
| References<br> - [AIL](https://github.com/ail-project/ail-framework)<br> - [MISP Modules](https://github.com/MISP/misp-modules) |

#### Task - Improve AIL Language detection
| Task AIL-Languages                                                                                                                                                                                                                                                                                                                                                    |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| AIL is using CLD3 and a new version of lexilange to detect chats languages. <br>Improve Lexilang's language dictionary <br> Propose an alternative to CLD3 for language detection that supports a broader range of languages with improved memory efficiency and performance <br>Propose an alternative to ISO 639-3 for representing unsupported regional languages. |
| Task Lead: **Aurelien Thirion** - AIL Project                                                                                                                                                                                                                                                                                                                         |
| References<br> - [AIL](https://github.com/ail-project/ail-framework)<br> - [Lexilang](https://github.com/ail-project/LexiLang/tree/ail)<br> - [AIL Languages detection](https://github.com/ail-project/ail-framework/blob/langs/bin/lib/Language.py)                                                                                                                  |

### Digital Forensics and Incident Response

Delve into tools and methodologies for investigating cyber incidents, uncovering evidence, and responding effectively to mitigate impact.

### EDR and Host-Based Detection

Enhance endpoint detection and response (EDR) capabilities with cutting-edge techniques for detecting and mitigating threats at the host level.

### Vulnerability Management

Develop and refine strategies and tools for identifying, assessing, and prioritizing vulnerabilities to reduce organizational risk.

#### Task - Extracting CVE/Vulnerability reference from large datasets such as [commoncrawl](https://commoncrawl.org/)

| Task VUL-EXTRACT|
| :--|
| Extracting CVE/Vulnerability reference from large datasets such as [commoncrawl](https://commoncrawl.org/). Adding references into vulnerability-lookup project.|
| Task Lead
 **vulnerability-lookup**|
| References<br> - [https://www.vulnerability-lookup.org/](https://www.vulnerability-lookup.org/)<br>- [commoncrawl dataset](https://commoncrawl.org) |

#### Task - Guessing CPE name based on vulnerability description.

| Task VUL-CPE-GUESS|
| :--|
| Facilitating the guessing of a CPE name via natural language processing based on vulnerability description.|
| Task Lead
 **vulnerability-lookup**|
| References<br> - [https://www.vulnerability-lookup.org/](https://www.vulnerability-lookup.org/)<br>- [cpe-guesser](https://github.com/cve-search/cpe-guesser) |

#### Task - Guessing CPE name with LLM

| Task VUL-CPE-LLM|
| :--|
| Facilitating the guessing of a CPE name with LLM.|
| Task Lead
 **Vulnerability-Lookup**|
| References<br> - [https://www.vulnerability-lookup.org](https://www.vulnerability-lookup.org)<br>- [VulnTrain](https://github.com/vulnerability-lookup/VulnTrain) |

#### Task - Predict exploitability with LLM

| Task VUL-EXP-LLM|
| :--|
| Estimating the exploitability of a new vulnerability with LLM.|
| Task Lead
 **Vulnerability-Lookup**|
| References<br> - [https://www.vulnerability-lookup.org](https://www.vulnerability-lookup.org)<br>- [VulnTrain](https://github.com/vulnerability-lookup/VulnTrain) |

#### Task - Enhanced Vulnerability-Lookup with Code Context

| Task VUL-Sourcecode-LLM|
| :--|
| When searching for vulnerabilities, provide relevant code snippets from impacted projects.<br>Extend Vulnerability-Lookup database/dataset by linking CVEs with corresponding source code segments from affected products/repositories. Fine tune CodeBert of CodeT5.|
| Task Lead
 **Vulnerability-Lookup**|
| References<br> - [https://www.vulnerability-lookup.org](https://www.vulnerability-lookup.org)<br>- [CodeBERT](https://huggingface.co/microsoft/codebert-base)<br>- [CodeT5](https://huggingface.co/Salesforce/codet5-base) |


### Cybersecurity - Open Data and Open Datasets

Use and create open data and datasets to support cybersecurity research, training, and collaborative innovation.

### API and Tooling Interoperability

Focus on creating and improving APIs and tools that enable seamless integration and interoperability between different cybersecurity platforms.

#### Task - Create MISPerer
| Task: MISPerer|
| :------------ |
| MISPerer leverages Anthropics's Model Context Protocol (MCP) to bridge Large Language Models (LLMs) with the MISP (Malware Information Sharing Platform & Threat Sharing) system. This simplifies interaction, allowing users and other systems to query MISP's threat intelligence data through intuitive natural language prompts. |

### Mercator  

Work on auto-discovery and update of existing objects using the [REST API](https://dbarzin.github.io/mercator/api/).

#### Tasks  

- **Auto-discovery with nmap**: Scan the network to identify active devices and retrieve basic information (IP, open ports, OS fingerprinting).  
- **Update server configuration with SNMP**: Collect hardware and software information from discovered devices and update Mercator accordingly.  
- **Integration with existing inventory data**: Cross-reference discovered devices with existing inventory records to update or flag discrepancies.  
- **Automated tagging and categorization**: Assign tags based on device type, OS, and role in the network.  
- **Web UI enhancements**: Display real-time discovered devices and provide an interface for manual validation and corrections.  
- **Alerting for new/unexpected devices**: Notify administrators when unknown or unauthorized devices appear on the network.  

### Cybersecurity Education

Create and share educational resources (e.g. CTF challenges), training modules, documentation and workshops to advance knowledge and skills in cybersecurity.

### Policy and Cybersecurity
Improve open source toolings to support policies, regulations, and frameworks to address the challenges and opportunities at the intersection of governance and cybersecurity.

### Lookyloo

Website capture interface

#### Tasks

- Implement dropdown to select which proxy to use for the capture (by country)

### Virgil

Ansible deployment of Lacus, Lookyloo, URL Monitoring and Pandora.

#### Tasks

- Review the preliminary playbooks
- Test the ansible playbooks on live systems
- Document the installation process
- Pre-configure the modules from a central file
- Validate the updating the services works as expected

### YALTF (Yet Another License Tool and Framework)
#### Tasks: ***(Click for more details)***
<details>
    <summary>
    <b>Expanded OS & platform support</b> <i>(Windows, macOS)</i>
    </summary>

- Extend linux support: Extend support to further Linux distributions, particularly Debian and its derivatives that are most used. Explore compressing license data for efficient scanning (additional feat)
- Windows (SSH-Based): Enable scanning of software on Windows systems accessible via SSH.
- Windows (native): Implement native scanning on Windows using the WinRM protocol.
- macOS support: Extend scanning to macOS, including Homebrew-managed packages.
- Docker compatibility:Support scanning of Docker images to detect license and security issues.
</details>

<details>
    <summary>
    <b>Enhanced UI (viewer)</b> <i>(advanced filters, better visualization)</i>
    </summary>

- Redesign the UI with modern web technologies for a better user experience.
- Introduce advanced filtering, classification, and compliance-checking features.
- Display scan summaries and elegantly visualize composite license structures.
</details>

<details>
    <summary>
    <b>Expand package scanning capabilities</b> <i>(Flatpak, Snap, npm ...)</i>
    </summary>

- Scan software installed via distribution-independent package managers (e.g., Flatpak, Snap).
- Support CLI-based application package managers (e.g., Go modules, npm) for deeper license analysis.
</details>


<details>
    <summary>
    <b>Error handling & logging</b>
    </summary>

- Improve logging with detailed and actionable diagnostic messages.
- Display errors and warnings directly in the scan report for better visibility.
</details>

<details>
    <summary>
    <b>Interoperability with other tools</b> <i>(ORT, CSV, SML, SPDX...)</i>
    </summary>

- Enable integration with existing license scanners. Provide outputs compatible with industry-standard tools like ORT for seamless report generation.
- Support additional output formats, including CSV, XML, SPDX, and more, alongside the existing JSON.
</details>

<details>
    <summary>
    <b>Advanced configuration/parameters</b> <i>(Custom output names, locations...)</i>
    </summary>

- Expand configuration settings to allow custom output directories, report names, and other preferences.
</details>

<details>
    <summary>
    <b>Improved accuracy and security</b> <i>(Validation, Vulnerability Detection...)</i>
    </summary>

- License data validation: Cross-check scan results against online sources to ensure completeness and detect outdated or missing license information.
- Vulnerability detection: Identify known vulnerabilities (CVEs) in scanned software by referencing security databases. Potentially leveraging lookup service from CIRCL.
- Weak or insecure configuration detection: Analyze server, database, and software configurations for security misconfigurations that could lead to potential exploits.
</details>

<details>
    <summary>
    <b>Testing & QA</b> <i>(Automated test suits)</i>
    </summary>

- Develop automated test suites for YALTF to ensure accuracy, reliability, and robustness.
</details>

[YALTF Github Repo](https://github.com/yaltf/yaltf)

### IDPS-ESCAPE  

Tasks partially based on the roadmap of [IDPS-ESCAPE](https://github.com/AbstractionsLab/idps-escape) focusing on the **ADBox** [subsystem](https://github.com/AbstractionsLab/idps-escape/blob/main/docs/manual/README.md#adbox)

#### Tasks

- Suggest (or add) new reusable anomaly detection use case scenarios, i.e., other than the ones geared towards resource usage monitoring
- Brainstorm on tailoring the underlying ADBox algorithms to specific SOC operations, e.g., to improve the detection of specific types of anomalies, such as those related to user behavior, network traffic, or system performance
- Enhance the existing Wazuh ADBox integration: improve the [visualization](https://github.com/AbstractionsLab/idps-escape/blob/main/docs/manual/detector_data_stream.md) and reporting capabilities of ADBox to provide more meaningful insights into detected anomalies
- Suggest approaches for automating the creation of incident response cases based on ADBox detections, e.g., via the [OpenCTI Wazuh connector](https://github.com/misje/opencti-wazuh-connector) or the MISP API
- Improve the scalability and performance of ADBox to handle larger volumes of ingested data
- Simplify the [ADBox engine](https://github.com/AbstractionsLab/idps-escape/blob/main/docs/manual/engine.md) as well as the [training](https://abstractionslab.github.io/idps-escape/docs/traceability/SWD.html#SWD-001) and [prediction](https://abstractionslab.github.io/idps-escape/docs/traceability/SWD.html#SWD-002) pipelines
- train new models for anomaly detection using large amounts of data to assess the performance and accuracy of the underlying anomaly detection algorithm(s)
- Suggest or add new automated response mechanisms aimed at preventive measures directly integrated into Wazuh, towards the SOAR goal of IDPS-ESCAPE
- Suggest simulation specifications for pairs of attack scenarios and automated response mechanisms, e.g., to assess the impact of response mechanism suites
- **Algorithmic agility** (choosing between multiple algorithms for the same
functionality): Integrate different AD algorithms into the ADBox engine to benchmark their performance and accuracy in the context of IDS
- add efficient **algorithmic multiplexing** (choosing between multiple implementations of the same algorithm)

### SATRAP

Tasks partially based on the roadmap of [SATRAP-DL](https://github.com/AbstractionsLab/satrap-dl)

#### Tasks

- **Identify sets of preconditions** commonly used to establish correlations (if-then scenarios) to convert to inference rules in SATRAP
- **Implement new inference rules** for SATRAP in TypeQL
- **Automate data ingestion from MISP into the SKB of SATRAP**: Design and implement a stream-oriented module for retrieving IOCs and other data from a MISP instance and running the SATRAP ETL process on this data, while keeping time and space complexity under control
- Identify candidate high-level functions to be added to the SATRAP `CTIAnalysisToolbox`
- Integrate functions of SATRAP with existing CTI playbooks, similar to the use of PyMISP and pycti, e.g., [the threat actor profiling playbook by MISP](https://github.com/MISP/misp-playbooks/blob/main/misp-playbooks/pb_threat_actor_profiling-with_output.ipynb)
- Suggest performance-related improvements for the SATRAP ETL (Extract-Transform-Load) subsystem, at an algorithmic level
- **Explainable inference**: Study the integration of visual explanations in Jupyter Notebooks
- Add support for ingesting STIX 2.1 custom and metadata objects
- **Reverse ETL**: Transform TypeQL results into STIX2.1 objects
