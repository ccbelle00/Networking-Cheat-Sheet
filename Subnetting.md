# 🖧 Subnetting Cheat Sheet

- **CIDR Notation** → /8, /16, /24, etc.
- **Subnet Mask Examples:**
  - /24 → 255.255.255.0 → 256 IP addresses (254 usable)
  - /16 → 255.255.0.0 → 65,536 IP addresses
- **Formula** → 2^(32 - prefix) = total IPs

### Quick Reference Table
| CIDR | Subnet Mask     | # of IPs | Usable IPs |
|------|-----------------|----------|------------|
| /30  | 255.255.255.252 | 4        | 2          |
| /29  | 255.255.255.248 | 8        | 6          |
| /28  | 255.255.255.240 | 16       | 14         |
| /24  | 255.255.255.0   | 256      | 254        |
| /16  | 255.255.0.0     | 65,536   | 65,534     |
