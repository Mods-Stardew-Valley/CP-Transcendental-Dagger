# Changelog

Todas as mudanças importantes deste projeto serão documentadas neste arquivo.


## v0.0.0 - 2026-08-18



### Outras alterações


- Initial commit

- Rename mod to Trancendental Dagger

Rename the mod directory from the generic template name '[CP] MOD NAME' to '[CP] Trancendental Dagger'. Update manifest.json to reflect the actual mod name and unique ID instead of placeholders.

- Add automated changelog generation with git-cliff

Set up GitHub Actions workflow to automatically generate and update CHANGELOG.md on pushes to main using git-cliff. Includes configuration for conventional commit parsing with localized category groupings (feat, fix, perf, etc.).

- melhorado automação

update do yml

- Add Transcendental Dagger assets and data

Add 10 dagger textures and wire them into Content Patcher. content.json now loads tk-lv01..tk-lv10, registers 10 new weapons (tk-lv_1..tk-lv_10) with stats and sets crafting recipe entries. Remove obsolete Leiame.txt. Update manifest metadata: version, description, UniqueID and UpdateKeys (GitHub + Nexus).

- Fix manifest update URL

Correct the GitHub UpdateKey in the mod manifest so update checks point to the proper repository for the Transcendental Dagger content pack.


### ♻️ Refatoração


- estrutura de pastas


### 📚 Documentação


- atualiza CHANGELOG.md [skip ci]


