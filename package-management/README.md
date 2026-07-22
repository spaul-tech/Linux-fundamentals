# 📦 Package Management

Package management is the process of **installing, updating, removing, and managing software** on a Linux system. In Debian-based distributions like **Kali Linux** and **Ubuntu**, the `APT` (Advanced Package Tool) package manager is commonly used.

---

## 📌 Common Commands

| Command | Description |
|---------|-------------|
| `sudo apt update` | Update the package list. |
| `sudo apt upgrade` | Upgrade installed packages. |
| `sudo apt install <package>` | Install a package. |
| `sudo apt remove <package>` | Remove a package. |
| `sudo apt purge <package>` | Remove a package along with its configuration files. |
| `sudo apt autoremove` | Remove unused dependencies. |
| `apt list --installed` | List all installed packages. |
| `apt search <package>` | Search for a package. |
| `apt show <package>` | Display information about a package. |

---

## 💡 Example

Update package lists:

```bash
sudo apt update
```

Install Nmap:

```bash
sudo apt install nmap
```

Remove Nmap:

```bash
sudo apt remove nmap
```

Search for Wireshark:

```bash
apt search wireshark
```

