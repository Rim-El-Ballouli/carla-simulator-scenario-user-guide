# Carla Simulator Scenario User Guide
**Scenarios** are an essential part of scenario based validation for autonomous vehicles (AV). Scenarios can encapsulate rare situation that may require a long time to happen in a real world testing environment. Therefore, scenarios allow for more rapid and eﬀicient testing by validating the performance of the AV in specific and diﬀicult situations.

**Carla** is a autonomous vehicle simulation platform. Carla support scenario based validation with its scenario runner tool. This repository covers all the information concerning scenario runner from its installation all the way to creating custom scenarios.

# Repository Objectives
This repository is intended to address three main objectives, which are:

- O1. Define the procedure for installing carla scenario runner
- O2. Define the different types of scenarios supported by Carla
- O3. Define the procedure for running a scenario using Carla simulator


# Carla ScenarioRunner
**ScenarioRunner** is a module that allows scenario definition and execution within the CARLA simulator. The scenarios can be defined through a Python interface or using the OpenScenario standard. More over, multiple scenarios can be defined
in a single map using routes. Routes are a complex structure where multiple scenarios can be placed, and will be triggered once the ego is close to them.

ScenarioRunner can also be used to evaluate autonomous driving agents, by adding criteria to check how the agent perform.

ScenarioRunner’s documentation is lacking a lot with respect to clarity and details. Therefore, refer to https://forum.carla.org/c/using-carla/scenario-runner, a forum dedicated for ScenarioRunner. The forum allows users to ask any questions to clarify any misscpnception that may arise during reading this documentatio

# Download
The releases of ScenarioRunner is in the form of packages that is tied to a specific CARLA release.

The process to download a ScenarioRunner release is quite straightforward.
- Download a CARLA release. Follow the process in the CARLA quick start.
- Download the matching ScenarioRunner release. All of the releases are listed here https://github.com/carla-simulator/scenario_runner/releases.
- Extract the content into the Carla directory. Refer to section 1.4 to know more about the content of the extracted folder and its structure.

Both, Carla and Scenario runner have matching versions. If the CARLA release is 0.9.9, use also ScenarioRunner 0.9.9.
To verify that the download and installation is complete follow the section below

# Run a quick Test





