# Hermes 🦀

Hermes is a cross-platform file manager written in C++, designed to empower users with intelligent task and file management. With planned AI integrations, Hermes aims to combine speed, usability, and advanced intelligence to redefine how users interact with their files. Hermes is part of a larger ecosystem of tools, including [SeaShell 🐚](https://github.com/JustinPhillipsPDX/SeaShell) and [Proteus 🐍](https://github.com/JustinPhillipsPDX/Proteus).

## Features (Planned)
- **Cross-Platform Support**: Seamless functionality on Windows, macOS, and Linux.
- **AI Integrations**: Smart suggestions, automation, and task initiation (details TBD).
- **Efficient Task Management**: Enhance productivity with intelligent workflows.
- **Integration with Proteus**: Provides enhanced functionality within the Proteus 🐍 window/tiling manager.

## Project Goals
1. Build a robust file manager core with standard file operations.
2. Design platform-specific modules for OS-level compatibility.
3. Integrate AI features to enhance functionality.
4. Seamlessly interact with Proteus 🐍 for a unified user experience.

## Development Setup

### Requirements
- A C++ compiler (GCC, Clang, or MSVC)
- CMake (3.10 or higher)
- Git for version control
- [SeaShell 🐚](https://github.com/JustinPhillipsPDX/SeaShell): For installation and build automation.

### Build Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/JustinPhillipsPDX/Hermes.git
   cd Hermes
   ```

2. Use [SeaShell 🐚](https://github.com/JustinPhillipsPDX/SeaShell) for installation and compilation:
   - **Linux/macOS**:
     ```bash
     ./install.sh
     ```
   - **Windows** (run in PowerShell):
     ```powershell
     ./install.ps1
     ```

3. Follow the prompts to complete the setup.

## Roadmap
- [x] Repository setup
- [ ] Core file manager functionality
- [ ] Platform-specific modules
- [ ] AI integration prototypes
- [ ] User interface design (via Proteus 🐍)
- [ ] Full integration with Proteus and SeaShell

## License
This project is licensed under the [MIT License](LICENSE).
