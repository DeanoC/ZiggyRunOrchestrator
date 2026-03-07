# ZiggyRunOrchestrator

Shared run lifecycle orchestration module for Ziggy runtime projects.

## Scope

- `run_engine` lifecycle state machine and persistence-backed run/event orchestration.
- `run_orchestration_helpers` timeout policy and run-step cancellation tracking utilities.

## Development Checkout

This development line tracks first-party dependencies as git submodules.
Use a recursive checkout instead of a source archive:

```bash
git clone --recursive https://github.com/DeanoC/ZiggyRunOrchestrator.git
```

If you already cloned the repo, initialize submodules with:

```bash
git submodule update --init --recursive
```

Source archive installs are not supported for the current development branch.

## Build

- `zig build`
- `zig build test`
