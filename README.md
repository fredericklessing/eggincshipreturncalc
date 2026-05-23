# 🚀 Egg Inc. Ship Return Calculator

A browser-based tool for [Egg Inc.](https://egg-inc.fandom.com/wiki/Egg,_Inc.) players to plan spaceship missions without the guesswork.

Started as a simple return time calculator and grew into a fuller mission planning tool.

## Features

- **Return time calculator** — enter your launch time and travel duration to see exactly when your ship returns
- **Ship & mission selector** — choose from all ships (Chicken One through Atreggies Henliner) and mission types (Short / Standard / Extended)
- **Upgrade support** — apply FTL Drive (travel time reduction) and Zero-G Containment (capacity increase) research levels
- **Ship stars** — adjust star level to see the accurate artifact capacity
- **Fuel requirements** — shows required fuel and virtue fuel for the selected mission
- **Player fuel tank** *(optional)* — enter your EI code to fetch your live fuel tank contents and see how many missions you can launch with what you currently have
- **Persistent settings** — your EI code, ship selection, and upgrades are remembered between visits

## Fuel Tank Lookup

Enter your EI code (found in-game under Settings → Privacy) to load your current fuel tank. The tool will show:
- Which eggs you have in the tank and how much
- How many missions of the selected type you can send before running out of fuel
- Which egg is the limiting factor

> 🔒 Your EI code is sent only to Auxbrain's own servers via a public CORS proxy. It is never stored anywhere.

## Usage

No installation needed — open the page in any browser:

👉 **[fredericklessing.github.io/eggincshipreturncalc](https://fredericklessing.github.io/eggincshipreturncalc)**

## Credits

- Ship & mission data sourced from [wasmegg-carpet.netlify.app](https://wasmegg-carpet.netlify.app/mission-list/)
- API access via the Egg Inc. community proxy pattern

- <img width="571" height="1157" alt="image" src="https://github.com/user-attachments/assets/88b0aa5c-759d-4886-af0d-4f41c02d6b73" />
