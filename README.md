# agent-reach

Sandbox repo for installing and testing the [agent-reach](https://github.com/Panniantong/agent-reach) CLI.

agent-reach is a third-party tool that gives an AI agent read/search access to
web pages, YouTube, GitHub, Twitter/X, Reddit, and other platforms, storing
auth tokens/cookies locally.

## Setup

```
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
```

## Usage

```
.venv/bin/agent-reach doctor
.venv/bin/agent-reach setup
```

See the upstream repo for full documentation and platform setup instructions.
