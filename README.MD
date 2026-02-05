# 🛡️ Reconquista Dev Team | Hub

> **Simplicidad y Control.**
> Hub centralizado de acceso a las herramientas y aplicaciones de Reconquista Dev Team (RDT).

Este proyecto actúa como página de aterrizaje (Landing Page) para centralizar el tráfico hacia los servicios auto-alojados del equipo. Está diseñado para ser ultraligero, estático y de fácil mantenimiento.

## 📱 Aplicaciones Integradas

El Hub da acceso directo a:

| Aplicación | URL | Descripción |
| :--- | :--- | :--- |
| **YouTube DL** | `ytdl.rdtserver.com` | Descarga de video y audio sin trackers ni anuncios. |
| **NoTiktok** | `idonthavetiktok.rdtserver.com` | Visualizador de privacidad para enlaces de TikTok. |
| **Ride To Gondor** | `ridetogondor.rdtserver.com` | Streaming Non-Stop de la trilogía LOTR. |

## 🛠️ Stack Tecnológico

* **Frontend:** HTML5 semántico.
* **Estilos:** Tailwind CSS (vía CDN, sin compilación).
* **Servidor Web:** Nginx.
* **Infraestructura:** VPS Linux.
* **Seguridad:** Cloudflare (SSL Offloading & WAF).

## 📂 Estructura de Archivos

Ruta recomendada en el servidor: `/var/www/rdt-hub/`

```text
/var/www/rdt-hub/
├── index.html        # Código fuente principal
├── logo-full.jpeg    # Logo principal (Cabecera) - Case Sensitive
├── logo-icon.jpeg    # Favicon y Footer - Case Sensitive
└── README.md         # Documentación
