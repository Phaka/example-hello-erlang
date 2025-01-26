# Hello World in Erlang

A minimal Erlang implementation of "Hello, World!".

## Installation

### macOS
```bash
brew install erlang
```

### Linux
```bash
sudo apt install erlang  # Ubuntu/Debian
sudo dnf install erlang  # Fedora/RHEL
```

### Windows
Download from https://www.erlang.org/downloads

## Running

```bash
erlc hello.erl
erl -noshell -s hello main -s init stop
```

## Code Explanation

Uses io:format for console output with ~n for newline.
