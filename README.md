# Dynasty Kickstarter – CK3 Mod

A Crusader Kings III mod that adds a custom **Norse spouse** to the 867 start date – perfect for “kickstarting” your dynasty.  
Solveig Haraldsdottir is designed as an ideal partner for your first Viking ruler, complete with **custom DNA** for a unique look.

---

## 📜 Features
- **Custom scripted character** (`solveig_kickstarter`) with:
  - Norse culture (`culture:norse`)
  - Ásatrú faith (`faith:asatru`)
  - Intelligent, Gregarious, Ambitious traits
  - Balanced skill set for diplomacy, stewardship, and court management
- **Custom DNA** stored in `common/dna_data`
- Spawns in your chosen ruler’s court at the **867 start date**
- Easy to expand with dynasty info, coat of arms, or more courtiers

---

## 🛠 Installation
1. Place the `dynasty_kickstarter` folder into your CK3 `mod` directory:
   - **Windows**: `Documents\Paradox Interactive\Crusader Kings III\mod\`
   - **Mac**: `~/Documents/Paradox Interactive/Crusader Kings III/mod/`
   - **Linux**: `~/.local/share/Paradox Interactive/Crusader Kings III/mod/`
2. Enable the mod in the CK3 launcher.
3. Start a new game in **867** as the Viking ruler whose court you scripted Solveig into.

---

## 📂 File Structure
```
dynasty_kickstarter/
common/
dna_data/
00_dynasty_kickstarter_dna.txt       # Stores Solveig’s DNA string
history/
characters/
00_dynasty_kickstarter_characters.txt # Character definition & traits
titles/
<title_history_file>.txt              # Adds Solveig to court at start
descriptor.mod
README.md
```
---

## 🧩 How It Works
- **DNA**: Generated via CK3’s Portrait Editor, saved as a named DNA entry.
- **Character script**: Uses that DNA, sets traits, skills, culture, faith.
- **Title history**: Adds the character as a courtier at game start.

---

## 🚀 Future Plans
- Add a **custom dynasty** (“Kickstarter”) with name, motto, and coat of arms.
- Option for Solveig to join the **player’s** court automatically regardless of ruler.
- Additional courtier(s) or family members to flesh out early-game roleplay.

---

## 📜 License
This mod is provided as-is for personal enjoyment. Feel free to fork and adapt with credit.

---

Happy raiding and may your dynasty flourish! ⚔️