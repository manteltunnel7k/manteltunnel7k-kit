# manteltunnel7k-kit

Sort a folder of files into per-type subfolders.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m manteltunnel7k_kit.cli --help
```

```python
from manteltunnel7k_kit.core import Manteltunnel7kTool

tool = Manteltunnel7kTool()
print(tool)
```

## Layout

```
manteltunnel7k_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 manteltunnel7k
