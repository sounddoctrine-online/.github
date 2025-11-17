<p align="center">
  <a href="https://apps.apple.com/in/app/sound-doctrine-online/id6443919279">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://storage.googleapis.com/sdo-public-assets/Text%20Logo.png">
      <img src="https://storage.googleapis.com/sdo-public-assets/Text%20Logo.png" height="128">
    </picture>
  </a>
  <h1 align="center">Sound Doctrine Online</h1>
</p>

<p align="center">
  <a href="https://sounddoctrine.online">Website</a> •
  <a href="https://apps.apple.com/in/app/sound-doctrine-online/id6443919279">iOS App</a> •
  <a href="http://sdo-keystone.onrender.com">Admin App</a>
</p>

---

## 📖 About

**Sound Doctrine Online (SDO)** is a video streaming platform that hosts non-charismatic, non-ecumenical, Independent Fundamental Baptist (IFB) preaching and congregational singing from around the world. Our goal is to make **hard preaching** accessible to a global audience — from documentaries to sermons, singing, and short clips.

This GitHub organization contains all the core repositories that power Sound Doctrine Online across platforms — mobile, web, and desktop.

---

## 🧱 Repositories

| Repository | Description |
|-----------|-------------|
| [**sdo-multiplatform**](https://github.com/sounddoctrine-online/sdo-multiplatform) | Kotlin Multiplatform app targeting Android, iOS, Desktop, and Web. |
| [**sdo-keystone**](https://github.com/sounddoctrine-online/sdo-keystone) | Admin content management app powered by Keystone JS. |
| [**sdo-firebase**](https://github.com/sounddoctrine-online/sdo-firebase) | Firebase configuration repository. |

<!--
| `sdo-backend` | (Private/internal) GraphQL backend, authentication, and media APIs. |
| `sdo-content-pipeline` | Tools and scripts for ingesting, processing, and uploading content. |
| `sdo-web` | Web frontend (if distinct from KMP WASM) or landing site for [sounddoctrine.online](https://sounddoctrine.online). |
| `sdo-media-hosting` | Static hosting scripts, CDN configuration, and asset storage automation. |
| `sdo-devops` | Infrastructure-as-code, CI/CD workflows, secrets, and environment provisioning (e.g., for Azure, Cloudflare, etc.). |
-->

> 🔒 Some repositories may be private/internal due to security and deployment concerns.

---

## 🚀 Featured App: sdo-multiplatform

The flagship cross-platform client for Sound Doctrine Online.

> 📍 See full README: [sdo-multiplatform/README.md]([https://github.com/sounddoctrine-online/sdo-multiplatform/blob/main/README.md](https://github.com/sounddoctrine-online/sdo-multiplatform/blob/main/README.md))

### Highlights
- Built using **Kotlin Multiplatform**
- iOS UI using **SwiftUI**
- Shared UI via **Compose Multiplatform** (planned)
- Native support for:
  - **Android**
  - **iOS (SwiftUI)**
  - **macOS/Windows/Linux (Desktop)**
  - **Web (Wasm)**

<p align="center">
  <a href="https://apps.apple.com/in/app/sound-doctrine-online/id6443919279">
    <img src="https://storage.googleapis.com/sdo-public-assets/Download_on_the_App_Store_Badge_US-UK_RGB_wht_092917.svg" height="48">
  </a>
</p>

---

## 🛠 Development Stack

- **Frontend:** Kotlin Multiplatform, Compose, SwiftUI
- **Backend:** GraphQL APIs (Hasura), Authentication (JWT)
- **Infrastructure:** Azure, Cloudflare, CI/CD pipelines
- **Tooling:** CodeQL, Gradle, Xcode, Docker

---

## 📚 Documentation

Each repository contains its own detailed documentation. Start with:
- [`sdo-multiplatform/README.md`](https://github.com/sound-doctrine-online/sdo-multiplatform/blob/main/README.md)
<!-- - Internal developer guides in the `sdo-devops` and `sdo-backend` repos (if access is available) -->

---

## 👥 Community & Contribution

At this time, contributions are limited to internal team members. For questions, feedback, or doctrinal clarity, visit [sounddoctrine.online](https://sounddoctrine.online) or contact us via the app.

---

## 🔐 Security & Doctrine Policy

Sound Doctrine Online is committed to maintaining both theological and digital integrity. All content is:
- **Doctrinally filtered** to align with **Independent Fundamental Baptist** teachings.

For inquiries related to doctrinal standards or content submissions, please use the contact form on our [website](https://sounddoctrine.online).

---

## 📦 Deployment

Apps are deployed via:
- **App Store:** [Sound Doctrine Online (iOS)](https://apps.apple.com/in/app/sound-doctrine-online/id6443919279)
- **Web:** [https://sounddoctrine.online](https://sounddoctrine.online)
- **Desktop:** macOS/Linux/Windows builds via `sdo-multiplatform`

CI/CD pipelines are managed via GitHub Actions (see `sdo-devops`).
