# 🎨 Compos Theme for Home Assistant

Compos es un tema moderno para Home Assistant con estilo **glass / iOS**, fondo con imagen,
colores semánticos y soporte completo para **modo claro y oscuro automático**.

Diseñado para dashboards elegantes, pantallas grandes y móviles.

---

## ✨ Características

- 🌗 Light & Dark mode real (compatible con Auto Dark Mode)
- 🌄 Fondo con imagen propia
- 🧊 Estilo glass (cards, sidebar, header)
- 🎨 Sistema de colores semánticos
- 🔌 Estados por dominio (luces, sensores, media, energía, etc)
- 📊 Energy Dashboard optimizado
- 🧭 Sidebar moderno con hover y selección visual
- 🖱️ Scrollbar y tooltips personalizados

---

## 📸 Preview

![Compos Theme](screenshots/dashboard-light.png)
*(Imagen de fondo incluida como ejemplo)*

---

## 📂 Instalación manual

1. Copia la carpeta "themes" y "www" a:
/config


2. Asegúrate de tener esto en tu "configuration.yaml":

frontend:
  themes: !include_dir_merge_named themes

3. Reinicia Home Assistant.

4. Ve a:
Perfil → Temas → Selecciona Compos

## 📸 Screenshots

### ☀️ Light mode
![Light](screenshots/dashboard-light.png)

### 🌙 Dark mode
![Dark](screenshots/dashboard-dark.png)

### 📱 Mobile ☀️ Light mode
![Light](screenshots/mobile-light.png)

### 📱 Mobile ☀️ Light mode sidebar
![Light](screenshots/mobile-light-sidebar.png)

### 📱 Mobile 🌙 Dark mode
![Dark](screenshots/mobile-dark.png)

### 📱 Mobile 🌙 Dark mode sidebar
![Dark](screenshots/mobile-dark-sidebar.png)


