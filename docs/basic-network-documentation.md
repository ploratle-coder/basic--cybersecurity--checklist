# Basic Network Documentation

Use this worksheet to maintain an authorized, high-level inventory of your organization's network. Keep it current, restrict access to people who need it, and store detailed diagrams or sensitive configuration separately in an approved location. Do not record passwords, shared secrets, private keys, or other credentials here.

## Document control

- **Organization / site:**
- **Document owner:**
- **Last reviewed (date):**
- **Next review due:**
- **Approved storage location for detailed diagrams:**
- **Classification / access restrictions:**

## Network overview

- **Purpose and scope:**
- **Sites / offices / cloud environments covered:**
- **Internet service provider(s) and support contact:**
- **High-level topology:** (for example: internet edge → firewall → core network → user and server segments)
- **Diagram reference / version:**
- **Remote access method and owner:**
- **Network monitoring / alerting contact:**

## Network segments

| Segment name | Purpose | Address range (if appropriate) | Key systems / user group | Owner | Notes |
|---|---|---|---|---|---|
|  |  |  |  |  |  |

Only include address ranges when appropriate for the document's audience. Avoid publishing internal addressing or topology publicly.

## Key infrastructure inventory

| Asset / service | Role | Site / environment | Business owner | Technical owner / support | Criticality | Review date |
|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |

Examples: firewall, router, managed switch, wireless controller, DNS, DHCP, identity service, VPN, cloud network, backup service. Keep detailed versions, configurations, and management interfaces in a restricted asset system rather than this overview.

## Trust boundaries and access

- **Network zones and their purpose:**
- **Approved paths between zones (high level):**
- **Guest and personal-device access approach:**
- **Administrative access process (describe; do not include credentials):**
- **Remote access approval and review owner:**
- **Third-party connections and business owner:**

## Resilience and operations

- **Configuration backup location and owner:**
- **Backup / restore test frequency and last test:**
- **Change management reference:**
- **Maintenance windows / escalation route:**
- **Incident-response contact / procedure:**
- **Monitoring coverage and log retention reference:**
- **Known dependencies or single points of failure:**

## Review checklist

- [ ] Asset owners and support contacts are current.
- [ ] Network segments and trust boundaries reflect the approved design.
- [ ] Remote access and third-party connections have owners and review dates.
- [ ] Diagram and configuration backups are stored in approved restricted locations.
- [ ] No credentials, secrets, or unnecessary sensitive details are included.
- [ ] Changes since the last review have been reconciled.
- [ ] Document access and next review date are set.

Update this document through the organization's approved change process. Share it only with authorized personnel.
