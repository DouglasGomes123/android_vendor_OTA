====================
     17-05-2019
====================

   * Ported Skulshady's "op3: Show battery icon in the QS header"
   * Switched to Olympian Kernel
   * Synced with Havoc upstream

====================
     16-05-2019
====================

   * Added kcal support (thx for NotesOfReality)
   * Added XiaomiParts
   * Under the hood tweaks in XiaomiParts
   * Ported Razziell's "init: clear and simplify init, remove hack for GSI" commit, which aims to bring stability
   * Synced with Havoc source: https://t.me/Havoc_OS/1024 and https://t.me/Havoc_OS/1064

====================
     12-05-2019
====================

   * device/xiaomi/markw/
87a51e0 Added maintainer name and removed hardware key backlight in Settings
203d0ab overlay: disable buttons lights (no hardware support)

   * frameworks/base/
fd9f34a0830 Revert "hwui: Enable quicksilver"
07523095420 base: SystemUI: fix themeing of notification shelf dot
fb5f843c261 Remove useless warning when dismissing notification
51c03601467 pocket: Use MD2 lock drawable
8506599337a KeyguardSliceView: Align as per the Clock Style
715da0ca193 base: Make FP detection in pocket mode configurable [1/2]
a99fb871186 Don't force show battery percentage while charging or powersave
ff1bbb393b8 Android Q text clock Portuguese translation

   * kernel/xiaomi/markw/
6ff91b5e026 Disable UserSpace & Conservative
52910bfc503 Add Usb Fast Charge

   * packages/apps/HavocSettings/
eda9d3d Settings: : Make FP detection in pocket mode configurable [2/2]

   * packages/apps/Settings/
c274d5ae0e Update Russian translations