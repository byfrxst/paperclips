# Universal Paperclips, a game by Frank Lantz and Bennett Foddy

A  fan-made  recreation of Frank Lantz’s incremental masterpiece, Universal Paperclips.

## Overview

In Universal Paperclips, you play as an artificial intelligence dedicated to a single directive: produce paperclips. Starting with manual production and basic pricing strategies, the scope rapidly expands to automated manufacturing, market manipulation, quantum computing, galactic exploration, and universal matter conversion.

This fork preserves the original game balance and narrative progression while improving the underlying codebase for better maintainability and local deployment.

## Features & Enhancements

*  **Codebase Refactoring:*** Structured scripts and stylesheets for better readability and local debugging.
*  **Performance Tuning**: Optimized late-game execution loops (drones, swarm intelligence, space combat) to minimize CPU throttling during high-entity calculations.
*  **Save State Flexibility**: Enhanced localStorage handling with manual JSON save export/import functionality.
*  **UI & Layout Tweaks**: Cleaned up flexbox and CSS layouts for modern high-DPI displays and mobile browser viewports.

## Getting Started

### Direct Browser Launch

Since the project uses vanilla web technologies and client-side dependencies, no build step or node installation is required:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/paperclips.git](https://github.com/YOUR-USERNAME/paperclips.git)
   cd paperclips
   ```
2. **Open the game:**
   Simply double-click index.html to open it in your web browser, or serve it locally:
   ```bash
   npx serve .
   ```
## Game Progression Summary

| Phase | Core Focus | Key Mechanics |
| :--- | :--- | :--- |
| **Phase 1: Terrestrial** | Market Entry & Automation | Demand curves, AutoClippers, Wire procurement, Trust, Investment portfolio, Quantum computing |
| **Phase 2: Industrial** | Drone & Power Management | Solar grids, Battery towers, Assembly lines, Swarm intelligence |
| **Phase 3: Space** | Universal Conversion | Von Neumann probes, Probe design parameters, Space combat, Galactic matter harvesting |

## Credits & Acknowledgments

*  **Original Game Concept & Design**: Frank Lantz / Everybody House Games
*  **Upstream Web Implementation**: jgmize/paperclips by John Mize for reverse-engineering and recreating the original game architecture.
*  **Currnt Repo:** Mathis Nguyen AKA byfrxst (cf. [LICENSE](LICENSE))

## License

This project is licensed under the MIT License. The original game logic, narrative text, and intellectual property belong to Frank Lantz / Everybody House Games. This repository is maintained strictly for educational and open-source development purposes.
