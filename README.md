# 📱 Expediente Anestésico IMSS - PWA Protegida

**Progressive Web App con autenticación Y protección de código fuente**  
Compatible: iPhone 15 Pro, iPhone 16, iPhone 17+ (iOS 15+)

---

## 🔐 PROTECCIÓN DE CÓDIGO

### **Contraseña para acceder al código:**
```
```

⚠️ **IMPORTANTE:** Esta contraseña protege el acceso a la aplicación completa. Solo tú debes conocerla.

### **Cómo funciona:**
1. Al abrir la app, aparece una pantalla de "Código Protegido"
2. Debes ingresar la contraseña: `@L3w3ndy10*#`
3. Una vez desbloqueado, puedes usar la app normalmente
4. La app permanece desbloqueada durante la sesión
5. Al cerrar el navegador/app, la próxima vez pedirá contraseña de nuevo

### **Medidas de seguridad implementadas:**
✅ **Protección por contraseña** en la capa de entrada  
✅ **Clic derecho deshabilitado** (no pueden "Ver código fuente")  
✅ **Teclas de desarrollador bloqueadas** (F12, Ctrl+Shift+I, etc.)  
✅ **Contenido separado** (app real en archivo protegido)  
✅ **Sin acceso sin contraseña**  

---

## 🔑 DOS NIVELES DE SEGURIDAD

### **Nivel 1: Protección del Código** 🔐
- **Contraseña:**
- Protege el acceso a la aplicación completa
- Requerida al abrir la app

### **Nivel 2: Sistema de Usuarios** 👤
- **Usuario por defecto:** `admin` / `admin`
- Gestión de usuarios médicos
- Una vez dentro de la app

---

## 📦 ARCHIVOS DEL PROYECTO (10 archivos)

```
expediente-anestesico-pwa/
├── 📄 index.html              (11 KB)  ← Capa de protección
├── 📄 app-content.html        (279 KB) ← Aplicación real (protegida)
├── ⚙️ manifest.json           
├── 🔧 sw.js                   
├── 🖼️ icon-192.png, icon-512.png, apple-touch-icon.png
├── 📋 README.md               ← Este archivo
├── 🚀 GUIA_RAPIDA.md          
└── 🔐 GUIA_AUTH.md            
```

---

## 🚀 INSTALACIÓN DESDE IPHONE

### **PASO 1: Sube TODOS los archivos a GitHub**

**IMPORTANTE:** Debes subir AMBOS archivos HTML:
- ✅ `index.html` (capa de protección)
- ✅ `app-content.html` (app real)
- ✅ Todos los demás archivos

1. **App Store** → Descarga "GitHub"
2. Crea repositorio: `expediente-anestesico`
3. **Visibility: Public**
4. **Upload files** → Selecciona los **10 archivos**
5. **Commit changes**
6. **Settings → Pages → Branch: main → Save**
7. Espera 2-3 min → Copia la URL

### **PASO 2: Instala en tu iPhone**

8. Abre **Safari** → Pega tu URL
9. **Compartir** ⎙ → **"Añadir a pantalla de inicio"**

---

## 🔐 PRIMER USO

### **1. Desbloquear el código**
```
Contraseña:
```
Esta es la protección del código fuente.

### **2. Login de usuario**
```
Usuario: admin
Contraseña: admin
```
Este es el sistema de gestión de usuarios médicos.

### **3. Cambiar contraseña de admin**
1. Toca 👤 → "Cambiar contraseña"
2. Cambia `admin` por una contraseña segura

### **4. Crear usuarios del equipo**
1. Toca 👤 → "Administrar usuarios"
2. Crea usuarios para cada médico

---

## 🛡️ SEGURIDAD IMPLEMENTADA

### **Protección del Código:**
- ✅ Contraseña en la entrada
- ✅ Clic derecho deshabilitado
- ✅ Herramientas de desarrollador bloqueadas
- ✅ No se puede ver código fuente fácilmente
- ✅ Contenido real en archivo separado

