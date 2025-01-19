# TESS
Threat Extraction and Summarization System - AI-Powered Threat Intelligence Summarizer

## Objective

To create an AI-powered system that extracts, correlates, and summarizes actionable cybersecurity insights, including IoCs, CVE identifiers, attack vectors, TTPs, and other contextual data, enabling organizations to transition from reactive to proactive security measures.


### Features

**1. IoC Extraction**

* Automatically extract Indicators of Compromise (IoCs):
    * IP addresses, domains, URLs.
    * File hashes (e.g., MD5, SHA256).
* Validate IoCs with enrichment sources such as VirusTotal, GreyNoise, and AbuseIPDB.

**2. CVE Identification and Enrichment**

* E*xtract CVE IDs from unstructured text in articles and reports.
* Enrich CVE data using the National Vulnerability Database (NVD) or CVE Details API:
    * Include exploitability scores, affected software, and patch availability.
* Highlight trending CVEs and emerging exploits.

**3. Attack Vector Analysis**

* Identify attack vectors from unstructured data (e.g., phishing, misconfigurations, zero-day exploits).
* Provide insights into how attacks propagate across systems or networks.

**4. TTPs Mapping**

* Map threats to the MITRE ATT&CK framework:
    * Tactics (e.g., Initial Access, Execution).
    * Techniques (e.g., Phishing, Command and Control).
* Correlate TTPs with known threat actors or campaigns.

**5. Threat Actor Intelligence**

* Enrich insights with threat actor profiles:
    * Historical campaigns.
    * Preferred attack methods and tools.
    *   Industries and regions targeted.

**6. Risk Scoring and Prioritization**

* Assign risk scores by combining:
    * IoCs, CVEs, and TTPs.
    * Contextual factors like exploitability, frequency, and severity.
* Provide dynamic prioritization for actionable responses.
