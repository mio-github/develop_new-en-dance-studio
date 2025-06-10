# Git Repository Restructuring

**Date:** 2025-06-10

## Action Taken

To prepare the project for pushing to a new central GitHub repository (`https://github.com/mio-github/develop_new-en-dance-studio`), the following nested Git repositories were removed:

-   `connect_en_docs/.git`
-   `connect_en_github/.git`

This action was taken to ensure that all files within these directories are included as part of the main project, rather than being treated as submodules. This allows for a unified version history for the entire `EnDaceStudio` project.
