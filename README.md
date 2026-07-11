# Unwind

A quiet minute to ease out of an anxious spiral.

Anxiety often runs as a loop: worry → freeze → more worry. **Unwind** is a low-friction
visual pattern-interrupt that gently pulls your attention out of that loop, then hands you
off to a calm breath — no login, no audio, no talking, works on phone and laptop.

## The flow

1. **Follow the light.** A glowing dot appears and drifts. You keep near it — drag it on a
   phone, chase it with the mouse on a laptop, or just track it with your eyes. Following a
   moving target quietly occupies the same attention the spiral was using.
2. **Breathe.** Once you've settled, a slow visual pacer guides ~6 breaths per minute:
   in through the nose, out through the mouth.
3. **You did it.** A short affirmation. An optional small movement is offered if you want it.

## Design notes

- Single self-contained `index.html` — Canvas 2D, no dependencies, no build step.
- Cross-device: unified pointer input (touch drag = mouse move), viewport-relative sizing.
- Respects `prefers-reduced-motion`; commits to a single dark theme so the light reads.
- Not a medical device. A moment of relief, not treatment.

## Run it

Open `index.html` in any modern browser, or visit the hosted version (GitHub Pages).