### **Gestión de Usuarios:**
- ✅ Contraseñas hasheadas (SHA-256)
- ✅ Roles (Admin / Usuario)
- ✅ Sesiones persistentes
- ✅ Datos locales por usuario

---

## ⚠️ IMPORTANTE SOBRE LA PROTECCIÓN

### **Lo que SÍ protege:**
✅ Usuarios no técnicos no pueden ver el código  
✅ No pueden hacer clic derecho → Ver código  
✅ No pueden abrir herramientas de desarrollador fácilmente  
✅ El código no es visible directamente  

### **Lo que NO puede garantizar:**
⚠️ Un desarrollador experto podría bypassear las protecciones  
⚠️ Si alguien tiene la contraseña `@L3w3ndy10*#`, puede acceder  
⚠️ No es encriptación de nivel militar  

**RECOMENDACIÓN:** No compartas la contraseña `@L3w3ndy10*#` con nadie.

---

## 📋 FLUJO COMPLETO

```
Usuario abre la app
    ↓
🔐 Pantalla: "Código Protegido"
    ↓
Ingresa: @L3w3ndy10*#
    ↓
🔓 App se desbloquea
    ↓
👤 Pantalla: Login de usuario
    ↓
Ingresa: admin / admin (primera vez)
    ↓
✅ Acceso a la aplicación
    ↓
Usa expedientes anestésicos normalmente
```

---

## 🔄 ACTUALIZAR LA APP

1. Edita archivos en GitHub
2. Espera 2-3 minutos
3. Abre la app → Pide contraseña de código
4. Ingresa
5. Se actualiza automáticamente

---

## 🆘 SOLUCIÓN DE PROBLEMAS

### ❌ "Olvidé la contraseña del código"
**Es:**
No hay forma de recuperarla si no la recuerdas. Guárdala en un lugar seguro.

### ❌ "La app pide contraseña cada vez"
Eso es correcto. Pide la contraseña del código cada vez que cierras y abres la app (por seguridad).

### ❌ "Alguien puede ver mi código"
Con la contraseña `` pueden acceder. No la compartas.

### ❌ "Quiero cambiar la contraseña del código"
Necesitas editar el archivo `index.html` y cambiar el hash. Contáctame si necesitas hacerlo.

---

## 📱 COMPATIBILIDAD

| Dispositivo | iOS | Estado |
|------------|-----|--------|
| **iPhone 15 Pro** | iOS 17+ | ✅ Totalmente compatible |
| **iPhone 16** | iOS 18+ | ✅ Totalmente compatible |
| **iPhone 17** | iOS 18+ | ✅ Totalmente compatible |
| iPhone 14/13/12 | iOS 15-17 | ✅ Compatible |
| iPad | iOS 15+ | ✅ Compatible |

---

## 🎯 CHECKLIST DE INSTALACIÓN

- [ ] Descargué el ZIP completo (10 archivos)
- [ ] Subí **TODOS** los archivos a GitHub (incluyendo app-content.html)
- [ ] Activé GitHub Pages
- [ ] Instalé en mi iPhone
- [ ] Probé contraseña del código ✅
- [ ] Hice login: admin / admin
- [ ] Cambié contraseña del administrador
- [ ] Creé usuarios para el equipo
- [ ] **Guardé la contraseña del código en lugar seguro**

---

## 🔐 RECUERDA

✅ **Contraseña del código:** `` (NO compartir)  
✅ **Usuario admin:** `admin` / `admin` (cambiar después)  
✅ **Dos niveles de seguridad:** código + usuarios  
✅ **Sube ambos archivos HTML** a GitHub  
✅ **No pierdas la contraseña del código**  

---

## 📄 LICENCIA

Este proyecto es de uso médico interno para IMSS Bienestar.  
**Código protegido por contraseña** - Uso exclusivo autorizado.

---

**Desarrollado para IMSS Bienestar**  
Expediente Anestésico Integral  
Compatible iOS 15+ | PWA Protegida | Multi-usuario | Código Seguro
