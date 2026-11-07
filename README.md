# Etienne Laplante

LC-MS specialist with over two decades of hands-on mass spectrometry experience, and a self-taught programmer who builds tools to make lab data easier to trust and use.

This is where I keep personal projects, learning notes and experiments. Everything here uses public or synthetic data.

## Repositories

| Repository | What's inside |
|---|---|
| [data-science](https://github.com/CoreSci/data-science) | Python notebooks and scripts for data analysis: PCA from scratch, machine learning with scikit-learn, signal processing and public market data, plus a bilingual (French/English) learning-with-kids series in Python |
| [lab-informatics](https://github.com/CoreSci/lab-informatics) | Readers, validators and writers for open laboratory data standards (JCAMP-DX and mzML), built on synthetic data, with unit tests running in CI on Python 3.9 to 3.15 |
| [automation-workflow](https://github.com/CoreSci/automation-workflow) | Reproducible workflow patterns: Docker environments, scheduled containerised jobs on Windows, Docker cleanup notes, API clients, PDF automation and a Raspberry Pi setup runbook |
| [arduino-showcase](https://github.com/CoreSci/arduino-showcase) | Embedded prototyping: sensors, a multichannel voltage logger, intermediate-level concept units (state machines, analog input), and a bilingual (French/English) learning-with-kids series in Arduino |
| [network-infrastructure](https://github.com/CoreSci/network-infrastructure) | Practical network troubleshooting and infrastructure notes: a Windows diagnostics toolkit, CLI reference, networking fundamentals and a disk/storage guide |
| [quality-engineering](https://github.com/CoreSci/quality-engineering) | Testing as a discipline: functional, negative, boundary and OpenAPI contract tests for a small local API service, with a test plan and CI |

## How this is built

- **lab-informatics and quality-engineering:** the code, tests and documentation were written by an AI assistant (Claude, through Claude Code) under my direction. I set the scope and requirements and publish everything by hand. These two repositories are also my learning material: open data standards and CI are new to me, and I am learning them by reading, running and extending this work.
- **My earlier material** (notebooks, scripts, prototypes, projects and course work): the code is my own. I used the assistant to organise it, to help debug and optimise it, and to write documentation.
- **Units added since late September 2026:** written with the assistant from my own plans and material.

**Working with AI, and checking it.** I work in separate roles: one chat plans, debugs and writes instructions, the assistant executes, and the output comes back to me for review. What makes this trustworthy is the verification around it: automated tests, CI on several Python versions, a requirements-to-tests traceability matrix for the mzML tools, and test plans that list known gaps. I have read most of what is published and keep reading the rest; the checks exist for what reading alone cannot catch. A few early commits carry the assistant's co-author trailer.

## Toolkit

Python · Pandas · NumPy · SciPy · scikit-learn · TensorFlow · Jupyter · Docker · C/C++ · Arduino

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/etienne-laplante-b147041a)
