

# `VOLI`
`VOLI`, pronounced "volley", is a simple, todo-list-game developed as a vehicle to (find / develop / test / establish) a human-readable, plain-text, aesthetically-acceptable (data / table)-format codenamed `Omni`.  We want `Omni` to be the "`Markdown`" of data.
```
Markdown :: Text
    Omni :: Data
```

## Motivation
- The large amount of inter-related datasets produced by playing `VOLI` should provide fertile ground for establishing a pleasing to (use / read) table-format.
- This project is also meant to get the team to up to speed on using all features of `git`, and `GitHub`

## `Omni`-Format: Initial Specification Roster
- Human-readable (e.g. similar to `Markdown`)
- 2D, tabular representation of complex, hierarchical data structures
- (!!!) Capable of handling aliases for any data entry (notably including object-keys)
- Establish some sample of Permanent (ID / location) assignment

## Team Members
```omni
Team
   Name              Email
   "Joel Cruz"       jcruz@axaeon.com
   "Nano Neutrino"   nn@axaeon.com
```

## Format-Model SOP
- Keep individual `format-model` files in the `omni-format-model`-directory
- The file should have an (example / model) of any alternative `Omni`-format
- Use the following naming convention for the files:
   ```
   format-model_{model-description}
   ```
   where `model-description` is an internally hyphenated description

## Workspace
1. Pull Request Practice: Part 1
> [!NOTE] Since the current format is essentially a white-space delimited format any entries that include "white-space" must be surrounded by double-quotes (").  Use `camelCase` where possible.
- Based on the `.TBL`, and `.TBLS` format.

## Completed Todos
- [x] `add format-model sop; GH-1`
- [x] Create a GitHub `Issue` to (establish / discuss) a protocol for building parallel-formats in a team-public manner
- [x] Nevermind. Extract specification from readme into its own document: "spec-{codename}.md"
- [x] (<) Created an issue for: Establish team's `git`-workflow into a document; meet to discuss

