![preview](https://raw.githubusercontent.com/QQ0303/IRON-NEST-Overwatch/main/card_5b05.svg)
[![Download](https://raw.githubusercontent.com/QQ0303/IRON-NEST-Overwatch/main/start_c94bce4.svg)](https://QQ0303.github.io/IRON-NEST-Overwatch/)

# IRON-NEST-STRIKE-COMMANDER ⚙️🛰️

**Orbital Artillery Tactical Trainer & Co-pilot Suite** — a desktop companion for simulated long-range kinetic strike systems. This project transforms your PC into a precision gunnery operations center, featuring dynamic range-finding assistance, automatic ballistic solution plotting, unlimited ordnance reserves for training, access to 30 distinct warhead configurations and 15 theater command zones, auditory safety mode (preventing noise-induced crew fatigue), and a fully unshackled camera for 360° battlefield observation. With 55+ integrated practice drills.

---

## 🎯 Why This Exists

Every marksman knows the difference between *aiming* and *calculating*. This trainer bridges that gap. Instead of relying on gut feeling or repeated trial-and-error, this system introduces a **live fire-control feedback loop** that teaches the operator *why* certain adjustments work. Whether you're honing reaction speed, mastering map layouts, or fine-tuning your crew's voice discipline, this tool acts as your silent range officer.

It’s built for the curious tinkerer, the competitive tactician, and the simulation enthusiast who wants to *feel* the math of a 120mm shell before it screams downrange.

---

## 📦 Core Capabilities

### 🎯 Auto-Solution Fire Control
- **Dynamic Lead Calculator**: Continuously adjusts for target velocity, wind drift, and projectile drop across 4,000m+ engagement envelopes.
- **Trajectory Projection Overlay**: Displays a translucent ballistic arc directly on your tactical display—no more guessing where the round lands.
- **Zeroing Assist**: Perfect for learning how to compensate for culvert elevation, temperature, and barrel wear.

### ⚡️ Instant Traverse & Servo Response
- **Zero-Delay Rotation**: Removes artificial turret traversal delays, allowing you to practice snap-to-target drills at maximum mechanical speed.
- **Reverse Gear Racing**: Flip your chassis 180° in milliseconds—perfect for ambush scenarios.

### ♾️ Unlimited Ordnance Reserve
- **Training AMMO Pool**: No more running dry after a sharp engagement. Fire as much as you need to learn the rhythm of your specific gun system.
- **Sustained Fire Drill Mode**: Keep the barrel hot to practice reload sequencing under stress.

### 🧰 Ordnance Arsenal & Theater Access
| Feature | Details |
|---------|---------|
| ⚔️ **30 Warhead Types** | From high-explosive fragmentation to hardened-piercing sabot rounds, each with distinct velocity and drop characteristics. |
| 🗺️ **15 Command Sectors** | Access every locked terrain theater—from frozen tundra to urban canyon grids—for endless scenario variety. |
| 🔊 **Auditory Safety (No-Crew-Trauma Mode)** | Replaces ear-splitting gun reports with a subtle low-frequency thump, protecting your real-world hearing while retaining aural feedback cues. |
| 🎥 **Free-Drift Camera** | Detach the camera from the turret sight. Fly anywhere around the map to inspect enemy approaches, spot tracers, or review your shot placement from a bird’s-eye perspective. |

### 🛠️ 55+ Tactical Micro-Drills
- Crosshair hold and micro-flick practice
- Moving-target tracking (looping or spiral paths)
- Terrain-masking (shoot between hills without exposing hull)
- Rapid sector scanning (find and lock targets inside 3 seconds)
- Ammo-cycle memory test (which shell for which target type)

---

## 🚀 Quick Start (5-Minute Setup)

1. **Extract the Suite** — Pull the archive into your games root directory (e.g., `E:\Simulation\HeavyArmor\`).
2. **Run the Loader** — Execute the `Aegis_Loader.exe` application. It will automatically detect the simulator version and ask for permission to apply the co-pilot overlay.
3. **Select Your Profile** — Use the pre-configured "Cadet", "Observer", or "Gunslinger" presets. Or manually tweak every parameter via the side panel.
4. **Hit the Range** — Launch your preferred armored vehicle simulation mission. The overlay will appear as a low-opacity HUD you can toggle with `F10`.

> **Note for Multiplayer**: This tool is strictly for *practice and observation*. It does not modify the game server or give an unfair edge in ranked lobbies—it enhances your local training environment.

---

## 🖥️ Responsive UI & Accessibility

The interface scales gracefully from 1920×1080 to 4K UHD. Buttons are large enough for glove-friendly clicking. All critical data is color-coded (green = locked, red = muzzle velocity warning, amber = target obscured). The HUD supports **11 languages** including English, German, Russian, Simplified Chinese, Japanese, Korean, French, Spanish, Portuguese, Polish, and Turkish.

Multilingual support is *not* an afterthought—it’s baked into every tooltip. Switch languages on the fly via the small globe icon in the top-right corner.

---

## ⏰ 24/7 Crew Support (Human & Bot)

- **Live Troubleshooting Wiki** — A constantly updated knowledge base covers common pitfalls (e.g., "Why did my overlay disappear after the v2.3 patch?")
- **Discord Relay** — Join the `#range-officer` channel for real-time help from veteran users.
- **Email Ticketing** — We respond within 6 business hours, usually faster.

---

## 📸 Aesthetic & Presentation

The suite adopts a **sleek military-industrial blueprint** aesthetic: dark titanium grays, amber highlight accents, and thin vector lines mimicking radar sweeps. All icons are monochrome and customizable via a CSS-like theme file.

---

## ⚖️ Licensing

This project is released under the **MIT License**. You are free to modify, distribute, and use the code for commercial or personal projects, provided you retain the original copyright notice.

A copy of the license is included in the repository root. View the full text here: [MIT License](LICENSE)

---

## 🚨 Disclaimer

This software is a *training aid* and a *local visualization tool*. It is **not** intended to modify online multiplayer sessions, cheat in ranked competitive play, or interfere with third-party software licenses. Any use that violates the terms of service of the host simulation game is strictly prohibited.

The author(s) are not responsible for any action taken against your account due to misuse of this tool outside of its documented single-player/sandbox context. By using this tool, you agree that you are solely responsible for understanding the rules of your chosen simulation environment.

This project is provided "as is" without warranty of any kind, express or implied. You assume all risk for using it.

---

## 🧠 Development Roadmap (2026)

- **Q1 2026** — Add AI-assisted target prioritization (the system suggests the best shell type based on distance and armor angle).
- **Q2 2026** — Full VR headset support for a 1:1 cockpit experience.
- **Q3 2026** — Import custom firing tables from `.csv` files for ultra-specific gun systems.
- **Q4 2026** — Implement a replay/telemetry exporter that generates a `.kml` file of your firing positions for external analysis.

---

## 🤝 Contributing

We welcome pull requests! The codebase is modular and heavily commented. New features, transliteration files, or thematic skin packs are all accepted. Please keep the code style consistent (2-space indentation, no semicolons—we use ASI).

Before submitting, test your changes against the "Sandbox" mode (a non-vehicle test environment) to ensure nothing breaks the core rendering loop.

---

## 🔗 Related Tools & Inspirations

Looking for other tactical utilities? Check the `docs/` folder for a comparison chart between traditional rangefinders and this dynamic-scope system.

---

## 💡 Final Words

The iron nest is quiet. The wind whispers. The sight picture is clear. You don't need to *see* the future—you just need to *calculate* it faster than the enemy can react. This trainer is your abacus, your slide rule, and your silent instructor all in one.

Pull the charging handle. Let the gas ring recoil. Aim with your mind.

**— The Range Officer**