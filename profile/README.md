[![Homepage](https://img.shields.io/website?logo=openucs&label=Homepage&url=https%3A%2F%2Fopenucs.org)](https://openucs.org)
[![Slack](https://img.shields.io/badge/openUCS-slack-red?logo=slack&color=E01A59)](https://openucs.slack.com)

![openUCS logo](https://github.com/openucs-org/.github/assets/30368350/536843cd-649c-47b3-998b-714a735051b6)
A modular, standards-faithful 5G Core (5GC) and Charging (CHF + Online Charging, Gy/CAP) implementation in modern C++, targeting 3GPP R19 (5G-Advanced). R19 is what 3GPP itself brands 5G-Advanced; 6G has no stage-3 specification yet and nothing here implements it, so it is deliberately absent from the title. When Release 20 lands and 3GPP defines 6G, the intent is to carry this architecture forward and revisit the name then — a statement of direction, not a capability claim. Every Network Function's northbound API is meant to be generated from the official 3GPP OpenAPI YAML — never hand-written — with a TM Forum SID-aligned charging/BSS domain, a JSON-schema-driven operator GUI, and AI/ML pipelines wired into both NWDAF and the CHF. The charging half is the CHF of TS 32.290/32.291 plus the online-charging interfaces it terminates: Diameter Gy credit-control with quota and re-authorization, Sy spending limits, and CAMEL/CAP for the legacy voice estate. OCS is deliberately not used as the title — TS 32.296 defines that as its own network function, this does not implement it, and a title should not need a footnote to be true.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/title-dark.svg">
    <img src="docs/assets/title.svg"
         alt="AI-Boosted 5G-Advanced Core and Charging — R19" width="920">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/motto-dark.svg">
    <img src="docs/assets/motto.svg" alt="Built by AI. Built for AI. Bound by the spec."
         width="760">
  </picture>
</p>
Projects and Repositories
![Architecture](https://github.com/prajithparan/AI-Boosted-5G-Advanced-Core-and-Charging-R19/blob/main/docs/diagrams/architecture.svg)
[https://github.com/prajithparan/5G-Advanced-Core-and-Charging-R19/tree/main](https://github.com/prajithparan/AI-Boosted-5G-Advanced-Core-and-Charging-R19)



