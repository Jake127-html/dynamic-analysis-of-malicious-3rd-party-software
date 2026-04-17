# Dynamic Analysis of Malicious 3rd Party Software

> [!WARNING]
> Do not recreate at home. Some PUPs (Potentially Unwanted Programs) can escape VMs and infect the Host Device. While rare, this is a real possibility.

## Abstract
The purpose of this lab is to further the Cybersecurity field by providing Threat Intelligence on various 3rd party software. The range of software 
### Lab Environment and Components
<details>
<summary> Click to see Lab Environment and Components </summary>
    
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
</details>  


### Software/ Tools & Monitoring
* Performance Monitoring: Task Manager & Resource Monitor
* Domain Index: [ICANN](https://lookup.icann.org/en/lookup), [GoDaddy WHOIS](https://www.godaddy.com/whois)

## Methods for Simulated "Infection"
### Goal: Simulate a non-technical, negligent user searching the web for various "free" software.
* Used Chrome Browser, Google Search Engine with various keywords to quickly locate PUP sites.
  Keywords include:
  ~~~
  * free minecraft torrent download
  * free games download
  * chrome toolbar download
  * free cursors download
  * free virtual desktop pet download
  * free antivirus no malware
  * gta v apk download
  * free ram download
  ~~~
  Additionally, each time a new "Download" button appeared on screen, or a software was reccomended it was to be clicked to simulate
  bundled PUPs installed by third-party software.

   <details>
        <summary>Click to see detailed Video Game Software Entries</summary>
        
          Videogame Related Software:
  
          [A] Website: torrent4you.org/en/minecraft-1-16-2/
  
          Software: Minecraft 1.11, World of Tanks, World of Warships, War Thunder

          Description: [A] Advertises free torrent downloads mostly for popular Indie Game titles some larger games are included
          such as Dying Light 2: Stay Human and Far Cry 6.
          Minecraft 1.16.2 Torrent was downloaded and uTorrent was used for seeding. Sofrware did not install as advertised.
          Instead, Minecraft Version 1.11 (Released four years earlier) was installed.
          Additionally, a strange version, small-window version of the 2016 client opened and it was entirely in Russian.
          A UUID and Token string was automatically filled in, presumable a "legitimate" game token. World of Tanks, World of Warships, and War Thunder
          were offered and installed during installation. However, for one reason or another they did not function properly.

          Malware Detection: While untrustrable in a legitimate scenario, Avast and TotalAV Antiviruses immediately detected both the
          installer file and resulting application as Malware and quarantined it multiple times. Exception had to be made to continue.
  
          ICANN Lookup Result: Almost every field was littered with Redacted Values.
          Host Location: Tambov Oblast, Russia
          ISP: Key-Systems GmbH (Sankt Ingbert, Germany) +49 6894 9396850
          
  <img width="482" height="286" alt="53" src="https://github.com/user-attachments/assets/9092827d-fa12-4dd4-b54d-8c0b4d94eba6" />
  
        [B] Website: iwin.com/categories/games/free
  
          Software: Play iWin Games

          Description: 

          ICANN Lookup Result:

          Host Location: 
          ISP: 
          








</details>
