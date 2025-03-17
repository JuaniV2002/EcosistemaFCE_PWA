# Ecosistema FCE: Moodle PWA

Este repositorio contiene la implementación de una **Progressive Web App (PWA)** para la instancia de Moodle de **v.eco.unrc.edu.ar**. El objetivo es mejorar la experiencia de usuario en Moodle permitiendo la instalación como aplicación, pantalla de inicio personalizada y mejor soporte para dispositivos móviles.

## Características

- UI/UX optimizada para PWA en escritorio y móvil.
- Atajos: mantén presionado el ícono de la app (Android y Windows) para tener rápido acceso a funcionalidades básicas de la PWA.
- Iconos estándar y **maskable** para Android e iOS.
- Splash screens para iOS mediante etiquetas `<meta>` (para apps añadidas desde Safari).
- Capturas de pantalla del funcionamiento de la app en varios dispositivos (iOS y Android), para permitir una UI de instalación más completa.

## Sitio en vivo

Puedes probar la PWA en el sitio de Moodle aquí:

[https://v.eco.unrc.edu.ar/](https://v.eco.unrc.edu.ar/)

## Capturas de pantalla

| Móvil | Escritorio |
|-------|------------|
| ![Captura Móvil](screenshots/screenshot-mobile-login.png) | ![Captura Escritorio](screenshots/screenshot-desktop-login.png) |
| ![Captura Móvil](screenshots/screenshot-mobile-dashboard.png) | ![Captura Escritorio](screenshots/screenshot-desktop-dashboard.png) |
| ![Captura Móvil](screenshots/screenshot-mobile-profile.png) | ![Captura Escritorio](screenshots/screenshot-desktop-profile.png) |
| ![Captura Móvil](screenshots/screenshot-mobile-courses.png) | ![Captura Escritorio](screenshots/screenshot-desktop-courses.png) |

## Recursos

- Guía de PWAs: [https://web.dev/progressive-web-apps/](https://web.dev/progressive-web-apps/).
- Documentación oficial de Moodle: [https://docs.moodle.org/](https://docs.moodle.org/).

## Notas

La PWA fue probada en los siguientes sistemas operativos:
  - macOS: Safari, navegadores basados en Chromium, Firefox.
  - Windows: navegadores basados en Chromium, Firefox.
  - iOS: Safari, navegadores basados en Chromium, Firefox.
  - Android: navegadores basados en Chromium, Firefox.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.
