# Yandex Practicum Git Exercises

This repository is a unified collection of small Git practice projects created during the Yandex Practicum course.  
It contains exercises, examples, and experiments with Git concepts, branching, forking, and GitHub workflows.

> ⚠️ **Note:** Individual repositories were merged into this monorepo using `git subtree`, preserving all commit histories.

---

## Cloning Specific Subprojects

You can clone only a single folder if you don't want the entire repository. For example, to clone only the `git-fork-case` folder:

```bash
git clone --filter=blob:none --sparse https://github.com/Stepsyota/Yandex-Practicum-Git-Exercises.git
cd Yandex-Practicum-Git-Exercises
git sparse-checkout set git-fork-case
