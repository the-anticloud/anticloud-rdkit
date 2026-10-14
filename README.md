# RDKIT

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-medicine_development-lightgrey)

> Anticloud-hardened packaging of the upstream project `RDKIT` in category **MEDICINE DEVELOPMENT**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** MEDICINE DEVELOPMENT · **Upstream:** https://github.com/rdkit/rdkit · **Upstream pin:** `fece8caa860bdf6c9c82bdb9253f22a0cf87150c` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# RDKit
[![Azure build Status](https://dev.azure.com/rdkit-builds/RDKit/_apis/build/status/rdkit.rdkit?branchName=master)](https://dev.azure.com/rdkit-builds/RDKit/_build/latest?definitionId=1&branchName=master)
[![DOI](https://zenodo.org/badge/10009991.svg)](https://zenodo.org/badge/latestdoi/10009991)

## What is it?

The [RDKit](https://www.rdkit.org) is a collection of cheminformatics and machine-learning software written in C++ and Python.

  * [BSD license](https://github.com/rdkit/rdkit/blob/master/license.txt) - a business friendly license for open source
  * Core data structures and algorithms in C++
  * [Python 3.x wrapper](https://www.rdkit.org/docs/GettingStartedInPython.html) generated using Boost.Python
  * Java and C# wrappers generated with SWIG
  * JavaScript (generated with emscripten) and CFFI wrappers around important functionality
  * 2D and 3D molecular operations
  * [Descriptor](https://www.rdkit.org/docs/GettingStartedInPython.html#list-of-available-descriptors) and [Fingerprint](http://www.rdkit.org/docs/GettingStartedInPython.html#list-of-available-fingerprints) generation for machine learning
  * Molecular database [cartridge](https://www.rdkit.org/docs/Cartridge.html) for PostgreSQL supporting substructure and similarity searches as well as many descriptor calculators
  * Cheminformatics nodes for [KNIME](https://www.knime.com/rdkit)
  * [Contrib](https://github.com/rdkit/rdkit/tree/master/Contrib) folder with useful community-contributed software harnessing the power of the RDKit

## Installation and getting started

If you are working in Python and using conda (our recommendation), installation is super easy:

```shell-session
$ conda install -c conda-forge rdkit
```

You can then take a look at our [Getting Started in Python](https://rdkit.org/docs/GettingStartedInPython.html) guide.

More detailed installation instructions are available in [Docs/Book/Install.md](https://github.com/rdkit/rdkit/blob/master/Docs/Book/Install.md).

## Documentation
Available on the [RDKit page](https://www.rdkit.org/docs/index.html)
and in the [Docs](https://github.com/rdkit/rdkit/tree/master/Docs) folder on GitHub

The [RDKit blog](https://greglandrum.github.io/rdkit-blog/) often has useful tips and tricks.

## Support and Community

If you have questions, comments, or suggestions, the best places for those are:

  * [GitHub discussions](https://github.com/rdkit/rdkit/discussions)
  * The [mailing list](https://sourceforge.net/p/rdkit/mailman/)

If you've found a bug or would like to request a feature, please [create an issue](https://github.com/rdkit/rdkit/issues)

We also have a [LinkedIn group](https://www.linkedin.com/groups/RDKit-8192558/about)

We have a yearly user group meeting (the UGM) where members of the community do presentations and lightning talks on things they've done with the RDKit. Materials from past UGMs, which can quite useful, are also online:
  * [2012 UGM, London](http://www.rdkit.org/UGM/2012/)
  * [2013 UGM, Hinxton](https://github.com/rdkit/UGM_2013)
  * [2014 UGM, Darmstadt](https://github.com/rdkit/UGM_2014)
  * [2015 UGM, Zurich](https://github.com/rdkit/UGM_2015)
  * [2016 UGM, Basel](https://github.com/rdkit/UGM_2016)
  * [2017 UGM, Berlin](https://github.com/rdkit/UGM_2017)
  * [2018 UGM, Cambridge](https://github.com/rdkit/UGM_2018)
  * [2019 UGM, Hamburg](https://github.com/rdkit/UGM_2019)
  * [2020 UGM, virtual](https://github.com/rdkit/UGM_2020)
  * [2021 UGM, virtual](https://github.com/rdkit/UGM_2021)
  * [2022 UGM, Berlin](https://github.com/rdkit/UGM_2022)
  * [2023 UGM, Mainz](https://github.com/rdkit/UGM_2023)
  * [2024 UGM, Zurich](https://github.com/rdkit/UGM_2024)

## License

Code released under the [BSD license](https://github.com/rdkit/rdkit/blob/master/license.txt).

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: setup.cfg; scanned in UPSTREAM_CLONE)
- Top-level source layout: `Code/`, `Contrib/`, `Data/`, `External/`, `Projects/`, `Regress/`, `Scripts/`, `Web/`, `build_support/`, `rdkit/`, `rdkit-stubs/`
- Snapshot size: **6450 files**, **755175 lines of code** (measured; see Benchmarks)
- Primary languages: `.cpp` (958), `.sdf` (767), `.mol` (594), `.h` (564), `.py` (527), `.mrv` (413)
- Upstream commit pinned for this packaging: `fece8caa860bdf6c9c82bdb9253f22a0cf87150c`

---

## Installation

[![DOI](https://zenodo.org/badge/10009991.svg)](https://zenodo.org/badge/latestdoi/10009991)

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

If you are working in Python and using conda (our recommendation), installation is super easy:

```shell-session
$ conda install -c conda-forge rdkit
```

You can then take a look at our [Getting Started in Python](https://rdkit.org/docs/GettingStartedInPython.html) guide.

More detailed installation instructions are available in [Docs/Book/Install.md](https://github.com/rdkit/rdkit/blob/master/Docs/Book/Install.md).

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

[![DOI](https://zenodo.org/badge/10009991.svg)](https://zenodo.org/badge/latestdoi/10009991)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | setup.cfg |
| Files in snapshot | 6450 |
| Lines of code | 755175 |
| Dependency references | 43 |
| Dependencies by ecosystem | native: 43 |
| Upstream license | BSD-3-Clause |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| native | Catch2 | - | CMakeLists.txt |
| native | Inchi | - | CMakeLists.txt |
| native | Python | - | CMakeLists.txt |
| native | nanobind | - | CMakeLists.txt |
| native | Python | - | CMakeLists.txt |
| native | Boost | - | CMakeLists.txt |
| native | Boost | - | CMakeLists.txt |
| native | Eigen3 | - | CMakeLists.txt |
| native | Threads | - | CMakeLists.txt |
| native | Boost | - | CMakeLists.txt |
| native | Boost | - | CMakeLists.txt |
| native | Boost | - | CMakeLists.txt |
| native | ZLIB | - | CMakeLists.txt |
| native | PostgreSQL | - | CMakeLists.txt |
| native | TBB | - | CMakeLists.txt |
| ... | (28 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `CMakeLists.txt`
- `setup.cfg`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

See [Getting Started with Contributing to the RDKit](Docs/Book/GettingStartedWithContributing.md).

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: BSD-3-Clause** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
BSD 3-Clause License

Copyright (c) 2006-2015, Rational Discovery LLC, Greg Landrum, and Julie Penzotti and others
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original BSD-3-Clause terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `BSD-3-Clause` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `RDKIT` (category: MEDICINE DEVELOPMENT)
- **Upstream URL:** https://github.com/rdkit/rdkit
- **Pinned commit (SHA):** `fece8caa860bdf6c9c82bdb9253f22a0cf87150c`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`1c5884658d551f20ff225a2eea33970790511fda6bd3a285548fb020cc801cc0`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

