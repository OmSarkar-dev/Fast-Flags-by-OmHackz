# 🚀 Fast Flags by OmHackz

Boost your Roblox FPS and smooth out your gameplay with the best fast flags, hand-tuned by **OmHackz**.  
This setup is perfect for low-end PCs, laptops, or anyone trying to squeeze more performance out of Roblox.

---

## 🔧 What Are Fast Flags?

Fast Flags (also called FFlags) are hidden Roblox settings that control how the client behaves.  
Disabling or tweaking certain flags can:
- 🧠 Reduce lag
- 🖥️ Improve frame rates
- 🌀 Turn off unnecessary visuals

---

## 📦 Features

- ✅ Works on **Official Roblox Client** and **Bloxstrap**
- 🧪 Tested for **maximum FPS gain**
- 💻 Designed for **low-end and mid-end PCs**
- 🔒 Safe to use (no cheating, just optimization)

---

## ⚙️ How to Use

### 📁 Method 1: ClientSettings (Manual)

1. Open this folder: `C:\Users<YourName>\AppData\Local\Roblox\Versions<latest_version>\ClientSettings`

2. If `ClientSettings` doesn’t exist, create it.
   
3. Inside it, create a file named: `ClientAppSettings.json`

4. Paste the fast flags from this repo into the file.

5. Save the file and start Roblox.

---

### 🚀 Method 2: Bloxstrap (Recommended)

1. Open **Bloxstrap**

2. Go to **Settings → Fast Flags**

3. Enable **Fast Flag Overrides**

4. Paste the flags into the editor

5. Save and launch Roblox through Bloxstrap

---

## 📄 Fast Flags JSON

```json
{
  "FFlagHumanoidOnlySetCollisionsOnStateChangeDefaultIsEnabled": "False",
  "FFlagHumanoidParallelFasterSetCollision": "True",
  "DFIntNewRunningBaseGravityReductionFactorHundredth": "1500",
  "DFIntMaxAltitudePDStickHipHeightPercent": "0",
  "DFIntSolidFloorPercentForceApplication": "100",
  "FFlagDebugAdornsDisabled": "False",
  "DFIntNonSolidFloorPercentForceApplication": "100",
  "FFlagDebugSkyGray": "False",
  "FFlagDebugDontRenderUI": "False",
  "FFlagEnableCommandAutocomplete": "False",
  "FFlagEnableBubbleChatFromChatService": "False",
  "FFlagCoreGuiTypeSelfViewPresent": "False",
  "FIntFullscreenTitleBarTriggerDelayMillis": "100",
  "FIntFontSizePadding": "1",
  "FFlagTrackerLodControllerDebugUI": "False",
  "FFlagSoundsUsePhysicalVelocity": "True",
  "FFlagAdServiceEnabled": "False",
  "FFlagDebugDisableTelemetryEphemeralCounter": "True",
  "FFlagDebugDisableTelemetryEphemeralStat": "True",
  "FFlagDebugDisableTelemetryEventIngest": "True",
  "FFlagDebugDisableTelemetryPoint": "True",
  "FFlagDebugDisableTelemetryV2Counter": "True",
  "FFlagDebugDisableTelemetryV2Event": "True",
  "FFlagDebugDisableTelemetryV2Stat": "True",
  "DFIntTaskSchedulerTargetFps": "9999",
  "FIntScrollWheelDeltaAmount": "100",
  "DFIntMaxActiveAnimationTracks": "256",
  "FLogNetwork": "0",
  "FFlagHandleAltEnterFullscreenManually": "False",
  "FFlagDebugDisplayFPS": "True"
}


