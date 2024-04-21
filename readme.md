
# Lecture Repository

Welcome to the lecture Repository! This README provides instructions on how to set up and use LaTeX with Visual Studio Code (VSCode) on Ubuntu. 

## Getting Started

### Prerequisites

Ensure you have the following installed on your Ubuntu system:
- **Ubuntu OS**: A recent version is recommended.
- **TeX Live**: A comprehensive TeX document production system.
- **Visual Studio Code (VSCode)**: A powerful source code editor.

### Installing TeX Live

To install TeX Live on Ubuntu, follow these steps:

1. Open a terminal window.
2. Update your package list:
   ```bash
   sudo apt update
   ```
3. Install TeX Live:
   ```bash
   sudo apt install texlive-full
   ```
   This command installs the full TeX Live distribution, which includes all the packages and fonts necessary for most LaTeX projects.

### Installing Visual Studio Code

Visual Studio Code can be installed from the Snap Store:

```bash
sudo snap install --classic code
```

### Setting Up LaTeX in VSCode

1. **Install LaTeX Workshop Extension**:
   - Open VSCode.
   - Go to the Extensions view by clicking on the square icon in the sidebar or pressing `Ctrl+Shift+X`.
   - Search for "LaTeX Workshop" and install it.
   - This extension provides rich editing support for LaTeX, including compiling LaTeX into PDFs.

2. **Configure LaTeX Workshop**:
   - After installation, configure the extension to suit your workflow. You can access settings by going to File -> Preferences -> Settings.
