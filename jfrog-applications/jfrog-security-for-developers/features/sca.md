# SCA

With JFrog's Software Composition Analysis, get enhanced CVE detection and enhanced CVE data with remediation options early on with the following JFrog capabilities:

[**SCA in the JFrog CLI for Xray**](../../jfrog-cli/cli-for-jfrog-security/):&#x20;

* [Scan your source code](../../jfrog-cli/cli-for-jfrog-security/scan-your-source-code.md) dependencies to find security vulnerabilities and license violations
* [Scan your binaries](../../jfrog-cli/cli-for-jfrog-security/scan-your-binaries.md) with the [on-demand binary scanning](https://jfrog-staging-external.fluidtopics.net/r/help/DevSecOps-Xray/Xray-On-Demand-Binary-Scan) that enables you to point to a binary in your local file system and receive a report that contains a list of vulnerabilities, licenses, and policy violations.
* JFrog CLI is integrated with JFrog Xray and JFrog Artifactory, allowing you to have your [build](../../jfrog-cli/cli-for-jfrog-security/scan-published-builds.md) artifacts and dependencies scanned for vulnerabilities and license violations.

[**SCA in your IDE**](broken-reference):&#x20;

* Find and fix security vulnerabilities in your projects and see valuable information about the status of your code by continuously scanning it locally.
* Scan your project dependencies for security issues. For selected security issues, get leverage-enhanced CVE data that is provided by our JFrog Security Research team.&#x20;
* Supported in [Visual Studio Code](../../ide/jfrog-security-in-your-ide/visual-studio-code/) and [IntelliJ IDEA](../../jfrog-applications/ide/jetbrains-ides/).&#x20;

[**SCA in your Git repositories (Frogbot)**](../../frogbot/)**:**

* Scan pull requests immediately after they are opened but before they are merged.&#x20;
* Get notified if the pull request is about to introduce new vulnerabilities to your code.&#x20;
* Scan the Git repository periodically and create pull requests with fixes for vulnerabilities that are detected.
* Frogbot uses JFrog's vast vulnerabilities database, to which we continuously add new component vulnerability data. Also included is VulnDB, the industry's most comprehensive security database, to further extend the range of vulnerabilities detected and fixed by Frogbot.
