# Android Security Updates Analysis: Lifecycle, Gaps, and Risks

## Overview

This project investigates the lifecycle, distribution, and risks associated with Android security updates. Android, the leading mobile operating system with over 3 billion global users, faces continuous challenges in ensuring timely and comprehensive security updates for its vast ecosystem of devices. This study provides a detailed, device-centric analysis of Android security updates, uncovering patterns, gaps, and risks to user security.

## Objectives

The study addresses the following key research questions:

1. **Lifecycle Analysis**: What does the maintenance chronicle of Android devices look like throughout their lifecycle?
2. **Factors Impacting Updates**: What factors influence the distribution of security updates during the support period?
3. **Unpatched Risks**: What risks do unpatched Android devices pose, and when do they become insecure?
4. **User Concerns and Best Practices**: What immediate issues concern users, and what best practices can be adopted by OEMs?
5. **OEM Compliance**: To what extent do OEMs follow best practices outlined in Android security guidelines?
6. **Common Vulnerabilities and Weaknesses (CWEs)**: What are the prevalent vulnerabilities and weaknesses observed in Android devices?

## Key Insights

- **Fragmentation Challenges**: OEMs like Samsung, Xiaomi, Oppo, and others face significant challenges in managing security updates across diverse devices, regions, and carriers.
- **Lifecycle Variability**: Devices follow differing support models (e.g., monthly, quarterly, biannual), with varying durations and frequencies based on the OEM, geography, and carrier.
- **Update Delays**: Non-flagship devices and regions with less market focus experience significant delays or missing updates, sometimes extending up to 300 days.
- **Unpatched Risks**: Unsupported devices are highly vulnerable, with critical Common Vulnerabilities and Exposures (CVEs) emerging soon after support ends, posing significant risks to users and developers.

## Dataset

- The dataset includes **567,000 security updates** for **904 devices** released between 2014 and 2024.
- Data is sourced from official OEM announcements and community feedback, providing comprehensive insights into global security update practices.

## Methodology

- Device-centric analysis focused on the lifecycle and support practices of Android devices.
- Inclusion of both flagship and non-flagship models to provide a holistic view of OEM performance.
- Cross-OEM comparison covering major players like Samsung, Google, Xiaomi, Oppo, Huawei, Vivo, Motorola, and LG.

## Findings

- **Support Disparities**: OEMs differ significantly in their security update approaches. Samsung exhibits variability based on geography and model, while Google ensures consistent monthly updates across all devices.
- **Global Inequities**: Users in certain regions and carrier partnerships face delays or lack updates entirely.
- **Post-Support Risks**: Unpatched vulnerabilities grow over time, with 35 critical CVEs identified within two years post-support.

## Contributions

- The largest device-centric study on Android security updates to date.
- Identification of gaps in OEM practices and their impact on user security.
- Recommendations for improving Android’s security update ecosystem globally.

## Publications

This work builds upon previous research:
[50 Shades of Support: A Device-Centric Analysis of Android Security Updates](https://github.com/cslfiu/Android-Security-Updates)

## Installation and Usage

To run the analysis using Jupyter Notebook, follow these steps:

### Step 1: Install Jupyter Notebook
#### On Windows:
1. Install Python: Download and install the latest version of Python from the official [Python website](https://www.python.org/downloads/). During installation, ensure that you check the box to "Add Python to PATH."
2. Install Jupyter Notebook: Open the Command Prompt and run the following command:
   ```bash
   pip install notebook
   ```

#### On macOS:
1. Install Python: If Python is not already installed, download and install the latest version of Python from the official [Python website](https://www.python.org/downloads/). Alternatively, you can use Homebrew to install it:
   ```bash
   brew install python
   ```
2. Install Jupyter Notebook: Open the Terminal and run the following command:
   ```bash
   pip install notebook
   ```

#### On Linux (Ubuntu/Debian):
1. Install Python: If Python is not already installed, run the following command to install it:
   ```bash
   sudo apt update
   sudo apt install python3 python3-pip
   ```
2. Install Jupyter Notebook: After installing Python, run the following command:
   ```bash
   pip3 install notebook
   ```

### Step 2: Clone the Repository
Clone this repository to your local machine using Git:
```bash
git clone https://github.com/hdoo7/mhealth_apps.git
```

### Step 3: Launch Jupyter Notebook
After installing Jupyter Notebook, you can launch it by running the following command in your terminal (or Command Prompt on Windows):
```bash
jupyter notebook
```

This will open Jupyter Notebook in your default web browser.

### Step 4: Run the Analysis
In Jupyter Notebook, navigate to the notebook file (e.g., `01_mhealth_apps.ipynb`) and run the cells to perform the analysis. You can execute a cell by selecting it and pressing `Shift + Enter`.

## Citation

If you use this dataset or analysis in your research, please cite:


## Contact

For questions or collaboration inquiries, please contact:

- **Lead Researcher**: [Haiyun Deng](mailto:hdeng007[at]fiu[dot]edu)  
- **Affiliation**: Cyber-Physical Systems Security Lab, Florida International University, Miami, Florida, USA
