# 📱 Expediente Anestésico IMSS - PWA

**Progressive Web App completamente funcional en iOS**  
Compatible: iPhone 15 Pro, iPhone 16, iPhone 17+ (iOS 15+)

---

## 🎯 Características

✅ **Funciona 100% sin internet** una vez instalada  
✅ **Se actualiza automáticamente** cuando subes cambios  
✅ **Guarda datos localmente** en tu dispositivo  
✅ **App nativa** en tu pantalla de inicio  
✅ **Optimizada para iOS** Safari 15+  

---

## 📦 Archivos del proyecto

Este proyecto contiene 6 archivos necesarios para la PWA:

```
expediente-anestesico/
├── index.html              # Aplicación principal
├── manifest.json           # Configuración PWA
├── sw.js                   # Service Worker (offline)
├── icon-192.png            # Icono 192x192
├── icon-512.png            # Icono 512x512
├── apple-touch-icon.png    # Icono iOS 180x180
└── README.md               # Este archivo
```

---

## 🚀 INSTALACIÓN PASO A PASO DESDE IPHONE

### OPCIÓN A: Usando la app GitHub (Recomendado)

#### 📥 **PASO 1: Instala la app GitHub**
1. Abre **App Store** en tu iPhone
2. Busca **"GitHub"**
3. Descarga e instala la app oficial de GitHub
4. Abre la app y **inicia sesión** con tu cuenta

#### 📂 **PASO 2: Crea un nuevo repositorio**
5. En la app GitHub, toca el **ícono + (arriba a la derecha)**
6. Selecciona **"New repository"**
7. Configura:
   - **Repository name**: `expediente-anestesico` (o el nombre que quieras)
   - **Description**: "Expediente Anestésico IMSS - PWA"
   - **Visibility**: **Public** (obligatorio para GitHub Pages)
   - **Initialize**: NO marques "Add a README" (lo subiremos después)
8. Toca **"Create repository"**

#### ⬆️ **PASO 3: Sube los archivos**
9. Toca **"Add file" → "Upload files"**
10. Toca **"Choose your files"**
11. Selecciona **TODOS** los archivos:
    - index.html
    - manifest.json
    - sw.js
    - icon-192.png
    - icon-512.png
    - apple-touch-icon.png
12. Toca **"Commit changes"**

#### ⚙️ **PASO 4: Activa GitHub Pages**
13. Ve a la pestaña **"Settings"** (abajo, ícono de engranaje)
14. Desplázate hasta **"Pages"** (en el menú lateral)
15. En **"Source"**, selecciona:
    - Branch: **main**
    - Folder: **/ (root)**
16. Toca **"Save"**

#### ⏳ **PASO 5: Espera el despliegue**
17. Espera **2-3 minutos**
18. Verás un mensaje verde:  
    **"Your site is published at https://[usuario].github.io/expediente-anestesico/"**
19. Copia esa URL

#### 📲 **PASO 6: Instala en tu iPhone**
20. Abre **Safari** (no Chrome, debe ser Safari)
21. Pega tu URL: `https://[usuario].github.io/expediente-anestesico/`
22. La app se carga
23. Toca el botón **"Compartir"** <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='20' height='20' viewBox='0 0 24 24' fill='none' stroke='%23007AFF' stroke-width='2'%3E%3Cpath d='M4 12v8a2 2 0 002 2h12a2 2 0 002-2v-8M16 6l-4-4-4 4M12 2v13'/%3E%3C/svg%3E" style="vertical-align:middle;"> (centro inferior de Safari)
24. Desplázate hacia abajo
25. Selecciona **"Añadir a pantalla de inicio"**
26. Toca **"Añadir"**

🎉 **¡LISTO!** La app está en tu pantalla de inicio.

---

### OPCIÓN B: Usando Safari (sin app GitHub)

#### 🌐 **PASO 1: Ve a GitHub en Safari**
1. Abre **Safari** en tu iPhone
2. Ve a **github.com**
3. Inicia sesión
4. Toca **+ (arriba a la derecha) → New repository**

#### 📂 **PASO 2: Crea el repositorio**
5. Nombre: `expediente-anestesico`
6. Visibility: **Public**
7. Toca **"Create repository"**

#### ⬆️ **PASO 3: Sube archivos**
8. Toca **"uploading an existing file"**
9. Arrastra o selecciona **TODOS** los 6 archivos
10. Toca **"Commit changes"**

