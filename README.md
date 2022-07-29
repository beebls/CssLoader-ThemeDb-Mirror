# CssLoader-ThemeDb-Mirror
This mirrors SuchMemeManySkill's CssLoader-ThemeDb JSON file in a format that does not have CORS restrictions.

## Why?
In order to create a web-accessible viewer for CssLoader themes, I needed a way to access the data in the themes.json file contained in release 1.0 of the ThemeDb repo.
However, unlike raw.githubusercontent.com files, github release files do not have CORS headers, so any fetch returns an opaque response with no usable data.

This repo clones that themes.json file into an actual repo itself, it is slightly commit-spammy, but it works.
