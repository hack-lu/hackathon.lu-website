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

#### Task - Review and update the MISP OpenAPI documentation (especially the allowed arguments), using the real MISP documentation
| Task MISP-OPENAPI-DOC|
| :--|
| Task Lead: **Jeroen Pinoy**  - MISP contributor|

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
