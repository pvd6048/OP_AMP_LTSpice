# Course Project EE206: Analog Circuits {Two-Stage OTA Design (TSMC180nm CMOS, LTspice)} 
**Author:** Pranav Vishal Deshmukh (ID: 230102073)

##  Problem Statement

Design a two-stage operational transconductance amplifier (OTA) using **TSMC 180nm technology** with the following specifications:

- OTA should be used in a **non-inverting amplifier** configuration with a **closed-loop gain of 2**.
- The **open-loop DC gain** of the OTA must be **at least 40 dB**.
- The amplifier must be **stable**, with a **phase margin of approximately 60°**.
- The design should respond properly to a **0.2 V step input**.

All simulations are performed in **LTspice**, and manual calculations were used for designing transistor widths, lengths, compensation, and other key analog parameters.

---

## 📁 Files Included

### 📄 Design Files
- `2_stage_ota_spandan_230102108_open_loop_2.asc`: Open-loop OTA schematic (DC gain ≈ 2360)
- `2_stage_ota_spandan_230102108_closed_loop.asc`: Closed-loop OTA schematic (non-inverting amplifier, gain ≈ 2)

### Documentation
- `230102108_Spandan_OTA.pdf`: Full report containing:
  - Design procedure
  - Hand calculations for MOSFET sizing
  - Gain, phase margin, and bandwidth analysis
  - Observations from simulations

- `Assignment_OTA_design.word`: Original problem statement (assignment brief)

### Screenshots (Located in `screenshots/`)
- `Bandwidth 1`: Bandwidth plot from AC analysis
- `DC_op`, `DC_op_2`: DC operating points of different nodes
- `Log_file`, `Log_file_2`: LTspice simulation logs
- `Open_loop_first_stage_and_overall_vout_with_0.1mv_sine_wave_input`: Small-signal open-loop response
- `Phase-Margin`: Phase margin verification plot (~60°)
- `Step_input_0.2v`: Transient step response of 0.2 V input (closed-loop)

---

## Technology & Tools
- **LTspice** for simulation
- **TSMC 180nm CMOS** design assumptions
- **Analog CMOS Design** principles (manual sizing, compensation)

---

## Key Design Highlights
- ✅ **Open-loop gain**: ~2360 (≈ 67.4 dB)
- ✅ **Closed-loop gain**: ≈ 2 (non-inverting)
- ✅ **Phase margin**: ~60°
- ✅ **Bandwidth**: Verified through simulation
- ✅ **Stable step response** to 0.2 V input

---

## 📚 References
- EE206: Analog Electronic Circuits, course materials and assignments  
- Behzad Razavi, *Fundamentals of Microelectronics*, Wiley, 2nd Edition

---
