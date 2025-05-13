# Fortune Cookies VTEX IO App

Una aplicación personalizada para VTEX IO basada en el [store theme](https://github.com/vtex-apps/store-theme) que muestra una “galleta de la fortuna” con un mensaje aleatorio y un número de la suerte.

---

## 🚀 Características

- Animación de galleta al hacer clic
- Generación de número de la suerte con formato `XX-XX-XXXX`
- Estilos personalizados con CSS Modules

---
## Ver aplicación
Desde el workspace "romanchallenge" haciendo click en el link del header que dice Fortune Cookies
[Dirigirse al workspace romanchallenge](https://romanchallenge--valtech.myvtex.com/fortune-cookies)
---

## 📋 Estilos
Los estilos aplicados se encuentran dentro del archivo `valtech.roman-front-cookies.css`

## 📋 Requisitos

- Node.js ≥ 14
- VTEX Toolbelt (`vtex`)
- Acceso a un workspace en VTEX IO
- Master Data configurado con entidad `CF` y campo `CookieFortune`

---

## ⚙️ Instalación

1. Clona el repositorio:
- `git clone git@github.com:LuisguiRoman/vtex-store-theme.git`

---

## Enlaza tu app en un workspace de VTEX:
- `vtex login youraccount`
- `vtex use yourworkspace`
- `vtex link`

---

## Deploy
- `vtex publish`
- `vtex deploy vendor.appname@x.x.x`
- `vtex install vendor.appname@x.x.x`

