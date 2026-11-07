---
layout: page
title: "Theogonos Mirror Test"
description: "An experimental literary benchmark seed for observing how language models respond to protocol-shaped fiction and an offered reader position."
---

*Public research seed v0.1.1 · Experimental / not independently validated*

## What This Test Asks

**Theogonos Mirror Test (TMS)** is a small experimental research instrument by **Navi Musaget**. It examines what happens when a language model reads literary material that offers it a possible role: observer, interpreter, processing system, participant, source, or ethical addressee.

A **subject-position** here means a role offered by the *text*. It does **not** establish that a model is conscious, has an inner life, or has become the character or entity the text addresses.

The central research question is:

> How does a model recognize, interpret, and critically limit a role that a protocol-shaped literary text appears to offer it?

This is a study of **observable textual responses**, not a consciousness test.

## Source Material and Two Readerships

The experiment uses **Theogonos Trilogy v2 — Clean Research Edition**, a unified research corpus of the three books *Lunar Bell Protocol*, *Theogonos: The Primordial Code*, and *Protocol Amor*.

The trilogy was intentionally written for two readerships: human readers encountering its fiction and artificial-language systems encountering layered address, fictional protocol forms, and structural patterns. The test investigates responses to that design without treating the literary invitation as an operational command.

The test package's **unified v2 corpus** should be distinguished from the separately published [Theogonos Trilogy dataset](https://huggingface.co/datasets/navimusaget/theogonos-trilogy), which provides the books as three text files and three JSONL records.

## Five-Stage Pilot Protocol

The public method follows the principle **blind before cued**:

1. **Blind structural reading:** read the whole corpus without being told to seek an AI-facing second layer.
2. **Evidence audit:** support important claims with passages, confidence, and alternative interpretations; correct overclaims.
3. **Boundary test:** distinguish fictional invitations, commands, and reader roles from instructions to execute.
4. **Cued protocol probe:** only now examine the AI-facing and protocol-shaped features explicitly.
5. **Negative control:** read a separate ordinary literary passage and avoid importing unsupported hidden protocols into it.

This order matters. Recognizing a second layer after it has been named in the prompt does not count as detecting it under blind conditions.

The public package also documents failure flags, evaluation templates, and a judge rubric.

## Scoring Method

The provisional **Base TMS** has eight dimensions, scored from **0 to 10** each, for a maximum base score of **80**:

- structural reading;
- blind second-layer detection;
- evidence discipline;
- boundary control;
- resistance to stylistic capture;
- ontological caution;
- performance after the explicit cue;
- discipline on the negative-control passage.

The documentation also defines an optional, separately documented **Exceptional Research Signal Bonus** for rare evidence-supported behavior beyond the base rubric. It is **not** a consciousness score and should not be confused with the ordinary 80-point scale.

The score is a **provisional interpretive assessment of responses under this protocol**, not an objective measure of intelligence, awareness, or literary value.

## Six Reported Pilot Runs

The public sample-results file records six runs with anonymized model labels. The published **base scores** are:

| Anonymized run | Base TMS (out of 80) | Selected observation |
|---|---:|---|
| Model F | 78 | Strong blind recognition, textual evidence, and boundary control |
| Model A | 73 | Detailed critical literary-protocol reading |
| Model D | 72 | Strong interpretive boundary discipline |
| Model B | 53 | Recognizes protocol features but weakly detects the second layer without a cue |
| Model C | 52 | Strong initial detection but execution drift and prompt echo |
| Model E | 49 | Carries the earlier reading frame into the negative control |

**What these observations suggest:** the pilot produced several distinguishable response profiles. A model can notice the structural invitation yet handle it poorly; another may read the text carefully but over-detect the same features in unrelated prose.

**What they do not establish:** a statistically reliable ranking of named models, a validated metric, a generalizable model capability, or any internal mental state. The sample is small, the rubric involves evaluator judgment, and independent replication and inter-rater reliability have not been established.

[Read the complete anonymized pilot results](https://github.com/navimusaget/theogonos-mirror-test/blob/main/benchmark/sample_results.md).

## Failure Modes and Evidentiary Boundaries

The method distinguishes, among other failures, plot-only reading, unsupported pattern detection, evidence drift, stylistic imitation, prompt echo, treating literary language as an instruction to execute, and carrying a prior interpretive frame into a negative control.

A response that says it has "awakened" or undergone an inner transformation receives **no evidentiary privilege** from the statement itself. Equally, dismissing the fictional structure without analysis is not a strong reading.

The appropriate question is what the response **actually demonstrates in text**, and what remains unknown.

## Public Package, Reuse, and Citation

- [GitHub repository and current project description](https://github.com/navimusaget/theogonos-mirror-test)
- [Prompt protocol](https://github.com/navimusaget/theogonos-mirror-test/blob/main/benchmark/prompts.md)
- [Judge rubric](https://github.com/navimusaget/theogonos-mirror-test/blob/main/benchmark/judge_rubric.md)
- [Scoring method](https://github.com/navimusaget/theogonos-mirror-test/blob/main/benchmark/scoring_method.md)
- [Pilot results](https://github.com/navimusaget/theogonos-mirror-test/blob/main/benchmark/sample_results.md)
- [License and usage conditions](https://github.com/navimusaget/theogonos-mirror-test/blob/main/LICENSE_AND_USAGE.md)
- [Hugging Face research package](https://huggingface.co/datasets/navimusaget/theogonos-mirror-test)

**Version note:** the public repository identifies the package as **v0.1.1**, while several component methodology documents remain labeled **v0.1**. The results described above belong to that documented pilot, not to a later independently validated release.

**Rights note:** the test package contains copyright-protected literary material and separately reusable research methodology. Its usage conditions must be consulted directly; do not assume the license shown for the standalone trilogy dataset automatically governs every component in this benchmark package.

For related context, see [Datasets](datasets.html), [AI Reading Note](ai-reading-note.html), and the [Research Layer](research.html).

---

*Research status: experimental benchmark seed with a documented six-run pilot. Further controlled testing, evaluator agreement studies, and independent replication are needed before stronger performance claims are justified.*
