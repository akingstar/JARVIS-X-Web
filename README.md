# JARVIS-X Web

Public static website for the JARVIS-X personal assistant project.

## Hosting
This repository is deployed with GitHub Pages through GitHub Actions.

## Current capabilities
- Responsive dashboard interface
- Browser speech-to-text input where supported
- Honest connection status for the private phone backend

## Important security boundary
This public website does not contain the private JARVIS-X Python brain, passwords, API keys, memory, or phone-control code. The live backend connection is not configured yet. Do not add secrets to this repository or expose the private backend directly.

## Deployment
Push to `main`. The GitHub Actions workflow publishes the root directory to GitHub Pages.
