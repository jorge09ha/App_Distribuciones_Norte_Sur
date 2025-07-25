# App_Distribuciones_Norte_Sur

Aplicación móvil multiplataforma desarrollada en **React Native** para la gestión de paquetes en bodegas de distribución. Esta app permite registrar recepciones y entregas de paquetes, escanear códigos de barras o QR, operar sin conexión y sincronizar datos automáticamente al restablecer la red. 

## 🚚 Funcionalidades principales

- 📦 Registro de paquetes con datos como remitente, destinatario y estado.
- 📲 Escaneo de códigos de barras o QR mediante la cámara del dispositivo.
- 🔄 Modo offline: guarda operaciones localmente cuando no hay conexión.
- ☁️ Sincronización automática con Supabase al recuperar señal.
- 📊 Visualización de métricas (paquetes entregados, pendientes, totales).
- 🌐 Soporte multilenguaje (Español / Inglés).
- 🔒 Almacenamiento cifrado local con EncryptedStorage.
- 📡 Notificaciones sobre entregas y sincronizaciones exitosas.

## 🛠️ Tecnologías utilizadas

- **React Native** (Expo)
- **Supabase** (Auth, Database, Storage)
- **EncryptedStorage**
- **NetInfo**
- **react-native-chart-kit**
- **react-navigation**
- **i18next** para internacionalización

## 📦 Instalación del proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/App_Distribuciones_Norte_Sur.git
