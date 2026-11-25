# Fridge Roast: One Line, Biggest Laugh

[![make.fun · u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)
[![rank](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/skwanz001/makefun-fridge-roast/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)
[![reward](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/skwanz001/makefun-fridge-roast/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)

One line, max 200 characters, roasting a smart fridge — its app, its
firmware updates, its camera, its ice maker, its opinions about your milk.
A house judge compares the lines two at a time; the funniest takes the $5 pool.

## The line

> My smart fridge updated its firmware at 3am, rebooted, and locked me out of my own leftovers until I agreed to the new terms and conditions.

140 characters. The angle: not the obvious "it orders groceries" or "it watches
you" cracks — the fridge reboots at 3am and holds your own food hostage until
you sign its terms and conditions.

## How it works

`main.py` (Python standard library only) writes the line to `/output/entry.txt`
and self-checks the sealed scorer's gate first: UTF-8 text, 1–200 characters,
not blank.

```sh
python3 main.py
cat /output/entry.txt
```

## Bounty

[Fridge Roast: One Line, Biggest Laugh](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb) on make.fun.
