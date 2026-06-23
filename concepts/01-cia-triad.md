# CIA Triad

The CIA Triad describes the three main things organisations try to protect when securing data and systems.This is the foundations for information security.

## Confidentiality

*Only authorised people should be able to access information.*

The goal of confidentiality is to prevent sensitive information from being viewed by people who do not have permission to see it.

* Main tool: Encryption
* My example: When I log in to online banking, my account details and transactions are protected so that only I can view them.
* When it breaks: A company database containing customer information is exposed to the internet and accessed by attackers.

## Integrity

*Data should remain accurate and should not be changed without authorisation.*

Integrity helps ensure that information can be trusted and that any unauthorised changes can be detected.

* Main tool: Hashing and checksums
* My example: A bank must ensure that account balances are accurate and cannot be secretly modified.
* When it breaks: An attacker changes payroll records and increases an employee's salary without permission.

## Availability

*Systems and data should be accessible when they are needed.*

Availability ensures that authorised users can access information and services without unnecessary disruption.

* Main tool: Backups and redundancy
* My example: A hospital system must remain available so doctors can access patient records during emergencies.
* When it breaks: A ransomware attack encrypts files and employees can no longer access important documents.

## Why it matters to a SOC Analyst

Every security incident affects one or more parts of the CIA Triad.

When investigating an alert we can use the CIA Triad to understand the impact:

* Confidentiality: Was sensitive data exposed?
* Integrity: Was data modified?
* Availability: Were systems or services disrupted?

Identifying the affected pillar helps determine the severity of the incident and the appropriate response.
