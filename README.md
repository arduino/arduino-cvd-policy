# Coordinated Vulnerability Disclosure (CVD) Policy

At Arduino, we consider the security of our systems and products a top priority. No technology is perfect, and Arduino believes that working with skilled security researchers across the globe is crucial in identifying weaknesses in any technology. We want security researchers to feel comfortable reporting vulnerabilities they've discovered, as set out in this policy, so that we can fix them and keep our information safe.

If you believe you've found a security issue in our products or services, we encourage you to notify us. We welcome working with you to resolve the issue promptly.

This policy describes **how to send us** vulnerability reports and **how long** we ask security researchers to wait before publicly disclosing vulnerabilities.

## Guidelines
We ask that you:

 - Make every effort to avoid privacy violations, degradation of user experience, disruption to production systems, and destruction or manipulation of data.
 - Only use exploits to the extent necessary to confirm a vulnerability, don’t exploit a vulnerability for gain. Do not use an exploit to compromise or exfiltrate data, establish command line access and/or persistence, or use the exploit to "pivot" to other systems. Once you've established that a vulnerability exists, or encountered any of the sensitive data outlined below, please stop your test and notify us immediately.
 - Please keep confidential any information about discovered vulnerabilities for  **up to 90 calendar days**  after you have notified Arduino, unless mutually agreed otherwise. For details, please review our [**Coordinated Disclosure**](#coordinated-disclosure) section below.
 - Please do not modify, store or access data that does not belong to you. Instead, use your own accounts for security research purposes.
 - If you inadvertently access, modify, delete, or store user data, we ask that you notify Arduino immediately at [**security@arduino.cc**](mailto:security@arduino.cc) and delete any stored data after notifying us.

When in doubt about if your potential conduct complies with this policy, please contact us first, before taking action, at [**security@arduino.cc**](mailto:security@arduino.cc) and we will address your questions.

## Reporting a vulnerability

We accept and discuss vulnerability reports via email at [**security@arduino.cc**](mailto:security@arduino.cc). Please encrypt your findings using  **our PGP key**  to prevent this critical information from falling into the wrong hands.

Reports should include:

 - Description of the location and potential impact of the vulnerability.
 - A detailed description of the steps required to reproduce the vulnerability. Proof of concept (POC) scripts, screenshots, and screen captures are all helpful. Please use extreme care to properly label and protect any exploit code.
 - Any technical information and related materials we would need to reproduce the issue.

Please keep your vulnerability reports current by sending us any new information as it becomes available.

## Exclusions

While researching, we'd like to ask you to refrain from:

 - Denial of service
 - Spamming
 - Social engineering (including phishing) of Arduino staff or contractors
 - Any physical attempts against Arduino property or data centers
 - Any interaction or unauthorized access to data

## Third-party bugs

If issues reported to our program affect a third-party library, external project, or another vendor, we reserve the right to forward details of the issue to that party without further discussion with the researcher. We will do our best to coordinate and communicate with researchers through this process, and we will not share your name with third parties without your approval.

## Safe Harbor

To encourage responsible reporting, we will not take legal action against you nor ask law enforcement to investigate you provided you comply with the guidelines of this policy. We understand that many our systems and services are interconnected with third-party systems and services. Please understand that we can only provide this legal commitment with respect to the components we own and control the rights on. If legal action is initiated by a third party against you in connection with activities conducted under this policy, we will take steps to make it known that your actions were conducted in compliance with this policy.

## Coordinated Disclosure

Arduino is committed to patching vulnerabilities  **within 90 days or less**, and disclosing the details of those vulnerabilities when patches are published. We believe that public disclosure of vulnerabilities is an essential part of the vulnerability disclosure process, and that one of the best ways to make software better is to enable everyone to learn from each other's mistakes. At the same time, we believe that disclosure in absence of a readily available patch tends to increase risk rather than reduce it, and so we ask that you refrain from sharing your report with others while we work on our patch. If you believe there are others that should be informed of your report before the patch is available, please let us know so we can make arrangements. We may want to coordinate an advisory with you to be published simultaneously with the patch, but you are also welcome to self-disclose if you prefer after 90 days. By default, we prefer to disclose everything, but we will never publish information about you or our communications with you without your permission, except when required by law, and to a third-party affected by the vulnerability as discussed above. In some cases, we may also have some sensitive information that should be redacted, and so please check with us before self-disclosing after the 90 days period.

Thank you for helping keep Arduino and our users safe!
