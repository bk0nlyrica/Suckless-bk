# Suckless Utilities Collection

This repository contains a curated collection of utilities from the [Suckless](https://suckless.org) project. These tools are designed to be minimal, efficient, and highly customizable through source code modifications.

## Purpose

The purpose of this repository is to maintain a personal configuration of Suckless tools with custom patches and modifications that enhance functionality while preserving the minimalist philosophy. By keeping these configurations in one place, it's easier to manage, update, and deploy across different systems.

## Included Tools

The collection includes the following Suckless utilities:

- **dwm** - Dynamic Window Manager: A lightweight and highly customizable tiling window manager that organizes windows efficiently.
  
- **dmenu** - Dynamic Menu: A fast and lightweight dynamic menu for X, primarily used as an application launcher but versatile enough for various menu needs.
  
- **st** - Simple Terminal: A minimalist terminal emulator that focuses on simplicity and performance.
  
- **slock** - Simple X Lock: A simple screen locker utility for X.
  
- **slstatus** - Status monitor for window managers that support text in the status bar (like dwm).

## Compilation Instructions

Each Suckless tool follows the same basic compilation pattern:

1. Navigate to the tool's directory:
   ```bash
   cd [tool-name]
   ```

2. Compile and install:
   ```bash
   make clean install
   ```

*Note: You may need root privileges for installation, in which case use:*
   ```bash
   sudo make clean install
   ```

### Requirements

To compile these utilities, you'll need:

- A C compiler (gcc or clang)
- X11 development libraries
- make
- Various dependencies depending on the specific tool

On Debian/Ubuntu-based systems, you can install the basic dependencies with:
```bash
sudo apt install build-essential libx11-dev libxft-dev libxinerama-dev
```

## Customization

The beauty of Suckless tools lies in their customizability through code modifications. Configuration is done by editing source files (usually `config.h`) and recompiling the program.

1. Make your changes to the configuration files
2. Recompile and reinstall using the instructions above
3. Restart the application to apply changes

## Contributing

Feel free to suggest improvements or share your own patches and configurations by opening an issue or pull request.

---

*This collection is maintained independently and is not officially affiliated with the Suckless project.*

