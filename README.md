<h1 align="center">Obvious Recipes</h1>
<p align="center"><img src="https://raw.githubusercontent.com/0xFOSSMan/obvious-recipes/main/logo.png" width="220" alt="Obvious Recipes logo" /></p>

<p align="center">
  <img alt="Minecraft" src="https://img.shields.io/badge/Minecraft-26.3-2ea043" />
  <img alt="Loader" src="https://img.shields.io/badge/Loader-Fabric-db4c3f" />
  <img alt="Java" src="https://img.shields.io/badge/Java-25-blue" />
  <a href="https://github.com/0xFOSSMan/obvious-recipes-fabric-26.3/actions/workflows/gradle.yml"><img alt="Build" src="https://github.com/0xFOSSMan/obvious-recipes-fabric-26.3/actions/workflows/gradle.yml/badge.svg?branch=main" /></a>
  <a href="https://github.com/0xFOSSMan/obvious-recipes-fabric-26.3/actions/workflows/super-linter.yml"><img alt="Lint" src="https://github.com/0xFOSSMan/obvious-recipes-fabric-26.3/actions/workflows/super-linter.yml/badge.svg?branch=main" /></a>
</p>

Obvious Recipes ist ein **Fabric-Mod für Minecraft 26.3** und bringt weiterhin "offensichtliche" Crafting- und Smelting-Rezepte ins Spiel.

## Features

- Zusätzliche Crafting-Rezepte (z. B. Sattel, Pferderüstungen, Nametag).
- Recycling-Rezepte für Leder- und Holz-Items.
- Zusätzliche Ofenrezepte (z. B. Rotten Flesh -> Leather, Metall-Recycling).

## Entwicklung

### Voraussetzungen

- JDK 25
- Gradle 9.9.2

Da der Mod nur Rezeptressourcen und keine Minecraft-Klassen enthält, wird er direkt gegen Fabric Loader gebaut; für Minecraft 26.3 sind keine Yarn- oder Mojang-Mappings verfügbar.

### Build

```bash
gradle build
```

### Linting & Formatierung

```bash
gradle spotlessCheck
gradle spotlessApply
```

## Lizenz

GPL-3.0
