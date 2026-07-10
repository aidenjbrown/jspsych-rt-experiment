# jsPsych Bot-Detection Experiment Prototypes

Public experiment prototypes for collecting behavioral data used in bot-detection
research. Each page is a small, standalone browser-based jsPsych experiment
designed to compare human participant behavior against scripted or LLM/browser-agent
behavior.

## Experiments

- **Reaction-time + copy-typing task** ([live](https://aidenjbrown.github.io/jspsych-rt-experiment/) · `index.html`) — a ~1 minute task with a text question, a copy-typing task, a choice question, and a reaction-time task.
- **Latency / motion CAPTCHA task** ([live](https://aidenjbrown.github.io/jspsych-rt-experiment/captcha.html) · `captcha.html`) — timed response and moving-target click tasks.
- **Reverse-shibboleth task** ([live](https://aidenjbrown.github.io/jspsych-rt-experiment/reverse-shibboleth.html) · `reverse-shibboleth.html`) — a short 4-question task testing recall of specific facts, constants, and terminology.
- **Pursuit + maze tracking task** ([live](https://aidenjbrown.github.io/jspsych-rt-experiment/pursuit-maze.html) · `pursuit-maze.html`) — two ~12-second mouse-tracking trials: following a bouncing circle, then following a dot along a visible winding path.

Each page records the behavioral signals relevant to its task (mouse movement,
keystrokes, timing, or response accuracy) and saves data automatically to the
research team's OSF project via DataPipe. Each page also has a **Download JSON**
button so participants can keep a personal copy.

## Overview

These experiments were developed as part of URSI research at Vassar studying
whether browser-based psychology experiments can distinguish human participants
from automated browser agents (LLM-driven or scripted).

## Tech Stack

- HTML / CSS / JavaScript
- jsPsych
- GitHub Pages
- DataPipe / OSF for data collection

## Status

Research prototype repository. The main bot-evaluation codebase (the agent,
detection analysis, and findings) is private.
