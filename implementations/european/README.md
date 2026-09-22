# European Federated Tradition

**Reference Implementation of the Federated Tradition Protocol**

**Status:** Draft
**Version:** 0.1

The **European Federated Tradition (EFT)** is the first reference implementation of the [Federated Tradition Protocol](../../federated-tradition-protocol-core-v0.1.md).

EFT demonstrates how the religion-neutral architecture defined by the Federated Tradition Protocol (FTP) can be instantiated as a concrete religious and cultural tradition.

It draws upon institutional patterns attested across multiple pre-Christian European traditions while adapting those patterns to modern conditions.

EFT does **not** claim that a single historical "European religion" existed, nor does it attempt to reconstruct one.

Instead, it identifies compatible institutional patterns, rejects incompatible historical practices, adapts surviving patterns where necessary, and deliberately constructs a modern federated tradition.

---

## Relationship to the Federated Tradition Protocol

The **Federated Tradition Protocol Core** defines the general institutional architecture that an FTP-compatible tradition must implement.

The **European Federated Tradition** supplies one particular religious and cultural implementation of that architecture.

In simplified form:

> **FTP defines the architecture. EFT implements it.**

EFT therefore contains substantive religious, ethical, ritual, and cultural commitments that are **not requirements of FTP itself**.

These include:

* household continuity
* ancestral remembrance
* sacred locality and stewardship
* sacred plurality
* reciprocity
* hospitality
* reputation and responsibility
* seasonal observance
* ritual practice
* mythic plurality
* offering

These are **EFT requirements**, not universal FTP requirements.

Other FTP implementations may adopt entirely different theological, philosophical, cultural, or symbolic content while preserving the same underlying institutional architecture.

---

## Governing Architecture

European Federated Tradition v0.1 is defined through seven governing documents.

### I. The Charter

Defines the purpose of the tradition, its foundational principles, member rights, institutional boundaries, and basic conditions of compatibility.

[Read Document I — The Charter](./document-i-the-charter.md)

### II. Federation Protocol

Defines the minimum institutional standards shared across affiliated communities and establishes the conditions under which autonomous Chapters remain part of the wider Federation.

[Read Document II — Federation Protocol](./document-ii-federation-protocol.md)

### III. Local Bylaws Template

Provides the governance framework from which individual Chapters can establish their own bylaws while remaining compatible with the Federation.

[Read Document III — Local Bylaws Template](./document-iii-local-bylaws-template.md)

### IV. Ritual Framework

Defines the general structure for seasonal observance, rites of passage, remembrance, offerings, and other forms of ritual practice while preserving substantial room for local variation.

[Read Document IV — Ritual Framework](./document-iv-ritual-framework.md)

### V. Ethical Code

Defines the tradition's ethical expectations concerning reciprocity, hospitality, reputation, responsibility, consent, stewardship, and relations within and beyond the community.

[Read Document V — Ethical Code](./document-v-ethical-code.md)

### VI. Officer Manual

Defines the responsibilities, authority, limitations, and accountability of institutional offices within Chapters and the wider Federation.

[Read Document VI — Officer Manual](./document-vi-officer-manual.md)

### VII. Dispute Procedure

Defines processes for addressing interpersonal, organizational, and institutional disputes at both Chapter and Federation levels.

[Read Document VII — Dispute Procedure](./document-vii-dispute-procedure.md)

Together, these seven documents constitute the **European Federated Tradition v0.1 governing architecture**.

---

## Design Principle

EFT follows the FTP distinction between strongly specified institutional structure and locally adaptable traditional content.

Its central design principle is:

> **Practice is required. Belief is not. Structure is specified. Content is local.**

Accordingly, EFT does not require every Chapter to possess identical mythology, theology, ritual language, pantheon, calendar, symbolism, or metaphysical interpretation.

Different distributions and Chapters may develop distinct local forms while remaining institutionally compatible.

This permits substantial cultural variation without reducing the Federation to an informal collection of unrelated groups.

---

## Federation and Local Autonomy

EFT is designed as a **federated rather than centralized tradition**.

The Federation establishes compatibility standards, institutional safeguards, and shared procedures.

Individual Chapters retain meaningful authority over local expression.

A Chapter may therefore adapt such elements as:

* local seasonal observances
* regional mythology and folklore
* honored deities or sacred figures
* ritual language
* music and artistic expression
* local sacred places
* community customs
* educational practices
* culturally appropriate forms of remembrance

Local autonomy does not eliminate institutional requirements. Chapters remain bound by the Charter, Federation Protocol, member protections, governance requirements, and other compatibility rules established by the governing architecture.

---

## Forking and Adaptation

EFT is intended not only to function as a tradition but also to serve as a **worked example of FTP implementation**.

Researchers, organizers, religious communities, cultural projects, and experimental institutions may study or adapt this implementation when developing their own federated traditions.

There are two conceptually different ways to do this.

### Adapt EFT

A community may retain the basic identity and principles of the European Federated Tradition while modifying locally adaptable elements for a particular region, language, culture, or Chapter.

### Implement FTP Independently

A project may instead use the religion-neutral **Federated Tradition Protocol Core** to construct an entirely different tradition.

Such an implementation need not inherit EFT theology, mythology, ethics, ritual forms, European cultural references, or other EFT-specific content.

In that case, EFT functions as a reference implementation rather than as the parent tradition.

---

## Repository Structure

```text
federated-tradition-protocol/
│
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

The Core defines the protocol.

The `implementations/` directory contains concrete systems built using that protocol.

The European Federated Tradition is the first such reference implementation.

---

## Status

**European Federated Tradition v0.1 is an experimental reference implementation.**

Its purpose is twofold:

1. to establish a coherent and usable federated religious and cultural tradition; and
2. to demonstrate how the religion-neutral Federated Tradition Protocol can be instantiated as a concrete institutional system.

Version 0.1 should therefore be understood as a foundation for testing, discussion, implementation, revision, translation, and further development.
