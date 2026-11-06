# GitIgnoreDoctor

Audit repository ignore rules against generated, secret, cache, build, and IDE artifacts that commonly leak into commits.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/GitIgnoreDoctor.git
cd GitIgnoreDoctor
python -m pip install .
```

## Usage

```bash
gitignore-doctor --help
```

## Development

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## License

MIT License.
