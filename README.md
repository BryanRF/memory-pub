# 🧠 MEMORY - App de Gestión Personal

<div align="center">

![Memory App](assets/images/image.png)

**Aplicación multiplataforma privada y segura con cifrado AES-256 y autenticación biométrica**

[![Flutter](https://img.shields.io/badge/Flutter-3.8+-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-Private-red)](LICENSE)
[![Null Safety](https://img.shields.io/badge/Null%20Safety-100%25-green)](https://dart.dev/null-safety)
[![Architecture](https://img.shields.io/badge/Architecture-Clean%20Architecture-blue)](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
[![GitHub release](https://img.shields.io/github/v/release/BryanRF/memory-pub?label=Release&style=flat-square)](https://github.com/BryanRF/memory-pub/releases/latest)

</div>

---

## 📥 Descarga

<div align="center">

### [⬇️ Descargar APK desde Releases](https://github.com/BryanRF/memory-pub/releases/latest)

[![Download APK](https://img.shields.io/badge/Descargar-v1.0.0-success?style=for-the-badge&logo=android&logoColor=white)](https://github.com/BryanRF/memory-pub/releases/latest)
[![GitHub release](https://img.shields.io/github/v/release/BryanRF/memory-pub?label=Última%20Release&style=flat-square)](https://github.com/BryanRF/memory-pub/releases/latest)

**Versión:** v1.0.0  
**Plataforma:** Android  
**Descarga:** Disponible en [Releases](https://github.com/BryanRF/memory-pub/releases)

</div>

---

## 📋 Descripción

**MEMORY** es una aplicación multiplataforma desarrollada con Flutter que ofrece una solución completa para la gestión personal de información sensible. Diseñada con un enfoque en la privacidad y seguridad, utiliza cifrado AES-256 de grado militar y autenticación biométrica para proteger tus datos más importantes.

La aplicación está construida siguiendo los principios de **Clean Architecture**, garantizando código mantenible, escalable y testeable.

## ✨ Características Principales

### 🔐 Seguridad y Privacidad
- **Cifrado AES-256**: Todos los datos se cifran con el algoritmo AES-256
- **Autenticación Biométrica**: Acceso seguro mediante huella dactilar o reconocimiento facial
- **Almacenamiento Local**: Tus datos permanecen en tu dispositivo
- **Sin conexión a internet requerida**: Funciona completamente offline

### 🏗️ Arquitectura y Rendimiento
- **Clean Architecture**: Separación clara de responsabilidades en 3 capas
- **Repository Pattern**: Abstracción de fuentes de datos
- **Event-Driven**: Arquitectura basada en eventos para mejor escalabilidad
- **Offline-First**: Funcionalidad completa sin conexión a internet
- **Paginación Infinita**: Carga eficiente de grandes volúmenes de datos

### 📱 Funcionalidades
- **15+ Módulos**: Amplia gama de funcionalidades para gestión personal
- **Backup Automático**: Respaldo automático de tus datos
- **100% Null-Safe**: Código completamente seguro con null safety
- **Interfaz Moderna**: UI/UX intuitiva y responsive

## 🛠️ Stack Tecnológico

### Framework y Lenguaje
- **Flutter 3.8+**: Framework multiplataforma
- **Dart**: Lenguaje de programación con null safety completo

### Gestión de Estado
- **Riverpod**: Gestión de estado reactiva y type-safe

### Base de Datos
- **SQLite**: Base de datos local para almacenamiento persistente

### Seguridad
- **Biometric Auth**: Autenticación biométrica nativa
- **AES-256**: Cifrado de datos de grado militar

### Arquitectura
- **Clean Architecture**: Separación en capas (Domain, Data, Presentation)
- **Repository Pattern**: Abstracción de acceso a datos
- **Event-Driven Architecture**: Comunicación basada en eventos

## 📸 Capturas de Pantalla

<div align="center">

| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|![Screenshot 1](assets/images/memory-screenshot-1.jpg)|![Screenshot 2](assets/images/memory-screenshot-2.jpg)|![Screenshot 3](assets/images/memory-screenshot-3.jpg)|
|![Screenshot 4](assets/images/memory-screenshot-4.jpg)|![Screenshot 5](assets/images/memory-screenshot-5.jpg)|![Screenshot 6](assets/images/memory-screenshot-6.jpg)|
|![Screenshot 7](assets/images/memory-screenshot-7.jpg)|![Screenshot 8](assets/images/memory-screenshot-8.jpg)|![Screenshot 9](assets/images/memory-screenshot-9.jpg)|

</div>

## 📦 Instalación

### Requisitos Previos
- Dispositivo Android (versión mínima: Android 5.0 / API 21)
- Habilitar instalación desde fuentes desconocidas (si es necesario)

### Instalación del APK

**Opción 1: Desde GitHub Releases (Recomendado)**
1. Ve a la página de [Releases](https://github.com/BryanRF/memory-pub/releases/latest)
2. Descarga el archivo `memory-app.apk` desde la última release
3. Una vez descargado, abre el archivo en tu dispositivo Android

**Opción 2: Descarga Directa**
- Haz clic en el botón de descarga arriba para ir a la última release
- Descarga el archivo `memory-app.apk`
- Transfiere el archivo a tu dispositivo Android si lo descargaste en otro dispositivo

**Pasos de Instalación:**
1. Abre el archivo APK en tu dispositivo Android
2. Permite la instalación desde fuentes desconocidas si se solicita
3. Sigue las instrucciones de instalación
4. ¡Listo! Ya puedes usar MEMORY

### Primera Configuración

1. Abre la aplicación **MEMORY**
2. Configura tu autenticación biométrica cuando se solicite
3. Establece una contraseña maestra (si es requerida)
4. ¡Comienza a usar la aplicación!

## 🏛️ Arquitectura

La aplicación sigue los principios de **Clean Architecture**, organizando el código en tres capas principales:

```
┌─────────────────────────────────────┐
│      Presentation Layer             │
│  (UI, Widgets, State Management)    │
└─────────────────────────────────────┘
              ↕
┌─────────────────────────────────────┐
│        Domain Layer                  │
│  (Entities, Use Cases, Interfaces)  │
└─────────────────────────────────────┘
              ↕
┌─────────────────────────────────────┐
│         Data Layer                   │
│  (Repositories, Data Sources, API)   │
└─────────────────────────────────────┘
```

### Principios Aplicados

- **Separación de Responsabilidades**: Cada capa tiene una responsabilidad única
- **Independencia de Frameworks**: La lógica de negocio no depende de Flutter
- **Testabilidad**: Fácil de testear gracias a la inyección de dependencias
- **Independencia de UI**: La UI puede cambiar sin afectar la lógica de negocio
- **Independencia de Base de Datos**: El almacenamiento puede cambiar sin afectar otras capas

## 🔒 Seguridad

### Cifrado
- Todos los datos sensibles se cifran usando **AES-256** antes de almacerse
- Las claves de cifrado se gestionan de forma segura
- No se almacenan datos en texto plano

### Autenticación
- **Autenticación Biométrica**: Utiliza las capacidades nativas del dispositivo
- **Contraseña Maestra**: Opción adicional de seguridad
- **Sesiones Seguras**: Gestión segura de sesiones de usuario

### Privacidad
- **Sin Telemetría**: No se recopilan datos de uso
- **Sin Servidores Externos**: Todo funciona localmente
- **Control Total**: Tú tienes control completo sobre tus datos

## 📚 Módulos Disponibles

La aplicación incluye más de 15 módulos para diferentes necesidades de gestión personal:

- Gestión de contraseñas
- Notas seguras
- Documentos cifrados
- Contactos privados
- Calendario personal
- Tareas y recordatorios
- Y muchos más...

## 🚀 Características Técnicas

### Rendimiento
- **Carga Rápida**: Optimizado para tiempos de inicio mínimos
- **Paginación Infinita**: Manejo eficiente de grandes listas
- **Caché Inteligente**: Sistema de caché para mejor rendimiento

### Confiabilidad
- **Offline-First**: Funciona sin conexión a internet
- **Backup Automático**: Respaldo automático de datos
- **Recuperación de Datos**: Sistema robusto de recuperación

### Calidad de Código
- **100% Null-Safe**: Código completamente seguro
- **Clean Code**: Código limpio y mantenible
- **SOLID Principles**: Principios SOLID aplicados
- **Design Patterns**: Uso de patrones de diseño apropiados

## 📄 Licencia

Esta aplicación es **privada** y su código fuente no está disponible públicamente.

## 🤝 Contribuciones

Esta es una aplicación privada. Las contribuciones no están abiertas al público.

## 📞 Soporte

Para soporte o consultas sobre la aplicación, por favor contacta al desarrollador.

---

<div align="center">

**Desarrollado con ❤️ usando Flutter**

[![Flutter](https://img.shields.io/badge/Made%20with-Flutter-02569B?logo=flutter&logoColor=white)](https://flutter.dev)

</div>

