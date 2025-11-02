# Firmware

This folder stores firmware and scripts used to run LuPiScope on a Raspberry Pi. Expected contents:

- `pi/` — Raspberry Pi-specific setup, services, and install scripts
- `firmware/` — compiled firmware binaries if applicable (note: prefer source whenever possible)
- `docs/` — flash instructions, dependencies, and a changelog

Security note: Do not commit secrets or private keys. Use configuration templates (e.g., `config.example.yml`).
