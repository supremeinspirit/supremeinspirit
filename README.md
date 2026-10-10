# supremeinspirit repo

APT repo for jailbreak package managers (Sileo, Zebra, Cydia).

Add this source:

    https://supremeinspirit.github.io/supremeinspirit/

| Package | Version | For |
| --- | --- | --- |
| Liquid (Gl)ass Reworked fixes (`com.supremeinspirit.liquidassreworked`) | 4~test29 (**Control Center sliders, Focus, call waves**; new in test29: the white fill of a Control Center slider keeps its round ends while the slider module opens and closes, and the expanded sliders have no line at the top left. Since test23: the Control Center Focus module shows its glyph without a round background. Since test22 on iOS 17: yellow sun and blue speaker on the Control Center sliders, no white circle on an active Focus, no dark box behind the audio waves in the Dynamic Island during a call. The call fix is the new library `LiquidAssFixCall` for InCallService: if Choicy blocks InCallService, allow it there and respring. As before: liquid glass on the text loupe and on search fields / Safari's address bar; "Clear Camera Pill" also clears the resting Dynamic Island, and the island's glass opens and closes without flicker; patch package, install the original `dylv.liquidass` 0.1.1-2b by dylv first, it is not in this repo) | rootless, iOS 15 and later, arm64 |
| Liquid (Gl)ass Reworked (`dylv.liquidass`) | 0.1.1-2b+ios13.17 | rootful (iphoneos-arm), iOS 13 port, the whole tweak |
| HIPCharge (`com.supremeinspirit.hipcharge`) | 1.6.1 | rootless (iphoneos-arm64) and rootful legacy (iphoneos-arm) |
| BegoneCIA Reworked (`com.supremeinspirit.begonecia`) | 1.2.0 | rootless (iphoneos-arm64, iOS 15 and later) and rootful legacy (iphoneos-arm, iOS 13 and 14) |

The Liquid (Gl)ass packages are the same two files as in the release v3 test29; older builds are no longer offered. Releases: [LiquidGlass-Reworked](https://github.com/supremeinspirit/LiquidGlass-Reworked/releases), [HIPCharge](https://github.com/supremeinspirit/HIPCharge/releases), [BegoneCIA Reworked](https://github.com/supremeinspirit/BegoneCIA-Reworked/releases).
