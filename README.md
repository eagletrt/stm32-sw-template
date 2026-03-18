## Git Hooks
> [!Warning]
> Make sure to add all the needed directories in TARGET_DIRS

To setup git hooks in your local repository you will have to execute the following commands:
```sh
cd <library-name>
```

```sh
chmod +x hooks/pre-commit
```

```sh
git config core.hooksPath hooks/
```
