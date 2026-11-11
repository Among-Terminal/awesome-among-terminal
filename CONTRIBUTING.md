# Contributing

## Add a plugin

Open a pull request that adds one plugin to a category in [README.md](README.md). Choose the category that fits what the plugin does, or propose a new category in the pull request. For notifications, choose Event producers, Controls or Delivery channels. Keep official entries first, with official and community entries each in alphabetical order by plugin name within their category. Use this row format:

```markdown
| Plugin name | One sentence about what it shows or does. | Required: list access; optional: list access or none. | [owner/repository](https://github.com/owner/repository) |
```

Replace the placeholders with your plugin's details. Describe access in plain language and distinguish required access from optional access. Fill in the pull request template, including the Among version you tested with.

## Entry requirements

- A public GitHub repository with the plugin's source code available.
- Built from or compatible with the [plugin template](https://github.com/Among-Terminal/among-plugin-template), so Among can install it.
- At least one published stable release. The latest stable release must be immutable and include `among-plugins.json` and matching package assets in the format produced by the template's release workflow. Follow the [packaging and release instructions](https://github.com/Among-Terminal/among-plugin-template/blob/main/docs/releasing.md#repository-releases-and-install-verification).
- A licence file in the plugin repository.
- A README that explains what the plugin shows or does and which access it requests, including required and optional access.

## Update or remove an entry

Open a pull request that edits or removes the row. Explain what changed or why the entry should be removed. Keep official entries first and preserve alphabetical order within each group in the category. To report a plugin that no longer installs or misbehaves, use the broken-entry issue template.

Maintainers may remove entries that stop working or mislead users.
