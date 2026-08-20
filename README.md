
# Electronics Engineer – Working Criteria

## Objective

Demonstrate practical, hands-on capability in electronics engineering through working projects and reproducible results.

## Scope

This repository focuses on:

- Functional hardware designs (schematics + PCB)
- Working firmware / embedded code
- Basic validation and test evidence

Non-essential content (long bios, resumes, excessive theory) is intentionally minimized.

## Working Criteria for Projects

Each project in this repository must satisfy:

1. **Clear Functionality**
   - The intended function is stated in 1–2 lines.
   - Inputs, outputs, and operating conditions are defined.

2. **Reproducible Hardware**
   - Schematics are complete and legible.
   - BOM is provided with part numbers and key parameters.
   - PCB files (or at least Gerbers) are included if applicable.

3. **Working Firmware / Logic**
   - Source code is included and builds without manual patching.
   - Build instructions (toolchain, IDE, commands) are provided.
   - Configuration files and pin mappings are documented.

4. **Basic Validation**
   - At least one of:
     - Measured waveforms / logs showing correct operation
     - Test procedure with expected vs observed results
     - Simple demo script or test firmware
   - Any known limitations or failure modes are listed.

5. **Usability**
   - A short “How to run” section:
     - Required tools and versions
     - Step-by-step build/flash/deploy instructions
     - How to verify it works (e.g., LED blink pattern, serial output, sensor reading)

6. **Safety & Constraints**
   - Voltage/current limits clearly stated.
   - Any safety warnings (e.g., mains voltage, high current, Li-ion) are explicit.
   - Operating temperature/environment constraints noted if relevant.

## Repository Structure (Recommended)

- `projects/` – Each subfolder is a self-contained, working project.
- `libs/` – Reusable hardware/firmware components used by projects.
- `docs/` – Shared notes, checklists, and templates.

Each project folder should contain at minimum:

- `README.md` – Function, how to build/run, validation evidence.
- `hardware/` – Schematics, BOM, PCB files/Gerbers.
- `firmware/` – Source code, build instructions.
- `tests/` (optional) – Test scripts, logs, screenshots.

## Acceptance Checklist (Per Project)

Before adding a project, ensure:

- [ ] It powers on and performs its main function.
- [ ] Another engineer can rebuild it from the repo alone.
- [ ] Build and test steps are documented and verified.
- [ ] No critical safety information is missing.

## Contact

- Email: aghkmnrsu@gmail.com
Website :
https://aghkmnrsu-cell.github.io/electronics-engineer
