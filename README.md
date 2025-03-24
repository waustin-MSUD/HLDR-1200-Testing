The War on Drugs
================

This site is for testing and proofreading the War on Drugs Twine simulation for HLDR 1200.

Live Demo
---------

This link lets reviewers play the Twine in its current state.

[Live Demo](https://waustin-MSUD.github.io/HLDR-1200-Testing/index.html)

Review
------

This tool allows reviwers to make edits and changes in each passage in the simulation.

[Proof/Add Comments](https://waustin-MSUD.github.io/HLDR-1200-Testing/illumination.html)

To use this tool, it helps to have it open in a second browser tab while reviewing.

You can select passages on the left side, make edits, then flag that passage as reviewed to remove it from your list.

See below for a screenshot.

When finished reviewing, **export the change list** and email it to the Will and Dawson.

It's a slightly clunky process, but better than a spreadsheet.

![alt text](https://github.com/waustin-MSUD/HLDR-1200-Testing/blob/main/illumination.png?raw=true)

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
