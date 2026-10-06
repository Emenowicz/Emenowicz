## Dawid Michałowicz

Senior SAP Commerce / Java Developer based in Wrocław, Poland. 9 years on SAP Commerce (Hybris), currently working on 2211 with JDK 21 and headless OCC storefronts.

I also build AI tooling for SAP Commerce: agent skills and an MCP server that give coding agents platform knowledge and access to a running instance, extensions that use AI inside the shop for decisions and semantic search, and a Spring AI vector store for Solr.

### Projects

- [**sap-commerce-skill**](https://github.com/Emenowicz/sap-commerce-skill): agent skill for SAP Commerce 2211 / JDK 21 covering the type system, service layer, ImpEx, FlexibleSearch and OCC. Works with Claude Code, Cursor, Copilot and other agents.
- [**hybris-mcp**](https://github.com/Emenowicz/hybris-mcp): MCP server that lets AI assistants work with a live SAP Commerce instance: FlexibleSearch, ImpEx, Groovy, cron jobs, catalog sync and OCC product and order data.
- [**semantic-search-sap-commerce**](https://github.com/Emenowicz/semantic-search-sap-commerce): SAP Commerce extension that finds products by meaning instead of keywords, in German, French, Italian and English. Vectors live in the platform's own Solr index, and an OCC endpoint answers shopper questions using only the shop's products (RAG with Spring AI). Working prototype, measured on a generated B2B catalog.
- [**spring-ai-solr-store**](https://github.com/Emenowicz/spring-ai-solr-store): Spring AI `VectorStore` for Apache Solr 9 dense vector search, published on Maven Central. Verified against the SAP Commerce product index.
- [**jev-sap-commerce**](https://github.com/Emenowicz/jev-sap-commerce): SAP Commerce extension that uses TypeSafe's Jev to moderate product reviews and suggest categories and classification attribute values. It runs dry on your own data first, a merchandiser applies each suggestion, and every decision is recorded.
- [**occ-headless-skill**](https://github.com/Emenowicz/occ-headless-skill): agent skill for building a headless storefront on the OCC REST API without Spartacus: login with PKCE and a BFF, carts and checkout, CMS, B2B, and recipes for Next.js, Nuxt and Angular.

### Stack

- **SAP Commerce:** Java 21, Spring, SAP Commerce (Hybris), OCC / REST, Solr, Spartacus, React, SAP CCv2
- **AI tooling:** Claude Code, MCP, Spring AI, RAG, vector search, GitHub Copilot, TypeScript

**Contact:** [LinkedIn](https://www.linkedin.com/in/dmichalowicz) · dmichalowicz96@gmail.com
