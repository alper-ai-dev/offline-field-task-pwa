# Fieldly — Offline Field Task PWA

An installable, mobile-first field operations task manager built as a portfolio project by Alper Sancar.

## What it demonstrates
- Progressive Web App architecture
- Installable app manifest
- Service Worker and offline asset caching
- Offline-first task creation and persistence
- Browser localStorage data layer
- Online/offline state detection
- Task completion and filtering
- Priority and location metadata
- Responsive mobile UI and bottom-sheet interaction
- XSS-safe task rendering

## Stack
HTML5, CSS3, Vanilla JavaScript, Web App Manifest, Service Worker API, Cache API, LocalStorage.

## Offline behavior
The application shell is cached by the Service Worker. Task data is stored locally in the browser, allowing task management without a network connection after the first successful load.

## Scope
Fieldly is a public portfolio demonstration. It does not claim cloud synchronization, multi-user accounts, GPS tracking or a production backend.

## Portfolio
Built by Alper Sancar to demonstrate mobile-first product design, PWA engineering and offline web application capabilities.