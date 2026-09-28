# Today

A private, on-device Android accountability app. The launcher name is Today. Inside the app, the title is One day at a time. A private prototype is noted at 0.5.4.

This repository is the public case study. It does not include the application.

![Today concept screens](./assets/today-concept.jpg)

*Synthetic concept placeholders, not photos from a personal device. See [the visual product notes](./VISUAL_PRODUCT.md).*

## Why I am building it

A day gets split across a timer, a few tasks still open, and small notes about money, body, or admin. The useful question is whether any of that belongs to something I named.

Today keeps that question on the phone. A named reward sits ahead as a puzzle. A piece can come from timed focus, from a prep task that was left open, or from a step logged under money, body, or work/admin.

## Product principles

- **On the device.** Today is a private Android app. The record of the day stays on the phone.
- **One day.** The in-app title is One day at a time. The day is the unit of the product.
- **A named reward.** Puzzle pieces point at a reward the person named.
- **Three ways to reveal a piece.** Timed focus, an open prep task, or a logged step. A timer is one of those ways.
- **Profile and Wins stay in their own places.** Health, phone, and screen live under Profile. Wins and badges live under Wins.

## What the day contains

The list below is the product being described, not a changelog of the private prototype. See [Current status](#current-status).

1. The launcher name is Today. The in-app title is One day at a time.
2. A named reward is shown as a puzzle.
3. Timed focus, an open prep task, or a logged step can reveal a piece. Logged steps are money, body, or work/admin.
4. Profile holds health, phone, and screen.
5. Wins holds wins and badges.
6. The interface uses dawn paper, a steel-blue accent, and a morning-sun launcher mark.

## Sample day

This sample is fictional. It shows the shape of a day. It is not a log from the 0.5.4 prototype, and the rows are not usage numbers. The concept board uses the same reward name and keeps the action labels generic.

Named reward: Saturday market

| Action | Kind | What it reveals |
| --- | --- | --- |
| Timed focus | Focus | A puzzle piece |
| Write the stall list | Prep task, was open | A puzzle piece |
| Set aside the stall fee | Logged step, money | A puzzle piece |
| Logged a workout | Logged step, body | A puzzle piece |
| Filed the market permit | Logged step, work/admin | A puzzle piece |

Profile on that same fictional day has three areas, health, phone, and screen, and the public sample leaves them blank.

Wins on that day can hold a win such as Morning focus, and a badge such as Focus. A win or a badge is not a puzzle piece.

## Quality bar

A day is not enough when:

- the only record is a running timer
- a piece appears with no action named
- a logged step does not say money, body, or work/admin
- a health, phone, or screen row is counted as a puzzle piece
- a badge is counted as a puzzle piece

A day holds up when:

- the reward has a name
- each revealed piece points at timed focus, an open prep task, or a logged step
- a logged step says money, body, or work/admin
- health, phone, and screen stay under Profile
- wins and badges stay under Wins

## Privacy boundary

- The app is private and on-device. This repository does not claim a Play Store listing.
- Personal device photos, health notes, phone records, screen figures, real reward names, and signing keys do not belong in a public repository.
- The pictures here are synthetic placeholders. They are not measurements from use.

## Current status

A private Android prototype is noted at 0.5.4. It is not published on the Play Store, and there is no public APK.

The product notes above are not an inventory of every screen in that build, and they are not usage numbers.

## What this case study shows

- A named reward, shown as a puzzle
- Three ways to reveal a piece: timed focus, an open prep task, or a logged step
- Profile kept apart from the puzzle
- Wins and badges kept apart from pieces
- A synthetic sample and a drawn board, with no real day of use

## What this repository is

A public case study, visual product direction, and planned system boundaries. See `VISUAL_PRODUCT.md` and `ARCHITECTURE.md`.

It is not the application. There is no Android source here, no installable build, no signing material, and no real record of use. The sample day and the pictures are synthetic. No application code is published here.

## Who is building it

Yashasvi Shailly. Product, design, and engineering.
