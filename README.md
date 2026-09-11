# 📦 EviBox Suite
**Bóveda Avanzada de Evidencia Digital e Integridad Forense**

EviBox es una herramienta web diseñada para la captura, preservación, verificación criptográfica y empaquetado de evidencias digitales provenientes de redes sociales y plataformas web con fines forenses o de auditoría.

---

## 📂 Estructura del Repositorio

Este repositorio contiene la evolución de la herramienta dividida en versiones estables:

* **[`EviBox2.0/`](./EviBox2.0)**: Versión base con soporte de archivo, cálculo de hash SHA-256 e integración con almacenamiento local.
* **[`EviBox2.1/`](./EviBox2.1)**: Versión forense avanzada con soporte multiplataforma optimizado (X/Twitter, Instagram, TikTok, YouTube), generación de paquetes `.zip`, fichas judiciales imprimibles y corrección de metadatos de autoría por URL.

---

## 🚀 Características Principales

* 🔒 **Integridad Criptográfica:** Generación y verificación de hashes SHA-256 para garantizar que las evidencias no han sido alteradas.
* 📥 **Empaquetado Forense:** Exportación de metadatos en formato JSON y recursos multimedia estructurados en `.zip`.
* 🖨️ **Fichas Imprimibles:** Vistas adaptadas para reportes físicos o exportación en PDF.
* 📁 **Soporte de Carpeta Local:** Integración directa con el sistema de archivos del navegador mediante File System Access API.

---

## 🛠️ Tecnologías Utilizadas
* HTML5 / CSS3 / JavaScript (Vanilla)
* [Tailwind CSS](https://tailwindcss.com/) (Estilos)
* [JSZip](https://stuk.github.io/jszip/) (Compresión de paquetes de evidencia)
