# Yggdrasil Overlay Template

Starter overlay for learning Yggdrasil and Guardian Driven Development.
Fork or copy this to create your own community overlay.

## Quick Start

```bash
# If you're exploring GDD for the first time:
cd yggdrasil
ws overlay init                    # clones this template
ws clone --all                     # clones the tutorial components

# Then start Claude Code and say hello!
```

## Creating Your Own Overlay

1. Fork this repo on GitHub
2. Rename it to `overlay-yggdrasil-live` (or any name you prefer)
3. Edit `ecosystem.yaml`:
   - Set `defaults.gitOrg` to your GitHub org URL
   - Update `identity` with your accounts
   - Declare your components under `components`
4. Add adapter files in `adapters/` for components with custom build systems
5. Clone your overlay:
   ```bash
   ws overlay https://github.com/YourOrg/overlay-yggdrasil-live.git
   ```

## Structure

```
ecosystem.yaml          # Components, defaults, identity
adapters/
  example.yaml          # Shows the adapter format (rename per component)
README.md               # This file
```
