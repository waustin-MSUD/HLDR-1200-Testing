The War on Drugs
============

This site is for testing and proofreading the War on Drugs Twine simulation for HLDR 1200.

There are two pages:

The first is a live demo of the simulation in its current state.

[Live Demo](https://waustin-MSUD.github.io/HLDR-1200-Testing/index.html)

The second is a page that allows reviewers to leave comments on each passage in the simulation.

[Proof/Add Comments](https://waustin-MSUD.github.io/HLDR-1200-Testing/Poof_%20War%20on%20Drugs.html)

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
