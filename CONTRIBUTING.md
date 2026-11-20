# Contributing to Pulse Linux

Thank you for your interest in contributing to **Pulse Linux** — *One Operating System. Two Worlds. Unlimited Possibilities.*

## How You Can Contribute

1. **Reporting Bugs**:
   * Verify the bug reproduces on the latest  ISO or package build.
   * Check existing issues before opening a new one.
   * Provide system hardware info, kernel logs (), and reproduction steps.

2. **Developing Core Packages & Scripts**:
   * Fork the [](https://github.com/Pulse-Linux/pulse) repository.
   * Create a feature branch: .
   * Follow PEP 8 for Python scripts and POSIX shell standards for shell scripts.
   * Test rootfs and ISO builds locally before submitting a Pull Request.

3. **Packaging Security Tools & Developer SDKs**:
   * Follow the modular isolation guidelines: tools must never clobber Debian base libraries.
   * Use containers or Flatpaks for rolling/bleeding-edge toolchains.

4. **Desktop Themes & Wallpapers**:
   * Wallpapers must be provided in vector SVG (3840x2160, 4K) adhering to the Pulse color palette.
   * GTK and GNOME Shell themes must support both light and dark variants.

## Submitting a Pull Request
* Ensure commit messages follow Conventional Commits (e.g., , , , ).
* Open a PR against the  branch with a clear description of changes.
