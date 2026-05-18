# GandCrab & Zeppelin Ransomware Log Datasets

Curated ransomware log datasets used in the **SEC-Gemini** security analysis for DFIR use case.

## Overview

This repository contains two datasets capturing network and system-level indicators associated with **GandCrab** and **Zeppelin** ransomware families. The logs were compiled for threat intelligence research, behavioral analysis, and detection engineering workflows.

## Datasets

- **`gandcrab_events.jsonl`** — Artifacts and behavioral logs tied to GandCrab ransomware activity, including C2 communications, file encryption patterns, and persistence mechanisms.
- **`zappilin2_events.jsonl`** — Indicators and event logs from Zeppelin ransomware incidents, covering payload delivery, lateral movement traces, and ransom note deployment.

> **Note:** Files are stored via **Git LFS** due to their size exceeding GitHub's standard file limits.

## SEC-Gemini Use Case

These datasets were presented as part of a SEC-Gemini evaluation to demonstrate:

## Usage

Clone with LFS enabled to pull the full datasets:

```bash
git clone https://github.com/<your-username>/my-dataset-repo.git
cd my-dataset-repo
git lfs pull
```

## License

For research and educational purposes only.
