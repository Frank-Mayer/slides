# Game Engine

Frank Mayer

---

## Ziel

- Eigene Game Engine
- Golang
- Cross Plattform
- Texturen laden & rendern
- CI/CD einfach einzurichten
  - Einfaches Testing
  - Export kompatibel mit Steam
- Level Editor

---

## Warum?

- Kann ich es besser als etablierte Engines?
- Warum Go?

---

## Was ist ein Shader

- Programm für die GPU
- GLSL, ESSL, HLSL, MSL, ...
- Mehrere APIs für Betriebssysteme

---

## Was ist OpenGL, Vulkan, DirextX und Metal?

- Kein Programm/Software
- Hardware interface
- Standartisierung

---

## Schwierigkeiten

- OpenGL & Vulkan auf Mac
- Text rendern

---

## OpenGL auf Mac

- Deprecated (v4.1)
- Bugs in GLSL die nie gefixt werden

---

## Vulkan auf Mac

- MoltenVK als Zwischenlayer zu Metal
- XCode Projektstruktur

---

## Alternativen zu OpenGL, Vulkan, ...

- SDL
- raylib
- Dawn

---

## SDL (Simple DirectMedia Layer)

[libsdl.org](https://libsdl.org)

- C Library
- Zwischenlayer zu hardware APIs
- Low level API

---

## raylib

[raylib.com](https://www.raylib.com)

- C Library
- Zwischenlayer zu hardware APIs
- High level API

---

## Dawn

[dawn.googlesource.com/dawn](https://dawn.googlesource.com/dawn)

- Googles native WebGPU-Implementierung
- Zwischenlayer zu hardware **grafik** APIs
- [Tint](https://dawn.googlesource.com/tint) Compiler von und zu [WGSL](https://www.w3.org/TR/WGSL/)
- C++ Library

---

## Text rendern

---

## Live Demo

---

## Eigene Engine: Pro

- Individuelle Anpassung
- Optimierung
- Flexibilität
- Lernmöglichkeiten
- 3rd Party Engines veralten, Portierung in Zukunft wird erschwert

---

## Eigene Engine: Contra

- Zeitaufwand
- Kosten
- Aktualisierungen und Support
- Risiken

---

## Firmen mit eigener Engine für ihre Spiele

- **id Software** id Tech
- **CD Project Red** red
- **Massive Entertainment** Snowdrow
- **From Software** Dantelion (inoffiziell)
- **Riot Games**
- **Valve Corporation** Source
- **Epic Games** Unreal
- **Remedy** Northlight
- **Thekla**
- **Cry Tech** Cry Engine

---

![](./slides-qr.png)
