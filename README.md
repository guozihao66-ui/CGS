# CGS Cobbler

CGS Cobbler is an internal consulting workflow prototype for CGS Advisors.

This upgraded prototype keeps the original product identity and dark consulting-studio style, but now behaves like a more convincing Google Drive-connected engagement studio.

## File to open

- Open `index.html` directly in a browser
- No build step required

## What is now genuinely dynamic

The prototype now recomputes all major outputs from the active client folder state:

- project classification
- visible tags
- matched frameworks
- matched archetypes
- matched templates
- matched governance rules
- engagement archetype recommendation
- 2–4 week diagnostic workplan
- interview guide
- storyline skeleton
- human review warnings
- visible evidence used from client files

## Google Drive-connected knowledge model

The product uses two visible knowledge layers:

1. **Firm Library**
   - represented as a structured reusable asset pack
   - frameworks
   - archetypes
   - templates
   - governance / QA rules

2. **Current Client Folder**
   - represented as either:
     - preloaded client folders, or
     - uploaded local company files
   - file names and file text are read in-browser and mapped into a simulated Google Drive client folder state

The logic is intentionally demo-safe and local:

- Firm Library tells the system how to think
- Current Client Folder tells the system what this company needs

## Demo script

1. Open `index.html`
2. Start with **CrestPoint Advisory**
   - show the Connected Knowledge Sources panel
   - point out Firm Library vs Current Client Folder
   - show that standardization-oriented assets and warnings are matched
3. Switch to **Northstar Components**
   - show the project classification change to AI enablement
   - show different frameworks, templates, and starter-kit outputs
   - show different review warnings around weak quantified AI claims
4. Switch to **Apex Enterprise Group**
   - show the classification shift to transformation inertia / sponsorship reset
   - show governance and sponsor-related evidence
   - show different review warnings around sponsor ambiguity
5. Upload a few custom files
   - show that the Current Client Folder changes to a custom upload state
   - show the evidence panel updating from uploaded content
   - show the starter kit and review gate changing again

## Notes

- This is still a lightweight prototype
- It does not require unstable live enterprise Google Drive integration
- The experience is designed to be visually credible, locally runnable, and responsive for demos
