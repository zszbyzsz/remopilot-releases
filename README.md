# RemoPilot downloads

Official signed binary distributions of RemoPilot. The application source is private.

Supports macOS 14+ (Apple Silicon and Intel) and glibc Linux (ARM64 and x86-64).

Install through the public Homebrew tap:

```sh
brew install zszbyzsz/remopilot/remopilot
remopilot homebrew --action install
remopilot setup
```

For upgrades, run `brew update`, `brew upgrade zszbyzsz/remopilot/remopilot`, then `remopilot homebrew --action install`. Existing configurations are retained; setup is for first-time users.

Homebrew manages candidate packages; the activated program and retained generations live outside Cellar. Do not use `brew services`; use RemoPilot's existing setup and service management.

Release packages include third-party notices and the application input required for LGPL relinking. RemoPilot is proprietary; third-party components retain their respective licenses.

Website: https://remopilot.com
