# Today, planned architecture

## Status

A private Android prototype is noted at 0.5.4. It is not a Play Store release, and this repository does not include a public APK. This document records the intended boundaries and the way a day moves. It is not a component-by-component claim about that build.

## Overview

Today is an on-device Android app. The person works one day at a time toward a named reward. The reward is a puzzle. Timed focus, an open prep task, or a logged step can reveal a piece. Logged steps are filed under money, body, or work/admin. Profile holds health, phone, and screen. Wins holds wins and badges. The interface reads that local day.

## Planned surfaces

- **Day.** The in-app title is One day at a time. The day is the record the person returns to.
- **Reward puzzle.** A reward has a name and a set of pieces. Revealing a piece is the progress event.
- **Focus.** A timed focus session is one way to reveal a piece.
- **Prep tasks.** A prep task can stay open, then reveal a piece when it is done.
- **Logged steps.** A step logged under money, body, or work/admin can reveal a piece. These are entries for the day, not a pedometer total and not a Profile chart.
- **Profile.** Health, phone, and screen are profile areas. They are context for the day. This document does not treat them as the action that reveals a puzzle piece.
- **Wins.** Wins and badges are kept apart from the reward puzzle.
- **Launcher.** The launcher name is Today. The mark is a morning sun. The interface accent is steel blue on dawn paper.

## Planned flow

1. The day opens under the title One day at a time, with a named reward waiting as a puzzle.
2. The person starts timed focus, works a prep task that is still open, or logs a step.
3. A logged step is marked money, body, or work/admin.
4. That completed action reveals a puzzle piece toward the named reward.
5. Profile can be opened for health, phone, and screen.
6. Wins can be opened for wins and badges.

## Trust boundary

- The product is a private on-device Android app.
- This case study does not describe an account, a public profile, or a Play Store listing.
- Health, phone, and screen details from a real device are not part of this repository.
- Public visuals use fictional names and empty placeholder rows.

## Held back

The application source, installable builds, signing material, and every real day of use are private and are not in this repository.
