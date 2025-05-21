# Administrare de sistem si retea

## 1. Ubuntu Server

Ubuntu Server a fost utilizat ca sistem de bază pentru instalarea și testarea serviciilor în VirtualBox. După instalare, s-au adăugat serviciile necesare pentru rularea aplicațiilor web și trimiterea de emailuri locale.

Servicii instalate și configurate:

- Docker + NGINX
- Postfix (MAIL – port 25)

---

## 2. Docker

Docker a fost instalat folosind repository-ul oficial, după adăugarea cheii GPG și configurarea sursei software.

```bash
sudo apt install docker-ce docker-ce-cli containerd.io -y
