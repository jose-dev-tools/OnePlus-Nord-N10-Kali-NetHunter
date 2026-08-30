# OnePlus-Nord-N10-Kali-NetHunter
Kali NetHunter + TWRP + Root para OnePlus Nord N10 5G (billie). Guía completa con TWRP Recovery 3.5.1 y Boot modificado con Magisk.

![Status](https://img.shields.io/badge/Status-Stable-green)
![Device](https://img.shields.io/badge/Device-OnePlus%20Nord%20N10%205G-blue)
![Android](https://img.shields.io/badge/Android-10%2F11-orange)

**Guía completa para instalar Kali NetHunter + Root en OnePlus Nord N10 5G (billie)**

## ✨ Características

- ✅ TWRP Recovery 3.5.1 (Funcional)
- ✅ Boot Image modificado con Magisk 26.x
- ✅ Soporte Kali NetHunter Chroot
- ✅ Acceso Root completo
- ✅ Encrypted Data support (Android 10)

## 📋 Requisitos

- Bootloader Desbloqueado
- ADB y Fastboot instalados
- Cable USB
- Batería 50%+ 

## 🚀 Instalación Rápida

### Boot Temporal (Recomendado primero)
```bash
fastboot boot recoverytwrp_3_5_1.img
```

### Flashear Boot Modificado
```bash
adb reboot bootloader
fastboot flash boot magisk_patched-30700_HOwgT.img
fastboot reboot
```

## ⚠️ Advertencias

🔴 NO instales en otros modelos Nord
🔴 Requiere Bootloader Desbloqueado
🔴 Ten boot.img original para revertir

## 📥 Descargas

Descarga en [Releases](../../releases)

## 📝 License

MIT License
