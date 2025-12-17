Phase 1
### Results
A total of three live hosts were identified within the internal network segment.
One Linux system was selected as the primary target for further enumeration based
on scope and assessment objectives.

## Phase 2 – Port Scanning & Service Enumeration

A targeted TCP SYN scan of the top 1000 ports was conducted against the identified
Linux host. The scan did not reveal any listening services on common ports.

All scanned ports were confirmed closed, indicating that the system is not exposing
network services by default. This behavior is consistent with a hardened or
workstation-style Linux host.

