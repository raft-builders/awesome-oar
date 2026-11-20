# Contribution Guidelines

- The project must actually use [OAR](https://github.com/botiverse/oar) (`@botiverse/oar` or `@botiverse/oar-cli`): as a library, through the CLI, or as a runtime driver or plugin. Say where in the pull request (for example a dependency in `package.json` or a section of the readme).
- Projects that only share the name are out of scope, such as Open Agent Relay (`@oar-sh/oar`), Open Action Record (`@openactionrecord/*`), `@carjms/oar-cli`, `@ferry-core/oar` and `@super-oar/*`.
- The repository must be public and have a readme that explains what the project does.
- One project per pull request. Use the format: `- [name](link) - Description.`
- Keep descriptions short, start with a capital letter and end with a period. Add `(Chinese)` or another language when the readme is not in English.
- Add it to the most relevant section. Projects from [Botiverse](https://github.com/botiverse) that are part of OAR itself go under **Official**.
- Add it at the end of the section and leave out the star count. Every list is sorted by GitHub stars, most first, and a [daily workflow](.github/workflows/stars.yml) updates the counts and the order. Entries that are not GitHub repositories (npm packages, folders in a larger repository) go after the ones with stars.
- Skip projects that are empty, abandoned or only a placeholder.
