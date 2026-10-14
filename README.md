# Awesome-Financial-Anti-Money-Laundering-AML-Monitors

## Top Financial Anti-Money Laundering (AML) Monitors Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Real-Time Transaction Screening, Network Analysis & Suspicious Activity Detection*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Financial Anti-Money Laundering (AML) Monitors**. These tools enable banks, fintechs, VASPs, and payment providers to screen transactions in real time, flag anomalous networks, and detect money laundering typologies before funds move.



**Examples** include ComplyAdvantage, Feedzai, NICE Actimize, Unit21, Flagright, Lucinity, Hawk AI, Napier AI, ThetaRay, and Sanction Scanner (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, real-time rule engines, and open transaction network analysis — ideal for compliance teams, fintech engineers, and developers seeking transparent, vendor-independent AML infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ComplyAdvantage](https://complyadvantage.com/)**  

  AML and sanctions screening platform with **real-time transaction monitoring**, customer risk scoring, and adverse media screening. Trusted by 1,000+ financial institutions globally.



- **[Feedzai](https://feedzai.com/)**  

  AI-native fraud and AML platform with **real-time decisioning** across payment channels. Features network analysis, behavioral biometrics, and explainable AI for compliance teams.



- **[NICE Actimize](https://www.niceactimize.com/)**  

  Enterprise financial crime compliance platform. Features **real-time transaction monitoring**, case management, CDD/EDD workflows, and AI-powered alert triage. Widely deployed at tier-one banks.



- **[Unit21](https://www.unit21.ai/)**  

  No-code fraud and AML platform for fintechs. Features **real-time transaction monitoring**, rules engine, case management, and graph-based network analysis for detecting mule networks and layering chains.



- **[Flagright](https://www.flagright.com/)**  

  AI-native AML compliance and transaction monitoring platform. Features real-time screening, risk scoring, and case management.



- **[Lucinity](https://lucinity.com/)**  

  AI-powered AML investigation platform with **Luci** copilot for alert triage and narrative generation. Features agentic AI for autonomous case analysis.



- **[Hawk AI](https://hawk.ai/)**  

  AI-powered AML and fraud monitoring platform. Features real-time transaction screening, customer risk scoring, and explainable AI for regulatory reporting.



- **[Napier AI](https://napier.ai/)**  

  AI-enhanced AML compliance platform. Features transaction monitoring, screening, and customer risk assessment.



- **[ThetaRay](https://thetaray.com/)**  

  AI-powered AML and fraud detection platform. Features **network-level anomaly detection** and behavioral analytics for identifying previously unknown money laundering patterns.



- **[Sanction Scanner](https://sanctionscanner.com/)**  

  AML screening and monitoring platform. Features sanctions, PEP, and adverse media screening with transaction monitoring.



## Open-Source GitHub Projects



- **[Tazama](https://github.com/tazama-lf)**  

  **The first open-source platform for real-time financial monitoring and fraud detection** (Apache-2.0), launched by the Linux Foundation with support from the Bill & Melinda Gates Foundation. Recognized as a **Digital Public Good**. Built to **ISO 20022 standards** for financial messaging interoperability. Microservices architecture with rule processors, typology scoring, and case management integration. Processes transactions in real time with **configurable rules** evaluating suspicious behavior. **Typology scoring** aggregates rule results into fraud and AML typology scores. Features transaction blocking, Kubernetes Helm charts, and GraphQL access via Hasura. **Deployed at COMESA JOPACC and the Jordanian Clearing House**. **The most comprehensive and institutionally-backed open-source AML platform available.**



- **[Marble (CheckMarble)](https://github.com/checkmarble/marble)**  

  **The flexible open-source alternative to ComplyAdvantage, Actimize, and Fiserv** for transaction monitoring, AML screening, and case investigation powered by AI. Used by **100+ fintechs, banks, and crypto exchanges in 15+ countries**. **Open-source core** with self-hosted or SaaS deployment. Features **real-time transaction monitoring** with custom data models, **sanctions/PEP/adverse media screening**, **continuous monitoring**, **investigation suite** with unified case manager, **AI automation** for rule building and alert triage, **reporting & BI** with direct database access, **audit trail** with searchable and unalterable logs, and **enterprise-grade governance** with RBAC, SSO, and SOC 2 Type II certification. **The most mature open-source AML platform for fintechs.** Marble built **Motiva**, a Rust reimplementation of OpenSanctions' matching engine optimized for high-concurrency real-time screening.



- **[Jube](https://github.com/jube-home/aml-fraud-transaction-monitoring)**  

  **Open-source AML and fraud detection using machine learning for real-time transaction monitoring** (AGPL-3.0). Features **flexible rule engine** with thresholds, velocity checks, aggregation counts, and sanctions screening integrated with ML outputs. **Cloud-native architecture** purpose-built for AML: fully containerized (Docker, Kubernetes), multi-tenancy, highly scalable. Configuration preservation enables backup, restore, and migration. **Default username/password: Administrator/Administrator** requiring change on first login. **The most ML-integrated open-source transaction monitoring platform.**



- **[OpenSanctions](https://github.com/opensanctions)**  

  **Open-source sanctions, PEP, and watchlist data** with matching algorithms (nomenklatura). The **yente** screening API service is fully open-source and self-hostable. Enables **full auditability and explainability** — any datapoint traces back to its source. Marble built Motiva on top of OpenSanctions' matching algorithms — demonstrating the power of open compliance infrastructure. **The foundational open-source data layer for AML screening.**



- **[aml-analytics](https://pypi.org/project/aml-analytics/)**  

  **Open-source Python toolkit for AML detection and financial crime analytics** (MIT). Covers **FATF and FinCEN typologies**: structuring (smurfing), layering, rapid fund movement, network-based laundering, and anomalous transaction behavior. Modules: **synthetic transaction generator**, **transaction network analysis** (structuring rings, layering chains, centrality scoring), **velocity checks** (rolling-window burst detection), **rules engine** (FATF/FinCEN typologies), **unsupervised anomaly scoring** (Isolation Forest, LOF), and **SQL query templates** for Oracle/PostgreSQL. **Built by a financial crimes analytics practitioner for compliance teams.** **The most typology-comprehensive open-source AML toolkit.**



- **[Osprey](https://github.com/opensource-finance/osprey)**  

  **Open-source transaction monitoring in one deployable service** — deploys in **60 seconds** with a single Go binary. Evaluates transactions against **CEL rules** returning ALRT or NALT decisions. Two modes: **detection** (weighted fraud rules with scoring) and **compliance** (rules grouped into FATF typologies). Runtime profiles: **community** (SQLite, in-memory cache) and **pro** (PostgreSQL, Redis, NATS). **The most lightweight open-source rules engine for AML.**



- **[chain-insights](https://www.npmjs.com/package/chain-insights)**  

  **Open-source AML investigation toolkit for AI agents and analysts** (npm). Screen blockchain addresses, trace role-specific fund flows, manage workspace evidence, and generate graph reports. Tools include **aml_address_risk**, **aml_trace_victim_funds** (forward to exchange deposit candidates), **aml_trace_deposit_sources** (backward to upstream sources), **aml_trace_suspect_funds** (scammer/mule/laundering-ring to cashout topology). **GraphRAG MCP endpoint** for read-only GQL/Cypher queries. **The most AI-agent-ready open-source crypto AML toolkit.**



- **[Ballerine](https://github.com/ballerine-io/ballerine)**  

  **Open-source infrastructure for identity and risk management** (Y Combinator-backed). Features **KYC/KYB UI flows**, **case management dashboard**, **integrations with identity verification providers**, and a **rule engine** to automate decisioning. **The most flexible open-source platform for building custom KYC/AML workflows.**



- **[FinSight AI](https://github.com/AwaisRehman/finsight-ai)**  

  **Open-source financial analytics dashboard with rule-assisted fraud screening** (MIT). Pairs **LLaMA 3.3 70B** with live MongoDB transaction store for natural-language querying grounded in actual data. **Rule engine scores each transaction 0-100** using amount and recipient heuristics, flagging entries at threshold 40. Loads dashboard endpoints in under 800ms, returns AI analyses in 1.5-3s on free-tier database. **The most accessible open-source conversational AML analytics tool.**



- **[cryptotrace](https://github.com/cognis-digital/cryptotrace)**  

  **Free-tier blockchain investigator for ETH/BTC clustering and sanctions cross-referencing**. Features **offline/air-gap workflow** with cached SDN sets for disconnected enclaves. **SARIF 2.1.0 output** for GitHub/GitLab code-scanning integration. Demos cover Tornado Cash deposits, SUEX OTC layering, Lazarus Group bridge exits, peel-chain laundering, and DPRK mixer chains. **The most investigation-focused open-source crypto AML tool.**



- **[crypto-aml](https://pypi.org/project/crypto-aml/)**  

  **Crypto AML/KYT Python SDK** with AnChain.AI integration. Features **address risk screening**, **graph visualization**, and **exchange whitelist policy** patterns. Risk score bands: 0-29 LOW, 30-50 GUARDED, 51-79 ELEVATED, 80-100 SEVERE. **The most exchange-integration-ready open-source crypto AML SDK.**



### Additional Strong Open-Source Options



- **[kyc-analyst](https://github.com/vyayasan/kyc-analyst)** — Open-source KYC/AML compliance automation with **17 human-in-the-loop checkpoints**, free public data sources, and deterministic four-factor risk scoring (Geographic 30%, Customer 35%, Product 25%, Channel 10%). **The most audit-trail-focused open-source KYC workflow.**

- **[Marble SAS](https://www.ventureradar.com/organisation/Marble%20SAS/194b98cc-1c7c-4550-be33-60de59c0ea7a)** — Open-source AI-powered FRAML orchestration platform with **no-code rule creation**, A/B testing, and **instant SAR filings**.

- **[fin-classifier](https://pypi.org/project/fin-classifier/)** — Flexible Python library for classifying bank statement transactions based on customizable rules with logical operators (AND, OR, NOT).

- **[nexus-sanctions](https://packagist.org/packages/azaharizaman/nexus-sanctions)** — PHP package for OFAC/UN sanctions screening and PEP detection with batch screening, similarity scoring, and EDD workflow triggers.

- Community **n8n** workflows for AML alert routing and sanctions screening automation.



**Frameworks for building custom systems**: Combine **Tazama** for ISO 20022 real-time monitoring with **Marble** for flexible transaction monitoring and case management, **OpenSanctions** for screening data, **Jube** for ML-integrated detection, **aml-analytics** for typology rules, and **PostgreSQL** for persistence — creating a fully self-hosted, enterprise-grade AML monitoring platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AML monitoring systems handling financial transactions must comply with **BSA/AML, FinCEN, OFAC, AMLD5/6, FATF recommendations**, and applicable local regulations. **SAR/STR filing obligations remain the institution's responsibility.**

- **Open-source AML monitoring is mature and production-ready.** Tazama is a **Linux Foundation Digital Public Good** with Bill & Melinda Gates Foundation support, deployed at clearing houses. Marble is used by **100+ fintechs in 15+ countries** with SOC 2 Type II certification. **These are genuine alternatives to commercial platforms.**

- **Typology coverage matters.** aml-analytics implements **FATF and FinCEN typologies** including structuring, layering, rapid fund movement, and network-based laundering. Jube integrates ML outputs with rule-based detection. **Rules alone are insufficient** — network analysis and ML anomaly detection catch what thresholds miss.

- **False positive reduction requires explainability.** Marble's **open architecture** lets you "basically do anything you want, with all your data" — transparency that proprietary black boxes cannot match. OpenSanctions provides **full auditability and explainability** with source tracing.

- **Crypto AML is converging with traditional finance.** chain-insights provides **AI-agent-ready blockchain investigation** with GraphRAG queries. cryptotrace supports **air-gap workflow** for disconnected enclaves. **Exchange whitelist policies** are a common VASP pattern but represent a **weaker AML posture** — always hard-block sanctions even when exchange tags co-occur.

- Self-hosted open-source solutions require proper security hardening, list update management, and ongoing maintenance. **AML compliance is a regulatory obligation** — tools support detection, but human judgment and legal accountability remain.



---



**Made for compliance officers, AML analysts, fintech engineers, and developers building transparent financial crime detection solutions.**  

Let's make Financial Anti-Money Laundering monitoring more open, data-driven, and explainable.
