# MacClean128k-

**Limpieza profunda para macOS. Sin bloat, sin App Store, sin límites.**

Descarga la última versión desde [Releases](https://github.com/maarkman90/MacClean128k-releases/releases/latest).

---

## Guía: Cómo abrir la app (saltar Gatekeeper)

Al ser una app fuera de la App Store, macOS bloquea la apertura por no estar notarizada. Sigue estos pasos:

### Método 1 — Click derecho (más fácil)
1. Descarga el `.dmg`
2. Haz **click derecho** (o Ctrl + click) sobre el `.dmg` → **Abrir**
3. Arrastra `MacClean128k-` a `Applications`
4. Haz **click derecho** sobre la app en Applications → **Abrir**
5. Click en **"Abrir"** en el diálogo (ya no aparecerá más)

### Método 2 — Terminal (si el método 1 falla)
```bash
xattr -cr /Applications/MacClean128k-.app
```

---

## Permiso de Acceso al Disco Duro (Full Disk Access)

MacClean128k- necesita **Full Disk Access** para escanear y limpiar archivos en todo el sistema.

### Cómo otorgarlo
1. Abre **Ajustes del Sistema** → **Privacidad y Seguridad**
2. Desplázate hasta **Acceso al Disco Duro**
3. Click en el candado 🔒 (esquina inferior) y autentícate
4. Activa el switch de **MacClean128k-**
5. Si no aparece, arrastra la app desde Applications a la lista

| Paso | Acción |
|------|--------|
| 1 | Ajustes → Privacidad y Seguridad |
| 2 | Desplázate a **Acceso al Disco Duro** |
| 3 | 🔓 Desbloquea con tu contraseña |
| 4 | ✅ Activa MacClean128k- |

> **¿Por qué necesita este permiso?** A diferencia de apps del App Store (restringidas por Sandbox), MacClean128k- accede directamente al sistema de archivos para eliminar basura real: cachés de sistema, logs, DerivedData de Xcode, y restos de apps desinstaladas.

---

## Próximos features
- [ ] Actualizaciones automáticas (Sparkle)
- [ ] Más recetas JSON para tipos de basura
- [ ] Modo programado (limpieza automática)
- [ ] Notarization con Apple

---

Hecho con ❤️ por [@maarkman90](https://github.com/maarkman90)
