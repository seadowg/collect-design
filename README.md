# ODK Collect Design 🎨📋

This repo collects design documents for [ODK Collect](https://github.com/opendatakit/collect).

## Research

Research will be planned and results posted within this repo. Each research round should be represented by a single document in the `research` directory.

Previous research rounds:

* [Repeats](/research/repeats)

## Prototypes

Prototypes for potential/experimental features in Collect will be added here. This can be in the form of wireframes, sketch files, working apps etc.

Previous feature prototypes:

* [Identify User](/prototypes/identify-user)
* [Track Changes Reason](/prototypes/track-changes-reason)
* [Repeat Tweaks](/prototypes/repeat-tweaks)

## Theme

Collect uses a [Material Theme](https://material.io/design/material-theming/) as the basis for its design and style guide. This repo contains the Sketch files (that use the [Material Theme Editor](https://material.io/tools/theme-editor/)) that define the theme. While the intention is for Collect to adhere to this theme as closely as possible over time, most of the app is still not up to date with it.

### Style guide

If you'd like to view the style guide for Collect you can do so [here](https://github.com/seadowg/collect-design/releases/latest/download/collect-styleguide.pdf).

### Building mockups

If you'd like to use the Sketch files as the basis for building mockups for Collect:

1. Install [Git](https://git-scm.com/downloads) and [Kactus](https://kactus.io/)
1. Clone the project:
```bash
git clone https://github.com/seadowg/collect-design
```
1. Open the cloned repo in Kactus and open the Sketch file by clicking "Regenerate Sketch File" and then "Open File"

### Contributing to the theme

If you'd like to propose and contribute changes to theme:

1. Install [Git](https://git-scm.com/downloads) and [Kactus](https://kactus.io/)
1. Fork this project
1. Clone your fork project:
```bash
git clone https://github.com/YOUR-GITHUB-USERNAME/collect-design
```
1. Open the cloned repo in Kactus and open the Sketch file by clicking "Regenerate Sketch File" and then "Open File"
1. Make a new branch for your changes (you can use Kactus or Git's command line)
1. Make your changes to the Sketch file
1. Commit your changes and push your branch using Kactus
1. Create a new [pull request](https://help.github.com/en/articles/creating-a-pull-request)

*Note: Kactus tracks the changes to your Sketch file and explodes it into many JSON files so it's easier to track the diffs between commits. You don't have to use Kactus for all your interactions with Git but if you don't have it open Git won't see the changes to the Sketch file.*
