# 💀 iGGAdPopupBlock

#### AD Blocker for [iGameGod](https://igamegod.app/) & [iOSGods App+](https://iosgods.com/topic/153130-introducing-igamegod-jailed-speed-manager-touch-recorder-cheat-engine-for-non-jailbroken-devices/#comment-4937789) Apps

A lightweight, sideload-safe companion dylib for jailed and sideloaded iOS devices to block iGameGod & iOSGods popup and interstitial ads (tested on iOS 27 Jailed) designed to block forced popup and interstitial ads in `iGameGod.framework`.

> **⚠️ CRITICAL — HOW TO ACTIVATE:** 
> **Zero ad blocking is active when you first launch the app.** 
> You **MUST take ONE in-app screenshot** after opening the game to arm and activate the ad blocker (`INST DONE`). Until you take that screenshot, ads will NOT be blocked.

## Features
- **Works with iOSGods App+, KSign, Feather & ESign:** Fully compatible with **iOSGods App+** custom dylib injection as well as local signers.
- **Sideload Safe:** Uses `@rpath/IGGAdPopupBlock.dylib` with zero hard dependencies on `CydiaSubstrate` or `libsubstrate`.
- **Zero UI Hang:** Main-queue execution keeps gameplay smooth and responsive.

## Quick Start
1. Download `IGGAdPopupBlock.dylib` from the [Releases](../../releases) page.
   - *Pro Tip for **iOSGods App+** users:* Rename `IGGAdPopupBlock.dylib` to any random name (e.g., `GameFix.dylib`) before injecting it via App+ Custom Dylibs so it can't be filename-filtered.
2. Inject `IGGAdPopupBlock.dylib` into your target IPA using **KSign**, **Feather**, **App+** or **ESign**.
3. Sign, install, and open the app.
4. Take **one screenshot** in-game to arm and complete hook activation (`INST DONE`).
