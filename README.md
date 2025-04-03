# configs

## Pre commit stuff
I prefer no dependencies so I would rather use the .pyz file for pre-commit hooks.

Print sample config:
``` bash
python pre-commit-4.2.0.pyz sample-config
```

Install git hooks:
``` bash
python pre-commit-4.2.0.pyz install
```

Running:
``` bash
python pre-commit-4.2.0.pyz run --all-files
```
