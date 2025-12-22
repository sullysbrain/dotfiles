# UV Notes

## pylock.toml

- Export from uv.lock to pylock.toml
uv export -o pylock.toml

- Compile from a requirements.in to pylock.toml
uv pip compile -o pylock.toml -r requirements.in

- Install from pylock.toml
uv pip sync pylock.toml

source: https://github.com/astral-sh/uv/releases/tag/0.6.15?featured_on=pythonbytes


