---
title: TopPrivacy
displaytext: Top 10 Privacy Risks
layout: null
tab: true
order: 1
tags: example-tag
---

## Top 10 Privacy Risks
Version 2.0 of the OWASP Top 10 Privacy Risks list from 2021. Further information and related countermeasures will be provided soon.

The type shows if a risk is rather :man_office_worker: organizational, :woman_technologist: technical, or both.

<table style="background-color:#FFFFFF;border-collapse:collapse;border:1px solid #000000;color:#000000;width:100%" cellspacing="3" cellpadding="3" border="1">

<tr>
<td bgcolor="#D8D8D8" width="64"><b>#</b></td>
<td bgcolor="#D8D8D8" width="75"><b>Type</b></td>
<td bgcolor="#D8D8D8" width="146"><b>Title</b></td>
<td bgcolor="#D8D8D8" width="124"><b>Frequency</b></td>
<td bgcolor="#D8D8D8" width="108"><b>Impact</b></td>
<td bgcolor="#D8D8D8"><b>Description</b></td>
</tr>

<tr>
<td>P1</td>
<td align=center>:woman_technologist:</td>
<td>Web Application Vulnerabilities</td>
<td bgcolor="orange">High</td>
<td bgcolor="red">Very high</td>
<td>Vulnerability is a key problem in any system that guards or operates on
sensitive user data. Failure to suitably design and implement an
application, detect a problem or promptly apply a fix (patch) is likely
to result in a privacy breach. This risk also encompasses the OWASP Top
10 List of web application vulnerabilities and the risks resulting from
them.</td>
</tr>

<tr>
<td>P2</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Operator-sided Data Leakage</td>
<td bgcolor="orange">High</td>
<td bgcolor="red">Very high</td>
<td>Failure to prevent the leakage of any information containing or related
to user data, or the data itself, to any unauthorized party resulting in
loss of data confidentiality. Introduced either due to intentional
malicious breach or unintentional mistake e.g. caused by insufficient
access management controls, insecure storage, duplication of data or a
lack of awareness.</td>
</tr>

<tr>
<td>P3</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Insufficient Data Breach Response</td>
<td bgcolor="red">High</td>
<td bgcolor="red">Very high</td>
<td>Not informing the affected persons (data subjects) about a possible
breach or data leak, resulting either from intentional or unintentional
events; failure to remedy the situation by fixing the cause; not
attempting to limit the leaks.</td>
</tr>

<tr>
<td>P4</td>
<td align=center>:man_office_worker:</td>
<td>Consent on Everything</td>
<td bgcolor="red">Very high</td>
<td bgcolor="orange">High</td>
<td>Aggregation or inappropriate use of consent to legitimate processing. Consent is "on everything" and not collected separately for each purpose (e.g. use of website and profiling for advertising).</td>
</tr>

<tr>
<td>P5</td>
<td align=center>:man_office_worker:</td>
<td>Non-transparent Policies, Terms and Conditions</td>
<td bgcolor="red">Very high</td>
<td bgcolor="orange">High</td>
<td>Not providing sufficient information to describing how data is
processed, such as its collection, storage, and processing. Failure to
make this information easily-accessible and understandable for
non-lawyers.</td>
</tr>

<tr>
<td>P6</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Insufficient Deletion of Personal Data</td>
<td bgcolor="red">High</td>
<td bgcolor="orange">High</td>
<td>Failure to effectively and/or timely delete personal data after
termination of the specified purpose or upon request.</td>
</tr>

<tr>
<td>P7</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Insufficient Data Quality</td>
<td bgcolor="orange">Medium</td>
<td bgcolor="red">Very high</td>
<td>The use of outdated, incorrect or bogus user data. Failure to update or
correct the data.</td>
</tr>

<tr>
<td>P8</td>
<td align=center>:woman_technologist:</td>
<td>Missing or insufficient Session Expiration</td>
<td bgcolor="yellow">Medium</td>
<td bgcolor="red">Very high</td>
<td>Failure to effectively enforce session termination. May result in
collection of additional user-data without the user’s consent or
awareness.</td>
</tr>

<tr>
<td>P9</td>
<td align=center>:man_office_worker::woman_technologist:</td>
<td>Inability of users to access and modify data</td>
<td bgcolor="orange">High</td>
<td bgcolor="orange">High</td>
<td>Users do not have the ability to access, change or delete data related to them.</td>
</tr>

<tr>
<td>P10</td>
<td align=center>:man_office_worker:</td>
<td>Collection of data not required for the user-consented purpose</td>
<td bgcolor="red">High</td>
<td bgcolor="orange">High</td>
<td>Collecting descriptive, demographic or any other user-related data that
are not needed for the purposes of the system. Applies also to data for
which the user did not provide consent.</td>
</tr>
</table>
Note: The values between 0 to 3 used for frequency and impact rating were replaced by a textual description: 0-1.5: Low, 1.5-1.9: Medium, 1.9-2.3: High, > 2.3: Very high
