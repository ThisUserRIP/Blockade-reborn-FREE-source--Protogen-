# 🛡️ Blockade Reborn FREE – Protogen

**Private Server + Client Pack** for **Blockade Classic** (Unity Mono, no IL2CPP / no EAC).

Prebuilt packages included: **server + client + free maps**.
Run your own private server locally or host it online for friends.

---

# 📦 Contents

## `game server/`

* `BlockadeServer.exe` — main game server
* `BlockadeMasterServer.exe` — master server
* `BlockadeProfileServer.exe` — profile/account server
* `itemdata/`
* `maptest.map`

## `x64mono/` (recommended)

* `BlockadeClassic.exe`
* `UnityPlayer.dll`
* `Assembly-CSharp.dll`
* `MonoBleedingEdge/`
* `BlockadeClassic_Data/`
* `AssetBundles/`

## `x86mono/`

32-bit version of the client (same structure as `x64mono/`).

## `free maps/`

* `ZACHISTKA_02_12_25_22_11_39.map`
* `ZB_oldmill.map`
* `maptest.map`

---

# 🛠️ Setup (no build required)

1. Clone the repository

```bash
git clone https://github.com/ThisUserRIP/Blockade-reborn-FREE-source--Protogen-.git
cd Blockade-reborn-FREE-source--Protogen-
```

2. Copy the **`x64mono`** folder — this will be your **client folder**.

3. Navigate to `game server/` and start the following:

```
BlockadeMasterServer.exe
BlockadeProfileServer.exe
BlockadeServer.exe
```

Order does **not** matter.

4. Launch the client:

```
x64mono/BlockadeClassic.exe
```

5. In-game connect to:

* `127.0.0.1` — for local server
* `YOUR_IP` — to allow friends to join

---

# 🗺️ Adding Maps

To install custom maps:

1. Copy `.map` files from `free maps/`
2. Paste them into either:

   * the **server map folder**, or
   * `BlockadeClassic_Data/`

Example maps included:

* `ZACHISTKA_02_12_25_22_11_39.map`
* `ZB_oldmill.map`
* `maptest.map`

---

# 🚀 How It Works

* Servers run as **separate executables**.
* The client **automatically connects** to the Master/Profile servers.
* Custom maps are loaded if `.map` files exist in the server directory.
* **No EAC** — runs on **pure Unity Mono**.

---

# ⚠️ Disclaimer

Use at your own risk.

The author (**ThisUserRIP**) is not responsible for:

* account bans
* data loss
* crashes
* legal consequences
* or any other issues

This project should be used **only in isolated testing environments** for **educational and research purposes**.
