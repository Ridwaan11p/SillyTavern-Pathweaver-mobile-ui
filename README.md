# 🧭 Pathweaver for SillyTavern

> **Never get stuck again. Let AI weave the next strand of your story.**

## 🆕 What's New

### ***ver 1.0.0***
- **Initial Release!**
- **Action Bar**: Sleek, glass-morphism UI that sits right where you need it.
- **Director Mode**: Take control. Tell Pathweaver exactly what you want (e.g., "A sudden betrayal. A knife fight ensues!"), and it will generate specific options.
- **Genre & Custom Dropdowns**: Dedicated, icon-rich menus for suggestions -- Context-Aware, Plot-Twist, New Character, Explicit, and Genre-specific, plus, create your own custom styles.
- **Mobile Optimized**: Fully responsive design that works perfectly on phones and tablets.

![Version](https://img.shields.io/badge/SillyTavern-v1.12%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

**Pathweaver** is a creative companion extension for [SillyTavern](https://github.com/SillyTavern/SillyTavern). It analyzes your current chat context and generates Suggestions — options for where the story could go next. Whether you need a sudden plot twist, a new character introduction, or just a little nudge to break writer's block, Pathweaver provides up to 6 distinctive suggestions for every request.

<p align="center">
  <img src="https://placeholder.com/pathweaver-hero.png" alt="Pathweaver Hero" width="100%">
  <br>
  <sub><em>The Pathweaver bar suggests next steps, twists, and character beats instantly</em></sub>
</p>

---

## ✨ Feature Highlights

| Feature | Description |
|---------|-------------|
| 🧭 **Context-Aware** | Analyzes the last 2 to 10 messages to suggest logical, coherent continuations |
| 🎬 **Director Mode** | You're the boss. Single Scene or Story Beat - input short directions to tailor your own suggestions |
| 🎭 **Genre Packs** | Specialized suggestions for Horror, Romance, Sci-Fi, Comedy, Fantasy, and more |
| 🔌 **Easy Connect** | Use your existing SillyTavern API connection, Connection Profiles, Ollama, or custom OpenAI-compatible endpoints |
| 📱 **Mobile Ready** | Smart responsive design that consolidates buttons into touch-friendly dropdowns on small screens |
| ✏️ **Custom Styles** | Create your own suggestion presets (e.g., "Emo", "Fluffcore", "Manga") |
| 🧩 **Seamless UI** | Integrated "Glass" design that looks like a native part of SillyTavern |

---

## 🎮 How It Works

Pathweaver adds a **Control Bar** above your chat input. Click any button to instantly generate up to 6 suggestions.

### The Categories

| Icon | Category | Usage |
|------|----------|-------|
| 🎬 | **Director** | Opens a simplified input box. You type a prompt, AI gives you tailored suggestions. |
| 🧭 | **Context-Aware** | "What happens next?" Smart suggestions based on story logic and context. |
| 🔀 | **Twist** | Throws a curveball. Unexpected events, betrayals, and shocks. |
| 👤+ | **New Character** | Adds a new character to the story based on a variety of character tropes. |
| 🔥 | **Explicit** | (Optional) NSFW Spicy suggestions. Only one hand needed. |
| 🎭 | **Genres** | A dropdown menu with specific genre flavors: Horror, Romance, Sci-Fi, etc. |
| 📚 | **Custom** | Your own saved styles appear here (e.g., specific lore prompts). |

<p align="center">
  <img src="https://placeholder.com/pathweaver-modal.png" alt="Pathweaver Suggestions" width="700">
  <br>
  <sub><em>Click a suggestion to instantly insert it into the chat input or copy it to clipboard</em></sub>
</p>

---

## 🛠️ Installation

1. Open SillyTavern and click the **Extensions** button (puzzle piece icon)
2. Select **Install Extension**
3. Paste this URL:
   ```
   https://github.com/mattjaybe/SillyTavern-Pathweaver
   ```
4. Click **Install** and refresh SillyTavern

---

## ⚙️ Configuration

Access Pathweaver settings by clicking the ⚙️ gear icon on the right side of the Pathweaver bar or in SillyTavern's extension menu.

### Generation Engine

| Engine | Description |
|--------|-------------|
| **Main (API)** | Uses your currently active SillyTavern API (Recommended). Easiest setup. |
| **Connection Profile** ⭐ | Recommended. Select a Connection Profile saved in SillyTavern. |
| **Ollama** | Connect directly to a local Ollama instance (default: `http://127.0.0.1:11434`). |
| **OpenAI Compatible** | Connect to KoboldCPP, LM Studio, vLLM, or other OpenAI-compatible endpoints. |

### Visual Settings

- **Show Explicit**: Toggle the visibility of the "Explicit" (Fire icon) category.
- **Button Size**: Compact, Default, or Max.
- **Font Size**: Adjust the size of the text from Small, Default, or Large.
- **Minimal Mode**: Arrow on the bar collapses the bar into a small pill when not in use.

---

## 🌟 Extras

### 🎨 EyeCare Theme

The screenshots use a custom high-contrast theme optimized for readability. Copy the JSON below and save as a `.json` file to import into SillyTavern:

<details>
<summary><strong>Click to view Theme JSON</strong></summary>

```json
{
    "name": "EyeCare",
    "blur_strength": 0,
    "main_text_color": "rgba(230, 240, 255, 1)",
    "italics_text_color": "rgba(150, 220, 255, 1)",
    "underline_text_color": "rgba(255, 200, 100, 1)",
    "quote_text_color": "rgba(180, 255, 180, 1)",
    "blur_tint_color": "rgba(15, 20, 28, 1)",
    "chat_tint_color": "rgba(15, 20, 28, 1)",
    "user_mes_blur_tint_color": "rgba(22, 28, 38, 1)",
    "bot_mes_blur_tint_color": "rgba(18, 24, 32, 1)",
    "shadow_color": "rgba(0, 0, 0, 1)",
    "shadow_width": 0,
    "border_color": "rgba(70, 100, 140, 1)",
    "font_scale": 1,
    "fast_ui_mode": true,
    "waifuMode": false,
    "avatar_style": 2,
    "chat_display": 1,
    "toastr_position": "toast-top-right",
    "noShadows": true,
    "chat_width": 50,
    "timer_enabled": false,
    "timestamps_enabled": true,
    "timestamp_model_icon": true,
    "mesIDDisplay_enabled": false,
    "hideChatAvatars_enabled": false,
    "message_token_count_enabled": false,
    "expand_message_actions": true,
    "enableZenSliders": false,
    "enableLabMode": false,
    "hotswap_enabled": false,
    "custom_css": "",
    "bogus_folders": false,
    "zoomed_avatar_magnification": false,
    "reduced_motion": true,
    "compact_input_area": false,
    "show_swipe_num_all_messages": false,
    "click_to_edit": false,
    "media_display": "list"
}
```
</details>

### 🎙️ Featured Scenario: Real Talk Podcast

The reactions in the screenshots are based on this original character card. Use it to test Pathweaver:

<table>
  <tr>
    <td width="35%" valign="top">
      <img src="https://github.com/user-attachments/assets/beee7c3e-b40b-4f2d-a857-79329ab7038b" width="100%" alt="Real Talk Podcast Card" />
      <p align="center"><sub><em>Right-click & Save to import</em></sub></p>
    </td>
    <td width="65%" valign="top">
      <strong>The Story:</strong>
      <blockquote>
        Victoria Cross, 38, built her podcast empire dissecting male mediocrity and modern dating's failures—until Daniel, 18, calls in and systematically dismantles her worldview on air. Their explosive debates accidentally spark the "New Pond Movement," urging older women to pursue younger men and leave the "stagnant pond" behind.
      </blockquote>
      <p><strong>Import Options:</strong></p>
      <ul>
        <li>Download the image and import into SillyTavern</li>
        <li>Or <a href="https://gist.githubusercontent.com/mattjaybe/8856eecdb2ada535095cbc35e107a4dc/raw/6490ea9f134a1c71272f0014fec31bc068d62469/realtalk-charactercard.json">download the character card JSON</a></li>
      </ul>
    </td>
  </tr>
</table>

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Submit bug reports and feature requests via [Issues](https://github.com/mattjaybe/SillyTavern-Pathweaver/issues)
- Share your custom styles with the community
- Submit pull requests for improvements

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with ❤️ for the SillyTavern community
</p>
