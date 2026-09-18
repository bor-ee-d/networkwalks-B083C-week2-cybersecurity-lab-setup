# W2-PM-FINAL — Week 2 Detailed Report

## Networkwalks Cybersecurity Internship — Batch B083C

### Completed Modules

1. **W2-PM3 — Maltego Based Footprinting**
2. **W2-PM5 — Zenmap Based Network Scanning**

This report is limited to the modules selected and completed for Week 2.

---

## 1. Introduction

The Week 2 practical work focused on cybersecurity reconnaissance, OSINT footprinting, and network scanning using tools available in the cybersecurity lab environment.

Maltego was used for graph-based OSINT and email-address footprinting, while Zenmap was used for network discovery and enumeration.

All activity was performed for authorized cybersecurity training.

---

## 2. Objectives

### Maltego
- Start an investigation from an authorized domain.
- Use entities and Transforms to discover related publicly indexed information.
- Perform email-address footprinting.
- Interpret graph-based results.

### Zenmap
- Identify the local lab network.
- Determine the network range.
- Perform network discovery/scanning with Zenmap.
- Review discovered hosts, ports, and services.
- Capture evidence and document observations.

---

## 3. Lab Network Information

The network information recorded during the Zenmap practical was:

| Item | Value |
|---|---|
| Local Wi-Fi IPv4 address | `192.168.1.242` |
| Subnet mask | `255.255.255.0` |
| Local network | `192.168.1.0/24` |
| Default gateway | `192.168.1.1` |

---

# 4. Module 1 — Maltego Based Footprinting

## 4.1 Target

**Authorized target:** `networkwalks.com`

## 4.2 Procedure

1. Opened Maltego and created a new graph.
2. Added `networkwalks.com` as the starting Domain entity.
3. Selected the Email Address entity/transform path.
4. Ran **To Emails @domain [Search Engine]**.
5. Waited for the Transform to complete.
6. Reviewed the returned Email Address entities.

## 4.3 Result

The Email Address Transform completed successfully and returned email-related entities associated with the authorized domain.

The exercise demonstrated how a domain can be used as the starting point for graph-based OSINT and how publicly indexed email information can be connected to that domain.

---

# 5. Module 2 — Zenmap Based Network Scanning

## 5.1 Network Identification

The practical identified:

- IPv4 address: `192.168.1.242`
- Subnet mask: `255.255.255.0`
- Network: `192.168.1.0/24`
- Gateway: `192.168.1.1`

## 5.2 Procedure

1. Identified the local IPv4 configuration.
2. Determined the local network range.
3. Opened Zenmap.
4. Configured the authorized target/network and scan profile.
5. Started the scan.
6. Reviewed discovered hosts and port/service information.
7. Captured the completed scan as evidence.

## 5.3 Result

The Zenmap practical was completed successfully.

The final host, port, and service values should be recorded directly from the completed Zenmap output and screenshots rather than being inferred.

---

# 6. Findings and Observations

### Maltego

The investigation demonstrated domain-to-email footprinting using Maltego. The Email Address Transform returned related email entities, providing a visual representation of information associated with the authorized domain.

### Zenmap

The exercise demonstrated the process of identifying a local network range and performing network enumeration with Zenmap. The detailed host, port, and service observations should be taken from the final scan evidence.

---

# 7. Challenges and Troubleshooting

During the Maltego exercise, the expected email result did not appear using the initial domain-oriented approach. Selecting the **Email Address** path and running **To Emails @domain [Search Engine]** produced the expected email entities.

This demonstrated the importance of selecting an entity and Transform that match the information being investigated.

---

# 8. Security & Ethical Considerations

- Only authorized domains and networks should be investigated or scanned.
- Network scanning can generate traffic and may be logged by security controls.
- OSINT results should be handled responsibly.
- Sensitive information should not be unnecessarily collected or published.
- Findings should be documented from actual evidence rather than assumptions.

---

# 9. Key Learnings

Through these modules, I gained practical experience with:

- OSINT and digital footprinting.
- Maltego entities and Transforms.
- Email-address enumeration from an authorized domain.
- Network addressing and CIDR notation.
- Zenmap/Nmap-based network scanning.
- Host and service enumeration.
- Capturing and organizing cybersecurity evidence.
- Applying authorization and ethical considerations to reconnaissance.

---

# 10. Conclusion

The Week 2 practical work provided hands-on experience with both OSINT footprinting and network scanning. Maltego demonstrated graph-based information discovery, while Zenmap provided practical experience with network enumeration and interpreting scan output.

The individual module READMEs and screenshots provide supporting evidence for the completed work.
