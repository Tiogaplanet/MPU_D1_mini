---
name: Bug report
about: Create a report to help us improve
title: "[BUG] "
labels: ''
assignees: ''

---

---
name: Hardware / PCB Bug Report
about: Create a report for a hardware issue, schematic error, or PCB defect.
title: "[PCB Bug] [Revision] - [Brief summary of the issue]"
labels: ['hardware', 'bug']
assignees: ['']
---

### 📋 Overview
A clear and concise description of the bug. (e.g., "5V regulator overheating," "I2C bus not pulling high," "Trace shorted near U1").

### 🎛️ Revision & Environment
* **PCB Revision:** [e.g., v1.2, Prototype B]
* **Assembly Status:** [e.g., Bare board, Fully assembled]
* **Firmware/Software Version:** [If testing with code, note the commit hash or tag]

### 🐞 Defect Details
Please provide the exact location and symptoms:
* **Location on Board:** [e.g., U4, Q2, between R12 and C5]
* **Expected Behavior:** [e.g., Output should be a steady 3.3V]
* **Actual Behavior:** [e.g., Output is oscillating at 120kHz / 0V]

### 📐 Reproduction Steps
What another person has to do to see the bug or test the failure:
1. Apply [e.g., 12V DC] to the [e.g., VIN] terminal.
2. Measure voltage at [e.g., test point TP1].
3. Observe [e.g., smoke coming from component D1].

### 📸 Evidence & Diagnostics
* **Visual Proof:** [Attach images of the physical board, zoomed in on the failed component, or solder joints].
* **Measurements:** [Provide multi-meter, oscilloscope screenshots, or thermal camera images].
* **Relevant Files:** [e.g., Link to a specific commit, schematic snapshot, or Gerber layer].

### 🛠️ Additional Context
Any other context about the problem (e.g., "I noticed a footprint mismatch for the JST connector," or "Testing was done at 60°C ambient temperature").
