# Mini-SOC-Home-Lab-Blue-Team-Detection-Foundations
This repository documents the design and implementation of a personal Mini Security Operations Center (SOC) built in an isolated virtualized environment.  The goal of this project is to gain hands-on SOC L1/L2 experience by setting up log collection, monitoring, alerting, and basic incident response workflows using realistic attack simulations.
he goal of this project is to gain hands-on SOC L1/L2 experience by setting up log collection, monitoring, alerting, and basic incident response workflows using realistic attack simulations.

Objectives

Build a functional mini SOC using open source tools

Collect and analyze logs from Windows and Linux endpoints

Detect common attack techniques through SIEM alerts

Create basic incident response playbooks

Document the lab in a professional, reproducible way

Lab Overview

The lab is fully isolated using virtual machines and includes:

A SIEM server for log centralization and alerting

A Windows endpoint simulating a user workstation

A Linux endpoint simulating a server

An optional attacker machine used only to generate controlled attack scenarios

No system is exposed to the Internet and all attacks are performed exclusively against owned virtual machines.

Key Topics Covered

Log collection and normalization

Authentication and process monitoring

Detection of suspicious behaviors

Alert triage and analysis

Incident response fundamentals

SOC documentation and reporting

Attack Scenarios Simulated

SSH brute force attempts

Failed authentication patterns on Windows

Execution of suspicious binaries

Privilege escalation related events

Internal network scanning activity

Why This Project

This project is intended as a foundation for Detection Engineering and Blue Team work.
It also serves as a technical portfolio demonstrating practical SOC skills rather than theoretical knowledge.

Future extensions include:

Writing custom detection rules

Mapping detections to MITRE ATT&CK

Using the lab as a base for detection engineering and GRC projects

Disclaimer

This lab is for educational purposes only.
All activities are conducted in a controlled, isolated environment on systems owned by the author.
