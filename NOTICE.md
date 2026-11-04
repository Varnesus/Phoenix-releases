# Składniki innych autorów

Phoenix zawiera lub wgrywa na urządzenia poniższe składniki. Każdy podlega własnej licencji; zakaz kopiowania z `LICENSE` Phoenixa ich nie dotyczy.

| Składnik | Gdzie | Licencja |
|---|---|---|
| QMK Firmware (klawiatury OneHand L/R, uniwersalny firmware, kreator) | pliki `.uf2` klawiatur | GNU GPL (wersja 2 lub nowsza, zależnie od pliku) |
| ChibiOS/HAL, ChibiOS-Contrib (w QMK dla RP2040) | pliki `.uf2` klawiatur | Apache-2.0 / GPL (w ramach QMK) |
| Raspberry Pi Pico SDK | firmware huba (mikser), plik `.uf2` | BSD-3-Clause |
| TinyUSB | firmware huba | MIT |
| Electron i Chromium | aplikacja desktopowa | MIT oraz licencje Chromium (m.in. BSD-3-Clause) — pełna lista w pliku `LICENSES.chromium.html` dołączonym do Electrona |
| Protokół VIA | zgodność komunikacji z klawiaturami QMK/VIA | protokół jawny; Phoenix nie zawiera kodu aplikacji VIA |

## Źródła firmware (GPL)
Do każdego wydania dołączane jest archiwum `firmware-src-<wersja>.zip` ze źródłami firmware, który wgrywa Phoenix (klawiatury OneHand L/R, uniwersalny firmware, hub miksera). Kto otrzymał plik `.uf2`, może je pobrać z tej samej strony wydania.

## Narzędzia deweloperskie
Playwright (Apache-2.0) służy wyłącznie do testów i nie jest dołączany do wydań.
