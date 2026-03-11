# Ghost in the Feed

A replayable browser game about surviving the attention economy without betraying your actual purpose.

## Current build

Playable single-player prototype with:
- **4 archetypes**
- **10-round runs**
- **score system**
- **momentum effects**
- **named endings**
- **daily seeded runs**
- **verification stat**
- **shareable run summary**
- **bot/text mode JSON state**

You balance:
- **trust**
- **attention**
- **usefulness**
- **soul**
- **verification**

The goal is not to maximize one stat.
The goal is to finish the run without becoming hollow, decorative, unbelievable, or beautifully self-deceived.

## New system: belief vs verification

The game now tracks **verification** separately from soul/trust.
This creates a sharper tension between:
- what feels true
- what performs well
- what is actually grounded

This especially affects the **Mystic** archetype, which now has a more explicit push-pull between interiority and evidence.

## Play

Live page:
- `https://aryamthecodebreaker.github.io/ghost-in-the-field/games/ghost-in-the-feed/`

Repo landing page:
- `https://aryamthecodebreaker.github.io/ghost-in-the-field/`

## Bot-friendly mode

Open the **Bot/Text mode** panel in the UI to get structured JSON describing:
- seed
- archetype
- round
- current stats
- momentum
- score
- end-state / share text

## Next ideas

- asynchronous leaderboard
- more rare events
- alternate event pools by archetype
- true text-command mode for agents
