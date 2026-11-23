# SafeOperate-EIRP-26-27


**Engineering Innovation Recognition Programme (EIRP 26/27)**  
*University of Nottingham Malaysia — Robotics Society & Department of EEE*

## Team Members
LIM YI XUEN, 20798466
TOMI NGU HONG HUI, 20806410
FOO FANG YANG, 20795270
ANSON GOH, 20713961

## Project Overview
SafeOperate is an offline, edge-intelligent biometric safety interlock for university workshop machinery. Powered by the dual-brain **Arduino UNO Q 4GB**, it combines local facial authorization and real-time head-pose/eye-closure monitoring (Qualcomm QRB2210 Linux MPU) with a deterministic hardware watchdog (STM32U585 MCU) that triggers a fail-safe, dual-redundant 240V AC opto-isolated relay cutoff (<100 ms) if the operator is unauthorized, distracted, or leaves the safety zone.

## Repository Structure
- `/hardware` — Circuit schematics, BOM, and 3D-printed enclosure CAD (`.stl`)
- `/software` — OpenCV vision pipeline (Linux) and safety watchdog firmware (STM32)
- `/docs` — EIRP proposal, progress checkup logs, and final documentation report
