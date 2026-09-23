https://discord.gg/36EAyW5Z4F
-------------------------------------
A powerful, high-accuracy CLI tool to check for available usernames on guns.lol using Selenium with advanced detection logic.

## ⚠️ Important Note
- Usernames that start or end with characters such as ".", "-", or "_" are **Premium Aliases**. You need a premium account to claim these.
- This tool includes a toggle to filter these out so you don't waste time on names you can't claim for free.

### 🧹 Chrome Auto-Cleanup
> When the tool finishes or is closed (including via `Ctrl+C`), **Chrome and chromedriver processes are automatically terminated**. No background Chrome processes will be left running on your system.


## ⭐ Features
- **Premium Purple CLI Theme:** Stylish, modern purple interface using `pystyle`.
- **Intro Animations:** Smooth fade-in effects and persistent headers for a high-quality professional feel.
- **Discord Webhooks:** Get instant notifications on Discord. Webhook URL is validated to ensure a correct link.
- **Chrome Auto-Cleanup:** Chrome and chromedriver processes are automatically killed on exit — no leftover background processes.

## 🛠️ Installation

1. **Prerequisites:** Ensure you have [Python 3.8+](https://www.python.org/) and Google Chrome installed.
2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt
   ```
   *Or just run `install.bat` on Windows, or `chmod +x install.sh && ./install.sh` on Linux/macOS.*

## 🚀 How to Use

Run the script:
```bash
python 67.py
```

### Prompt Flow
0. **Press Enter** — Enjoy the smooth fade-in intro.
1. **Username length** — Char count for random generation.
2. **Delay (Interval)** — Seconds between requests (Recommended: 0).
3. **Use customlist.txt?** — Load your own list of usernames.
4. **Filter Premium?** — Auto-skip names free users can't claim.
5. **Save to unclaimed.txt?** — Log hits to a file.
6. **Discord webhook?** — Real-time alerts via Discord.

## 🙏 Acknowledgements
  - [@litecoinwallet]([https://github.com/noivan0](https://github.com/mowgli-exe/guns.lol-)) — Thanks for the filtering feature contributions and readme shield badges suggestion.
