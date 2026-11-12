# Brute-force attack simulation on Windows

[Version française](README.md)

**Period:** 2024 – 2025 · **Tools:** Kali Linux, penetration-testing tools · **Topics:** authentication, password management

> **Scope:** this project was carried out only in an isolated virtual lab, on machines that I own. No real system was targeted. This repository contains no password lists and no credentials.

## Objective

Run a full penetration-testing scenario against a Windows machine in order to analyze its **authentication mechanisms** and identify **weaknesses related to password management**.

## Why this project

Passwords remain one of the most common entry points into an information system. Understanding how a brute-force attack works makes it possible to design effective protections.

## Environment

- Attacker machine: Kali Linux and its security tools
- Target machine: Windows workstation
- Virtualized, isolated network

## Steps

1. Lab setup and verification that it is isolated.
2. Analysis of how Windows authentication works.
3. Execution of the brute-force attack with Kali Linux tools.
4. Analysis of the results and identification of password-related weaknesses.

## Lessons learned

- Password quality and management directly determine how well a system resists this type of attack.
- A penetration test must be prepared and scoped: perimeter, isolated environment, defined objective.
- In-depth hands-on experience with Kali Linux and offensive security tools.

## Recommended countermeasures

- Strong password policy (length, complexity, no common passwords)
- Temporary account lockout after several failed logins
- Multi-factor authentication
- Monitoring and alerts on repeated failed logins
