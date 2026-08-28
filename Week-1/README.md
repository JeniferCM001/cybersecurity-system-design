# WEEK 1 – CYBERSECURITY SYSTEM DESIGN & ARCHITECTURE

## Five Cybersecurity Case Studies

### Objective

The objective of Week 1 is to identify and study five unique cybersecurity-related system design problems. Each case study focuses on a different real-world cybersecurity challenge and explains the problem, proposed solution, working process, main objective, key features, and uniqueness.

---

# CASE STUDY 1: CYBER ATTACK PATH PREDICTION & PREVENTION PLATFORM

## Problem Statement

In a large organization, an attacker who gains access to one device may move through other connected systems and eventually reach critical resources such as databases, servers, and applications. Traditional security tools may detect individual suspicious activities but may not clearly identify the complete path an attacker could follow.

## Proposed Idea

The Cyber Attack Path Prediction & Prevention Platform is designed to identify and analyze possible routes that an attacker could take through an organization's infrastructure. It considers relationships between users, devices, applications, servers, vulnerabilities, and access permissions.

## How It Works

The system collects information about assets, vulnerabilities, permissions, and security events. It creates a representation of the relationships between these resources and identifies possible attack paths. Each path is analyzed and assigned a risk level. High-risk paths are highlighted so that security teams can take preventive actions.

## Main Objective

To predict dangerous attack paths and help organizations prevent attackers from reaching critical systems.

## Key Features

- Attack-path mapping
- Asset relationship analysis
- Vulnerability analysis
- Risk scoring
- Critical asset identification
- Security recommendations
- Continuous monitoring

## Why It Is Unique

Instead of focusing only on detecting an attack, the system focuses on understanding where an attacker could move next and preventing the attack path before serious damage occurs.

## Expected Benefit

The system can help organizations identify weaknesses in their infrastructure and prioritize the most important security controls.

---

# CASE STUDY 2: SELF-HEALING SECURITY INFRASTRUCTURE FOR COMPROMISED SERVICES

## Problem Statement

When a server or application is compromised, organizations normally depend on security teams to investigate and recover the affected service. Manual recovery can take considerable time and may result in service downtime.

## Proposed Idea

The Self-Healing Security Infrastructure is designed to automatically detect compromised services and perform controlled recovery actions. The system can isolate the affected service, deploy or restore a clean version, verify its security status, and return it to normal operation.

## How It Works

The system continuously monitors services and collects security and health information. When suspicious behavior is detected, the system evaluates the risk. If the service is confirmed or strongly suspected to be compromised, it is isolated from normal traffic. A clean service instance can then be deployed and verified before traffic is redirected to it.

## Main Objective

To reduce the impact of cyberattacks by automatically containing compromised services and restoring secure operation with minimum downtime.

## Key Features

- Continuous service monitoring
- Compromise detection
- Automatic isolation
- Clean service replacement
- Configuration restoration
- Health verification
- Traffic redirection
- Recovery logging

## Why It Is Unique

Most security systems primarily detect and report attacks. This system goes one step further by supporting the complete cycle:

**Detect → Analyze → Isolate → Recover → Verify → Restore**

## Expected Benefit

It can reduce recovery time, limit attack propagation, and improve the availability and resilience of cloud-based services.

---

# CASE STUDY 3: DIGITAL FORENSIC TIMELINE RECONSTRUCTION SYSTEM

## Problem Statement

After a cyberattack, investigators may have thousands of logs from different sources. Understanding these separate events and determining the exact sequence of an attack can be difficult.

## Proposed Idea

The Digital Forensic Timeline Reconstruction System collects digital evidence from multiple sources and organizes it into a chronological timeline. This allows investigators to understand how an incident started and how it progressed.

## How It Works

The system collects events from sources such as authentication logs, application logs, endpoint activity, file activity, and network events. It normalizes their timestamps and correlates related events. The system then generates a timeline showing important actions during the incident.

