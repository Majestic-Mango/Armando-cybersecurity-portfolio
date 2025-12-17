## Phase 1 – Host Discovery

An internal network scan identified a Linux host exposing multiple network
services. The system was selected as the primary assessment target based on
scope and accessibility within the internal network segment.

---

## Phase 2 – Service Enumeration

### Overview
Service and version enumeration revealed numerous legacy and insecure services,
including FTP, SMB, RPC, remote shell services, database services, and remote
desktop protocols. Several of these services are known to present high risk
when improperly configured or running outdated versions.

---

### FTP Enumeration (Port 21)

An FTP service was identified as exposed on the target host during service
enumeration. Further analysis was conducted to assess authentication
requirements and access controls.

#### Findings
The FTP service was identified as **vsFTPd version 2.3.4** and permitted
unauthenticated (anonymous) access. Unauthenticated users were able to
successfully log in and enumerate directory listings on the target system.

This configuration increases the risk of information disclosure and may provide
attackers with insight into system structure or sensitive data. Anonymous FTP
access may also be abused as a staging point for further attacks within an
internal network.

