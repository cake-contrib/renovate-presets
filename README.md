# Renovate presets

This repository contains [shared presets] for [Renovate] used in the repositories of this organization.

## Usage

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>cake-contrib/renovate-presets"]
}
```

## Available presets

| Preset                                                | Description                                                                  |
|-------------------------------------------------------|------------------------------------------------------------------------------|
| `github>cake-contrib/renovate-presets`                | [Default configuration](default.json)                                        |
| `github>cake-contrib/renovate-presets:cake-issues`    | [Configuration for Cake.Issues addins](cake-issues.json)                     |
| `github>cake-contrib/renovate-presets:cake-recipe`    | [Configuration for Cake.Recipe based addins](cake-recipe.json)               |
| `github>cake-contrib/renovate-presets:frosting-addin` | [Additional configuration for addins for Cake Frosting](frosting-addin.json) |

[shared presets]: https://docs.renovatebot.com/config-presets/
[Renovate]: https://renovatebot.com/