## Main Objective

To help security investigators reconstruct cyber incidents in a clear chronological order.

## Key Features

- Log collection
- Timestamp normalization
- Event correlation
- Attack timeline generation
- Evidence organization
- Incident investigation
- Search and filtering

## Why It Is Unique

Instead of showing thousands of individual logs, the system converts them into an understandable sequence of events that explains how an attack occurred.

## Expected Benefit

It can reduce investigation time and help security teams understand the source, progression, and impact of an incident.

---

# CASE STUDY 4: INSIDER ACTIVITY DETECTION USING ACCESS SEQUENCES

## Problem Statement

An authorized user may have legitimate access to many systems, making insider threats difficult to identify. A single action may appear normal even when a sequence of actions indicates suspicious behavior.

## Proposed Idea

This system analyzes sequences of user activities rather than examining each activity independently. It identifies unusual patterns involving logins, file access, database access, privilege changes, and downloads.

## How It Works

The system collects user activity and creates a sequence of actions for each session. Normal activity patterns are established for different users or roles. When a user's activity sequence significantly differs from expected behavior, the system calculates a higher risk level and generates an alert for investigation.

## Main Objective

To identify suspicious user behavior and detect potential insider threats or compromised accounts.

## Key Features

- User activity monitoring
- Access sequence analysis
- Normal behavior profiling
- Risk scoring
- Suspicious activity detection
- Security alerts
- Investigation support

## Why It Is Unique

Instead of asking only whether an individual action was allowed, the system analyzes whether the complete sequence of actions makes sense for that user.

## Expected Benefit

It can help organizations identify unusual account behavior that may be missed by traditional access-control systems.

---

# CASE STUDY 5: SECURE EMERGENCY COMMUNICATION SYSTEM UNDER CYBERATTACK

## Problem Statement

During a major cyberattack, an organization's normal communication infrastructure may become unavailable or unreliable. Security teams still need a trusted method to communicate and coordinate their response.

## Proposed Idea

The Secure Emergency Communication System provides a protected communication mechanism that can be activated during a cyber incident. It supports authenticated users, secure messages, emergency priorities, and alternative communication channels.

## How It Works

Under normal conditions, the organization uses its standard communication infrastructure. When a serious security incident is detected, the emergency communication system can be activated. Authorized security personnel authenticate themselves and communicate through the protected channel while important messages are prioritized and recorded.

## Main Objective

To maintain secure and reliable communication between authorized personnel during a cyberattack or major network failure.

## Key Features

- Emergency communication mode
- User authentication
- Secure messaging
- Message integrity protection
- Priority alerts
- Alternative communication channel
- Communication logs

## Why It Is Unique

Most cybersecurity systems focus on detecting or preventing attacks. This system focuses on maintaining trusted communication while an attack is already affecting the organization's infrastructure.

## Expected Benefit

It can help security teams coordinate incident response even when normal communication services are disrupted.

---

# SUMMARY OF THE FIVE CASE STUDIES

| No. | Case Study | Main Focus |
|---|---|---|
| 1 | Cyber Attack Path Prediction & Prevention Platform | Predicting and preventing attack paths |
| 2 | Self-Healing Security Infrastructure for Compromised Services | Automated containment and recovery |
| 3 | Digital Forensic Timeline Reconstruction System | Reconstructing cyber incidents |
| 4 | Insider Activity Detection Using Access Sequences | Detecting unusual user behavior |
| 5 | Secure Emergency Communication System Under Cyberattack | Maintaining communication during cyberattacks |

## Conclusion

The five case studies address different cybersecurity challenges, including proactive attack prevention, automated recovery, digital forensics, insider threat detection, and emergency communication.

Among these five case studies, the Cyber Attack Path Prediction & Prevention Platform and the Self-Healing Security Infrastructure for Compromised Services are identified as high-level system design problems suitable for further study and cloud deployment in the upcoming stages.
