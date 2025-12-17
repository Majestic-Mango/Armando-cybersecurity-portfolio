## Phase 1 – Host Discovery & Enumeration

An internal network scan identified a Linux host exposing multiple network
services. A targeted service and version enumeration scan was conducted to
identify potential attack surface.

### Key Findings
The target system exposes numerous legacy and insecure services, including FTP,
SMB, RPC, remote shell services, database services, and remote desktop protocols.
Several of these services are known to be high-risk when improperly configured
or running outdated versions.

## Phase 2 – FTP Enumeration (Port 21)

An FTP service was identified as exposed on the target host during service
enumeration. Further analysis was conducted to assess authentication
requirements and potential misconfigurations.

### Findings
The FTP service permitted unauthenticated (anonymous) access, allowing users to
connect without valid credentials. This configuration increases the risk of
unauthorized file access, information disclosure, and potential abuse of the
service for lateral movement or payload staging within an internal network.
