# 🔧 Custom sysctl.conf for High Performance LNMP Server

This configuration is optimized for:
- High concurrency Nginx web servers
- MySQL/MariaDB databases
- Low-latency TCP performance
- Secure and stable network handling

## 📂 File Location

Copy the config file to:

```bash
/etc/sysctl.d/99-custom.conf
````
Apply config
```bash
sudo sysctl --system
```
