# 🔐 GUÍA RÁPIDA - Sistema de Autenticación

## 🚀 INICIO RÁPIDO (5 minutos)

### 1️⃣ PRIMER LOGIN
```
Usuario: admin
Contraseña: admin
```

### 2️⃣ CAMBIAR CONTRASEÑA (OBLIGATORIO)
```
1. Toca 👤 (arriba derecha)
2. "Cambiar contraseña"
3. Actual: admin
4. Nueva: (tu contraseña segura)
5. Guardar
```

### 3️⃣ CREAR USUARIOS
```
1. Toca 👤
2. "Administrar usuarios"
3. "➕ Agregar nuevo usuario"
4. Completa formulario
5. "Crear usuario"
```

---

## 👤 ROLES DE USUARIO

### **SUPER ADMINISTRADOR** (admin)
✅ Crear usuarios  
✅ Eliminar usuarios  
✅ Ver todos los usuarios  
✅ Usar la aplicación  

### **USUARIO NORMAL**
✅ Usar la aplicación  
✅ Cambiar su contraseña  
❌ No puede gestionar otros usuarios  

---

## 🔑 GESTIÓN DE USUARIOS

### **Crear usuario:**
```
Usuario: dr.perez
Nombre: Dr. Juan Pérez  
Rol: Usuario
Contraseña: (mínimo 4 caracteres)
```

### **Eliminar usuario:**
```
1. Panel admin
2. Usuario → 🗑️
3. Confirmar
```

⚠️ **NO puedes:**
- Eliminarte a ti mismo
- Eliminar al super admin original

---

## 📱 FLUJO DE USO DIARIO

### **Para cada médico:**

**Mañana:**
```
1. Abrir app
2. Login (si no está la sesión activa)
3. Usar normalmente
```

**Noche:**
```
1. Toca 👤
2. "Cerrar sesión"
3. Listo
```

---

## 🔐 SEGURIDAD

✅ Contraseñas hasheadas (SHA-256)  
✅ Nunca en texto plano  
✅ Almacenamiento local  
✅ Sin envío a servidores  

⚠️ **IMPORTANTE:**
- Si desinstalas la app = se pierden usuarios
- Cada dispositivo tiene sus propios usuarios
- NO se sincronizan entre dispositivos

---

## 🆘 PROBLEMAS COMUNES

### ❌ "Olvidé mi contraseña"
**Solución (solo admin puede):**
1. Admin crea un nuevo usuario temporal
2. Usuario inicia sesión con credenciales temporales
3. Cambia su contraseña

### ❌ "No puedo crear usuarios"
**Causa:** No eres administrador  
**Solución:** Pide al admin que te dé rol de administrador

### ❌ "Los usuarios desaparecieron"
**Causas posibles:**
- Limpiaste caché del navegador
- Reinstalaste la app
- Usaste "Modo Privado"

**Prevención:**
- Anota las credenciales en lugar seguro
- No uses Modo Privado

---

## 📋 CHECKLIST INICIAL

Para el administrador del hospital:

- [ ] Instalé la PWA
- [ ] Cambié contraseña de admin
- [ ] Creé usuarios para el equipo
- [ ] Probé login con cada usuario
- [ ] Compartí URL con el equipo
- [ ] Proporcioné credenciales a cada médico
- [ ] Expliqué cómo cerrar sesión

---

## 💡 TIPS

1. **Usa nombres de usuario claros:**
   - ✅ `dr.perez`, `dra.garcia`
   - ❌ `usuario1`, `doc123`

2. **Roles:**
   - Administrador = Solo 1-2 personas de confianza
   - Usuario = Todo el resto del equipo

3. **Contraseñas:**
   - Mínimo 4 caracteres (recomendado: 8+)
   - Usa combinación de letras y números
   - No compartas contraseñas

4. **Sesiones:**
   - Cierra sesión en dispositivos compartidos
   - La sesión persiste entre aperturas de la app

---

## 🎯 RECUERDA

✅ **Usuario por defecto:** `admin` / `admin`  
✅ **Cambiar contraseña** inmediatamente  
✅ **Crear usuarios individuales** para cada médico  
✅ **Cerrar sesión** en dispositivos compartidos  
✅ **Los datos se guardan por dispositivo**, no se sincronizan  

---

**Compatible: iPhone 15 Pro, 16, 17+ (iOS 15+)**  
**100% Offline | Multi-usuario | Seguro**
