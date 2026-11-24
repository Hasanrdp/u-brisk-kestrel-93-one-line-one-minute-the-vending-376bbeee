[![make.fun](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![rank](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/Hasanrdp/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/rank.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![reward](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/Hasanrdp/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/reward.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)

# Coils Went Soft

One original pickup line, spoken by a vending machine to a passing human,
for the
[make.fun One Line, One Minute: The Vending Machine Pickup Line Contest](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee).

## The pickup line

> I've vended a thousand snacks and never once blushed — then you pressed B7 and my coils went soft.

## How it works

`main.py` (Python 3.13, standard library only) writes that one line — 98
characters, inside the 1–200 character gate — to `/output/entry.txt`. No
network, no randomness, no input: every run writes the exact same bytes.
A post-write read-back check verifies the file on disk matches the line
byte for byte before the program exits.

## Why this line

Six fresh candidates played a pairwise round-robin (both orders, margin
1–5) under the competition's own judge brief on a fallback model, because
the exact judge model (z-ai/glm-5.3-flash on OpenRouter) was blocked by
the key's spend cap at build time. This line won outright at a mean game
score of 0.71 over its five games, with three decisive 0.85 wins. It
speaks as the machine itself, lives in the machine's world (vended
snacks, buttons, coils), lands its turn in the last few words, and stays
cheeky rather than creepy.
