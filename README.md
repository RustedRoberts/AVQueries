# Queries
This repository hosts a collection of queries tailored for security products, including Microsoft Defender ATP and CrowdStrike. These crafted queries enable security professionals and analysts to perform. Explore, customize, and leverage these queries to enhance response actions, and proactive defence against cybersecurity threats.

## Threat Detection:
The repository includes a range of queries that aid in the detection of known threats, suspicious activities, and potential vulnerabilities within an environment. These queries leverage the advanced features to swiftly identify and mitigate security risks.

## Incident Response:
This responsitory contains queries designed to be used during an active incident to provide aid in validating and triaging potential security incidents when an alert is raised. These queries will be basic and offer more flexibility to cover as wide a range of potenital incident as possible.

## Forensic Investigations:
Detailed queries assist in conducting in-depth forensic investigations. These queries enable the retrieval of crucial information related to security events, such as file modifications, process execution, network activity, and more, helping you trace the root cause of incidents.

# CrowdStrike

CrowdStrike queries are crafted using Falcon Query Language (FQL), a syntax designed specifically for the CrowdStrike Falcon platform and based on Splunk's Search Processing Language (SPL). These queries leverage a wide array of parameters, including process details, file behavior, network activities, registry changes, and more, enabling comprehensive visibility into endpoint events. The structure of CrowdStrike queries emphasizes flexibility, allowing for complex logic and detailed investigation criteria.

# Defender ATP

Defender ATP queries are formulated using the Kusto Query Language (KQL), a language optimized for Microsoft Defender Advanced Threat Protection (ATP) ecosystem and is based on Structured query language (SQL). KQL can construct queries that explore various endpoint behaviors, including process executions, network communications, file modifications, and other datasets that is dependant on your current licensing structure.

# Sentinel Queries

Microsoft Sentinel is a cloud-native Security Information and Event Management (SIEM) and Security Orchestration, Automation, and Response (SOAR) solution. Built on Microsoft Azure, Sentinel empowers organizations to collect, correlate, and analyze vast amounts of security data from various sources in real-time. The language for threat detection and response is identical to Defender ATP, and queries are formulated using the Kusto Query Language (KQL). In some cases, there is overlap between Sentinel and Defender logs, where Sentinel will provide an advantage of greater log retention.

All queries provided are created to be versatile where possible, and can be customized to match specific use cases. They serve as a foundational resource that can adapt and extend based on your own requirements.
