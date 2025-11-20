Modeling Fast and Slow Twitch Skeletal Muscle Using the Hill Muscle Model

This repository contains a complete Python implementation of the classical Hill muscle model, adapted for simulating and comparing the mechanical and energetic behavior of slow-twitch and fast-twitch skeletal muscle fibers. The project was originally developed for a quantitative physiology and biomechanics analysis, with model parameters tuned using experimental data from published muscle physiology studies (e.g., Barclay 1993, Journal of Physiology).



Overview

Skeletal muscles exhibit distinct mechanical and energetic behaviors depending on fiber type:

Slow-twitch (Type I) fibers are oxidative, economical, and produce force efficiently but contract slowly.

Fast-twitch (Type II) fibers contract rapidly, develop higher power, and generate substantially more heat for the same force output.

The Hill model provides a mathematically tractable way to capture these differences using a small number of empirical parameters (P0,a,b,k).
This repository includes a Python notebook that:

Implements the Hill differential equation for force evolution

Simulates isometric tetanus, force–velocity curves, and power–velocity curves

Models heat production during activation

Allows direct comparison of fast-twitch and slow-twitch muscles

Produces plots analogous to experimental figures from classical muscle physiology papers
