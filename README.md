# Leeway

**Built for the long game.**

Leeway is a concept for a wearable system that helps you plan your day around your energy. It pairs an ultra-thin, screenless wrist band with an optional stress-hormone sweat patch and a phone app that turns body signals into a daily plan.

This repository holds the interactive prototypes, built for a Dartmouth Engineering class project.

**Live site:** https://pranavc33.github.io/leeway-wearable/

## What's inside

The site has four tabs:

| Tab | What it shows |
|---|---|
| **Overview** | How the band, patch and app fit together. |
| **Band** | An interactive 3D model of the Leeway Thin band. You can rotate it, explode the layers, view a cross-section and see it on a wrist. It covers the stacked skin sensor (heart rate and EDA), the optional olfactory sensing window, the push-to-talk microphone, and thermal, gas-flow and wet-condition views. |
| **Cortisol patch** | A step-by-step simulation of a sweat patch that measures cortisol, epinephrine and norepinephrine across five timed chambers, with an illustrative hormone chart. |
| **App** | A clickable phone prototype following "Maya" through her day. It includes a working reaction-time readiness test, an energy forecast, plan fixes for low-energy meetings, meal and alcohol insights, and push-to-talk voice logging. |

## Research behind the concept

- **Olfactory (skin-gas) sensing.** Ye et al., "Miniaturized olfactory sensor chip-based AI-wearable biometric ring for human body metabolic odor analysis," *Nature Communications* 17, 4541 (2026). https://doi.org/10.1038/s41467-026-70746-z
- **Sweat stress-hormone patch.** Based on the Stressomic design from Caltech (Tu et al., *Science Advances*, 2025).

Both were demonstrated in small, controlled studies. Leeway's uses of them, such as all-day wear, mixed real-world meals and a multi-week patch, would need further development.

## Running it locally

There's nothing to install. The whole site is a single self-contained file, so you can open `index.html` in a browser.

An internet connection is needed for the fonts (Google Fonts) and the 3D band model, which loads three.js r128 from cdnjs.

## Disclaimer

These are concept prototypes. All dimensions, data, readings and insights are illustrative design targets, not measured product performance. Nothing here is medical advice.
