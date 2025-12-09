# Cutscene-Fix-for-Obscure-The-Aftermath
This is a set of fixes distributed as a precompiled save state for newer versions of PPSSPP.   The game started to break from PPSSPP version 1.11.3 and above, causing issues such as broken cutscenes and timing problems.   This save state restores proper behavior and makes the game playable again on modern builds of the emulator.

## ***📦 Simplified Installation***

- I simplified the installation and use of my modifications into a single **precompiled Save State**.
- You only need to place it in the **Save States** folder of your emulator.


**Before Fix (PPSSPP without Fixes)**  
![aefl7q](https://github.com/user-attachments/assets/36642609-78af-4c3d-a18f-fb927951d13e)

**After Fix (PPSSPP with Save State Fix)**  
![aeflb7](https://github.com/user-attachments/assets/204a5b73-d161-4ba1-862f-2c3f1a189b41)
---

## ***⚠️ Important Warning***

- **NEVER overwrite this Save State**, or the modifications will be lost.
- If that happens, you will need to add it again to your Save States folder.

---

## ***⚙️ Configuration Recommendations***

- It is recommended to use the **OpenGL** renderer in the emulator.

### ***Why OpenGL?***

- With **Vulkan**, this game shows strange behavior: the emulator may show **60 FPS**, but the real frames reaching your screen stay around **40 ~ 55 FPS**.
- When set to **30 FPS**, the real output usually stays around **27 ~ 28 FPS**.

- With **DirectX 9, 11 and 12**, this issue usually does not happen on **Windows**, but it appears frequently on **Linux** and **Android**.

- On **iOS**, this problem most likely does not happen because **Vulkan** is not fully implemented. The system uses **Metal** as the base, which results in more stable behavior.

---

## ***🧠 Extra Important Configuration***

- Go to the game settings and set the **emulated CPU speed to 1000%**.
- To do this, open the **System** tab in your emulator settings.

---

## ***❓ Frequently Asked Questions***

### ***Is the Save State compatible with multiplayer?***

- Yes, it is **fully compatible with multiplayer** and there are **no limits** for multiplayer mode.

---

## ***🖥️ How to Enable 120 FPS (or more)***

- Go to the emulator settings:  
  **Tools → Developer Tools → Graphics**

- Look for the option **“Display refresh rate”**.
- It is usually set to **60Hz** — just change it to **120Hz** or any value you want.

---

## ***⚡ High FPS: Pros and Cons***

### ***Advantages ✅***

- Reduces **ping** and delay between players in multiplayer.
- Fixes the issue of **damage not being calculated correctly**.
- The game responds better in **Quick Time Events**.
- Events that require spinning the analog stick become faster and more accurate.

### ***Why does this happen?***

- The original versions (**Wii, PC and PS2**) had no FPS cap.
- The **PSP** version had an FPS cap, which caused several calculation problems in gameplay.

### ***Disadvantages ⚠️***

- The game can become slightly harder against the **harpies**, as they start attacking faster.
- This happens because their speed was reduced in the **PSP** version to match the capped FPS, and unlocking the FPS breaks their damage balance.

---

## ***🎯 Recommended FPS***

- **30 to 120 FPS** → Excellent experience ✅
- **120 to 220 FPS** → *Casual speedrun* and better **VR** experience 🥽
- **Above that** → Considered overkill ⚠️

---

## ***💬 extra message from brokenzinhu***

I think that’s everything I have to say about the game.  
I hope my modifications and fixes help you.

**Have a great Christmas 🎄**  
**And may you achieve many victories on the battlefield! ⚔️**
