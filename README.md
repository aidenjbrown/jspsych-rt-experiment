# jspsych-rt-experiment

Browser-based reaction-time and copy-typing experiment for collecting human baseline data in bot-detection research.

## Overview

This project was built as part of URSI research at Vassar studying whether browser-based psychology experiments can distinguish human participants from automated browser agents.

The experiment collects interaction data such as reaction time, keyboard events, mouse movement, and task timing. These human baseline sessions can then be compared against scripted or LLM/browser-agent sessions.

## Features

- Reaction-time task built with jsPsych
- Copy-typing task for behavioral data collection
- Browser interaction recording using the jsPsych `record_session` schema
- Optional JSON download for local session records
- GitHub Pages deployment for browser-based testing

## Tech Stack

- HTML/CSS/JavaScript
- jsPsych
- GitHub Pages
- Browser-based experiment tooling

## Status

Research prototype developed during Vassar's Undergraduate Research Summer Institute.

This repository is a public-facing experiment prototype. The main URSI bot-evaluation codebase is private.
