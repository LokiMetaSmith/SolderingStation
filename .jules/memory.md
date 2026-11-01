## Archived: 2026-10-31

* Repository contains hardware design, firmware, and documentation for a custom STM32-based project.
* `Docs/` directory holds various datasheets, application notes, and reference manuals (e.g., STM32F0 HAL, LM7805, LCD displays).
* `Firmware/` directory contains an STM32CubeMX-generated project (STM32F0xx), complete with HAL drivers, `Inc/`, and `Src/` containing main logic and LCD handling.
* `Model/` directory includes LTspice simulation files (`.asc`) for components like power supply startup, RF stages, and tip detector.
* `Theory/` directory provides PIXls design spreadsheets and calculations.
* `gerber/` directory holds PCB manufacturing files (gerber files and drill files).
* Root level contains layout and schematic files (`pcb1.dip`, `ps1.dch`), and images.
