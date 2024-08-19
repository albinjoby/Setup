# Mac Setup Automation

This repository contains the initial setup scripts and package lists for quickly configuring a development environment on a new macOS machine.

## Files in the Repository

1. **`casks.txt`**:  
   A list of applications to install via Homebrew Cask.

2. **`run.sh`**:  
   A shell script that reads from `casks.txt` and installs each application listed using Homebrew Cask.

## Prerequisites

1. **Homebrew**:  
   Make sure you have Homebrew installed. You can install it by running the following command in your terminal:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"