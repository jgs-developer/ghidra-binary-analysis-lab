# Ghidra Binary Analysis Lab
## Table of Contents

- [Summary](#summary)
- [About Ghidra](#about-ghidra)
- [Project Objectives](#project-objectives)
- [Practical Lab Overview](#practical-lab-overview)
- [Laboratory Environment](#laboratory-environment)
- [Laboratory Workflow](#laboratory-workflow)
- [Conclusion](#conclusion)
## Summary

This repository presents a practical laboratory demonstrating the use of **Ghidra**, an open-source reverse engineering framework used for binary analysis and software inspection.

The goal of this project is to show how compiled programs can be analyzed without access to their original source code. Through this laboratory exercise, a Linux executable is imported and analyzed using Ghidra in order to explore its internal structure, functions and logic.

The repository is organized into several stages that represent the workflow of a basic reverse engineering process.

---

## About Ghidra

Ghidra is a **Software Reverse Engineering (SRE) framework** developed by the National Security Agency (NSA). It provides a suite of tools that allow analysts to inspect compiled software, understand program behavior and identify potential vulnerabilities.

Some of its main capabilities include:

* Binary disassembly
* Integrated decompiler
* Function and symbol analysis
* Control flow visualization
* Support for multiple architectures and executable formats

Due to these capabilities, Ghidra is widely used in areas such as malware analysis, vulnerability research and digital forensics.

---

## Project Objectives

The main objectives of this laboratory are:

* Install and launch the Ghidra reverse engineering framework
* Create a project environment for binary analysis
* Import a compiled executable into Ghidra
* Perform automatic analysis of the binary
* Explore assembly instructions and decompiled pseudocode

These steps demonstrate the basic workflow followed during a reverse engineering analysis.

---

## Practical Lab Overview

The practical laboratory is divided into several stages, each one represented by a section of this repository.

The workflow followed during the analysis is the following:

1. Installation of the Ghidra framework
2. Initial setup and creation of the analysis project
3. Importing the target binary into Ghidra
4. Performing automatic analysis and exploring the results

This structure allows the reader to follow the reverse engineering process step by step.

---

## Laboratory Environment

The laboratory was performed in the following environment:

| Component        | Description                           |
| ---------------- | ------------------------------------- |
| Operating System | Kali Linux                            |
| Tool             | Ghidra                                |
| Analysis Type    | Reverse Engineering / Binary Analysis |
| Target Binary    | `/bin/ls`                             |

The `/bin/ls` executable was selected because it is a standard Linux binary that allows the reverse engineering workflow to be demonstrated clearly.

## Laboratory Workflow

📦 [Installation](./1_installation) → ⚙️ [Setup](./2_setup) → 📥 [Binary Import](./3_binary_import) → 🔬 [Binary Analysis](./4_binary_analysis)

---

## Conclusion

This repository demonstrates the basic use of **Ghidra** for reverse engineering and binary inspection. Through a structured laboratory approach, the project shows how a compiled executable can be imported, analyzed and interpreted using disassembly and decompilation tools. This repository demonstrates the basic workflow of reverse engineering using Ghidra, from installation to automated binary analysis of a Linux ELF executable.
