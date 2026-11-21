# Screenshot guide

Each image below comes directly from **Cyber Home Lab Doc 1.docx**. Screenshots are mapped to the matching README section. No placeholder files are included.

| Original document image | Repository filename | What it shows |
|---|---|---|
| `image82.png` | `screenshots/01-windows-server-ip-configuration.png` | Server IPv4 172.60.1.2 /24 and default gateway 172.60.1.1 |
| `image76.png` | `screenshots/02-ad-ds-domain-controller-wizard.png` | Additional Options screen with NetBIOS domain AOC |
| `image77.png` | `screenshots/03-server-manager-domain-controller.png` | DC01, domain int.aoc.com, and AD DS/DNS roles visible |
| `image78.png` | `screenshots/04-dns-new-zone-wizard.png` | Forward Lookup Zones including int.aoc.com and DNS zone creation wizard |
| `image79.png` | `screenshots/05-dns-name-server-record.png` | DC01.int.aoc.com in reverse zone properties, listing 10.0.2.15 as a record at that stage |
| `image83.png` | `screenshots/06-active-directory-user-creation.png` | John Brown user John.B in IT Users OU |
| `image84.png` | `screenshots/07-ad-user-password-settings.png` | User must change password at next logon selected |
| `image85.png` | `screenshots/08-active-directory-user-verified.png` | John Brown user shown in IT Users OU |
| `image88.png` | `screenshots/09-it-security-group-setup.png` | IT Group, Global scope, Security type in New Group wizard |
| `image86.png` | `screenshots/10-windows-10-domain-sign-in.png` | John.B@int.aoc.com on Windows 10 VM domain login screen |
| `image87.png` | `screenshots/11-domain-password-change-confirmed.png` | Windows states Your password has been changed |
| `image89.png` | `screenshots/12-dc01-network-shares.png` | IT_Files, netlogon and sysvol visible over the network |
| `image80.png` | `screenshots/13-dhcp-server-role-selection.png` | Add Roles and Features wizard, DHCP Server selected for installation |

**Important:** `image83.png` shows a **user-creation wizard**, not group creation. The group wizard is `image88.png`.

All screenshots were taken from the supplied document and are shown without changes.
