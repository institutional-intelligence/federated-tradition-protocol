# Federated Tradition Protocol

**An open, religion-neutral protocol for designing durable, federated traditions and institutions.**

The **Federated Tradition Protocol (FTP)** is a framework for turning shared ideas, practices, identities, and values into institutions capable of persisting beyond their founders.

It treats tradition-building as an institutional design problem.

A tradition may possess compelling ideas while remaining dependent on particular personalities, informal relationships, or temporary communities. FTP provides a general architecture for addressing continuity, governance, transmission, replication, succession, institutional memory, and federation.

---

## Religion-Neutral by Design

FTP does not specify what a tradition must believe.

The protocol is intended to be usable by religious, philosophical, cultural, artistic, civic, or other communities seeking durable institutional structures.

The content of a tradition belongs to the tradition.

FTP concerns the institutional machinery that allows that content to be organized, transmitted, adapted, governed, and reproduced.

---

## Architecture

FTP is organized in two layers:

### 1. Religion-Neutral Core

The **Federated Tradition Protocol — Religion-Neutral Core** defines general institutional primitives and compatibility requirements without prescribing a particular theology, mythology, ideology, culture, or body of beliefs.

**[Read Federated Tradition Protocol — Religion-Neutral Core v0.1](./federated-tradition-protocol-core-v0.1.md)**

### 2. Implementations

Implementations apply the Core to particular traditions, communities, or institutional projects.

An implementation may supply its own:

* identity and purpose
* teachings or source material
* practices and rituals
* calendar and observances
* membership structures
* local Chapters or equivalent communities
* leadership and succession
* governance
* archives and records
* amendment procedures
* federation between communities
* methods of replication and transmission

The Core defines the architecture.

Implementations supply the content.

---

## Core Specification

The current religion-neutral specification is:

### Federated Tradition Protocol — Religion-Neutral Core v0.1

**[Read Core v0.1](./federated-tradition-protocol-core-v0.1.md)**

Core v0.1 defines the institutional primitives and minimum compatibility requirements for FTP implementations.

It addresses governance, functional authority, accountability, institutional memory, right of exit, due process, conflict resolution, succession, federation, replication, and local adaptation while leaving substantive worldview and traditional content to individual implementations.

---

## Reference Implementations

Reference implementations demonstrate how the abstract FTP architecture can be instantiated as a concrete institutional system.

### European Federated Tradition v0.1

The **European Federated Tradition (EFT)** is the first reference implementation of FTP.

EFT applies the religion-neutral architecture to a modern federated religious and cultural tradition constructed from institutional patterns attested across multiple pre-Christian European traditions.

It does not claim that a single historical "European religion" existed. Instead, it deliberately constructs a modern federated system using compatible historical patterns adapted to contemporary conditions.

**[Explore European Federated Tradition v0.1](./implementations/european/README.md)**

The implementation consists of seven governing documents:

1. **The Charter**
2. **Federation Protocol**
3. **Local Bylaws Template**
4. **Ritual Framework**
5. **Ethical Code**
6. **Officer Manual**
7. **Dispute Procedure**

Together they provide a worked example of how FTP's institutional primitives can become an operational governing architecture.

The European implementation is **not the protocol itself**.

Future implementations may be culturally, religiously, philosophically, artistically, or creatively unrelated to EFT while remaining compatible with the same underlying protocol.

---

## Repository Structure

```text
federated-tradition-protocol/
│
├── README.md
├── federated-tradition-protocol-core-v0.1.md
│
└── implementations/
    └── european/
        ├── README.md
        ├── document-i-the-charter.md
        ├── document-ii-federation-protocol.md
        ├── document-iii-local-bylaws-template.md
        ├── document-iv-ritual-framework.md
        ├── document-v-ethical-code.md
        ├── document-vi-officer-manual.md
        └── document-vii-dispute-procedure.md
```

This structure separates the **general protocol** from the **traditions that implement it**.

Additional implementations can be added without changing the religion-neutral character of the Core.

---

## Forking and Adaptation

FTP is designed for adaptation.

A community may use the Core to construct a new implementation suited to its own worldview, culture, practices, and institutional needs.

Existing implementations may also be forked and adapted where their substantive content is relevant.

These represent two different forms of reuse:

> **Fork an implementation to create a variation of that tradition.**

> **Implement the Core to create a different tradition.**

Neither requires centralized doctrinal control by the original authors.

The goal is not institutional uniformity. The goal is to provide enough structure for traditions to achieve continuity, accountability, transmission, local adaptation, and replication without making every community identical.

---

## Project Status

**Version 0.1 — Experimental architecture**

FTP Core v0.1 and the first reference implementation, European Federated Tradition v0.1, are now published in this repository.

Version 0.1 should be understood as a foundation for testing, discussion, implementation, revision, translation, and further development.

The protocol, terminology, templates, implementation patterns, and licensing model may continue to evolve.

---

## Institutional Intelligence

FTP is a project of **Institutional Intelligence**, an open laboratory for studying how ideas become durable structures.

The broader project focuses on institutional architecture: how communities preserve knowledge, coordinate people, distribute authority, reproduce themselves, survive leadership transitions, adapt to local conditions, and remain coherent across time.

## License

The Federated Tradition Protocol and its reference implementations are licensed under the **Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)**.

You may share and adapt this material, including for commercial purposes, provided that appropriate attribution is given and adaptations are distributed under the same or a compatible license.

See the [LICENSE](./LICENSE) file for the full license terms.
