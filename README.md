# ⚡ Electrical Power System Studies

This repository brings together two separate electrical power system studies carried out with **ETAP** and **PowerWorld Simulator**. Both projects use network models and simulation to examine system operation, but they focus on different types of networks and engineering questions.

## 📁 Repository structure

```text
electrical-power-system-studies/
├── README.md
├── etap-industrial-installation/
│   ├── load-flow-analysis/
│   ├── reactive-power-compensation/
│   ├── protection-coordination/
│   └── etap-industrial-installation-presentation.pdf
└── powerworld-transmission-network/
    ├── powerworld-transmission-study-report.pdf
    ├── transmission-network-case.pwb
    └── transmission-network-case.pwd
```

## 🏭 Project 1 — Industrial installation study with ETAP

This study models an industrial electrical installation supplied from a 33 kV medium-voltage network. The installation includes transformers feeding 11 kV and 0.4 kV sections, industrial motors, and other workshop loads.

The work is organized into three parts:

- **`load-flow-analysis/`** — ETAP project files for examining power flow and the operating conditions of the installation under different scenarios.
- **`reactive-power-compensation/`** — ETAP project files for evaluating the installation's reactive power and power factor, and studying capacitor compensation.
- **`protection-coordination/`** — ETAP project files for configuring and coordinating protective relays, including fault scenarios.
- **`etap-industrial-installation-presentation.pdf`** — presentation summarizing the industrial network model, analyses, and main results.

The overall study covers network modelling, load-flow analysis, reactive power compensation, protection settings, and fault coordination.

## ⚡ Project 2 — Transmission network study with PowerWorld

This study models a 230 kV transmission network that includes thermal, wind, and photovoltaic generation. It compares three operating cases: the initial network, the network after adding a new township load, and the expanded network with an additional power plant.

- **`transmission-network-case.pwb`** — PowerWorld Binary case containing the electrical network model.
- **`transmission-network-case.pwd`** — PowerWorld Display file containing the one-line diagram associated with the case.
- **`powerworld-transmission-study-report.pdf`** — report describing the scenarios, simulation results, and checks on bus voltages and generator active and reactive power limits.

The two PowerWorld files are kept together because the `.pwb` file stores the case data and the `.pwd` file stores its display diagram. PowerWorld documents these as separate file types. See the [PowerWorld case-format documentation](https://www.powerworld.com/WebHelp/Content/MainDocumentation_HTML/Case_Formats.htm) and its explanation of [PWB and PWD files](https://www.powerworld.com/knowledge-base/what-is-the-difference-between-the-pwb-and-pwd-files-used-by-simulator).

## 🧰 Software

- **ETAP** — industrial installation modelling and analysis.
- **PowerWorld Simulator** — transmission network modelling and scenario analysis.

## 📝 Notes

- The ETAP and PowerWorld studies are independent projects grouped here under the broader topic of electrical power system analysis.
- Keep each simulation's native files together in its corresponding folder. Preserve their original file extensions when renaming or moving them.
- The repository documents academic design and simulation work; results depend on the assumptions and data in each project file and report.
