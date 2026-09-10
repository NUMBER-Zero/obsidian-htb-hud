# HTB HUD Theme for Obsidian

**Author:** DR4V3N1X (Yahya Ouarrak)  
**Version:** 1.1.0  

A meticulously crafted, ultra-high-quality Cyberpunk and "Hack The Box" inspired HUD theme for Obsidian. Designed with absolutely **zero UI/UX error tolerances**, this theme transforms your Obsidian vault into a sleek, professional, high-tech terminal environment without sacrificing readability or daily usability.

---

## 🎯 Core Features

### 💻 Deep System Overhaul
- **Hardware Control Aesthetics:** Toggle switches, sliders, and dropdown menus have been entirely rebuilt to look like physical hardware readouts and terminal selects.
- **BIOS-Style Settings:** The Obsidian settings menu has been re-skinned to resemble an old-school mainframe configuration panel.
- **System Alerts:** Callouts (`> [!danger]`, `> [!info]`) and native Obsidian toast notifications slide in and flash like critical system alerts.

### ⚡ Interactive HUD Effects
- **Targeting Crosshair:** The standard mouse pointer is replaced with a precise HUD crosshair.
- **Cyber-Glitch Links:** Hovering over an internal note link triggers a lightning-fast (0.25s) Red/Blue channel shift glitch before settling into a glowing highlight.
- **Image Reticles:** Hovering over any image in your vault snaps it into a glowing targeting reticle (sharp corner clip-paths).
- **Modal Boot-ups:** Opening the Command Palette (`Ctrl+P`) or any prompt triggers a rapid un-blur and scale "boot up" animation.
- **Command Targeting:** Selecting a command in the palette locks onto it with glowing neon `[ ]` brackets.

### 📂 Advanced Workspace UI
- **Active Line Focus:** The exact line you are typing on receives a faint, distraction-free glowing background to keep your eyes locked on your work.
- **Secure Data Embeds:** Embedded notes (`![[Note]]`) are styled as "Secure Data Containers" with dedicated technical borders and "SECURE LINK" badges.
- **Mainframe Tables:** Standard markdown tables are upgraded into live data grids with glowing green headers and hover-row tracking.
- **Laser Folder Indents:** The file explorer features dashed green indent lines and glowing collapse arrows for perfect visual hierarchy.
- **Ambient Standby Mode:** When all notes are closed, a faint, animated CSS radar and a glitching `STANDBY MODE` readout run quietly in the absolute bottom-right corner of your screen so it never blocks your core Obsidian buttons.

---

## ⚙️ Customization (Style Settings Plugin)

This theme natively supports the **[Style Settings](https://github.com/mgmeyers/obsidian-style-settings)** plugin. It is highly recommended that you install it to unlock full control over the HUD.

Once installed, go to **Settings > Style Settings > HTB HUD Theme Configuration** to tweak:
1. **Core Theme Colors:** Swap out the default Hacker Green for any custom hex color. Adjust the deep and mid-level background colors.
2. **Heading Colors:** Customize the specific neon colors for H1 through H6 tags.
3. **Glow & Opacity:** Fine-tune the intensity of the HUD drop-shadows and hover glows.
4. **Extra Sick Features (Toggles):**
   - Toggle **CRT Scanlines & Flicker** on/off.
   - Toggle **Sharp Corners (HUD Style)** on/off (strips all border-radius from the app).
   - Toggle the **HUD Crosshair Cursor** on/off.
   - Toggle **HUD Data Tooltips** on/off (turns hover tooltips into sharp neon data readouts).

---

## 📥 Installation

Currently, this theme is installed manually.

1. Download the `HTB HUD` folder containing `theme.css` and `manifest.json`.
2. Open your Obsidian Vault on your computer.
3. Navigate to the hidden `.obsidian/themes/` folder. (If the `themes` folder doesn't exist, create it).
4. Drop the entire `HTB HUD` folder inside.
5. Restart Obsidian, go to **Settings > Appearance**, and select **HTB HUD** from the Themes dropdown.

---

*“No errors or mistakes tolerated. Built for maximum efficiency.”* - DR4V3N1X
