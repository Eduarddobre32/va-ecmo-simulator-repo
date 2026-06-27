# VA-ECMO Advanced Simulator

A single-file, offline-capable teaching simulator for **veno-arterial ECMO** (femoro-femoral), built for medical students and bedside teaching.

Open `index.html` in any modern browser — no build step, no internet required. All images and physiology are embedded.

## Scenarios
1. **Harlequin / differential hypoxia** — north–south syndrome; right radial vs left radial blood gases; cerebral & limb NIRS.
2. **LV ballooning** — aortic valve closure, LV distension, pulmonary edema, and unloading (inotrope / IABP / Impella / lower flow).
3. **Limb ischemia** — femoral cannula occlusion, distal perfusion cannula, compartment syndrome.
4. **Impella / ECPELLA** — Impella P-level unloading combined with VA-ECMO.
5. **Weaning** — turn-down trial distinguishing a recovered from a failing heart.

## Features
- Bedside monitor with live ECG / arterial line / dual pleth / CVP waveforms and an oxygenator pressure strip.
- ECMO console (RPM-driven flow), gas blender (FiO₂ + sweep), Impella P-level, and a pressure-control ventilator.
- Steady-state physiology engine: aortic watershed / mixing point, LV pressure–volume model, Hgb-based O₂ delivery, acid–base from sweep gas, regional NIRS.
- Movable **aortic transition point** illustration that recolors the aorta and arch branches by the ECMO ↔ native mixing front.
- **Challenge mode** — diagnose the hidden scenario, treat it, and get scored against scenario-specific goals.
- Built-in teaching reference table.

*Educational use only — not a substitute for clinical judgement or device manuals.*

<!-- pages rebuild trigger -->