#### ⚙️ **PASO 4: Activa Pages**
11. Ve a **Settings → Pages**
12. Source: **Deploy from a branch**
13. Branch: **main** → **Save**
14. Espera 2-3 minutos
15. Copia la URL que aparece

#### 📲 **PASO 5: Instala**
16-26. Sigue los pasos 20-26 de la Opción A

---

## 🔄 Actualizar la app

Una vez instalada, para actualizar:

1. Edita los archivos en tu repositorio GitHub
2. Haz commit de los cambios
3. Espera 2-3 minutos
4. Abre la app en tu iPhone
5. La app se **actualiza automáticamente** (Service Worker detecta cambios)
6. Si no se actualiza, cierra y reabre la app

---

## ✅ Verificar que funciona offline

1. Abre la app desde tu pantalla de inicio
2. Activa **Modo Avión** en tu iPhone
3. La app **sigue funcionando** normalmente
4. Rellena formularios → los datos se guardan
5. Desactiva Modo Avión
6. Los datos siguen allí

---

## 🛠 Solución de problemas

### ❌ "La app no aparece en mi pantalla de inicio"
- Verifica que seguiste **TODOS** los pasos del Paso 6
- Debe ser **Safari** (no Chrome ni otro navegador)
- Asegúrate de tocar "Añadir a pantalla de inicio", no "Favoritos"

### ❌ "La app no funciona sin internet"
- Espera 2-3 minutos después de activar GitHub Pages
- Verifica que **sw.js** se haya subido correctamente
- Abre Safari → Desarrollador → [tu sitio] → Service Workers

### ❌ "Los datos no se guardan"
- El almacenamiento funciona solo si instalaste como PWA
- Si abres desde Safari normal (sin instalar), los datos pueden perderse
- Instala la app en pantalla de inicio (Paso 6)

### ❌ "GitHub Pages no se activa"
- El repositorio DEBE ser **Public** (no Private)
- Verifica que el branch sea **main** (no master)
- Espera 3-5 minutos, GitHub Pages puede tardar

---

## 📋 Checklist de instalación

Marca cada paso cuando lo completes:

- [ ] Descargué los 6 archivos del proyecto
- [ ] Creé un repositorio en GitHub (Public)
- [ ] Subí TODOS los archivos al repositorio
- [ ] Activé GitHub Pages (Settings → Pages)
- [ ] Esperé 2-3 minutos
- [ ] Copié mi URL de GitHub Pages
- [ ] Abrí la URL en Safari (iPhone)
- [ ] Toqué Compartir → Añadir a pantalla de inicio
- [ ] La app aparece en mi pantalla de inicio
- [ ] Probé Modo Avión → funciona offline ✅

---

## 🔐 Privacidad y Seguridad

- ✅ **Todos los datos se guardan SOLO en tu dispositivo**
- ✅ No hay base de datos externa
- ✅ No se envía información a servidores
- ✅ Funciona 100% offline
- ✅ Solo tú tienes acceso a los datos guardados
- ⚠️ Si desinstales la app, los datos se borran
- ⚠️ Los datos NO se sincronizan entre dispositivos

---

## 🆘 Soporte

Si tienes problemas:

1. Revisa la sección "Solución de problemas" arriba
2. Verifica que tu iPhone tenga iOS 15 o superior
3. Asegúrate de usar Safari (no Chrome)
4. Revisa que GitHub Pages esté activo (verde en Settings)

---

## 📱 Compatibilidad

| Dispositivo | iOS | Estado |
|------------|-----|--------|
| iPhone 15 Pro | iOS 17+ | ✅ Totalmente compatible |
| iPhone 16 | iOS 18+ | ✅ Totalmente compatible |
| iPhone 17 | iOS 18+ | ✅ Totalmente compatible |
| iPhone 14/13/12 | iOS 15-17 | ✅ Compatible |
| iPhone 11/XR | iOS 15-16 | ✅ Compatible |
| iPad | iOS 15+ | ✅ Compatible |

---

## 📄 Licencia

Este proyecto es de uso médico interno.

---

**Desarrollado para IMSS Bienestar**  
Expediente Anestésico Integral — Consentimiento, Valoración y Registro  
Compatible iOS 15+ | PWA Optimizada | 100% Offline
