# RainbowTags
A port of rainbowtags before it was archived. Find original [here](https://github.com/BuildBoy12-SL/RainbowTags).

# Features
- Detects if the user is in 173 and replaces their item with a whitelisted item.

# Default config:
```yaml
rainbow_tags:
  is_enabled: true
  debug: false
  # The time, in seconds, between switching to the next color in a sequence.
  tag_interval: 0.5
  # A collection of group names with their respective color sequences.
  sequences:
    owner:
    - red
    - orange
    - yellow
    - green
    - blue_green
    - magenta
    admin:
    - green
    - silver
    - crimson

```
# Installation

**[EXILED](https://github.com/galaxy119/EXILED) must be installed for this to work.**

Place the "RainbowTags.dll" file in your Plugins folder.

# Find colors by using `colors` in the `~` console.
