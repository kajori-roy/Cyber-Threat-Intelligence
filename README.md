# Mining Hacker Forums for Proactive Threat Intelligence

## Overview
This project aims to develop a pipeline-based approach for identifying key actors using Cyber Threat Intelligence (CTI) gathered from hacker forums. The primary goal is to proactively gather intelligence that can alert organizations to threats they were previously unaware of. By analyzing data from hacker forums, the project provides a systematic method to identify and rank key hackers, offering actionable insights to enhance cybersecurity measures.

## Contents
1. [Introduction](#introduction)
2. [System Architecture](#system-architecture)
3. [Tools](#tools)
4. [Results](#results)
5. [Conclusion and Future Work](#conclusion-and-future-work)

## Introduction
### Project Overview
With the increasing complexity and frequency of cyber threats, traditional security measures are often inadequate. This project addresses the need for proactive CTI by leveraging data from hacker forums to identify key actors and provide early warnings about potential threats.

### Objectives
- **Information Gathering:** Collect and preprocess data from various hacker forums.
- **Content Analysis:** Analyze the data to identify key hackers based on activity and content quality.
- **Ranking:** Rank the top hackers using a weighted metric system.
- **Intelligence Provision:** Provide actionable intelligence about key hackers.

## System Architecture
### Pipeline
The pipeline follows a four-phase model:
1. **Information Gathering:** Collect data from hacker forums, including threads, posts, usernames, profiles, and content.
2. **Content Analysis:** Use content analysis to evaluate user data based on metrics such as activity and content quality.
3. **Ranking:** Rank the top hackers based on the weight of each metric.
4. **OSINT Visualization:** Use IntelOwl and OpenCTI to visualize the data and provide detailed reports on key hackers.

### Content Analysis
Content analysis involves identifying the presence of specific words, themes, or concepts within the collected data. This helps quantify and examine the significance and connections of various terms used by forum participants.

### Ranking
Key hackers are identified using two main factors: content quality and knowledge dissemination abilities. Entropy is used to measure the unpredictability or diversity of the data, with higher entropy indicating more significant influence.

### OSINT Visualization
IntelOwl and OpenCTI are integrated into the pipeline to gather and visualize intelligence on key actors. This helps analysts understand and interpret the raw data, providing meaningful insights.

## Tools
- **Google Collab:** For running Python code and data analysis on larger datasets.
- **IntelOwl:** An OSINT solution to gather threat intelligence data about files, IPs, or domains.
- **OpenCTI:** A platform to store, organize, and visualize cyber threat intelligence information.
- **Jupyter Notebook:** For compiling data projects, creating visualizations, and sharing the entire process with the intended audience.

## Results
### Content Analysis Metrics
- **Hacker Words:** Identifying and counting hacker-related words.
- **Technical Jargons:** Counting technical terms used by hackers.
- **Indicators of Compromise (IOC):** Analyzing shared URLs, IP addresses, domains, and email addresses.

### Ranking
Data standardization and entropy calculations are used to determine the weight of each metric. A comprehensive evaluation is performed to rank the hackers based on their influence and activity.

### OSINT and Visualization
The IntelOwl-OpenCTI connector is used to format and report the data. This integration provides detailed insights into the key actors and their potential threats.

## Conclusion and Future Work
### Conclusion
The project successfully identifies key hackers in underground forums using content analysis and OSINT tools. By visualizing the data and providing detailed reports, it offers valuable insights into potential threats and enhances proactive cybersecurity measures.

### Future Work
Future enhancements could include integrating machine learning and deep learning techniques to analyze interactions between forum members. This could provide better insights into the relationships and hierarchies within hacker communities. Additionally, further development could focus on classifying vulnerabilities and attacks discussed in the forums.

## Bibliography
1. Abbasi, A., et al. (2014). Descriptive analytics: Examining expert hackers in web forums. IEEE Joint Intelligence and Security Informatics Conference.
2. Benjamin, V., & Chen, H. (2012). Securing cyberspace: Identifying key actors in hacker communities. IEEE International Conference on Intelligence and Security Informatics.
3. Deliu, I., et al. (2017). Extracting cyber threat intelligence from hacker forums: SVM vs CNN. IEEE International Conference on Big Data.
4. Huang, C., et al. (2021). Hackerrank: Identifying key hackers in underground forums. International Journal of Distributed Sensor Networks.
5. Samtani, S., et al. (2016). Azsecure hacker assets portal: CTI and malware analysis. IEEE Conference on Intelligence and Security Informatics.
6. Zhang, X., et al. (2015). Classification of hackers by knowledge exchange behaviors. Information Systems Frontiers.

---

For more details, please refer to the full project report.

