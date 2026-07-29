# Credits & Collaborators

State Viewer was built as a team capstone project for **CS 472 (Software Engineering)**
at the University of Nevada, Las Vegas, in Fall 2021, in collaboration with engineers at
NASA's Jet Propulsion Laboratory.

## Team — "cs472 team 2 / JPL"

- Ed Friesema
- Julien Flores
- Shizhao Wang
- Devon Erb
- Michael Corona
- Leslie Ordonez
- Maurice Martinez

## JPL mentors

- **Garth Watney** — NASA Jet Propulsion Laboratory
- **Leonard Reeder** — NASA Jet Propulsion Laboratory

Both engineers met with the team weekly, across nine separate sessions, to discuss
design and implementation choices and to help the team understand event-driven
programming.

## Faculty

- **Dr. Andreas Stefik** — UNLV, recommended the project and guided the team through
  the team-building and software engineering process.

## Prior work this builds on

The system is built around the **NSM autocoder**, a C++ state machine autocoder
developed by an earlier UNLV student team (Reynolds B. et al.):
<https://github.com/JPL-UNLV-CS-2021/nsm>

The `machine/Device.qm` model and its generated C++ come from
[QM](https://www.state-machine.com/products/qm), the QP framework's UML state machine
modeling tool.

## About this repository

Original team repository:
<https://github.com/UNLV-CS-State-Machine-Viewer/State-Viewer>

This copy preserves the original commit history, so authorship of the original work
remains attributed to its authors in `git log`. Changes made after the original project
(build fixes and documentation) are in separate, later commits.

## Note on scope

The design portfolio in `docs/` describes an intended Python/Flask backend running in
Docker. The implementation that was actually delivered — and what is in this repository —
uses a Node.js backend (Express + `ws`) run directly, without containerization. The
docs are preserved as the historical design record, not as a description of the
shipped code.
