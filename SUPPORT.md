Bugema Linux Support

This document explains how users, students, contributors, researchers, and other members of the Bugema Linux community can obtain support.

Bugema Linux is developed by the Bugema Open Source Community (BOSC) at Bugema University, Uganda.

GitHub is the primary platform for technical collaboration, documentation, issue tracking, and project discussions.

Quick Support Guide
Type of request	Where to go
Reproducible bug	GitHub Issues
General question	GitHub Discussions
Feature request	GitHub Issues
Security vulnerability	Follow SECURITY.md
Contribution question	GitHub Discussions
Documentation problem	GitHub Issues

Before opening a new request, search existing Issues and Discussions to avoid duplicates.

Before Requesting Support

Please check the following first:

README.md

Installation documentation

User guide

Administration documentation

Existing GitHub Issues

Existing GitHub Discussions

Known issues for your Bugema Linux release

Your problem may already be documented or reported.

Technical Problems

Use a GitHub Issue when you have identified a reproducible technical problem with Bugema Linux.

Examples include:

Installation failures

Boot failures

Application failures

Networking problems

Package conflicts

Desktop problems

Hardware compatibility issues

Provide enough technical information for another person to reproduce and investigate the problem.

Questions and General Discussion

Use GitHub Discussions for:

General questions

Getting started

Project ideas

Design discussions

Community conversations

Non-urgent technical questions

Questions should be specific and include relevant information about what you have already tried.

Feature Requests

Feature requests should describe the underlying problem or need rather than only requesting a particular implementation.

A useful feature request should explain:

Problem:
Proposed solution:
Expected benefit:
Potential users:
Possible implementation:
Testing requirements:


The project team may modify, postpone, or decline a feature depending on technical requirements, resources, security considerations, and project priorities.

Security Problems

Do not report potentially serious security vulnerabilities through a public GitHub Issue or Discussion.

Follow the private reporting procedure described in SECURITY.md.

Do not publicly disclose:

Exploit details

Credentials

Security-sensitive configuration

Private keys

Access tokens

Other information that could put users or project infrastructure at risk

Reporting a Good Bug

A useful bug report should contain enough information for another contributor to understand and reproduce the problem.

Environment

Include information such as:

Bugema Linux version:
Computer/device:
Processor:
RAM:
Storage:
Graphics:
Virtual machine or physical machine:
Virtualization platform:

Problem

Clearly explain:

What happened?

What did you expect to happen?

What steps caused the problem?

Reproduction

Provide the smallest possible sequence of steps that reproduces the problem.

Example:

1. Boot Bugema Linux Alpha 0.1
2. Open Network Settings
3. Enable Wi-Fi
4. Select the wireless network
5. Enter the password
6. Click Connect
7. Network fails to connect

Evidence

Where appropriate, include:

Error messages

Logs

Screenshots

Terminal output

Relevant configuration information

Remove passwords, tokens, private keys, and other sensitive information before posting logs or configuration files.

Installation Support

When requesting installation assistance, provide:

Bugema Linux version

Installation method

Computer model

CPU architecture

RAM

Storage configuration

BIOS/UEFI information where relevant

Installation-media creation method

Error messages

Relevant screenshots or logs

Virtual Machines

If Bugema Linux is being installed in a virtual machine, also provide:

Virtualization platform

Virtual CPU allocation

RAM allocation

Disk size

Network configuration

Hardware Compatibility

Hardware reports are particularly valuable during Bugema Linux development.

When reporting hardware compatibility, provide:

Manufacturer:
Model:
CPU:
RAM:
GPU:
Network adapter:
Wi-Fi adapter:
Storage:
Other relevant hardware:


Indicate the status of each relevant component:

Works

Partially works

Does not work

Not tested

Where possible, include relevant logs or hardware-detection output.

Student Support

Students participating in the Open Source Systems course are encouraged to use the project's support mechanisms.

Students should first:

Read the relevant documentation.

Search existing Issues.

Search Discussions.

Discuss the problem with their team.

Ask a focused technical question if the problem remains unresolved.

Students should demonstrate their own investigation when requesting help with coursework.

Bugema Linux support is intended to encourage problem solving and open-source collaboration rather than simply providing completed assignment answers.

Contributor Support

Contributors who are unsure how to begin should:

Review README.md.

Read CONTRIBUTING.md.

Review available GitHub Issues.

Look for issues labelled good-first-issue.

Ask questions through an appropriate GitHub Discussion.

New contributors are encouraged to begin with documentation, testing, bug fixes, or clearly defined development tasks before attempting major architectural changes.

Emergency and Critical Problems

If a problem could cause immediate and serious harm to users or project infrastructure, contact an authorized project maintainer through an appropriate private communication channel.

Do not publish sensitive credentials, exploit details, or confidential institutional information in public discussions.

Security vulnerabilities must follow the process described in SECURITY.md.

What Not to Post

Never publicly post:

Passwords

API keys

Access tokens

Private SSH keys

Private certificates

Database credentials

Personal information

Confidential University information

Unpublished research data

Sensitive security information

If sensitive information is accidentally posted, remove it if possible and notify a project maintainer immediately.

Support Does Not Guarantee a Fix

Bugema Linux is an open-source project. Submitting a support request does not guarantee that a problem will immediately be fixed.

Issues may be:

Investigated

Reproduced

Prioritized

Assigned

Deferred

Closed as duplicates

Closed when unsupported

Addressed in a future release

The project team will aim to communicate the status of significant issues clearly.

Supported Releases

As Bugema Linux matures, the project will define its supported release policy.

The support documentation should identify:

Current development release

Current stable release

Previous supported release

End-of-support releases

The exact release-support policy will be established before production releases.

Documentation First

When a recurring support question is identified, the project team should consider adding the solution to the documentation.

This helps future users solve similar problems without creating duplicate support requests.

Useful documentation areas include:

docs/
├── installation/
├── administration/
├── development/
└── user-guide/


Contributors are encouraged to improve documentation whenever they discover unclear, incomplete, or outdated information.

Community Support

Bugema Linux is intended to develop a community of users, students, lecturers, researchers, developers, and open-source contributors.

Community members are encouraged to help one another while following the project's Code of Conduct.

Useful answers and troubleshooting solutions should be documented so that knowledge remains available to future contributors.

Continuous Improvement

The support process will evolve as Bugema Linux grows.

Feedback about documentation, support procedures, and user experience is welcome through the project's GitHub collaboration channels.

Suggestions that improve accessibility, clarity, documentation, or the support experience are encouraged.

Bugema Linux
Bugema Open Source Community (BOSC)
Bugema University, Uganda

Learn. Build. Share. Innovate.
