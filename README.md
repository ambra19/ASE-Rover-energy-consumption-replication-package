# Assessing and Improving the Energy Efficiency of an Autonomous Rover

## Research project submitted under the requirements for the degree of Bachelor of Science in Computer Science at the Vrije Universiteit Amsterdam. 

### This project contributes to the ASE Labs at Vrije Universiteit Amsterdam by assessing and improving the energy consumption of the ASE/Rover, a battery-powered autonomous vehicle built to perform in racing competitions. 

> Author: Ambra Mihu 

> First supervisor: Ivano Malavolta 

> Second reader: Vincenzo Stoico 

This repository is a companion package for the bachelor thesis project.

This thesis aims to assess and improve the current energy consumption patterns of the ASE rover, under different operational conditions, propose two targeted interventions (CPU governor adjustments and imaging resolution scaling) to improve efficiency, and evaluate their impact through systematic experimentation and analysis.

## Repository structure

    ASE/Rover-energy-consumption-replication-package
     .
     |     
     |--- data/                            Data that was used in this study
     |
     |--- experiment-runner/               Scripts for running the experiments, including all of the energy results
     |
     |--- modified_services/               Two services that handle different parameters compared to the default ones
     |
     |--- summary_and_plots/               Detailed summaries of results and plots used in the paper


## Setup

**Clone this repository:**

```bash
git clone https://github.com/ambra19/ASE-Rover-energy-consumption-replication-package.git
cd ASE-Rover-energy-consumption-replication-package
```

---

**Create a virtual environment:**

```bash
python3 -m venv venv
```

Activate it:

```bash
source venv/bin/activate
```

---

**Install the dependencies:**

```bash
pip install -r requirements.txt
```

---

The Jupyter notebooks should now be able to load and run the cells without issues.
