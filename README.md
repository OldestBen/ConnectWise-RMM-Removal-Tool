## ConnectWise RMM Removal Tool


## Overview

This repository contains a PowerShell script designed to remove the ConnectWise RMM (Remote Monitoring and Management) agent from Windows machines. This tool helps in completely uninstalling the ConnectWise RMM agent, including cleaning up residual files and registry entries.
Script

RMMRemoval.ps1: This script automates the process of uninstalling the ConnectWise RMM agent.

## Prerequisites

PowerShell with administrative privileges.
Appropriate permissions to uninstall software and delete registry entries on the target machine.
Ensure all critical data is backed up before running the script.

## Installation

Clone the repository to your local machine:
```
git clone https://github.com/OldestBen/ConnectWise-RMM-Removal-Tool.git
```
Navigate to the repository directory:
```
cd ConnectWise-RMM-Removal-Tool
```

## Usage

Open PowerShell with administrative privileges.

Run the removal script:
```
.\RMMRemoval.ps1
```

## License

This project is licensed under the AGPL-3.0 License - see the LICENSE.md file for details.
