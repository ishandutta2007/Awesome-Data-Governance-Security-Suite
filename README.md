# Awesome-Data-Governance-Security-Suite

# Awesome-Data-Governance-Security-Suite

**Top Data Governance Security Suite (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Data Catalogs, Access Control, Privacy Automation & Self-Hosted Metadata Governance*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Governance & Security Suites**. These tools enable organizations to catalog data assets, enforce access policies, automate privacy compliance, and govern AI systems—from fully managed enterprise platforms with agent identity and semantic layers to open-source metadata frameworks that give teams control over their governance infrastructure.



**Examples** include Snowflake Horizon, Collibra, Alation, Immuta, Privacera (Trust3 AI), Atlan, Microsoft Purview, Apache Atlas, OneTrust, and BigID (the category leaders in commercial and open-source space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted data governance, metadata management, and open access control. **Critical note**: The open-source landscape is anchored by **Apache Atlas**—the most mature metadata governance framework for Hadoop ecosystems—and **DataHub** and **OpenMetadata** as modern catalog alternatives. However, no open-source project matches Snowflake Horizon's agent identity governance or Collibra's business glossary depth out of the box.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global data governance market is valued at approximately **$4.3B–$5.4B in 2025** and projected to surpass **$17B+ by the early 2030s**, propelled by regulatory pressure (GDPR, EU AI Act) and multi-cloud architectural complexity. The vendor landscape is **moderately concentrated at the top**—dominated by mega-cap cloud providers (Microsoft, Snowflake) and specialized leaders (Collibra, OneTrust) holding 30%–40% share—yet remains **fragmented across point solutions** in cataloging, data access control, and privacy posture management.

## SaaS/Hosted Platforms

| Product | Company Valuation / Revenue | Pricing (Starting Tier) | Free Tier / Free Trial Limits | Key Focus & Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Purview](https://www.microsoft.com/purview)** | **$3.1T–$3.6T** (Market Cap) / **$245B+** Revenue | **$0.0165 / governed asset / day** (~$0.50/asset/month) on Unified Catalog pay-as-you-go; or part of M365 E5 compliance suites | **Free version** includes up to **1,000 annotated assets** (inactivity cleanup after 90 days); plus a **90-day free trial** with 25 M365 Purview Suite licenses | Unified enterprise catalog, data map scanning, DLP, and cross-cloud sensitivity labeling. |
| **[Snowflake Horizon](https://www.snowflake.com/)** | **~$55B–$65B** (Market Cap) / **$3.6B** Revenue | Included with Snowflake; full Horizon governance requires **Enterprise Edition at $3.00/credit** (plus compute/storage consumption) | **30-day free trial** with **$400 in free usage credits** (whichever limit is reached first) | Native governance, Agent Identity for AI agents, Open Semantic Interchange, and Trust Center posture monitoring. |
| **[Collibra Data Intelligence](https://www.collibra.com/)** | **$5.25B** (Valuation) / **~$210M+** ARR | Starts at **~$170,000/year** (SAP Store listing for 20 Standard users + unlimited read-only users, base integrations) | **No self-serve free trial**; access provided strictly via custom enterprise PoC or guided demo | Enterprise data catalog, policy governance, continuous data quality, and business glossaries. |
| **[OneTrust](https://www.onetrust.com/)** | **$4.5B** (Valuation) / **~$500M+** ARR | Entry-level packages start at **~$10,000/year** (~$800–$1,100/month for single modules like basic consent) | **14-day free trial** for select modules (e.g., Cookie Consent/Privacy); full suite requires sales-led guided PoC | Data privacy automation, consent management, DSAR workflows, and compliance posture. |
| **[Alation](https://www.alation.com/)** | **$1.7B** (Valuation) / **~$109M** ARR | Base platform entry packages start at **~$20,000–$60,000/year**; standard full enterprise deployments average **~$198,000/year** | **No self-serve free trial**; evaluation conducted via tailored guided enterprise PoC / pilot program | Data catalog with ALLIE AI auto-tagging, column-level lineage, and AI Agent SDK (MCP support). |
| **[BigID](https://bigid.com/)** | **~$1.0B–$1.25B** (Valuation) / **~$100M+** ARR | Starter enterprise discovery packages (e.g., AWS Marketplace Foundation) start at **~$175,000/year** | **No self-serve free tier** for main suite; offers free risk assessment & CMP Express trial (full platform via scoped PoC) | Deep data discovery, classification across structured/unstructured data, DSPM, and shadow AI governance. |
| **[Immuta](https://www.immuta.com/)** | **~$1.0B** (Valuation) / **~$24M+** ARR | Base packages on AWS Marketplace start at **~$96,000/year** (bundled Immuta Units for access orchestration) | **No open-ended free tier**; custom evaluation / PoC available on request via AWS Marketplace private offers | Attribute-based access control (ABAC), dynamic masking, and Custom Securables beyond native databases. |
| **[Atlan](https://atlan.com/)** | **$750M** (Valuation) / **~$30M–$70M** ARR | Enterprise cloud marketplace listings start at **~$120,000/year** (scales by assets, user seats, and AI credits) | **14 to 30-day guided PoC** with read-only connectors available via sales or AWS private offer; no open self-serve tier | Active metadata platform, AI context layer, Model Context Protocol (MCP) server, and data marketplace. |
| **[Privacera (Trust3 AI)](https://privacera.com/)** | **~$250M–$500M** (Valuation) / **~$35M–$38M** ARR | PrivaceraCloud Starter Pack on AWS Marketplace starts at **~$100,000/year** (covers core data access governance) | **30-day free trial** for PrivaceraCloud on AWS Marketplace; custom PoC for enterprise multi-cloud setups | Agentic data and AI access governance, Apache Ranger-based centralized policies, and trust agents. |


## Open-Source GitHub Projects



- **[Apache Atlas](https://github.com/apache/atlas)**

  **Open-source metadata management and governance framework** (Apache-2.0) — **the most mature open-source data governance framework**, designed for enterprises to capture, manage, and govern metadata across systems . **Features**: **Centralized metadata repository** for databases, tables, columns, and relationships; supports Hadoop, relational databases, cloud storage, and more; **data classification** and access controls; **data lineage tracking**—trace origin and transformations of data assets for GDPR compliance; **data discovery** and metadata search; integration with other data management tools . **Tech stack**: Java. **Deploy**: Self-hosted (requires Hadoop ecosystem). **Trade-off**: **Hadoop-ecosystem-centric**—heavier and more complex than modern alternatives; UI and architecture feel dated. **Best for**: organizations running Hadoop/Spark ecosystems needing centralized metadata governance with lineage and classification.



- **[DataHub](https://github.com/datahub-project/datahub)**

  **Modern metadata platform** (Apache-2.0, originally LinkedIn) — **the most actively developed open-source metadata catalog**, with real-time metadata ingestion and a modern UI. **Features**: **Metadata search and discovery**; **column-level lineage**; **governance** with tags, terms, and ownership; **real-time ingestion** from warehouses, BI tools, and pipelines; **extensible** via metadata model and APIs. **Tech stack**: Java, Python, React. **Deploy**: Self-hosted (Docker, Kubernetes) or Acryl Cloud. **Trade-off**: **Catalog and metadata, not full governance suite**—no native access control enforcement or privacy automation like Immuta or BigID. **Best for**: teams wanting a modern, actively maintained metadata catalog with lineage—especially those migrating from Apache Atlas.



- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**

  **Open metadata platform with governance features** (Apache-2.0) — **the most complete open-source alternative to commercial catalogs**, with classification and quality capabilities. **Features**: **Auto Classification** for PII tagging; **Data Quality tests**; **column-level lineage**; **governance** with tags, glossary, and ownership; **Collate** (commercial) adds AI-powered recognizers and feedback loops. **Tech stack**: Java, React, PostgreSQL. **Deploy**: Self-hosted (Docker, Kubernetes) or Collate Cloud. **Trade-off**: **Advanced classification features are Collate-gated**—open-source version has base capabilities but not the full AI recognizer loop. **Best for**: organizations wanting a self-hosted catalog with PII classification and governance basics—especially those not on Hadoop.



### Additional Strong Open-Source Options



- **Apache Ranger** — Centralized security policy framework (Apache-2.0). Column masking, row filtering, audit for Hadoop ecosystem. **Note**: **Policy enforcement for Hadoop**, not a full governance catalog. **Best for**: Hadoop/Spark teams needing access control enforcement.

- **Apache Gravitino** — Federated metadata catalog (Apache-2.0, Apache TLP). Unified metadata across warehouses, lakes, and AI assets; MCP server. **Note**: **Catalog federation**, not governance workflows. **Best for**: organizations with heterogeneous metadata sources.



**Frameworks for building custom systems**: Combine **DataHub** or **OpenMetadata** for catalog and lineage with **Apache Ranger** for policy enforcement and **Apache Atlas** for Hadoop-native lineage—creating a composable open-source governance stack. **None of these match Snowflake Horizon's agent identity governance or Collibra's business glossary depth**, but for core cataloging and metadata governance, the open-source options are production-capable.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Data governance platforms handling sensitive data and access policies must comply with data protection regulations (GDPR, CCPA, HIPAA, etc.) and implement appropriate access controls and audit logging.

- **The "agentic governance" vs. "catalog-centric" vs. "access control" vs. "privacy automation" vs. "metadata framework" distinction is critical.** **Snowflake Horizon** is **agentic governance**—it assigns identities to AI agents and monitors their activity . **Collibra, Alation, and Atlan** are **catalog-centric**—they focus on discovery, lineage, and business context . **Immuta** is **access control**—it enforces attribute-based policies across data platforms and custom securables . **OneTrust and BigID** are **privacy automation**—they handle DSARs, consent, and classification . **Apache Atlas** is a **metadata framework**—it captures and governs metadata but does not enforce access policies . **Choose based on whether you need AI agent governance, catalog discovery, access enforcement, privacy compliance, or metadata lineage.**

- **Snowflake Horizon's Agent Identity is a category-defining feature for AI governance.** It assigns verified identities to agents before data access, with full audit trails—addressing the gap where traditional access controls were built for humans, not autonomous agents . **No open-source project replicates this.**

- **Immuta's Custom Securables extend governance beyond databases.** You can register APIs, SaaS applications, and dashboards as securables and apply subscription policies—Immuta decides, your tools enforce via API/webhook . **This is unique among both open-source and commercial options.**

- **Microsoft Purview's governed asset billing requires careful planning.** You are only charged for assets linked to governance concepts (data products, glossary terms, critical data elements)—unlinked assets in Data Map are free . **This rewards governance maturity but penalizes broad cataloging without curation.**

- **Collibra's SAP Store listing shows ~$170,000/year** for 20 Standard users and unlimited read-only users . **This is a six-figure commitment—do not evaluate without enterprise budget approval.**

- **Atlan reviewer notes privacy governance as a weakness** . **For privacy-first requirements, OneTrust or BigID are stronger choices.**

- **Apache Atlas is Hadoop-centric.** It was designed for the Hadoop ecosystem and remains the standard there, but modern alternatives (DataHub, OpenMetadata) offer better UX and active development. **Choose Atlas only if you are already on Hadoop.**

- **Pricing opacity is universal** across Collibra, Alation, Immuta, Privacera, Atlan, OneTrust, and BigID. All require sales contact or quote requests. **Microsoft Purview publishes pay-as-you-go pricing** . **Snowflake Horizon is included with Snowflake.** **Validate with direct vendor conversations against your data source count and governance maturity.**

- Self-hosted open-source solutions require proper infrastructure (Hadoop for Atlas, PostgreSQL for OpenMetadata, Docker for DataHub), security hardening, and ongoing maintenance. **Governance platforms handle sensitive metadata and access policies**—ensure your deployment meets your organization's security and compliance requirements before connecting production systems.



---



**Made for data governance teams, privacy officers, and organizations building transparent governance solutions.**

Let's make Data Governance & Security Suites more open, data-driven, and AI-governed.
