---
title: TopPrivacy
displaytext: Top 10 Privacy Risks
layout: null
tab: true
order: 1
tags: example-tag
---

## Top 10 Privacy Risks
Version 1.0 of the OWASP Top 10 Privacy Risks list from 2014. Further information and related countermeasures are provided in this PDF document.

No. |Title|Frequency|Impact|Description|
----|-----|-----|-----|----------------|
P1 |Web Application Vulnerabilities|<span bgcolor=orange>High</span>|<span color=red>Very High</span>|Vulnerability is a key problem in any system that guards or operates on sensitive user data. Failure to suitably design and implement an application, detect a problem or promptly apply a fix (patch) is likely to result in a privacy breach. This risk also encompasses the OWASP Top 10 List of web application vulnerabilities and the risks resulting from them.
P2 |Operator-sided Data Leakage|High|Very High|Failure to prevent the leakage of any information containing or related to user data, or the data itself, to any unauthorized party resulting in loss of data confidentiality. Introduced either due to intentional malicious breach or unintentional mistake e.g. caused by insufficient access management controls, insecure storage, duplication of data or a lack of awareness.
P3 |Insufficient Data Breach Response|High|Very High|Not informing the affected persons (data subjects) about a possible breach or data leak, resulting either from intentional or unintentional events; failure to remedy the situation by fixing the cause; not attempting to limit the leaks.
P4 |Insufficient Deletion of Personal Data|Very High|High|Failure to effectively and/or timely delete personal data after termination of the specified purpose or upon request.
P5 |Non-transparent Policies, Terms and Conditions|Very High|High|Not providing sufficient information to describing how data is processed, such as its collection, storage, and processing. Failure to make this information easily-accessible and understandable for non-lawyers.
P6 |Collection of data not required for the primary purpose|Very High|High|Collecting descriptive, demographic or any other user-related data that are not needed for the purposes of the system. Applies also to data for which the user did not provide consent.
P7 |Sharing of Data with Third Party|High|High|Providing user data to any third-party, without obtaining the user’s consent. Sharing results either due to transfer or exchanging for a monetary compensation or otherwise due to inappropriate use of third-party resources included in the web site like widgets (e.g. maps, social networks buttons), analytics or web bugs (e.g. beacons).
P8 |Outdated personal data|High|Very High|The use of outdated, incorrect or bogus user data. Failure to update or correct the data.
P9 |Missing or insufficient Session Expiration|Medium|Very High|Failure to effectively enforce session termination. May result in collection of additional user-data without the user’s consent or awareness.
P10|Insecure Data Transfer|Medium|Very High|Failure to provide data transfers over encrypted and secured channels, excluding the possibility of data leakage. Failure of enforcing mechanisms limiting the leak surface, e.g. allowing to infer any user data out of the mechanics of Web application operation.

Note: The values between 0 to 3 used for frequency and impact rating were replaced by a textual description: 0-1: Low, 1-1.5: Medium, 1.5-2: High, > 2: Very high
