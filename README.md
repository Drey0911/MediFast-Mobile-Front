<p align="center">
  <img src="./img/logo-green.png" alt="MediFast logo" width="260"/>
</p>

<h1 align="center">MediFast · App móvil</h1>

<p align="center">
  App para consultar medicamentos y agendar su recolección en el dispensario.<br/>
  <sub>App to check medications and schedule their pickup at the dispensary.</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Android-3DDC84?style=flat&logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/type-Degree%20project-22C55E?style=flat" alt="Degree project"/>
  <img src="https://img.shields.io/badge/license-All%20rights%20reserved-6B7280?style=flat" alt="All rights reserved"/>
</p>

<p align="center">
  <a href="#español">Español</a> · <a href="#english">English</a> ·
  <a href="https://github.com/Drey0911/TG-MediFast-Dispensario-BACKEND">Backend</a>
</p>

## Tech stack

<p align="center">
  <img src="https://img.shields.io/badge/React%20Native-0.81-61DAFB?style=flat&logo=react&logoColor=black" alt="React Native 0.81"/>
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/React%20Navigation-7-6B52AE?style=flat" alt="React Navigation 7"/>
  <img src="https://img.shields.io/badge/Axios-HTTP-5A29E4?style=flat&logo=axios&logoColor=white" alt="Axios"/>
  <br/>
  <img src="https://img.shields.io/badge/Socket.IO-Realtime-010101?style=flat&logo=socketdotio&logoColor=white" alt="Socket.IO"/>
  <img src="https://img.shields.io/badge/AsyncStorage-Local-FF6B6B?style=flat" alt="AsyncStorage"/>
  <img src="https://img.shields.io/badge/JWT-Auth-000000?style=flat&logo=jsonwebtokens&logoColor=white" alt="JWT"/>
</p>

## Screenshots

<table>
  <tr>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project2/project2-1.png" alt="Login and sign up"/>
      <br/><b>Acceso · Sign in</b><br/><sub>Inicio de sesión y registro</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project2/project2-2.png" alt="Home and medications"/>
      <br/><b>Inicio y medicamentos · Home and medications</b><br/><sub>Módulos principales y catálogo con disponibilidad</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project2/project2-4.png" alt="Pickup package"/>
      <br/><b>Paquete de recolección · Pickup package</b><br/><sub>Stock por sede, cantidad, fecha y hora</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project2/project2-5.png" alt="Pickups and favorites"/>
      <br/><b>Recolecciones y favoritos · Pickups and favorites</b><br/><sub>Seguimiento de solicitudes y alertas</sub>
    </td>
  </tr>
</table>

---

## Español

> App móvil del proyecto de grado MediFast. Los usuarios consultan medicamentos, ven su disponibilidad por sede, arman un paquete y agendan la recolección. Los cambios llegan en tiempo real desde el [backend](https://github.com/Drey0911/TG-MediFast-Dispensario-BACKEND).

### Funcionalidades

| Área | Descripción |
|---|---|
| **Cuenta** | Registro, inicio de sesión y recuperación de contraseña. |
| **Medicamentos** | Listado, búsqueda y detalle con disponibilidad por sede. |
| **Recolecciones** | Paquete con varios medicamentos, fecha y hora; seguimiento y cancelación. |
| **Favoritos** | Alertas cuando un medicamento guardado vuelve a estar disponible. |
| **Historial y perfil** | Solicitudes anteriores y edición de datos personales. |
| **Chatbot (beta)** | `HomeScreenChatBot.tsx`: renómbrala a `HomeScreen` para usarla como pantalla principal. |

**Arquitectura MVP:** `models/` (datos), `views/` (componentes y pantallas) y `presenters/` (lógica y consumo de la API con Axios).

### Cómo ejecutarlo

1. Requisitos: **Node.js 18+**, JDK 17 y Android Studio.
2. Pon la URL del backend (local, ngrok o desplegado) en `config/apiBase.ts`.
3. Ejecuta:
   ```bash
   npm install
   npx react-native start
   npx react-native run-android
   ```

> [!TIP]
> Para generar el APK: `cd android && ./gradlew assembleRelease` (en Windows `gradlew assembleRelease`). Queda en `android/app/build/outputs/apk/release/`. Necesitas un keystore configurado en `~/.gradle/gradle.properties`.

---

## English

> Mobile app for the MediFast degree project. Users browse medications, check availability per branch, build a package and schedule its pickup. Changes arrive in real time from the [backend](https://github.com/Drey0911/TG-MediFast-Dispensario-BACKEND).

### Features

| Area | Description |
|---|---|
| **Account** | Sign up, sign in and password recovery. |
| **Medications** | List, search and details with availability per branch. |
| **Pickups** | Package with several medications, date and time; tracking and cancellation. |
| **Favorites** | Alerts when a saved medication is available again. |
| **History and profile** | Past requests and personal data editing. |
| **Chatbot (beta)** | `HomeScreenChatBot.tsx`: rename it to `HomeScreen` to use it as the main screen. |

**MVP architecture:** `models/` (data), `views/` (components and screens) and `presenters/` (logic and API calls with Axios).

### Getting started

1. Requirements: **Node.js 18+**, JDK 17 and Android Studio.
2. Set the backend URL (local, ngrok or deployed) in `config/apiBase.ts`.
3. Run:
   ```bash
   npm install
   npx react-native start
   npx react-native run-android
   ```

> [!TIP]
> To build the APK: `cd android && ./gradlew assembleRelease` (on Windows `gradlew assembleRelease`). It is saved in `android/app/build/outputs/apk/release/`. You need a keystore set in `~/.gradle/gradle.properties`.

---

## Licencia · License

Todos los derechos reservados · All rights reserved. © 2025 Andrey Stteven Mantilla Leon y Daniel Esteban Pinzon Cardenas. No puede ser reproducido, distribuido o utilizado sin autorización expresa · It may not be reproduced, distributed or used without express permission.
