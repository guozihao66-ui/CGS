# CGS Cobbler

CGS Cobbler is an internal consulting workflow prototype for CGS Advisors.

## File to open

- Open `index.html` directly in a browser
- This remains a standalone prototype

## What changed

This version preserves the original prototype presentation style and overall structure, while adding functional enhancements:

- visible Firm Library and Current Client Folder knowledge layers
- client folder selection in intake
- local company file upload support
- Google Drive-style connected source panel
- folder-aware classification and matching behavior
- visible evidence used from client files
- starter-pack outputs influenced by current client folder
- smarter human review warnings that vary by company context
- compact workflow strip inside the knowledge activation step

## Dynamic interactions

Switching the active client folder or uploading custom files now changes:

- project classification emphasis
- visible tags
- matched asset framing
- starter kit recommendation context
- evidence shown to the user
- review warnings
- session-only feedback memory
- immediate in-session starter-pack revisions after reviewer feedback

## Google Drive-connected model

- **Firm Library** is represented as a fixed reusable consulting asset layer
- **Current Client Folder** is represented as either a preset folder or uploaded local company files
- The prototype combines the two to simulate Google Drive-connected consulting workflow behavior without requiring unstable live enterprise integration

## Demo flow

1. Open `index.html`
2. In intake, switch between preset client folders
3. Optionally upload several local company files
4. Move to Knowledge Activation and show:
   - Connected Knowledge Sources
   - workflow strip
   - why the result is different
5. Move to Starter Pack and show:
   - archetype recommendation changing
   - retrieved client files
6. Move to Wear-Test Review and show:
   - evidence used
   - different warnings by company context
   - Feedback replacing Escalate on each review item
   - inline reviewer guidance entry with Save Feedback / Cancel
   - Feedback Memory as session-only reusable review guidance
   - immediate starter-pack revisions in Storyline Skeleton, Risk / Review Checklist, and 2–4 Week Diagnostic Workplan after feedback is saved
