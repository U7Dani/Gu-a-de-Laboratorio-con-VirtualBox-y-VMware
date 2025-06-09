![image](https://github.com/user-attachments/assets/52428fb1-a552-4ce0-8ecc-261b1f174dfe)

# 🧪 Guía Completa: Laboratorio de Ciberseguridad con VirtualBox y VMware

Esta guía está pensada para principiantes que desean montar un entorno de laboratorio de ciberseguridad utilizando máquinas virtuales. Aprenderás a instalar VirtualBox y VMware, configurar redes (NAT, Host-Only, Bridge), e instalar sistemas operativos como Kali Linux, Ubuntu y Windows 10.

---

## 📥 Descarga del software necesario

- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [VMware Workstation Player](https://www.vmware.com/go/getplayer-win)
- [Kali Linux ISO](https://www.kali.org/get-kali/)
- [Ubuntu Desktop ISO](https://ubuntu.com/download/desktop)
- [Windows 10 ISO (Microsoft)](https://www.microsoft.com/en-us/software-download/windows10ISO)

---

## 🛠️ Instalación de VirtualBox

1. Descarga el instalador desde el enlace oficial.
2. Ejecuta el archivo y sigue las instrucciones por defecto.
3. Instala el Extension Pack para compatibilidad avanzada (USB, red, etc.).

## 🛠️ Instalación de VMware Workstation Player

1. Descarga desde el enlace oficial.
2. Acepta los términos de uso e instala.
3. Regístrate con tu correo para la licencia gratuita personal.

---

## 🌐 Tipos de red en virtualización

- **NAT**: La VM accede a Internet a través del host. Ideal para navegar de forma segura.
- **Host-Only**: Solo permite comunicación entre el host y la VM. Útil para pruebas aisladas.
- **Bridge**: La VM se conecta directamente a la red física. Perfecto para pruebas reales.

---

## 📦 Crear una VM en VirtualBox

1. Haz clic en "Nueva".
2. Asigna nombre, tipo (Linux) y versión.
3. Asigna memoria RAM (2 GB mínimo).
4. Crea disco virtual (VDI, dinámico, 20 GB mínimo).
5. Monta la ISO en "Almacenamiento".
6. Configura red: NAT, Host-only o Bridge.

## 📦 Crear una VM en VMware Player

1. Haz clic en "Create a New Virtual Machine".
2. Selecciona "Installer disc image file (ISO)" y carga tu ISO.
3. Configura nombre, ubicación y espacio en disco.
4. Ajusta RAM, CPU y red en "Customize Hardware".
5. Inicia la VM e instala el sistema.

---

## 💻 Instalación de sistemas operativos

- **Kali Linux**: Selecciona "Graphical Install", elige idioma, zona, usuario y contraseña.
- **Ubuntu**: Idioma, instalación normal, usuario y contraseña.
- **Windows 10**: Instala sin clave si es solo para pruebas, configura usuario local.

---

## ✅ Recomendaciones finales

- Toma snapshots antes de pruebas importantes.
- Usa redes NAT o Host-Only para evitar filtraciones.
- Crea una VM atacante (Kali) y otras víctimas (Ubuntu/Windows).
- Documenta todo para futuras prácticas.

---

📌 Esta guía forma parte del proyecto educativo **Ciber IQ**. Si te ha sido útil, ⭐ dale una estrella al repositorio y comparte con otros aprendices de ciberseguridad.
