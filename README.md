# SONYC Home Project Summary
The SONYC Home project aims to address the issue of urban noise pollution, which poses a threat to the quality of life and public health of urban inhabitants. The World Health Organization (WHO) has documented various adverse health effects caused by noise pollution, including hearing impairment, interference with speech communication, disturbance of rest and sleep, mental health and performance effects, residential behavior and annoyance, and interference with intended activities.

In New York City (NYC), noise is monitored through the 311 civil complaint service, which has received close to 5 million noise-related complaints to date, outnumbering any other complaint type. However, this service has limitations in terms of validating and resolving complaints in a timely manner due to resource constraints and the transient nature of noise sources.

To address these challenges, the SONYC Home project has developed a solution that involves deploying a fleet of noise sensors on the exteriors of NYC residents' windows. These sensors provide accurate decibel measurements, utilize machine learning algorithms for sound source identification, and enhance noise reporting to city agencies responsible for enforcing noise regulations. Residents can interact with the sensor data through an app, which includes visualizations of decibel data over time and allows for human-in-the-loop machine learning.

The deployment of sensor networks in urban settings presents technical and logistical challenges. The SONYC Home sensors rely on existing power outlets and utilize LTE cellular connectivity to overcome limitations in power and networking infrastructure. Mounting the sensors on residential windows allows for proximity to complainants and easy access to power outlets.

The ideal domestic noise monitoring sensor for the SONYC Home project should have features such as simple deployment, unintrusiveness, low maintenance, weather resistance, data privacy, accessible data insights/visualization, and user interactivity.

The SONYC Home sensor network consists of remote acoustic sensors deployed outside the apartments of participants with noise issues. These sensors transmit data to central servers, where it is securely stored and made available to users and relevant city agencies through web browsers. The sensor design prioritizes usability and utility, with a single board computer, cellular connectivity, custom calibrated acoustic front-end, and a custom housing with a heat sink to address overheating issues.

The mounting of the sensors is designed to be user-friendly, allowing users to easily mount the devices on their windows with adhesive strips. The sensors undergo physical stress testing to ensure they can withstand environmental conditions and remain securely mounted. The sensors are equipped with a custom microphone board, featuring a high-performance digital MEMS microphone that captures the full frequency range of urban sound. The microphone is calibrated for accuracy, and measures are taken to protect it from water damage.

The software running on the SONYC Home sensors extracts relevant information from the environment, including overall sound level and machine learning classifications. The collected audio samples are used for identification purposes and can contribute to the development of advanced machine learning algorithms. Privacy is maintained by sparse sampling of audio and ensuring conversations cannot be reconstructed.

Overall, the SONYC Home project provides a comprehensive solution for monitoring and mitigating urban noise issues, combining advanced sensor technology, machine learning, and user engagement to improve the quality of life for urban inhabitants.

This repository is a centralized hub for all resources related to the project. It consists of three main directories, each dedicated to a specific component of the system:

### [Hardware](<./Hardware>)
The **Hardware** directory stores hardware design files, including schematics, PCB layouts, and relevant documentation.

### [Node software](<./Node software>)
The **Node software** directory contains firmware, drivers, and software modules for the noise sensor nodes. These components capture noise data, implement machine listening algorithms and transmit it to the central server.

### [Server software](<./Server software>)
The **Server software** directory houses the software components running on the project server. It includes backend infrastructure, data processing algorithms, database management systems, and web interfaces for data visualization and analysis.

**This is all a work in progress so will be updated as this content is compiled**


------------------------------------------------------------------------------------------------------------------------
Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg