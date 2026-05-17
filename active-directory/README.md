# Active Directory Home Lab

## Objective

Build a Windows Server domain environment and simulate day-to-day systems administration tasks in a controlled lab environment.

Goals:

- Deploy and configure Active Directory Domain Services
- Configure DNS and DHCP
- Join Windows clients to the domain
- Apply Group Policies
- Troubleshoot common enterprise issues
- Document failures and resolutions

---

## Environment

Host Machine:

- MacBook Pro M4 Pro
- 24GB RAM
- UTM virtualization
- Apple Silicon (ARM)

Virtual Machines:

### Domain Controller

| Item | Value |
|---|---|
| Hostname | DC01 |
| OS | Windows Server 2022 |
| IP Address | 192.168.10.10 |
| Domain | lab.local |
| Roles Installed | AD DS, DNS, DHCP |

### Client Machine

| Item | Value |
|---|---|
| Hostname | WIN11-CLIENT01 |
| OS | Windows 11 |
| Joined to Domain | Yes |

## Documentation

- Setup procedure → `setup-guide.md`
- Troubleshooting → `troubleshooting/`
- Screenshots → `screenshots/`
