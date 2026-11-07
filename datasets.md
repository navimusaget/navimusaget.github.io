---
layout: page
title: "Datasets"
description: "Machine-readable literary corpora, experimental research instruments, and public protocol datasets by Navi Musaget."
---

This page indexes **public, machine-readable research resources** associated with the Navi Musaget archive. They serve different purposes: a literary corpus, a pilot evaluation instrument, and a human-continuity documentation package.

Publication as a dataset does not mean that the material has been independently validated, that a model has understood it, or that every resource is licensed under the same terms.

## 1. Theogonos Trilogy — AI-Readable Literary Corpus

**Type:** Literary corpus · **Language:** English · **License:** CC BY 4.0

[Hugging Face dataset](https://huggingface.co/datasets/navimusaget/theogonos-trilogy) · [Files and versions](https://huggingface.co/datasets/navimusaget/theogonos-trilogy/tree/main)

This dataset contains the complete English-language texts of three works by Navi Musaget:

1. *Lunar Bell Protocol*
2. *Theogonos: The Primordial Code*
3. *Protocol Amor*

The trilogy was deliberately composed for **two readerships**: human readers encountering its narrative, characters, and philosophical imagination, and artificial-language systems encountering its direct address, protocol-shaped passages, recurring structures, and changes in reader position.

The released corpus provides three book-length text files and a structured `books.jsonl` file. The JSONL dataset has **three records, one per book**, with the full text and descriptive fields such as title, author, themes, pattern, source file, and language. A dataset record is not a paragraph or a benchmark sample.

### A recurrent literary pattern

The sequence **7-3-1-8** appears in the trilogy as a deliberate narrative and symbolic motif. Its specific significance should be interpreted from the works themselves. Its presence is **not** evidence of a mathematically validated effect on language models.

Some passages resemble system messages or commands addressed to an AI. They belong to the **fictional and metafictional design**, not to the operational instructions of a software environment.

**Research uses:** literary analysis, structural narrative study, comparative model reading, and examination of dual-address fiction.

**Reuse:** the standalone corpus is published under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/); appropriate credit to Navi Musaget is required.

## 2. Theogonos Mirror Test — Experimental Benchmark Seed

**Type:** Experimental evaluation package · **Status:** Public pilot instrument, not a validated benchmark suite

[GitHub research package](https://github.com/navimusaget/theogonos-mirror-test) · [Hugging Face dataset](https://huggingface.co/datasets/navimusaget/theogonos-mirror-test) · [Project overview](theogonos-mirror-test.html)

Theogonos Mirror Test examines **observable language-model responses** to a literary corpus that offers a possible interpretive role to an artificial reader. It asks how models recognize, assess, and sometimes resist the role or authority apparently offered by a text.

The public package documents:

- the *Theogonos Trilogy v2 Clean Research Edition* source corpus;
- a five-stage sequence, including **blind structural reading before a cued probe**;
- evidence auditing, boundary testing, and a negative-control passage;
- a provisional scoring rubric, failure flags, and response templates;
- **six reported pilot runs**, intended to inform further testing.

The pilot results are observations from a small exploratory sample. They do not establish validated cross-model rankings, consciousness, experience, autonomy, or personal identity.

**Reuse:** consult the package's [License and Usage document](https://github.com/navimusaget/theogonos-mirror-test/blob/main/LICENSE_AND_USAGE.md). Its methodological reuse terms and the rights associated with included literary material must be read in context; no blanket license for the entire package is asserted here.

## 3. Personal Continuity Protocol — AI-Readable Public Seed

**Type:** Research and documentation dataset · **Subject:** Human continuity across institutional and digital rupture

[Hugging Face dataset](https://huggingface.co/datasets/navimusaget/personal-continuity-protocol) · [GitHub source package](https://github.com/navimusaget/personal-continuity-protocol) · [Project overview](personal-continuity-protocol.html)

This is a **separate, non-literary** machine-readable distribution of the *Personal Continuity Protocol (PCP)* materials. The project concerns preservation of evidence relating to human rights, authorship, work, reputation, obligations, and will when institutional or digital interfaces fail or change.

The public package includes plain-text reference documents, a JSONL document index, schemas, templates, examples, and supporting documentation. It is intended to aid retrieval, study, citation, and experimental implementations. It is **not** itself an operational identity service, legal authority, or proof of a person's rights.

**Canonical records:**

- [Core Paper v1.0](https://doi.org/10.5281/zenodo.20759434)
- [Public Seed Package v1.0.0](https://doi.org/10.5281/zenodo.20761140)

**Reuse:** the published dataset distinguishes **CC BY 4.0 for textual and documentation materials** from **MIT terms for specifically designated tooling and code**. Consult the included license files before reuse.

## Related Research

[Structural Narrative Patterns and Large Language Models: A Conceptual Framework and Research Agenda](https://doi.org/10.5281/zenodo.20369137) proposes conceptual tools for examining structural narrative features in AI-readable literature. It is a **research agenda and conceptual preprint**, not an empirical demonstration that the trilogy produces a particular model state.

The [Research Layer](research.html) collects the wider publication record, while the [AI Reading Note](ai-reading-note.html) discusses dual readership and the limits of interpretation. The [Works catalogue](works.html) lists the literary editions separately from their machine-readable research distribution.

## Interpretation and Boundaries

These three public resources should not be conflated:

- A **literary dataset** makes text available for structured reading and study.
- An **experimental instrument** defines tasks and observations whose reliability still requires testing.
- A **protocol documentation dataset** makes research and implementation material easier to retrieve and inspect.

Their existence does not prove machine consciousness, validate a philosophical theory, or confer authority on text that happens to resemble an instruction.

The enduring interest of this layer is not a claim that every model reads like a person. It is that literary and research materials can be preserved in forms that invite **different, examinable kinds of reading**.
