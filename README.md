# VW_Micronas_24C32

> [!CAUTION]
> For educational purposes only. I'm not responsible for any damage. If You need assistance, feel free to open an issue. Other than that, You're on Your own.

# 1Z0 920 842D (Octavia 2 Pre Facelift)
> [!WARNING]
> Most of these values (if not all of them) won't work on older clusters (841)

|Address|Value|Description|Note|
|---|---|---|---|
| 0x50 - 0xA0  |   | Adaptation values - These can be set by diagnostic software | eg. 0x88 - Language - 08 - Czech, 09 - Chinese etc. |
| 0x145  |   |   |  You need to change 0x161 to 05 to see this |
|   | 01  | VW welcome logo (VW Information system)  |   |
||02|VW welcome logo (VW Information system)
||03|VW welcome logo (VW Information system)
||04|Skoda Logo (Welcome on board)
||05|Empty screen
||06|Empty screen
||07|VW welcome logo + Passat B6 Mode (Temp instead of ODO)| Passat B6 has two more displays, Left - Date + Time, Right - ODO + Trip
|0x161|||This works for B6 clusters aswell
||02|Default (Welcome logo disabled)
||05|Welcome logo enabled
