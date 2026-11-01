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
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Snowflake Horizon](https://www.snowflake.com/)**
  **Native governance and security suite** within the AI Data Cloud. **Horizon Context** unifies business logic across the enterprise so tools, teams, and AI agents operate on the same definitions; **Semantic Studio** lets users define shared business logic without SQL, and **Semantic View Autopilot** generates and refines semantic views automatically . **Agent Identity** assigns verified identities to AI agents before data access, enforcing role-based permissions and full audit trails; **Trust Center** continuously monitors AI security posture and investigates violations . Supports **Open Semantic Interchange (OSI)** for vendor-neutral business definitions . **Pricing**: Included with Snowflake; consumption-based credits apply. **Free tier**: Trial credits. **Best for**: Snowflake customers wanting unified governance across data and AI agents—**trade-off**: Snowflake ecosystem lock-in.

- **[Collibra Data Intelligence](https://www.collibra.com/)**
  **Enterprise data governance and catalog** platform. **Pricing**: SAP Store lists **~$170,000/year** for 20 Standard users + unlimited read-only users, production and non-production environments, and initial integrations . **Free tier**: None. **Best for**: enterprises needing flexible governance, enterprise-wide catalog, continuous quality, and built-in privacy —**trade-off**: six-figure annual commitment.

- **[Alation](https://www.alation.com/)**
  **Data catalog with AI-powered discovery** and governance. **Features**: Machine learning interprets natural language for data search; lineage, tags, trust flags, and endorsements; **ALLIE AI** recommends metadata descriptions; **Agentic Platform** with Documentation Agent and Data Quality Agent (beta/GA Q2 2025); **AI Agent SDK** supporting Anthropic's MCP for building agents on Alation's capabilities . **Pricing**: Quote-only. **Free tier**: None. **Best for**: teams wanting a people-first governance approach with AI-assisted cataloging—**trade-off**: no public pricing; privacy governance noted as weaker area .

- **[Immuta](https://www.immuta.com/)**
  **Data security and access control** platform. **Custom Securables** extend subscription policies to any object—APIs, SaaS applications, dashboards—beyond directly integrated data platforms. Immuta acts as **policy decision point**, providing access decisions while self-administered tools enforce them via API or webhooks . Named Snowflake's Data Cloud Product Data Security Partner of the Year (2024, second consecutive year) . **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting fine-grained, attribute-based access control across diverse systems—**trade-off**: enterprise pricing; custom securables require integration work.

- **[Privacera (Trust3 AI)](https://privacera.com/)**
  **Agentic data and AI governance** platform. **Features**: Trust agents for governing data and AI with enterprise-grade security; positioned as "the #1 Agentic Platform to Meet All Your Data and AI Governance Needs" . **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises wanting AI-era governance with agentic automation—**trade-off**: rebranded platform; verify feature continuity.

- **[Atlan](https://atlan.com/)**
  **Enterprise context layer for AI** and data catalog. **Features**: Connects to **100+ systems**—knowledge bases, work systems, warehouses, BI tools—reverse-engineering context from metadata, column-level lineage, and query history; delivers context downstream via **Model Context Protocol, A2A, SQL, and APIs**; **Data Quality Studio**, **Data Product Marketplace**, and **Context Agent Studios** . **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting AI-ready context with fast time-to-value (1 month per reviewer)—**trade-off**: privacy governance noted as a weakness .

- **[Microsoft Purview](https://www.microsoft.com/purview)**
  **Unified data governance** with pay-as-you-go billing since January 6, 2025. **Unified Catalog** charges based on **unique governed assets per day**—assets are only counted when linked to governance concepts like data products, critical data elements, or glossary terms; unlinked assets in Data Map are free . **Data Map** scanning is free under certain billing conditions . **Pricing**: Pay-as-you-go (governed assets + data health processing units). **Free tier**: Data Map scanning free under conditions; classic Data Catalog available without pay-as-you-go consent . **Best for**: Microsoft-centric enterprises wanting usage-based governance—**trade-off**: governed asset definition requires careful planning to control costs.

- **[OneTrust](https://www.onetrust.com/)**
  **Privacy and data governance** platform. **Features**: Data discovery and classification, data mapping, DSAR automation, consent management, incident management, policy management, and privacy training . **Pricing**: Quote-only. **Free tier**: None. **Best for**: privacy teams needing comprehensive compliance automation—**trade-off**: privacy-first; less depth in technical metadata governance.

- **[BigID](https://bigid.com/)**
  **Data intelligence platform** for the AI era. **Features**: Discovery and classification across structured, unstructured, cloud, SaaS, on-premises, and AI-connected data; connects sensitivity to identity, access, activity, lineage, ownership, and business context; **AI Security and Governance**—discovers models, agents, copilots, prompts, datasets, vector stores, pipelines, and shadow AI . **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting data intelligence across data, identity, and AI—**trade-off**: enterprise pricing; broad platform requires scoping.

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
