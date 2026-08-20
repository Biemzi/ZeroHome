# 🚀 ZeroHome — Personal Infrastructure & Homelab

Servidor doméstico centralizado basado en **Debian GNU/Linux (Headless)** para la orquestación de servicios en contenedores mediante **Docker & Docker Compose**.

---

## 🛠️ Especificaciones del Host
* **Nombre del Proyecto:** ZeroHome
* **Host Direct IP:** `192.168.0.171/24`
* **Puerta de Enlace (Gateway):** `192.168.0.1`
* **Sistema Operativo:** Debian GNU/Linux 13 (Trixie) x86_64
* **Kernel:** `6.12.101+deb13-amd64`

---

## 📦 Mapa de Servicios

| Servicio | Puerto Host | Protocolo | Estado | Descripción |
| :--- | :---: | :---: | :---: | :--- |
| **Portainer CE** | `9443` | HTTPS | 🟡 Planeado | Dashboard de gestión visual de contenedores |
| **Nginx Proxy Manager** | `81` / `80` / `443` | HTTP/HTTPS | 🟡 Planeado | Proxy inverso y gestión de certificados SSL |
| **Nextcloud** | `8080` | HTTP | 🟡 Planeado | Almacenamiento en nube privada y archivos |

---

## 📁 Estructura del Repositorio

```text
homelab/
├── README.md               # Documentación general de ZeroHome
├── .gitignore              # Exclusiones de Git para seguridad
├── scripts/                # Scripts de automatización en Bash
└── services/               # Configuración individual por servicio
    ├── portainer/          # Definición de Portainer
    ├── nginx-proxy/        # Definición del Proxy Inverso
    └── nextcloud/          # Definición de Nextcloud





