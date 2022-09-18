# Lapce plugin for Yaml (`yaml-language-server`)

## Prerequisites

Install `yaml-language-server` (Requires NodeJS) via `npm` or your system package manager

```shell
npm i --global yaml-language-server
```

## Configuration

In `settings.toml`:

```toml
[lapce-yaml.volt]
serverPath = "<custom executable>"
serverArgs = ["--stdio"] # --stdio is required for all LSPs made in nodejs
```
