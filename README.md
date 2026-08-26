[README.md](https://github.com/user-attachments/files/31486160/README.md)
# The One Stop Profession Shop

An in-game leveling guide covering every profession in TBC Classic — all 8 primary crafting/gathering professions, plus First Aid, Cooking, and Fishing. No more alt-tabbing to a website mid-craft.

## Features

- **Full 1-375 leveling routes** for every profession: what to craft, materials needed, and notes on what to stockpile for later steps
- **Auto skill detection** — reads your actual profession skill and highlights exactly where you are in the route
- **Checkboxes** to mark steps complete, saved per character
- **Multi-character tracking** — every character on your account keeps its own saved progress, and you can view (or edit) any of your alts' checklists from whichever character you're currently on
- **Collapsible sections**, grouped by rank bracket, each showing a live "x/y done" count
- **Shopping List** — totals every material you still need across your *unchecked* steps, checks your bags automatically, and shows where to get each one (mined, gathered, smelted, or bought, with zones/vendors), sorted by the order you'll actually need things rather than alphabetically
- **Combined shopping lists** for paired professions — if your current character knows both First Aid + Tailoring, or Fishing + Cooking, their shared material needs are totaled together automatically
- **Farm-mode toggle** for gathering professions (Mining, currently) — swap between "buy/smelt with concrete quantities" and "just tell me which zone to farm"
- **Trainer locations**, filtered to your faction automatically, for both the 1-300 trainers and the Master-rank Outland trainers
- **Minimap button** — click to open, drag to reposition

## Installation

1. Download and extract the zip
2. Make sure the extracted folder is named `OneStopProfessionShop` and drop it directly into:
   `World of Warcraft\_classic_\Interface\AddOns\`
3. The path should look like `...\AddOns\OneStopProfessionShop\OneStopProfessionShop.toc` — if there's an extra nested folder in between, move the files up a level
4. Restart WoW (or `/reload` if it's already running)
5. At the character-select screen, click **AddOns** and make sure it's checked

## Usage

- **Open/close the window**: click the minimap button, or type `/1stop`
- **Switch professions**: use the dropdown at the top of the window
- **Switch characters**: use the second dropdown to view any of your alts' saved progress (skill highlighting only works for whichever character you're actually logged into, since it needs live data)
- **Open the Shopping List**: click the "Shopping List" button in the main window, or `/1stop shop`
- **Check your current step without opening the window**: `/1stop current`
- **See every profession this addon covers**: `/1stop list`
- **Clear all checkboxes** for the character you're currently viewing: `/1stop reset`

## Professions covered

Engineering, Alchemy, Mining, Blacksmithing, Tailoring, Leatherworking, Jewelcrafting, Enchanting, Herbalism, Skinning, First Aid, Cooking, Fishing.

## Notes and known limitations

- Skill breakpoints and recipe quantities are drawn from community leveling guides. Actual skill-ups have some randomness (green/yellow/orange chance), so treat numbers as "approximately here," not exact — this is called out inline wherever a step is especially prone to variance.
- Where a profession's guide offers several equally-valid recipes for a bracket, one was picked as the default route (favoring options with the fewest reputation/quest/drop-rate prerequisites), with the main alternatives noted in that step's description.
- The farm-vs-buy toggle currently only exists for Mining. It can be extended to other gathering professions the same way if that's useful later.
- The Shopping List only lists steps you haven't checked off yet — if it looks empty or short, double check you haven't accidentally marked upcoming steps as done.

## Feedback

This is under active development for the guild. Any and all criticism is welcome — wrong numbers, a confusing screen, a recipe that doesn't match what you see in-game, anything. Report it however works for you (Discord, in-person, whatever) and it'll get fixed.
