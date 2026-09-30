# Awesome-Data-Catalog-Platform

# Top Data Catalog Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Metadata Management, Data Discovery, Lineage, Business Glossary, Governance & Data Context Layers*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Catalogs**. These systems inventory data assets, capture lineage, maintain glossaries, and help teams discover, understand, and govern data across warehouses, lakes, and pipelines.

**Examples** include Alation, Atlan, Collibra, Microsoft Purview, DataHub, CastorDoc, Secoda, IBM Watson Knowledge Catalog, Informatica EDC / Enterprise Data Catalog, Apache Atlas, Select Star, Alex Solutions, and OvalEdge (the category leaders).

**Open-source emphasis**: Data catalogs have a mature open-source ecosystem. **DataHub**, **OpenMetadata**, **Apache Atlas**, **Amundsen**, and related projects are production-ready for many teams. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Alation](https://www.alation.com/)**  
  Enterprise data intelligence and catalog platform strong on discovery, query-driven metadata, and analyst adoption.

- **[Atlan](https://atlan.com/)**  
  Modern data catalog and active metadata platform popular with cloud stacks (Snowflake, dbt, Databricks).

- **[Collibra](https://www.collibra.com/)**  
  Leading data governance and catalog suite for regulated enterprises with formal stewardship workflows.

- **[Microsoft Purview](https://azure.microsoft.com/products/purview/)**  
  Microsoft’s unified data governance and catalog service tightly integrated with Azure and Microsoft 365 estates.

- **[DataHub (Managed / Acryl)](https://datahubproject.io/)**  
  Commercial offerings and managed services around the open-source DataHub metadata platform.

- **[CastorDoc](https://www.castordoc.com/)**  
  Collaborative data catalog focused on documentation, discovery, and analytics team productivity.

- **[Secoda](https://www.secoda.co/)**  
  AI-assisted data catalog and knowledge platform for fast deployment and search across data assets.

- **[IBM Watson Knowledge Catalog](https://www.ibm.com/products/watson-knowledge-catalog)**  
  IBM’s catalog and governance capabilities within the broader Watson and Cloud Pak data portfolio.

- **[Informatica Enterprise Data Catalog / EDC](https://www.informatica.com/)**  
  Enterprise metadata and catalog capabilities within Informatica’s Intelligent Data Management Cloud.

- **[Select Star](https://www.selectstar.com/)**  
  Automated data catalog with strong lineage and usage analytics for modern warehouses.

- **[Alex Solutions](https://www.alexsolutions.com/)**  
  Data catalog and intelligence platform oriented toward enterprise metadata and governance.

- **[OvalEdge](https://www.ovaledge.com/)**  
  Data catalog and governance platform with connectors, lineage, and collaboration features.

## Open-Source GitHub Projects
- **[DataHub](https://github.com/datahub-project/datahub)**  
  Leading open-source metadata platform (originated at LinkedIn) with real-time ingestion, lineage, search, and GraphQL APIs.

- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**  
  Modern open-source data catalog and governance platform with rich connectors, UI, lineage, and quality features.

- **[Apache Atlas](https://github.com/apache/atlas)**  
  Open-source metadata and governance framework with strong lineage and classification roots in the Hadoop ecosystem.

- **[Amundsen](https://github.com/amundsen-io/amundsen)**  
  Lightweight open-source data discovery and metadata engine (originated at Lyft); still used in many existing deployments.

- **[Marquez](https://github.com/MarquezProject/marquez)**  
  Open-source metadata service focused on data lineage; reference implementation of OpenLineage.

- **[OpenLineage](https://github.com/OpenLineage/OpenLineage)**  
  Open standard and tooling for collecting lineage events from data pipelines and jobs.

- **[CKAN](https://github.com/ckan/ckan)**  
  Open-source data portal and catalog platform widely used for open data publishing and discovery.

- **[Magda](https://github.com/magda-io/magda)**  
  Open-source federated data catalog for multi-source discovery and publishing.

- **[Documentation and DataHub / OpenMetadata playbooks](https://datahubproject.io/docs/)**  
  Guides for self-hosting, connector configuration, and operating open catalogs at scale.

- **[Self-hosted catalog stacks](https://github.com/)**  
  Patterns combining DataHub or OpenMetadata with OpenLineage producers and open BI tools.

### Additional Strong Open-Source Options
- Deploying **DataHub** for event-driven, large-scale metadata platforms.
- Choosing **OpenMetadata** for a unified UI, connectors, and governance features out of the box.
- Using **Apache Atlas** in Hadoop/Cloudera-centric environments.
- Emitting lineage with **OpenLineage** / **Marquez** regardless of the front-end catalog.
- Accepting that enterprise stewardship workflows, heavy regulatory packaging, and fully managed operations still drive many organizations to commercial platforms (Alation, Atlan, Collibra, Purview, Informatica, etc.).
- Focusing open-source efforts on metadata ownership, cost control, and integration with modern data stacks.

**Frameworks for building custom systems**: Ingest metadata with DataHub or OpenMetadata connectors → capture lineage via OpenLineage → maintain glossary and ownership in the catalog → expose search to analysts and AI agents. Suitable for engineering-led and mid-market teams. Large regulated enterprises often still standardize on commercial catalogs.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data catalogs surface sensitive metadata and access patterns. Secure deployment, access control, and compliance remain the operator’s responsibility. This list is not governance or legal advice.

---
**Made for data engineers, analytics leaders, and open metadata advocates.**
Let's keep data discoverable, governed, and as open as practical.
