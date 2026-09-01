# Power Series — GitHub Workflow Rules

**Author/Project Owner:** Emmanuel Tuffet  
**Repository:** `donteck/The-power-series`

## Core Series Architecture

`WORD → LETTERS → PRINCIPLES → MODULES → ROADMAP → COURSE → BOOK`

Series identity: **One Word. One Framework. One Transformation.**

## GitHub Sync Rule

GitHub is the permanent source of truth for The Power Series.

Whenever new material is created or revised for a Power Series book, the repository should be kept synchronized.

- If the material clearly belongs to an existing Power Series book, add or update it in that book's folder as part of the workflow.
- If the destination or whether the material should be permanent is ambiguous, ask Emmanuel whether it should be added to GitHub before committing it.
- Never silently overwrite finished manuscript text when a new version may be a draft. Preserve version intent and confirm when necessary.
- New books receive the next sequential number and the same folder architecture.
- Roadmaps prompts should remain at or below 400 characters when a compact Roadmaps prompt is required.
- Covers should be portrait flat-front covers and stored with the corresponding book.
- Full manuscripts supplied later should be added as an additional manuscript layer rather than replacing roadmap/project material unless explicitly requested.

## Standard Book Folder

```text
books/NN-the-power-of-word/
├── README.md
├── roadmap.md
├── publishing-package.md
├── manuscript/
│   ├── README.md
│   └── chapters/
├── marketing/
└── cover/
```

## Publishing Package

Each book may include:

- Dedication (under 500 characters)
- Epigraph (one powerful phrase or quote)
- Preface
- Foreword
- Acknowledgments
- Introduction
- Prologue
- Conclusion
- Epilogue
- Afterword
- Amazon Book Description
- YouTube Description
- Seven optimized Amazon keyword phrases

## Manuscript Rule

The roadmap and publishing package are project-development assets. The complete finished manuscript is a separate authoritative deliverable. When Emmanuel provides a complete book manuscript, add it under `manuscript/` and preserve the roadmap, publishing package, marketing assets, and cover files.