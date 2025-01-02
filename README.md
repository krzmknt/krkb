# KRKB (KRzmknt's KeyBoard configuration)

## Dependencies

First, please install `mise`.

- mise (tested with the version "2025.1.0 macos-arm64 (ef6936a 2025-01-01)")

## Installation

To install dependencies other than `mise`, run the following command:

```bash
mise i
```

This will install `uv`. Use `uv` to install the Python version specified in `.python-version`.

```bash
uv install
```

Then, use uv to install the required Python packages.

```bash
uv sync
```

Iinitialize the ZMK repository and update it.

```bash
cd zmk
west init -l app
west update
```

## Build

Build the project by running the following command:

```bash
./build
```
