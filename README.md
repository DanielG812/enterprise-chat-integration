# 🏢 Integración de Chat Empresarial y Almacenamiento Híbrido (Nextcloud & SharePoint)

## 📖 Descripción del Proyecto
Diseño e implementación de una solución integral de colaboración y chat empresarial para optimizar la seguridad, el control de acceso a la información y la trazabilidad de documentos corporativos.

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Nextcloud:** Plataforma central de colaboración y gestión documental.
* **Sharepoint Online:** Repositorio central corporativo sincronizado.
* **Rclone (WebDAV):** Montaje seguro y segmentado de directorios remotos.
* **Ubuntu Server / Linux:** Entorno de despliegue y servidores.
* **Políticas de Seguridad:** Auditoría avanzada y control de acceso por grupos.

## ⚙️ Arquitectura y Características Clave
1. **Segmentación por Sedes:** Configuración de montajes WebDAV individuales restringidos por grupo (Gerencia, Bogotá, Cali, etc.) asegurando que cada empleado visualice únicamente las carpetas autorizadas.
2. **Trazabilidad y Auditoría:** Activación de registros detallados de descargas, modificaciones y eliminación de archivos confidenciales.
3. **Conectividad Segura:** Enlace robusto entre servidores locales y la nube corporativa de Microsoft 365.
