# Guía de Uso: PlayEpicGameInSteam.ps1

Este script de PowerShell permite utilizar la funcionalidad **Remote Play Together** de Steam con juegos de **Epic Games Store**.

## 🎯 ¿Para qué sirve?

Steam Remote Play Together normalmente solo funciona con juegos de Steam. Este script permite "engañar" al sistema lanzando el **Epic Games Launcher** a través de Steam, permitiendo así que invites a amigos a jugar a tus juegos de Epic (como si estuvieran sentados a tu lado) usando la infraestructura de streaming de Steam.

## ⚙️ Configuración

Antes de usar el script, debes configurar la ubicación de tu lanzador de Epic Games.

### 1. Ruta del Launcher (`$appBase`)
Abre el archivo `PlayEpicGameInSteam.ps1` con un editor de texto (o clic derecho > Editar) y busca la siguiente línea:

```powershell
$appBase = "C:\Program Files (x86)\Epic Games\Launcher\Portal\Binaries\Win32\EpicGamesLauncher.exe"
```

*   Debes modificar el valor entre comillas para que coincida con la ruta donde tienes instalado `EpicGamesLauncher.exe` en tu PC.
*   Si instalaste Epic Games en la ubicación por defecto, es probable que no necesites cambiar nada.

## 🚀 Cómo usarlo

https://www.youtube.com/

---
*Nota: Este método transmite la ventana del lanzador y posteriormente la del juego, permitiendo que el control remoto funcione sobre la aplicación de Epic.*
