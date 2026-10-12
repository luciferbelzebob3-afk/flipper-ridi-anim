# Flipper Zero Animations - Ridi + Dolphin

Všechny animace, které jsme dělali.

## Soubory v repo (base64):

| Soubor | Popis |
|--------|--------|
| **RidiAnim_slow.zip.b64** | Hlavní - zpomalená verze (frame rate 5) z tvých framů |
| **RidiAnim.zip.b64** | Původní rychlost (frame rate 7) |
| **CoolDolphin_anim.zip.b64** | Delfínek plavající |
| **DolphinRidi_anim.zip.b64** | Delfínek v autě (vymyšlená) |
| **Ridi_from_your_frames.zip.b64** | Verze z prvních framů |

## Jak dekódovat jakýkoliv .b64:

```bash
# stáhni
curl -L -o soubor.b64 https://raw.githubusercontent.com/luciferbelzebob3-afk/flipper-ridi-anim/main/SOUBOR.b64

# dekóduj
base64 -d soubor.b64 > soubor.zip
unzip soubor.zip
```

Pak složku nahraj do `/ext/dolphin/`.

**Repo:** https://github.com/luciferbelzebob3-afk/flipper-ridi-anim
