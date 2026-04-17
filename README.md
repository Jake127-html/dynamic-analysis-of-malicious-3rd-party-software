# Windows 10 Performance Remediation Lab w/ ServiceNow

> [!WARNING]
> Do not recreate at home. Some PUPs (Potentially Unwanted Programs) can escape VMs and infect the Host Device. While rare, this is a real possibility.

## About the Lab
The purpose of this lab is to showcase the workflow of a ServiceNow ticket involving a machine "infected" with 

### Lab Environment and Components
* Hypervisor: VirtualBox Version 7.2.6 r172322
* OS: Windows 10 Home 22H2, Build: 19045.3803
* Network Adapter Configuration:
    ~~~
    Attatched to: Host-only Adapter
    Name: VirtualBox Host-Only Ethernet Adapter
    Adapter Type: Intel PRO/1000 MT Desktop (82540EM)
    Promiscuous Mode: Deny
    Mac Address: - 0 o 0 o 0 o 0 -
    Virtual Cable Connected [X}
    ~~~
* Hardware Resources:
    ~~~
    Base Memory: 7.792 Gb
    Number of CPUs: 8
    Processing Cap: 100%
    Paravirtualization Interface: Hyper-V
    Hardware Virtualization: [X] Nested Paging
    Video Memory: 128 Mb
    ~~~
## Software/ Tools & Monitoring
* Ticketing System: ServiceNow (Personal Developer Instance)
* Performance Monitoring: Task Manager & Resource Monitor

## Methods for Simulated "Infection"
### Goal: Simulate a non-technical, negligent user searching the web for various "free" software.
* Used Chrome Browser, Google Search Engine with various keywords to quickly locate PUP sites

  Keywords include:
  ~~~
  dddddd
  ~~~
