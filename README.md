# Beat the Predictor

A two-minute phone game. Tap left or right as randomly as you can for 100 taps. A small program guesses each tap before you make it.

Guessing blindly, it would be right about 50% of the time. Most people let it do better, because people trying to be random switch too often and avoid streaks.

## How the predictor works

It keeps a tally of what you tapped after each combination of your last 1 to 5 taps. Before each tap, it bets you'll do what you usually do after your current combination. It knows nothing else about you.

## What the results show

- **Guess rate**: how often it was right, with the odds a coin would let it score that high.
- **Chart**: its guess rate over the game, against the range a coin lands in 95% of the time.
- **Switch rate**: a coin switches about 50% of the time. Most people switch more.
- **Longest streak**: a coin's is usually 5 to 10 in 100 flips. Most people stop short.
- **Let a coin play**: runs the same program against real random taps for comparison.
- **History** of your last 20 games, saved in your browser only.

## Limits

One game of 100 taps is a small sample. A score near 50% means this program couldn't find a pattern, not that you were truly random.

## Background

Wagenaar (1972); Tversky and Kahneman (1971); Walker and Wooders (2001); Neuringer (1986); the Aaronson oracle.

## Run it

Open `index.html` in any browser, or turn on GitHub Pages for this repo (Settings > Pages > Deploy from branch > main).
