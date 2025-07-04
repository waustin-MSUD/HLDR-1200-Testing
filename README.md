The War on Drugs
================

This Twine simulation was designed for HLDR 1200 as part of the CTLD course development cycle 18 (Spring 2025).
It's archived here in case errors are found when the course goes live.

Live Demo
---------

This link lets reviewers play the simulation.

[Live Demo](https://waustin-MSUD.github.io/HLDR-1200-Testing/index.html)

Review
------

This tool allows reviewers to make edits and changes in each passage in the simulation.

[Review Twine Simulation](https://waustin-MSUD.github.io/HLDR-1200-Testing/illumination.html)

* It helps to have it open in a second browser tab while reviewing, with the live demo in another tab.
* You can select passages on the left side and make edits (see screenshot).
* Flag that passage as reviewed to remove it from your list (see screenshot).
* When finished with every review session, **export the change list** and email it to Will and Dawson (see screenshot). I don't think this will save change lists from session to session.

It's a slightly clunky process, but better than a spreadsheet.

![illume screenshot showing flag as reviewed and export change list](https://github.com/waustin-MSUD/HLDR-1200-Testing/blob/main/illumination.png?raw=true)

Passage Structure
------------

```bash
├── Start
│   └── Character Select (return point after each character)
│       ├── John Anderson (bio)
│       │   ├── (videos) JA90S, JA00S, etc., always ending with "S"
│       │   └── (passages) JA0A, JA1A, etc.
│       ├── Jamal Washington (bio)
│       │   ├── (videos) JW90S, JW00S, etc., always ending with "S"
│       │   └── (passages) JW0A, JW1A, etc.
│       └── Michael Thompson (bio)
│           ├── (videos) MT90S, MT00S, etc., always ending with "S"
│           └── (passages) MT0A, MT1A, etc.
├── StoryInit (special passage)
├── StoryCaption (special passage, progress bars)
├── StoryTitle (special passage)
├── StoryData (special passage)
├── StoryStylesheet (special passage, CSS)
└── StoryScript (special passage, JS)
```
