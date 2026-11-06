<div align="center">

# Server Profiles

**Different servers, different settings.**

`FABRIC` · `MINECRAFT 1.21.11` · `CLIENT-SIDE`

[Download](https://github.com/Vaileks/ServerProfiles/releases/latest) · [Report an issue](https://github.com/Vaileks/ServerProfiles/issues)

</div>

---

Server Profiles is a client-side Fabric mod by **Vaileks**.

## Features

- Keeps separate settings for this PvP mod series on each server.
- Separates single-player worlds too.
- Creates new profiles from your global defaults.

## Installation

1. Use **Minecraft Java 1.21.11**, **Fabric Loader 0.19.2+** and **Java 21+**.
2. Download `server-profiles-1.0.0+1.21.11.jar` from [Releases](https://github.com/Vaileks/ServerProfiles/releases/latest).
3. Put the JAR in your client `mods` folder and start the game.

No server installation or Fabric API is required. The shared runtime is already bundled in the JAR, so this mod can be installed on its own or alongside other mods in the series.

## Configuration

Press **F8** or use the mod's settings button in **Mod Menu**. Mod Menu is optional.

Adjust the available colors, thresholds and feature controls in the settings screen. HUD panels support scale, shadow, background, item names or icons, and mouse placement where applicable. Save changes with **Done / Готово**. The action key is unbound by default to avoid conflicts; assign one in **Functions / Функции**.

Settings are stored in `config/server_profiles.json`.

## Compatibility notes

Supports settings from this PvP mod series. It does not rewrite configuration files belonging to unrelated mods.

## Русский

Server Profiles разделяет настройки модов этой серии по серверам и одиночным мирам. Новые профили получают копию общих настроек.

Установка: Fabric **1.21.11**, Java **21+**. Поместите JAR в клиентскую папку `mods`. Настройки — **F8** или Mod Menu. Fabric API не требуется.

## Build

With JDK 21–25 and Python 3 installed:

```sh
./gradlew packageMods
```

Output: `dist/mods/server-profiles-1.0.0+1.21.11.jar`.

## License

[MIT](LICENSE).
