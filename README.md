# MacClean128k-

🍏 **Limpieza profunda para macOS... con estilo retro.**

Revive la **Macintosh 128k** de 1984 directamente en tu Mac moderno. Interfaz pixel-art, tipografía System 1, sonidos clásicos — mientras limpias tu sistema hasta los huesos.

> "Es como si una Mac 128k y un limpiador moderno tuvieran un hijo". — *Los foros*

---

## ¿Qué lo hace diferente?

| ❌ App Store / Modernas | ✅ MacClean128k- |
|------------------------|------------------|
| GUI genérica plana | **Interfaz retro System 1** (píxeles, curvas Mac clásicas) |
| Sandbox (no pueden tocar el sistema) | **Sin Sandbox — acceso total** |
| Sin personalidad | **Sonidos de arranque y clics de los 80s** |
| $9.99/mes | **Gratis, MVP en desarrollo** |

---

## Captura

*(Próximamente — mientras tanto, descárgalo y vélo tú mismo)*

---

## Guía: Cómo abrir la app (saltar Gatekeeper)

Al ser una app fuera de la App Store, macOS la bloquea. Fácil de saltar:

### Método 1 — Click derecho
1. Descarga el `.dmg` desde [Releases](https://github.com/maarkman90/MacClean128k-releases/releases/latest)
2. **Click derecho** sobre el `.dmg` → **Abrir**
3. Arrastra `MacClean128k-` a `Applications`
4. **Click derecho** sobre la app → **Abrir** → **"Abrir"**

### Método 2 — Terminal
```bash
xattr -cr /Applications/MacClean128k-.app
```

---

## Permiso de Acceso al Disco Duro (Full Disk Access)

MacClean128k- necesita **Full Disk Access** para escanear todo el sistema.

### Cómo otorgarlo
1. **Ajustes del Sistema** → **Privacidad y Seguridad**
2. **Acceso al Disco Duro**
3. 🔒 Desbloquea con tu contraseña
4. ✅ Activa **MacClean128k-**
5. Si no aparece, arrastra la app desde Applications a la lista

> **¿Por qué?** Al no tener Sandbox (como sí exige la App Store), podemos acceder a archivos reales del sistema: cachés de sistema, logs de macOS, DerivedData de Xcode, restos de apps desinstaladas. Las apps sandboxed no pueden tocar nada de esto.

---

## Roadmap
- [x] GUI retro System 1
- [x] Escaneo de basura con recetas JSON
- [x] Desinstalador profundo
- [ ] Actualizaciones automáticas (Sparkle)
- [ ] Más skins retro (System 6, Platinum, etc.)
- [ ] Sonidos personalizables
- [ ] Notarization con Apple

---

**Descarga la última versión:** https://github.com/maarkman90/MacClean128k-releases/releases/latest

Hecho con nostalgia por [@maarkman90](https://github.com/maarkman90)
