# FLUX.1 Prompt Engineer Skill Package

## Overview

When installed, Claude will automatically use this skill whenever users request AI-generated images.

## What's Inside

### SKILL.md (Main Instructions)

- Core workflow for generating three prompt variants
- Prompt construction principles (specificity, layering, dynamics)
- Anti-patterns to avoid
- Quick examples
- References to advanced techniques

### Reference Files (Loaded on demand)

1. **layering-hierarchy.md** - Foreground/middle/background composition techniques
2. **contrasts.md** - Visual impact through color and aesthetic contrasts
3. **text-rendering.md** - Font selection, styles, and text integration
4. **camera-settings.md** - Technical parameters (cameras, lenses, ISO, aperture)
5. **materials-textures.md** - Transparent materials, reflections, atmospheric effects
6. **advanced-techniques.md** - Artistic references, concept blending, temporal narratives

## How It Works

1. **User requests an image** → Claude automatically triggers this skill
2. **Claude analyzes the request** → Identifies key elements, mood, style
3. **Claude generates three variants** → Each in a code block for easy copying
4. **Advanced requests** → Claude reads relevant reference files as needed

## Key Features

- ✅ **Progressive disclosure** - Only loads detailed references when needed
- ✅ **Token-efficient** - Concise main instructions, comprehensive references
- ✅ **Three variants** - Gives users options for different interpretations
- ✅ **Best practices** - Incorporates all techniques from your original guides
- ✅ **Anti-pattern awareness** - Avoids Stable Diffusion syntax and common mistakes

## Installation

Upload the `flux-prompt-engineer.zip` file to Claude as a custom skill. Once installed, simply ask Claude to create images and it will automatically use this skill to generate optimized FLUX.1 prompts.

## Example Usage

**User:** *"Create a cyberpunk street scene"*

**Claude will output three code blocks:**

```prompt
[Detailed prompt with layering, technical specs, mood]
```

```prompt
[Alternative interpretation with different angle/time]
```

```prompt
[Creative variation with unique elements]
```

## Structure

```shell
flux-prompt-engineer/
├── SKILL.md (4.5K - always loaded)
└── references/ (23K - loaded on demand)
    ├── layering-hierarchy.md
    ├── contrasts.md
    ├── text-rendering.md
    ├── camera-settings.md
    ├── materials-textures.md
    └── advanced-techniques.md
```

## Configuration Notes

- Optimized for `FLUX.1 [dev]` variant
- Default settings:
  - Guidance Scale: `3.5`
  - Steps: `50`
  - Dimensions: `1024x1024`
