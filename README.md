# webapp-common

Shared, non-code files (setup guides, notes, .cmd scripts) for Vijay's web apps:
Baro Stay web and future projects. No app source code lives here.

## Contents
- `docs/` - shared guides (empty for now).

## Reuse in a project
Option 1 - clone next to the project (simplest):

    cd D:\mobileapp
    git clone https://github.com/VijayVaithiyanathan/webapp-common.git

Option 2 - add as a git submodule inside a project:

    git submodule add https://github.com/VijayVaithiyanathan/webapp-common.git common
    git submodule update --remote common   (to pull later changes)

Mobile projects use the sibling repo `mobileapp-common` the same way.
