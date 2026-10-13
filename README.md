# 🏢 Integración de Chat Empresarial y Almacenamiento Híbrido (Nextcloud & SharePoint)

![OS](https://img.shields.io/badge/OS-Ubuntu%20Server-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Nextcloud-0082C9?style=for-the-badge&logo=nextcloud&logoColor=white)
![Storage](https://img.shields.io/badge/Cloud-SharePoint%20Online-0078D4?style=for-the-badge&logo=microsoftsharepoint&logoColor=white)
![Sync](https://img.shields.io/badge/Tool-Rclone-1E88E5?style=for-the-badge&logo=linux&logoColor=white)
![Security](https://img.shields.io/badge/Security-Advanced%20Audit%20%26%202FA-28A745?style=for-the-badge&logo=security&logoColor=white)

Repositorio oficial que documenta la arquitectura, diseño y despliegue de una solución integral de colaboración y chat empresarial, orientada a optimizar la seguridad, el control de acceso a la información y la trazabilidad de documentos corporativos.

---

## 🏛️ Arquitectura de la Solución

La infraestructura opera sobre un servidor dedicado con **Ubuntu Server**, integrando Nextcloud para mensajería unificada (Talk) y gestión documental, sincronizado de manera segura mediante **Rclone (WebDAV)** con repositorios corporativos en **SharePoint Online**.

## ⚙️ Características Clave y Seguridad

1. **Segmentación por Sedes:** Configuración de montajes WebDAV individuales restringidos por grupos para asegurar que cada área visualice únicamente sus carpetas autorizadas.
2. **Trazabilidad y Auditoría:** Activación de registros avanzados de auditoría (`admin_audit`) para el control de descargas, modificaciones y eliminación de archivos confidenciales.
3. **Conectividad Robusta:** Enlace seguro entre entornos locales y la nube corporativa bajo estrictas políticas de cumplimiento corporativo.
