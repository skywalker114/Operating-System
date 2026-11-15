# Operating Systems Coursework

A collection of educational projects exploring operating-system concepts, including Unix processes and signals, command-line shells, virtual-memory simulation, and concurrent network programming.

This repository is organized across coursework branches rather than as one consolidated application. The projects are independent exercises, not components of a single system.

## Repository status

The default branch, `main`, contains this README but not the project source files. The implementations and related materials are on the branches listed below. There is no unified build, test, or run command for the repository.

| Branch | Project material |
| --- | --- |
| [`Practial-1`](https://github.com/skywalker114/Operating-System/tree/Practial-1) | C exercises involving Unix signals and a small command-line shell. |
| [`Practial-2`](https://github.com/skywalker114/Operating-System/tree/Practial-2) | Memory-simulation coursework, with C, Java, and Python artifacts, trace files, reports, and archives. |
| [`Practical-3`](https://github.com/skywalker114/Operating-System/tree/Practical-3) | A Python TCP-server exercise involving threaded client handling. |

The spelling `Practial` in the first two branch names is intentional here: it matches the branch names in GitHub.

## Project topics

### Processes, signals, and shells

The Practical 1 materials cover process-related Unix programming, signal handling, and shell behavior. The exercises include a program that responds to signals and a shell exercise involving command execution, `cd`, and background processes.

### Memory simulation

The Practical 2 materials explore virtual-memory concepts using memory-access traces and page-replacement strategies. The repository contains implementations or coursework artifacts in multiple languages. Their completeness and exact build requirements may differ; consult the files and assignment materials on that branch.

### Threaded network server

The Practical 3 materials include a Python server exercise focused on TCP connections and threading. The assignment brief describes a broader pattern-analysis task; the code on the branch should be assessed against that specification before treating the full task as implemented.

## Languages and dependencies

The repository includes **C**, **Java**, and **Python** coursework. The visible implementations primarily use language and operating-system APIs; no shared application framework or third-party dependency setup is documented.

## Getting started

Choose the branch for the exercise you want to inspect and review its files before building or running anything. The repository does not currently document a common installation process, verified commands, or a unified test suite.

## Project status and limitations

These are separate educational exercises, not a maintained operating-systems product. Build instructions, automated tests, and implementation status are not consistently documented across the branches. Some materials are reports, trace data, or archives rather than source code.

## Portfolio development

To make the work easier to evaluate:

- Add a verified, branch-specific build and run guide for each project.
- Document each exercise’s goals, design decisions, limitations, and validation results.
- Add focused tests and reproducible sample inputs and outputs.
- Make the status of each implementation clear, especially where it differs from its assignment specification.
- Review coursework rules and permissions before presenting or redistributing submitted work.
