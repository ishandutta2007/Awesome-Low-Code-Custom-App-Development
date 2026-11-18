# Awesome-Low-Code-Custom-App-Development

# Awesome-Low-Code-Custom-App-Development

# Awesome-Low-Code-Custom-App-Development

# Awesome-Low-Code-Custom-App-Development

# Awesome Low-Code Custom App Development

> A curated list of top Low-Code Custom App Development platforms — both SaaS/Hosted commercial solutions and open-source alternatives for building internal tools, business apps, and operational systems with minimal hand-coding.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Microsoft Power Apps](#microsoft-power-apps)
  - [Zoho Creator](#zoho-creator)
  - [OutSystems](#outsystems)
  - [Mendix](#mendix)
  - [Appian](#appian)
  - [Quickbase](#quickbase)
  - [Retool](#retool)
  - [Caspio](#caspio)
  - [Glide](#glide)
  - [Betty Blocks](#betty-blocks)
- [Open-Source Software](#-open-source-software)
  - [Appsmith](#appsmith)
  - [ToolJet](#tooljet)
  - [Budibase](#budibase)
  - [Lowcoder](#lowcoder)
  - [Windmill](#windmill)
  - [Saltcorn](#saltcorn)
  - [NocoBase](#nocobase)
  - [Baserow](#baserow)
  - [Open Mercurio](#open-mercurio)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Low-Code Custom App Development platforms. These are not open-source but are included as reference points for feature comparison.

### Microsoft Power Apps
**Type:** Low-code app builder within Power Platform
Power Apps provides a drag-and-drop canvas for building business apps connected to Microsoft 365, Dynamics 365, and hundreds of connectors. It includes Power Fx formula language and integration with Power Automate flows. It is the default choice for organizations already standardized on Microsoft, with per-user and per-app licensing options.

### Zoho Creator
**Type:** Low-code platform with Deluge scripting
Zoho Creator combines visual app building with Deluge, a scripting language for custom logic and API integration. It includes forms, workflows, reports, dashboards, and a mobile app builder, with pricing based on users and records. It is the natural choice for organizations already in the Zoho ecosystem.

### OutSystems
**Type:** Enterprise low-code platform
OutSystems is a long-standing enterprise low-code platform for building web and mobile applications with visual modeling, full-stack capabilities, and deployment automation. Known for enterprise governance, lifecycle management, and integration depth. Pricing is quote-based and targets mid-to-large enterprises.

### Mendix
**Type:** Enterprise low-code with model-driven development
Mendix (Siemens) provides a visual development environment with model-driven architecture, multi-cloud deployment, and strong governance features. It supports collaborative development between business users and IT. Pricing is quote-based with a free tier for small teams.

### Appian
**Type:** Low-code automation with process orchestration
Appian's low-code platform combines visual app design with process automation, case management, and AI capabilities. It is strong in regulated industries needing audit trails and compliance controls. Pricing is quote-based.

### Quickbase
**Type:** Low-code platform for operational apps
Quickbase provides a no-code/low-code platform for building operational apps with forms, workflows, dashboards, and Pipelines for automation. It is positioned for teams wanting to replace spreadsheets with structured business apps.

### Retool
**Type:** Internal tool builder for developers
Retool is a widely adopted platform for building internal tools, admin panels, and dashboards with drag-and-drop components and connections to databases and APIs. It includes a JavaScript code editor for custom logic. Pricing is per-user with a free tier.

### Caspio
**Type:** No-code database app builder
Caspio provides a no-code platform for building database-driven apps with forms, reports, and workflows, without requiring server infrastructure. It is positioned for organizations wanting a managed database backend with app-building capabilities.

### Glide
**Type:** No-code app builder from data sources
Glide builds apps from Google Sheets, Airtable, and other data sources with a visual editor. Focused on simplicity for business users creating internal apps and directories. Pricing is per-user with a free tier.

### Betty Blocks
**Type:** Low-code platform for enterprise innovation
Betty Blocks provides a no-code/low-code platform with a visual builder and reusable components, positioned for enterprise innovation teams wanting to build apps quickly without deep technical skills.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Low-Code Custom App Development tools. The open-source ecosystem spans **internal tool builders**, **all-in-one no-code platforms**, **code-first workflow platforms**, **configurable database-backed apps**, and **Airtable-style hybrids**.

### Appsmith
**Stack:** Java / React / MongoDB | **License:** Apache-2.0
Appsmith is an open-source framework to build admin panels, CRUD apps, and workflows, positioned as a Retool alternative. It has **41k GitHub stars**, a Repoly health score of **98/100**, and **1,896 commits in 90 days** . Its **Apache-2.0 license is permissive**, allowing forking or embedding without publishing changes . It offers a cloud free plan and paid plans from $15/user/month (Business) . It is the strongest choice for teams that need permissive licensing or plan to embed the builder into their own product.
**Best for:** Teams prioritizing a permissive license and high development velocity for internal tools, particularly those wanting to embed or customize without copyleft obligations.

### ToolJet
**Stack:** Node.js / React / PostgreSQL | **License:** GPL-3.0 (Community) / AGPL-3.0 (self-hosted)
ToolJet is an extensible low-code framework for building and deploying internal tools, positioned as an alternative to Retool and Mendix . Key features include a drag-and-drop interface with **40+ pre-built UI components**, **30+ database connectors**, REST API and GraphQL integration, real-time data synchronization, and multi-user collaboration with role-based permissions . It is **one of the healthiest open-source projects** in this category, with a Repoly health score of **98/100**, **41k GitHub stars**, and **1,421 commits in 90 days** . It offers a **permanent cloud free plan** (2 builders, 50 end users, 2 apps, 100 AI credits/month) and a fully open-source community edition for unlimited self-hosted users .
**Best for:** Teams wanting the most feature-dense open-source Retool alternative with strong health metrics and a generous free tier, accepting copyleft licensing for self-hosted distribution.

### Budibase
**Stack:** Node.js / Svelte | **License:** GPL-3.0 (Open Source) / Proprietary (Enterprise)
Budibase is an open-source low-code platform for building, automating, and shipping internal tools on your own infrastructure, positioned as an alternative to OutSystems, Retool, Mendix, and Appian . It includes a **built-in database** plus connectors for Postgres, MySQL, MongoDB, Airtable, and REST APIs, with an automation engine for scheduled jobs and multi-step workflows . The **self-hosted edition is free forever under GPLv3** with no per-seat or per-app license fee . **Important caveat:** Its cloud free tier has been limited to 5 users, and Repoly reports its current license as Proprietary/source-available rather than pure open source—verify licensing terms carefully for your use case .
**Best for:** Teams wanting an accessible, all-in-one open-source internal tool builder with built-in automation, verifying current licensing before deployment.

### Lowcoder
**Stack:** Java / Node.js / React / MongoDB / Redis | **License:** AGPL-3.0 (Community Edition)
Lowcoder is an open-source Retool alternative for building internal tools, admin panels, dashboards, and customer-facing apps with a drag-and-drop editor . It connects to databases and APIs, is scriptable with JavaScript, and supports embedding. The Community Edition is self-hostable with MongoDB and Redis dependencies . It is positioned as a direct alternative to Retool with a familiar visual editor and JavaScript scripting.
**Best for:** Teams wanting a self-hosted Retool alternative with a familiar visual editor and JavaScript scripting, accepting the AGPL license and MongoDB/Redis dependencies.

### Windmill
**Stack:** Rust / Go / TypeScript / PostgreSQL | **License:** AGPLv3 (Community)
Windmill is an open-source developer platform that turns scripts into webhooks, workflows, and UIs, positioned as an **open-source alternative to Retool and Temporal** [from previous context]. It is a **code-first** platform: you write scripts in Python, TypeScript, Go, or Bash, and Windmill automatically generates a UI from the script's parameters. It claims to be the **fastest workflow engine (13x vs Airflow)** . It has 12,931 GitHub stars and active development . The community edition is free for internal use under AGPLv3 .
**Best for:** Developer teams wanting to turn existing scripts into internal UIs and workflows with a fast, code-first platform, accepting AGPL terms.

### Saltcorn
**Stack:** Node.js / PostgreSQL | **License:** MIT
Saltcorn is an open-source no-code application builder with a focus on **self-hosting simplicity**—it can run on a **2 GB VPS** and installs via a simple `npx saltcorn-install -y` command on Linux . It provides a drag-and-drop UI builder, data views, and a plugin ecosystem. It is positioned for users wanting a straightforward, self-hosted no-code platform without the complexity of enterprise tools. **Trade-off:** Less feature-dense than ToolJet or Appsmith, with a smaller community.
**Best for:** Individuals and small teams wanting a lightweight, MIT-licensed no-code builder they can run on minimal infrastructure.

### NocoBase
**Stack:** Node.js / TypeScript / PostgreSQL | **License:** AGPL-3.0 (open-core)
NocoBase is an open-source, self-hosted no-code development platform with a **data-model-driven** architecture, allowing teams to build internal apps and business systems by defining collections, fields, relationships, and pages . It supports multiple data sources (PostgreSQL, MySQL, MariaDB, SQLite), block-based page building, role-based access control, and plugin extensibility . It is explicitly positioned for projects that are **complex, private, or require tight control over data and deployment** . **Trade-off:** The open-core model gates some enterprise features, and the data-model-driven approach requires understanding the underlying architecture.
**Best for:** Teams wanting a data-model-driven no-code platform they fully control, particularly for complex internal systems with custom data structures.

### Baserow
**Stack:** Python / Django / Vue.js / PostgreSQL | **License:** MIT (Open Source Edition) / Proprietary (Premium)
Baserow is an open-source no-code database and application builder, positioned as an Airtable alternative with a **production-ready Application Builder** (declared stable in version 2.4.1) . It provides a spreadsheet-like interface with 20+ field types, forms, and automations. The **Open Source Edition is MIT-licensed**, with premium features under a separate commercial license. Self-hosting uses an all-in-one Docker image that bundles PostgreSQL, Redis, and Caddy .
**Best for:** Teams wanting an open-source Airtable alternative with a production-ready application builder, accepting that it is database-first rather than a full drag-and-drop tool builder.

### Open Mercurio
**Stack:** TypeScript / Next.js / NestJS / PostgreSQL | **License:** Open Source (GitHub)
Open Mercurio is an open-source **meta-framework for building internal business applications** with a visual, no-code interface, positioned as an alternative to Retool, Power Apps, Appsmith, and Budibase . Key characteristics:
- **Visual database editor**: Drag-and-drop tables, columns, and relations 
- **No-code UI builder**: Master-detail views, data grids, validation, forms, and role-based permissions 
- **Role-based access control** with per-table and per-action permissions 
- **AI-ready**: Described as "Made for AI" (MCP-based) with modular architecture 
- **Monorepo**: Applications (API + web), shared model packages, and integration packages (LangChain, OpenAI, TypeORM) 

**Important:** It is described as **experimental** (version 0.1.1) and more of a boilerplate/platform foundation than a finished product—it may not be production-ready.  
**Best for:** Developers wanting an extensible, TypeScript-based foundation for building custom no-code platforms, accepting experimental maturity.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Built-in DB | Visual Builder | Self-Hosted | Best For |
|----------|---------|-------|-------------|----------------|-------------|----------|
| **Power Apps** | Proprietary | Cloud | (Dataverse) | ✅ Drag-and-drop | ❌ | Microsoft ecosystem |
| **Zoho Creator** | Proprietary | Cloud | ✅ | ✅ Visual | ❌ | Zoho ecosystem + Deluge |
| **OutSystems** | Proprietary | Cloud | ✅ | ✅ Visual | ❌ | Enterprise low-code |
| **Mendix** | Proprietary | Cloud | ✅ | ✅ Model-driven | ❌ | Enterprise collaboration |
| **Retool** | Proprietary | Cloud | (Connectors) | ✅ Drag-and-drop | (Self-hosted) | Internal tools |
| **Appsmith** | Apache-2.0 | Java/React/MongoDB | (Connectors) | ✅ Drag-and-drop | ✅ | Permissive OSS + embed |
| **ToolJet** | GPL/AGPL | Node.js/Postgres | (Connectors) | ✅ 40+ components | ✅ | Feature-dense OSS |
| **Budibase** | GPL-3.0 | Node.js/Svelte | ✅ Built-in | ✅ Drag-and-drop | ✅ | All-in-one + automation |
| **Lowcoder** | AGPL-3.0 | Java/Node/MongoDB | (Connectors) | ✅ Drag-and-drop | ✅ | Self-hosted Retool alt |
| **Windmill** | AGPLv3 | Rust/Go/TS | (Script-based) | (Auto-generated) | ✅ | Code-first scripts → UIs |
| **Saltcorn** | MIT | Node.js/Postgres | ✅ | ✅ Drag-and-drop | ✅ | Lightweight 2GB VPS |
| **NocoBase** | AGPL-3.0 | Node.js/TS/Postgres | ✅ | ✅ Data-model-driven | ✅ | Complex data-driven apps |
| **Baserow** | MIT (OSS) | Python/Vue | ✅ | ✅ App Builder | ✅ | Airtable-style database |
| **Open Mercurio** | Open Source | TypeScript/Postgres | ✅ | ✅ Visual | ✅ | Meta-framework (experimental) |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Low-Code Custom App Development tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source (or clearly note if it is source-available but not OSI-approved, as with Budibase's current licensing).

**Note on the open-source ecosystem:** The open-source landscape for **low-code custom app development** is **very mature for internal tools**, with **ToolJet** and **Appsmith** leading on health and community metrics . **Appsmith** is the strongest choice if a permissive license matters , while **ToolJet** offers the densest feature set with a generous cloud free tier . **Budibase** provides an all-in-one option with built-in database and automation, though its current licensing warrants verification . For **code-first developer teams**, **Windmill** turns scripts into UIs automatically . For **data-model-driven complex apps**, **NocoBase** offers a configurable approach . **Saltcorn** and **Baserow** serve teams wanting simpler, lightweight options . No single open-source project fully replicates Power Apps' breadth of Microsoft ecosystem integration or OutSystems' enterprise governance, but these tools cover the core visual app-building workflow comprehensively for self-hosted deployments.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
