# Bitácora

## Lección 0 — Entorno (2026-11-08)

**Resultado:** entorno instalado y comprobado en el portátil personal.

| Herramienta | Versión | Notas |
|---|---|---|
| Ubuntu | 22.04.5 LTS | Soporte estándar hasta abril 2027 |
| Git | 2.34.1 | |
| g++ | 11.4.0 | C++17 completo; C++20 casi completo (sin `std::format`) |
| CMake | 3.22.1 | Suficiente para GoogleTest vía FetchContent |
| Python | 3.10.12 | |
| VS Code | 1.145.2 | Instalado con snap `--classic` |
| Claude Code | 2.1.319 | Instalador nativo, sesión con suscripción individual |

**Decisiones:**
- Se mantiene Ubuntu 22.04 (no se actualiza a 24.04 por ahora). Si hace falta más C++20, se instala g++-13 en paralelo.
- Cuenta GitHub `falarconromerotrabajo`, plan Free, 2FA activo.
- Git: correo privado noreply de GitHub, rama por defecto `main`, editor `code --wait`.
- Autenticación con GitHub por clave SSH ed25519 con passphrase ("Portátil personal Ubuntu"); conexión verificada contrastando la huella del servidor.

**Pendiente:** primer commit de esta bitácora al crear el repositorio en la Lección 1.
