# CMV ODE System - Vivarium Framework

This repository contains the initial implementation of the **Predator-Prey dynamic system** using the **Vivarium framework**, as a starting point toward the ultimate goal of developing and simulating the **CMV ODE system**. The Predator-Prey system serves as a foundational example to demonstrate how Vivarium can model dynamic biological systems.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Future Work: CMV ODE System](#future-work-cmv-ode-system)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project begins with the **Predator-Prey system**, modeled using the Vivarium framework, to build familiarity with dynamic system modeling. The ultimate goal of this project is to implement a **Cytomegalovirus (CMV) ODE system**, which will simulate viral dynamics and immune interactions at multiple scales. The Predator-Prey model is an essential first step in validating the approach and understanding how Vivarium handles system topologies, time-series data, and modular process definitions.

## Features
- **Dynamic Simulation**: The predator-prey interaction is simulated over a configurable time period, using **Lotka-Volterra equations**.
- **Visualizations**:
  - **Time-series plots** of population dynamics.
  - **Topology visualizations** representing the interaction between system components.
- **Vivarium-based Modeling**: Demonstrates how to structure biological systems in a modular, composable way using the Vivarium framework.

## Installation

### Prerequisites
- Python 3.8 or later
- Jupyter Notebook
- Vivarium Core
- Other dependencies (install via `requirements.txt`)

### Steps

1. Clone this repository:
    ```bash
    git clone https://github.com/your_username/cmv-ode-vivarium.git
    cd cmv-ode-vivarium
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. (Optional) Install Vivarium if you haven't already:
    ```bash
    pip install vivarium-core
    ```
