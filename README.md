# SSBU-Matchups

A collection of community-sourced advice for every Matchup in Super Smash Bros Ultimate, used as the source for [SmashMatchsups.com](http://www.smashmatchups.com).

## How to contribute

This repository is structured in the format of `/your_character/opponent_character.md`. For example, the file found at `/mewtwo/bowser.md` shows tips for the Mewtwo-Bowser matchup, with advice for the character playing Mewtwo - where `/bowser/mewtwo.md` will have advice for the Bowser.

### Generic Files

As of this writing, there are as many as 81 characters (depending on how you count) - creating thousands of potential matchups. In order to make sure there is some content available for every matchup - each character also has a generic `how_to_beat.md` - which can be shown when specific matchup data isn't available. Eventually, we should hope to show none of those generic results for any matchup.

### Matchup Style Guide

In order to keep pages somewhat consistent, pages must adhere to this common style:

1. Start with a **Character vs. Character** heading
2. Split suggestions into categories such as
  - Winning Neutral
  - Disadvantage
  - Edgeguarding
  - Dealing with Projectiles
  - Stage Meta
  These are not requirements, just suggestions. Not every matchup needs to have all the same sections. But splitting it up into sections makes it more quickly scannable, especially inbetween online battles.

### Character Names

Matchup file names have to be specific (otherwise SmashMatchups.com won't find them). We can't have one matchup have "R.O.B.md" as the file, and another "rob.md".

To fix this, names are normalized into lowercase, periods are removed, "&" becomes "and", and spaces become underscores. For example "Mr. Game & Watch" becomes "mr_game_and_watch". When in doubt, simply refer to the top level directories, which are already named appropriately. Additionally:

1. Pokemon Trainer is split into 3 separate characters
2. These echo fighters will be counted as separate characters:
  - Lucina and Marth
  - Chrom and Roy
  - Dark Pit and Pit
  - Ken and Ryu
  - Dark Samus and Samus
3. These echo fighters will use the same document, since their differences are extremely subtle:
  - Richter matchups use `simon.md`.
  - Daisy matchups use `daisy.md`.
