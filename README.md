# FarmaNorte — Despliegue en Hostinger

Repositorio público optimizado para despliegue continuo en **Hostinger Web Hosting** mediante la herramienta de integración Git de hPanel.

---

## 📌 Configuración en Hostinger (hPanel)

1. En el panel de control de tu cuenta de Hostinger (**hPanel**), dirígete a:
   **Avanzado** ➔ **Git**.
2. Configura los siguientes campos:
   * **URL del repositorio:** `https://github.com/tinychef/farmanorte-hostinger-deploy.git`
   * **Rama:** `main`
   * **Ruta de instalación:** `/public_html`
3. Haz clic en **Crear / Desplegar**.
4. *(Opcional)* Activa la opción **Despliegue automático (Auto-Deployment)** copiando la URL del Webhook en los Webhooks de este repositorio en GitHub para que cada cambio subido a `main` se actualice en Hostinger al instante.

---

## 🏢 Sedes y Horarios Oficiales

* **Sede 1: Manuel Montt 712**, Providencia (a pasos de Metro Manuel Montt).
  * Teléfono / WhatsApp: **+56 9 2032 2285**
  * Horario: Lunes a Viernes de 08:00 a 21:30 hrs | Sábados de 10:00 a 20:00 hrs | Domingos cerrado.
* **Sede 2: Condell 480**, Providencia (Sector Barrio Italia / Salvador).
  * Teléfono / WhatsApp: **+56 9 7949 3250**
  * Horario: Lunes a Viernes de 08:00 a 21:30 hrs | Sábados de 10:00 a 20:00 hrs | Domingos cerrado.

---

## 📁 Estructura del Repositorio

* `index.html`: Página principal estática con scroll orgánico, sedes, horarios y contacto.
* `img/`: Fotografías minimalistas de alta resolución de las fachadas y atención farmacéutica.
* `_next/`: Hojas de estilo CSS y componentes de hidratación optimizados.
* `laboratorios/`: Logotipos de los 22 principales laboratorios farmacéuticos en Chile.
* `.htaccess`: Reglas de compresión Gzip, caché de navegador y seguridad para servidores LiteSpeed/Apache.
* `404.html`: Página de error personalizada.
