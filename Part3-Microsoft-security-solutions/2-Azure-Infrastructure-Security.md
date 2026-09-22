# Azure Infrastructure Security

## Azure DDoS Protection

Protects Azure resources against distributed denial-of-service attacks at network layers 3 and 4.

Tiers:

- DDoS Network Protection
- DDoS IP Protection

---

## Azure Firewall

A managed, cloud-based, stateful firewall that filters network traffic.

Available SKUs:

- Basic
- Standard
- Premium

Azure Firewall Manager provides centralized management.

---

## Web Application Firewall (WAF)

Protects web applications against common attacks such as:

- SQL injection
- Cross-site scripting (XSS)

WAF works with services such as Azure Application Gateway and Azure Front Door.

---

## Azure Virtual Networks

Azure Virtual Networks provide private networking and segmentation through:

- Subnets
- VNet peering
- Network Security Groups
- Azure Firewall

Segmentation supports defense-in-depth and Zero Trust.

---

## Network Security Groups

NSGs filter inbound and outbound traffic using rules based on:

- IP address
- Port
- Protocol

Application Security Groups organize virtual machines by application role.

---

## Azure Bastion

Provides secure RDP and SSH access to Azure virtual machines through the Azure portal.

Benefits:

- No public IP address required
- No exposed RDP or SSH ports
- Connections are protected using TLS

---

## Azure Key Vault

Securely stores and manages:

- Secrets
- Encryption keys
- Certificates

Access is controlled through Microsoft Entra ID and Azure RBAC.

---

## Key Takeaways

- DDoS Protection defends against network-layer attacks.
- Azure Firewall filters and controls network traffic.
- WAF protects web applications from common exploits.
- VNets and subnets provide network segmentation.
- NSGs filter inbound and outbound traffic.
- Azure Bastion provides secure remote access to virtual machines.
- Key Vault protects secrets, keys and certificates.
- Together, these services provide defense-in-depth.
