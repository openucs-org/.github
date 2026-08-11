[![Homepage](https://img.shields.io/website?logo=openucs&label=Homepage&url=https%3A%2F%2Fopenucs.org)](https://openucs.org)
[![Slack](https://img.shields.io/badge/openUCS-slack-red?logo=slack&color=E01A59)](https://openucs.slack.com)

![openUCS logo](https://github.com/openucs-org/.github/assets/30368350/536843cd-649c-47b3-998b-714a735051b6)
openUCS envisions building community-driven open-source software components to address the rapidly 
evolving landscape of digital telecom. Fostering a collaborative environment empowers telecom operators 
to harness the collective wisdom and expertise to develop agile, scalable, and effective charging solutions.

## Projects and Repositories
https://github.com/prajithparan/5G-Advanced-Core-and-Charging-R19/tree/main : AI enabled Universal Charging System and 5G Advanced Core 
A modular, standards-faithful 5G Core (5GC) implementation in modern C++, targeting 3GPP Release 19 (5G-Advanced). Every Network Function's northbound API is meant to be generated from the official 3GPP OpenAPI YAML — never hand-written — with a TM Forum SID-aligned charging/BSS domain, a JSON-schema-driven operator GUI, and AI/ML pipelines wired into NWDAF.

This targets a production-grade, spec-traceable reference implementation (raised from an original lab-grade scope — see docs/DECISIONS.md ADR-0009 for why and what that changed). Repo slug (5gc-r19) and technical identifiers (CMake project name, vcpkg package name) stay as short slugs; this is the display name. See docs/DECISIONS.md for every architectural choice made (and rejected) along the way.

