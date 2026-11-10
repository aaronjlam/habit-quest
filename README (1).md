# Habit Quest

Turn daily habits into an RPG. Pick a class, check off habits to earn XP, level up, finish daily quests, and take on a weekly boss.

It's a single self-contained file (`index.html`) with no build step, no dependencies, and no network requests.

## Features

- **Classes:** Warrior, Mage, Cleric and Rogue, each with a stat they're strong in. Quests that match your class pay +50% XP.
- **Advanced classes:** At level 11 each class splits into two paths (for example Warrior into Tank or Paladin), with their own perks and gear.
- **Stats:** Strength, Intelligence, Wisdom, Vitality and Dexterity grow as you complete the habits tied to them.
- **Levels and ranks:** Novice (1 to 10), Apprentice (11 to 25), and higher ranks beyond that.
- **Daily quest, weekly boss, streak combo:** Plus a free streak freeze each month.
- **Pixel hero:** Chibi pixel-art character with hair, eye and accessory options, and gear that changes as you level up.
- **Your habits:** Add, rename, remove and re-tag habits. Changes only affect future days, so past XP and streaks never change.
- **Fix a missed day:** Tap any of the last 7 days in the calendar to correct it.
- **Class plans:** A 4-week self-improvement plan and example careers for each class.
- **Backup and restore:** Export your progress to a file and restore it later.
- **Daily reminder:** Download a calendar file with a repeating reminder.

## Run it locally

Open `index.html` in any modern browser. That's it.

## Publish it with GitHub Pages

1. Create a new repository on GitHub and upload `index.html` and this `README.md` to the main branch.
2. Open the repository's **Settings**, then **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose the **main** branch and the **/ (root)** folder, then **Save**.
5. After a minute or two your app is live at `https://<your-username>.github.io/<repository-name>/`.

## Your data and privacy

- Progress is saved in your browser's local storage on the device you use. Nothing is sent anywhere, and there are no accounts, ads or analytics.
- Because it's stored per browser, clearing your browser data erases it. Use **Export my data** now and then to keep a backup.
- Progress does not move between devices on its own. To switch devices, export on one and restore on the other.
- A version hosted inside Claude also syncs progress to your Claude account. This standalone version doesn't.

## Notes

- Habit, fitness and career suggestions in the app are general ideas, not medical or career advice.
- No license file is included yet. Add one (for example MIT) before others reuse the code.
