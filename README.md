# homebrew-tap

Custom Homebrew formulae by generalquin1991.

## Available formulae

- **holdcom** — on-demand serial take-over that never resets the MCU (picocom-like).
  Install (on brew 4.x a third-party tap must be trusted first):

  ```bash
  brew tap generalquin1991/tap
  brew trust generalquin1991/tap   # required once; otherwise sandbox_apply fails
  brew install holdcom
  ```

  `holdcom` is a pure-stdlib Python script; it runs with whatever `python3`
  is already on your PATH (macOS built-in, Homebrew, or user-installed) — no
  separate Python interpreter is pulled in.
