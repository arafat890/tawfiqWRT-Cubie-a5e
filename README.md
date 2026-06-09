# OpenWrt for Radxa Cubie A5E

iStore OS-style OpenWrt build for **Radxa Cubie A5E** (Allwinner A527, arm64)  
Built automatically via **GitHub Actions** — no local Linux machine needed.

## Features

| Feature | Status |
|---|---|
| LuCI Web UI | ✅ |
| Argon Theme (iStore-style) | ✅ |
| iStore App Store | ✅ |
| Docker | ✅ |
| Dual Gigabit Ethernet | ✅ |
| WiFi | ❌ (driver নেই) |

## How to Build

1. এই repo **Fork** করুন
2. GitHub repo-র **Settings → Actions → General** এ যান
3. "Read and write permissions" enable করুন
4. **Actions** tab-এ যান → "Build OpenWrt for Cubie A5e" → **Run workflow**
5. Build শেষে **Releases** থেকে firmware download করুন

## Flash করার নিয়ম

### SD Card
1. PhoenixCard download করুন
2. `.img` file select করুন → SD card flash করুন

### eMMC / SPI Flash
1. PhoenixSuit download করুন
2. Board কে download mode-এ রাখুন → flash করুন

## Default Login

| Setting | Value |
|---|---|
| IP | `192.168.1.1` |
| Username | `root` |
| Password | `password` |

> **Note:** এটি unofficial build। WiFi কাজ করে না, শুধু wired Ethernet কাজ করবে।
