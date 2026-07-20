# Changelog

Todas as mudanças importantes deste projeto serão documentadas neste arquivo.


## Unreleased



### Outras alterações


- Initial commit

- Rename mod to Trancendental Dagger

Rename the mod directory from the generic template name '[CP] MOD NAME' to '[CP] Trancendental Dagger'. Update manifest.json to reflect the actual mod name and unique ID instead of placeholders.

- Add automated changelog generation with git-cliff

Set up GitHub Actions workflow to automatically generate and update CHANGELOG.md on pushes to main using git-cliff. Includes configuration for conventional commit parsing with localized category groupings (feat, fix, perf, etc.).


