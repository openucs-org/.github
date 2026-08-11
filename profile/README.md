[![Homepage](https://img.shields.io/website?logo=openucs&label=Homepage&url=https%3A%2F%2Fopenucs.org)](https://openucs.org)
[![Slack](https://img.shields.io/badge/openUCS-slack-red?logo=slack&color=E01A59)](https://openucs.slack.com)

![openUCS logo](https://github.com/openucs-org/.github/assets/30368350/536843cd-649c-47b3-998b-714a735051b6)
openUCS envisions building community-driven open-source software components to address the rapidly 
evolving landscape of digital telecom. Fostering a collaborative environment empowers telecom operators 
to harness the collective wisdom and expertise to develop agile, scalable, and effective charging solutions.

Projects and Repositories

5G-Advanced Core and Charging (R19) — AI-Enabled Universal Charging System and 5G Advanced Core

A modular, standards-faithful 5G Core (5GC) built in modern C++ for 3GPP Release 19 (5G-Advanced). Every Network Function's northbound API is generated directly from the official 3GPP OpenAPI YAML rather than hand-written, paired with a TM Forum SID-aligned charging/BSS domain, a JSON-schema-driven operator GUI, and AI/ML pipelines integrated into NWDAF.

The project aims to be a production-grade, spec-traceable reference implementation, expanded from its original lab-grade scope (see docs/DECISIONS.md, ADR-0009, for the reasoning behind that shift). The repo slug (5gc-r19) and technical identifiers (CMake project name, vcpkg package name) remain short and stable; the fuller name above is used for display purposes only. Every architectural decision made along the way, including ones ultimately rejected, is documented in docs/DECISIONS.md.

A couple of notes: I tightened some phrasing ("meant to be generated" → "generated directly," "targets" → "aims to be") for a more confident, polished tone, and cleaned up minor redundancy. Let me know if you'd rather keep it closer to the original wording or want a shorter version.

