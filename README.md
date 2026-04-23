# STM32CubeMX PlatformIO Project Template

To get started, create a repo starting from this template and clone it locally.

## Steps

1. Generate the code from CubeMX into the folder.
2. Modify the `platformio.ini` to compile your exact structure (check other repositories for examples).
3. Setup git hooks (instructions below).
4. Setup Doxygen (instructions below).

## Git Hooks
> [!Warning]
> Make sure to add all the needed directories in TARGET_DIRS

To setup git hooks in your local repository you will have to execute the following commands:
```sh
cd <project-name>
```

```sh
chmod +x hooks/pre-commit
chmod +x hooks/commit-msg
```

```sh
git config core.hooksPath hooks
```

## Doxygen setup

If the project structure is the normal **CubeMX** generated, you only need to change the `PROJECT_NAME`, `PROJECT_NUMBER` and `PROJECT_BRIEF` variables in the `Doxyfile` to generate the documentation. 
