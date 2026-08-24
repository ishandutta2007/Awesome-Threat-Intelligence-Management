# Awesome-Threat-Intelligence-Management

## Top Threat Intelligence Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cyber Threat Intelligence Lifecycle, IOC/TTP Management, Knowledge Graphs, Sharing, Enrichment & Analyst Workflows*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Threat Intelligence Management**. These systems collect, structure, store, enrich, correlate, score, and operationalize cyber threat intelligence — from indicators of compromise (IOCs) to adversary TTPs, campaigns, and strategic context — so security teams can drive detection, hunting, and response.



**Examples** include ThreatConnect, Anomali, Cyware, EclecticIQ, OpenCTI Enterprise, MISP Professional, SOCRadar, Recorded Future, Silent Push, and ThreatQuotient (the category leaders).



**Open-source emphasis**: The open-source threat intelligence ecosystem is mature and widely adopted. **OpenCTI** and **MISP** are the two dominant platforms, complemented by connectors, enrichment tools, and related projects. This section is heavily expanded with these and supporting open-source options.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform / Product | Description / Focus | Starting Price (Pricing) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[ThreatConnect](https://threatconnect.com/)** | Threat intelligence platform with analyst workflows, intelligence lifecycle management, confidence scoring, and native SOAR automation. | Starts at ~$60,000/year (mid-market entry tier; typical enterprise range $60,000–$200,000+/year based on user seats, data volume, and SOAR/RQ modules) | No free-forever tier; offers a 30-day guided Proof of Concept (PoC) / evaluation sandbox upon sales qualification (scoped to test feeds and evaluation environment) |
| **[Anomali](https://www.anomali.com/)** (ThreatStream) | Enterprise TIP focused on high-volume IOC management, automated multi-feed ingestion, confidence scoring, and SIEM/EDR/SOAR integration. | Starts at ~$50,000/year (mid-market entry tier; average enterprise contracts ~$93,000/year; scaling to $250,000–$500,000/year for global deployments) | No free-forever tier (legacy STAXX tool discontinued); provides a 30-day guided sales-assisted evaluation / PoC environment with limited test feed ingestion |
| **[Cyware](https://www.cyware.com/)** (CTIX) | Cyber Threat Intelligence Exchange platform emphasizing automated ingestion, enrichment, bidirectional hub-and-spoke sharing, and SecOps orchestration. | Starts at ~$35,000/year (CTIX Lite / entry deployment; full enterprise multi-hub deployments scale $50,000–$150,000+/year) | No free-forever tier; offers a 14-to-30-day private Proof of Concept (PoC) trial via sales / AWS Marketplace Private Offer for scoped hub testing and integration validation |
| **[EclecticIQ](https://www.eclecticiq.com/)** (Intelligence Center) | Intelligence-driven security platform and TIP built on STIX/TAXII standards, featuring analyst workbench tools and graph correlation. | Starts at ~$45,000/year (base tier for core Intelligence Center; enterprise packages range $60,000–$180,000+/year based on analyst seats and feed connectors) | No free-forever tier; offers time-limited 30-day integration "TIP Bundles" / evaluation trials for specific vendor integrations to validate operational impact |
| **[OpenCTI Enterprise](https://filigran.io/)** (Filigran Cloud) | Commercial enterprise and managed SaaS edition of OpenCTI, adding automated playbooks, AI-assisted reporting, RBAC, and dedicated cloud hosting. | Starts at ~$12,000/year (~€10,000–€15,000/year for dedicated Cloud Standard / Medium instance; scales with compute/cluster resources) | **Community Edition** is 100% free forever (open-source Apache 2.0, self-hosted, full STIX 2.1 model); **Filigran Cloud Enterprise** offers a **30-day free trial** with access to all enterprise features, playbooks, and AI modules |
| **[MISP Professional / Commercial Support](https://www.misp-project.org/)** | Commercial support contracts, SLA services, and dedicated managed cloud hosting built around the open-source MISP platform by MISP Project / CIRCL & partners. | Starts at ~€6,000/year (~$6,500/year for single-instance managed hosting and standard SLA support tier; enterprise multi-instance support €15,000–€35,000+/year) | MISP core is 100% free forever (AGPLv3 open-source, self-hosted, unlimited events/attributes/users); commercial hosting partners offer 14-day evaluation demo instances upon request |
| **[SOCRadar](https://socradar.io/)** | Extended Threat Intelligence (XTI) platform combining cyber threat intelligence, digital risk protection, and external attack surface management. | Starts at $4,550/year (Advanced Dark Web module; comprehensive CTI & attack surface packages range $7,900–$11,950+/year) | **SOCRadar Free Edition** free for 12 months (1 year) with limits: 1 monitored corporate domain, up to 100 auto-discovered digital assets, basic dark web / exposed credential alerts, and critical zero-day vulnerability notifications |
| **[Recorded Future](https://www.recordedfuture.com/)** | Leading intelligence cloud that continuously collects open, dark-web, and technical sources to deliver real-time risk scores and threat graph analytics. | Starts at ~$50,000/year (base core module/license; typical enterprise contracts range $50,000–$250,000+/year based on modules: SecOps, Brand, Vuln, Attack Surface) | No free-forever tier for full platform (free standalone browser extension and malware sandbox tools available); offers a **30-day free trial** for specific ecosystem integrations (e.g., Microsoft Sentinel integration) and guided 14-to-30-day evaluation PoC |
| **[Silent Push](https://www.silentpush.com/)** | Threat intelligence platform specializing in global DNS/infrastructure analysis, domain reputation, and early adversary infrastructure detection. | Starts at ~$1,200/year ($100/month for Starter tier; Professional/Enterprise tiers scale $4,800–$25,000+/year based on query volume and API feeds) | **Free Community Edition** (free forever for non-production/eval use) limited to **1 user seat** and **250 query requests per month**; also offers a 14-day full-feature trial for Pro evaluation |
| **[ThreatQuotient](https://threatq.com/)** (ThreatQ) | Threat intelligence platform centered on Threat Data Integrity, customizable prioritization scoring, and security operations workflow integration. | Starts at ~$40,000/year (base deployment tier; typical enterprise deployments scale $50,000–$150,000+/year based on analyst seats and connector volume) | No free-forever tier; provides a 30-day structured Proof of Concept (PoC) / sandbox evaluation through sales engineering and partner channels (e.g., Carahsoft) |



## Open-Source GitHub Projects

- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)**  

  Leading open-source Cyber Threat Intelligence platform built on STIX 2.1. Structures, stores, visualizes, and connects technical and non-technical threat knowledge with a rich connector ecosystem and GraphQL API. Community Edition is fully open.



- **[MISP](https://github.com/MISP/MISP)**  

  The most widely deployed open-source threat intelligence and sharing platform. Excellent for collecting, storing, correlating, and distributing indicators and threat events with strong community sharing and galaxy/taxonomy support.



- **[OpenCTI Connectors](https://github.com/OpenCTI-Platform/connectors)**  

  Official and community connectors that import/export intelligence between OpenCTI and dozens of sources (MISP, MITRE ATT&CK, VirusTotal, AlienVault OTX, commercial feeds, SIEMs, etc.).



- **[Yeti](https://github.com/)**  

  Open-source observables and indicators management platform designed for fast IOC triage, enrichment, and analyst-friendly workflows.



- **[TheHive + Cortex](https://github.com/TheHive-Project)**  

  Open-source security incident response platform frequently paired with TIPs for case management and observable enrichment.



- **[MITRE ATT&CK datasets and STIX exports](https://github.com/mitre/cti)**  

  Foundational open knowledge base of adversary tactics, techniques, and procedures that most TIPs ingest.



- **[STIX/TAXII open implementations and libraries](https://github.com/)**  

  Reference libraries and tools for producing, consuming, and transporting structured threat intelligence.



- **[Abuse.ch, CIRCL, and public feed tooling](https://github.com/)**  

  Open tooling and pipelines for ingesting high-quality public threat feeds into MISP, OpenCTI, or custom platforms.



- **[Threat intelligence sharing and community instances](https://github.com/)**  

  Projects and documentation supporting trusted MISP or OpenCTI sharing communities (ISACs, national CERTs, etc.).



- **[Custom enrichment and scoring engines](https://github.com/)**  

  Open scripts and services that score, deduplicate, or contextualize indicators before or after they enter a TIP.



### Additional Strong Open-Source Options

- TAXII servers and clients for standardized intelligence exchange.

- Jupyter / notebook environments for exploratory analysis of TIP data.

- Graph databases and visualization tools used alongside OpenCTI’s knowledge graph.

- Detection-as-code repositories that consume structured intelligence from TIPs.

- Integration examples connecting OpenCTI/MISP to Elastic, Wazuh, Splunk, or TheHive.



**Frameworks for building custom systems**: Deploy **OpenCTI** as the central knowledge graph and analyst workbench (STIX-native), use **MISP** for high-volume indicator sharing and community exchange, and connect both via official connectors. Enrich with public and commercial feeds, push relevant indicators to SIEMs/EDRs, and manage investigations in TheHive. This combination provides a complete, self-hosted threat intelligence management capability with full data ownership, strong standards compliance, and a vibrant community — at the cost of operational effort for maintenance, connector management, and content curation.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Threat intelligence platforms handle sensitive security data and influence detection and response decisions. Open-source TIPs offer excellent transparency and control but require proper access controls, data-quality processes, and integration work. Intelligence is only as useful as the processes and people that operationalize it.

- Always respect sharing agreements, TLP markings, and legal constraints when exchanging threat intelligence.



---

**Made for threat intelligence analysts, SOC teams, and detection engineers building intelligence-driven security programs.**

Let's make structured, actionable threat intelligence more open, shareable, and operational.
