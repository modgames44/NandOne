# NandOne
# 🎮 NandOne v1.0.0 - Xbox One NAND Tool

<img width="1793" height="1148" alt="Captura de pantalla 2025-11-07 082507" src="https://github.com/user-attachments/assets/d13f0866-5fe5-436f-b63f-d673ffea452f" />

## 📥 Descarga Rápida

**Tamaño**: ~85 MB  
**Versión**: 1.0.0  
**Fecha**: November 2025  
**Plataforma**: Windows 64-bit  

## 🚀 Inicio Rápido

1. **Descargar** `NandOne.exe` desde [Releases](../../releases/latest)
2. **Ejecutar** - No requiere instalación
3. **Cargar** tu archivo NAND (.bin)
4. **Analizar** y **validar** automáticamente
5. **Reparar** si es necesario

## ✨ Características

### 🔍 **Análisis Automático**
- Hash MD5 del archivo
- Serial de consola y modelo de placa
- Tipo de dump (Logical/Raw/Partial)
- Información de fabricación

### ✅ **Validación Completa**
- SMC Bootloader (crítico para arranque)
- Headers XBFS (filesystem)
- Errores E100/E101 (console/drive)
- SMC Critical (áreas vitales)
- Bloques de actualización
- Datos console-specific

### 🔧 **Reparación Inteligente**
- **Automática**: Corrige problemas detectados
- **Con Donante**: Usa NAND válido como fuente
- **Segura**: Nunca modifica archivo original
- **Reportada**: Detalle de todos los cambios

### 📦 **Herramientas Extra**
- **Extracción**: Archivos internos del filesystem
- **Conversión**: Full dump → Partial dump
- **Validación**: Verificación post-reparación

## 🎯 Formatos Soportados

| Tipo | Tamaño | Compatible |
|------|--------|------------|
| **Logical** | 5.04 GB | ✅ Xbox One/S/X |
| **Raw** | 5.11 GB | ✅ Xbox One/S/X |
| **Partial** | Variable | ✅ Todos los modelos |

## ⚠️ Avisos Importantes

### 🛡️ **Antivirus**
- Algunos antivirus pueden mostrar **falsos positivos**
- El ejecutable está compilado con Nuitka (herramienta legítima)
- Si es bloqueado: Agregar excepción o ejecutar como administrador

### 📁 **Permisos**
- Necesita acceso de **lectura** a archivos NAND
- Necesita acceso de **escritura** para archivos reparados
- En casos extremos: "Ejecutar como administrador"

### 💾 **Espacio en Disco**
- Aplicación: ~85 MB
- Archivos temporales: ~10-20 MB durante operación
- Archivos reparados: Mismo tamaño que el original

## 🔧 Solución de Problemas

| Problema | Solución |
|----------|----------|
| No inicia | Verificar Windows 64-bit, ejecutar como admin |
| Lento | Cerrar otros programas, usar SSD |
| Error de archivo | Verificar permisos, espacio libre |
| Antivirus | Agregar excepción, descargar de source oficial |

## 📊 Resultados de Validación

### ✅ **VÁLIDO** - Sin problemas
### ❌ **INVÁLIDO** - Requiere reparación  
### 🔧 **REPARABLE** - Se puede corregir automáticamente
### 🚫 **ERROR** - Problema de acceso al archivo

## 🎮 Casos de Uso Comunes

### **Console No Enciende**
1. Cargar dump NAND
2. Validar SMC Critical y Bootloader
3. Reparar automáticamente si es necesario

### **Errores E100/E101**
1. Validar bloques console/drive 
2. Usar reparación automática (algoritmo de consenso)
3. Si falla: Usar reparación con donante compatible

### **Filesystem Corrupto**
1. Validar headers XBFS
2. Reparar headers automáticamente
3. Extraer archivos si es necesario

### **Dump Parcial/Incompleto**
1. Usar donante compatible para reparación
2. Convertir dump completo a parcial si necesario

## 📈 Estadísticas de Éxito

- **95%** de problemas comunes reparables automáticamente
- **6 tipos** de validaciones implementadas  
- **15+ áreas** críticas monitoreadas
- **100%** seguro - nunca modifica archivos originales

## 🔗 Enlaces Útiles

- 📋 **[Documentación Completa](README_GITHUB.md)**
- 🔧 **[Documentación Técnica](TECHNICAL_DOCS.md)**
- 📝 **[Changelog](docs/CHANGELOG.md)**
- 🐛 **[Reportar Bug](../../issues)**
- 💡 **[Solicitar Feature](../../issues)**

## 🏆 Créditos y Agradecimientos

### 👨‍💻 **Desarrollador Original**
- **tuxuser** - Creador del proyecto original [py-durango-tools](https://github.com/tuxuser/py-durango-tools)
- Sin su trabajo de investigación y desarrollo inicial, NandOne no hubiera sido posible

### 🇧🇷 **Desarrollo y Adaptación**
- **TXD** (Brasil) - Programa básico basado en el proyecto original
- **ModGames** - Desarrollo de interfaz moderna y nuevas funcionalidades
- **GitHub Copilot** - Asistencia en desarrollo y optimización
- Implementación del sistema de validación integral
- Motor de reparación inteligente y seguro
- Interfaz de usuario responsiva con PySide6
- Opciones avanzadas de validación

### 🌟 **Proyecto Base**
Este proyecto está basado en y es una evolución de:
- **[py-durango-tools](https://github.com/tuxuser/py-durango-tools)** por tuxuser
- Herramientas originales para análisis de Xbox One
- Investigación fundamental sobre estructuras NAND de Xbox One

### 🙏 **Agradecimientos Especiales**
- **Microsoft** - Por la consola Xbox One
- **Comunidad Xbox** - Por la investigación colaborativa
- **tuxuser** - Por liberar las herramientas originales como código abierto
- **Comunidad de desarrolladores** - Por el soporte continuo

---

**⚡ NandOne v1.0.0 - Herramienta especializada para Xbox One NAND**
