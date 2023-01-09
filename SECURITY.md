![CrowdStrike Falcon](https://raw.githubusercontent.com/CrowdStrike/falconpy/main/docs/asset/cs-logo.png)
![GitHub issues](https://img.shields.io/github/issues-raw/nthnthcandrew/Falcon-Logscale-Community-Content?logo=github)
![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/nthnthcandrew/Falcon-Logscale-Community-Content?color=green&logo=github)

# Security Policy
This document outlines security policy and procedures for the CrowdStrike LogScale Community Content project.

It should be noted that LogScale integrations are largly packages of YAML assets including Parsers, Dashboards, Queries, Scheduled Searches, Alerts and Actions.

These YAML assets should be benign and there is no known method to achieve code execution or damage through package import.

## Supported LogScale versions

Most content should work against all versions.  When some version dependency is discovered it will be identified in the documentation for a specific package/integration.

## Reporting a potential security vulnerability

We have multiple avenues to receive security-related vulnerability reports.

Please report suspected security vulnerabilities by:
+ Submitting a [bug](https://github.com/nthnthcandrew/Falcon-Logscale-Community-Content/issues/new?assignees=&labels=bug+%3Abug%3A&template=bug_report.md&title=%5B+BUG+%5D+...).
<!-- + Starting a new [discussion](https://github.com/CrowdStrike/falconpy/discussions). -->
+ Submitting a [pull request](https://github.com/nthnthcandrew/Falcon-Logscale-Community-Content/pulls) to potentially resolve the issue. (New contributors: please review the content located [here](https://github.com/nthnthcandrew/Falcon-Logscale-Community-Content/blob/main/CONTRIBUTING.md).)
<!--  + Sending an email to __xxxxxxx@crowdstrike.com__.  -->

## Disclosure and mitigation process

Upon receiving a security bug report, the issue will be assigned to one of the project maintainers. This person will coordinate the related fix and release
process, involving the following steps:
+ Communicate with you to confirm we have received the report and provide you with a status update.
    - You should receive this message within 48 - 72 business hours.
+ Confirmation of the issue and a determination of affected versions.
+ An audit of the codebase to find any potentially similar problems.
+ Preparation of patches for all releases still under maintenance.
    - These patches will be submitted as a separate pull request and contain a version update.
    - This pull request will be flagged as a security fix.
    - Once merged, and after post-merge unit testing has been completed, the patch will be immediately published to both PyPI repositories.

<BR/><BR/>

<p align="center"><img src="https://raw.githubusercontent.com/nthnthcandrew/Falcon-Logscale-Community-Content/main/docs/asset/cs-logo-footer.png"><BR/><img width="300px" src="https://raw.githubusercontent.com/nthnthcandrew/Falcon-Logscale-Community-Content/main/docs/asset/adversary-goblin-panda.png"></P>
<h3><P align="center">WE STOP BREACHES</P></h3>
