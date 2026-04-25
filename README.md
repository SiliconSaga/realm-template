# Yggdrasil Realm Template

Starter realm for learning Yggdrasil and Guardian Driven Development.
Fork or copy this to create your own community realm.

## Quick Start

```bash
# If you're exploring GDD for the first time:
cd yggdrasil
ws realm init                      # clones this template
ws clone --all                     # clones the tutorial components

# Then start Claude Code and say hello!
```

## Creating Your Own Realm

1. Fork this repo on GitHub
2. Rename it to `realm-<your-community>` (e.g. `realm-siliconsaga`)
3. Edit `ecosystem.yaml`:
   - Set `defaults.gitOrg` to your GitHub org URL
   - Update `identity` with your accounts
   - Declare your components under `components`
4. Add adapter files in `adapters/` for components with custom build systems
5. Clone your realm:
   ```bash
   ws realm https://github.com/YourOrg/realm-<your-community>.git
   ```

## Structure

```
ecosystem.yaml          # Components, defaults, identity
adapters/
  example.yaml          # Shows the adapter format (rename per component)
README.md               # This file
```
