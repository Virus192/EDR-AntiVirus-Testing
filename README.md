# EDR and Anti-Virus Security Control Testing

## Project Title: Assessment Design for Security Controls

### Test: Signature-Based Validation Testing with AttackIQ Breach and Attack Simulation Framework

---

## Description

This repository contains documentation for a cybersecurity project aimed at validating the effectiveness of existing security controls at LinQ Technologies. As a Security Validation Analyst, the primary task is to design and execute tests to ensure that the security measures in place are functioning correctly. This involves signature-based validation testing using the AttackIQ Breach and Attack Simulation Framework. The project focuses on using EICAR test files and real-world ransomware samples to simulate potential threats and assess the robustness of the company's defenses.

---

### Table of Contents

1. [Introduction](#introduction)
2. [Test Plan Scenario](#test-plan-scenario)
3. [Test Schedule Planning](#test-schedule-planning)
4. [Anti-Virus Signature-Based Testing](#anti-virus-signature-based-testing)
5. [Requirements](#requirements)
6. [Selected Assets](#selected-assets)
7. [Pre-Assessment Verification](#pre-assessment-verification)
8. [Reporting](#reporting)
9. [Conclusion](#conclusion)

---

## Introduction

In this project, we aim to validate the efficacy of LinQ Technologies' security controls. As a Security Validation Analyst, my role is to design and execute tests to ensure that our security measures are functioning correctly.

## Test Plan Scenario

### Role

I joined LinQ Technologies as a Security Validation Analyst, tasked with testing and validating the company's existing security controls.

### Objective

To test the anti-virus capabilities of our systems using the EICAR test files and simulate real-world ransomware attacks to ensure our defenses are robust.

## Test Schedule Planning

Scheduling the assessments is crucial for accurate results. Considerations include:

- **Asset Availability**: Are the assets remote or local? Are they business-critical?
- **Impact on Users**: Will the scenarios affect local users?
- **Test Frequency**: How often could test results change?
- **Integration with IT/Security Operations**: How does this fit into the overall schedule?

## Anti-Virus Signature-Based Testing

### Test Statement

Does the anti-virus in place stop Malware?

### Hypothesis

The Security Team believes that the security controls are working as expected.

### Assets

- **System 1 (acad6969)**: A Microsoft Windows 10 Pro, protected with CB-EDR by Carbon Black.
- **System 2 (acad2815)**: A Microsoft Windows 10 Pro, unprotected.

### Scenarios

1. Download EICAR files to memory.
2. Download zipped EICAR file to memory.
3. Download txt EICAR file to memory.
4. Download double-zipped EICAR file to memory.

### Schedule

- At least 2 times a week, during non-business days/hours.

### References

The EICAR Anti-Virus Test File is a computer file developed by the European Institute for Computer Antivirus Research (EICAR) and the Computer Antivirus Research Organization (CARO) to test the response of computer antivirus programs.

## Requirements

1. **ATTC&CKIQ Breach and Simulation Platform**
2. **EICAR Anti-Virus Test Files**
   - EICAR File
   - Zipped EICAR File
   - TXT EICAR File
   - Double Zipped EICAR File
3. **Ransomware Test Files**
   - MAZE Ransomware Sample
   - Robinhood Ransomware RBNL Test Script
   - Robinhood Ransomware STEEL Application Stealer Test Script
   - Coverton Ransomware Test Script

## Selected Assets

- **ACAD6969-prot**: Protected with CB EDR by Carbon Black.
- **ACAD2815-un**: Unprotected.

## Pre-Assessment Verification

Verification steps before starting the assessment to ensure everything is configured correctly.

## Reporting

A comprehensive assessment report will be prepared, starting with an executive summary and detailing the results of each scenario, including pass rates, individual scenario analysis, asset evaluation, and mitigation recommendations.

## Conclusion

The project concludes with a detailed report presented to the Board of Executives, highlighting the overall effectiveness of the current security controls and providing actionable recommendations for improvement.

---

For detailed documentation, please refer to the respective files in this repository.

---
