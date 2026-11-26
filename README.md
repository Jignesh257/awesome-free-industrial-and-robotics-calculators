# Awesome Free Industrial & Robotics Engineering Calculators

Engineers waste hours clicking paywalled vendor spreadsheets just to check a pipe wall thickness, an RTD ohm reading, or a robot alarm reset sequence. Zero-login browser tools fix that friction. This curated index tracks `35+` free, dual-unit (`SI Metric` + `US Imperial`) calculators, standards charts, and `20` step-by-step OEM troubleshooting checklists maintained across [EngiTech.in](https://engitech.in/engineering-tools/) and [RoboticsEngineering.in](https://roboticsengineering.in/tools/).

Live searchable GitHub Pages index: https://jignesh257.github.io/awesome-free-industrial-and-robotics-calculators/

## VFD Fault Code & Drive Troubleshooting (`6` Major OEM Brands)

Record drive sub-codes before cycling breaker power (`r0949` on Siemens SINAMICS clears on reboot) and run a `1,000 V DC` megger test (`>100 M-ohm`) before condemning output IGBTs:

- [Multi-Brand VFD Fault Code Troubleshooter (55+ Codes)](https://engitech.in/vfd-fault-code-troubleshooter/)
- [Siemens SINAMICS G120 / V20 Hub](https://engitech.in/siemens-sinamics-vfd-fault-codes-troubleshooting/) | [F30001 & F07801 Overcurrent Checklist](https://engitech.in/siemens-sinamics-f30001-f07801-overcurrent-fix/)
- [ABB ACS580 / ACS880 Hub](https://engitech.in/abb-vfd-fault-codes-troubleshooting/) | [Fault 2330 Earth Leakage & 2310 Fix](https://engitech.in/abb-acs580-acs880-2330-earth-leakage-2310-overcurrent-fix/)
- [Danfoss VLT FC51 / FC302 Hub](https://engitech.in/danfoss-vlt-vfd-fault-codes-troubleshooting/) | [Alarm A13 & A14 Reset Guide](https://engitech.in/danfoss-vlt-fc302-alarm-a13-a14-overcurrent-earth-fault-fix/)
- [Delta MS300 / C2000 Hub](https://engitech.in/delta-vfd-fault-codes-troubleshooting/) | [ocA, GFF & ovd Fault Reset Guide](https://engitech.in/delta-vfd-ms300-c2000-oca-gff-ovd-fault-fix/)
- [Schneider Altivar ATV320 / ATV630 Hub](https://engitech.in/schneider-altivar-vfd-fault-codes-troubleshooting/) | [OCF, SCF1 & OBF Recovery](https://engitech.in/schneider-altivar-atv320-atv630-ocf-scf1-obf-fault-fix/)
- [Yaskawa V1000 / A1000 / GA700 Hub](https://engitech.in/yaskawa-vfd-fault-codes-troubleshooting/) | [oC, GF, ov & oL2 Troubleshooting](https://engitech.in/yaskawa-v1000-a1000-ga700-oc-gf-ov-ol2-fault-fix/)

## Process, Piping, Instrumentation & Mechanical Sizing

- [4-20 mA Scaling Calculator](https://engitech.in/4-20ma-scaling-formula-calculator/) | [NAMUR NE43 Loop Fault Guide (`0 mA`, `3.8 mA`, `21.5 mA`)](https://engitech.in/4-20ma-loop-fault-0ma-3-8ma-21-5ma-namur-ne43-troubleshooting/)
- [PT100 RTD Resistance Chart (IEC 60751)](https://engitech.in/pt100-rtd-resistance-table-iec-60751-chart/) | [PT100 3-Wire vs 4-Wire Lead Resistance Error Fix](https://engitech.in/pt100-rtd-3-wire-vs-4-wire-lead-resistance-error-fix/)
- [Centrifugal Pump Power Calculator](https://engitech.in/pump-power-calculator/) | [Mechanical Seal Failures & API Plan 11 vs 53A](https://engitech.in/mechanical-seal-failure-modes-dry-running-api-plan-11-53a/)
- [ASME B16.5 Flange Chart (Class `150` & `300`)](https://engitech.in/asme-b16-5-flange-dimensions-chart-class-150-300/) | [ASME PCC-1 Star Pattern Bolt Torque Guide](https://engitech.in/asme-b16-5-flange-bolt-tightening-star-pattern-torque-guide/)
- [Control Valve Cv / Kv Sizing & Choked Flow Calculator](https://engitech.in/control-valve-cv-kv-sizing-calculator/)
- [ASME B36.10 Pipe Schedule 40 & 80 Chart (`NPS 1/8"` to `24"`)](https://engitech.in/asme-b36-10-pipe-schedule-40-80-dimensions-chart/)
- [AWG to mm2 Cable Size & 3-Phase Voltage Drop Calculator](https://engitech.in/awg-to-mm2-cable-size-voltage-drop-calculator/)
- [Metric & Imperial Bolt Torque Chart (ISO `898-1` / SAE)](https://engitech.in/bolt-torque-chart-metric-imperial/)
- [Bearing L10 / L10h Life Calculator (ISO `281`)](https://engitech.in/bearing-life-l10-number-calculator/) | [SKF / FAG / NSK Bearing Chart](https://engitech.in/skf-fag-nsk-bearing-dimensions-size-chart/)
- [Saturated Steam Table & Pressure-Temp Calculator (IAPWS)](https://engitech.in/saturated-steam-table-pressure-temperature-calculator/)
- [Transformer kVA & Bolted Short-Circuit Fault Current Calculator](https://engitech.in/transformer-kva-short-circuit-calculator/)

## Industrial Robot Alarms, Cobots, ROS 2 & Stepper Drivers

Unplanned cell stops cost `$400` to `$2,500` per hour on factory floors. Keep direct OEM recovery checklists bookmarked ahead of shift handovers:

- [Industrial Robot Fault Code Finder (`50+` OEM Codes)](https://roboticsengineering.in/industrial-robot-fault-code-finder/)
- [FANUC Robot Fault Hub](https://roboticsengineering.in/fanuc-robot-fault-codes-srvo-motn-troubleshooting/) | [SRVO-062 BZAL & SRVO-075 Quick Master](https://roboticsengineering.in/fanuc-srvo-062-bzal-srvo-075-pulse-not-established-reset/) | [SRVO-050 Collision & SRVO-023 Stop Error](https://roboticsengineering.in/fanuc-srvo-050-collision-detect-srvo-023-stop-error-excess-fix/)
- [ABB IRC5 / OmniCore Hub](https://roboticsengineering.in/abb-robot-fault-codes-irc5-omnicore-troubleshooting/) | [50204 Motion Supervision Reset](https://roboticsengineering.in/abb-irc5-omnicore-50204-motion-supervision-triggered-fix/) | [10036 SMB Battery & Rev Counter Update](https://roboticsengineering.in/abb-irc5-10036-smb-battery-lost-revolution-counter-update/)
- [KUKA KRC4 / KRC5 Hub](https://roboticsengineering.in/kuka-robot-fault-codes-krc4-krc5-kss-troubleshooting/) | [KSS01133 Gear Torque & KSS01422 Mastering](https://roboticsengineering.in/kuka-krc4-krc5-kss01133-gear-torque-kss01422-mastering-fix/)
- [Yaskawa Motoman Hub](https://roboticsengineering.in/yaskawa-motoman-robot-fault-codes-troubleshooting/) | [4107 ABSO, 4315 Collision & 4414 Tracking Fix](https://roboticsengineering.in/yaskawa-motoman-alarm-4107-abso-4315-collision-4414-tracking-fix/)
- [Universal Robots Hub](https://roboticsengineering.in/universal-robots-cobot-fault-codes-c150-c153-c204/) | [C204 Path Sanity & C74 48V PSU Recovery](https://roboticsengineering.in/universal-robots-c204-path-sanity-c74-48v-psu-fault-fix/)
- [ROS 2 Error Codes Cheatsheet](https://roboticsengineering.in/ros2-error-codes-cli-cheatsheet-troubleshooting/) | [TF2 Extrapolation Error Fix](https://roboticsengineering.in/ros2-tf2-extrapolation-into-past-future-error-fix/) | [ros2_control Controller Manager Load/Activate Fix](https://roboticsengineering.in/ros2-control-controller-manager-failed-to-load-activate-fix/)
- [NEMA 17/23/34 Stepper Torque Chart](https://roboticsengineering.in/stepper-motor-nema-17-23-34-specs-torque-chart/) | [TMC2209 UART, Overtemp & StallGuard Fix](https://roboticsengineering.in/tmc2209-uart-communication-error-overtemp-stallguard-fix/)
- [PID Controller Tuning Calculator & Live Oscilloscope](https://roboticsengineering.in/pid-tuning-robot-motion/)
- [ISO `10218-2:2025` & ISO/TS `15066` Cobot Safety Calculator](https://roboticsengineering.in/iso-10218-iso-ts-15066-cobot-safety-guide/)
- [Cobot vs 6-Axis Industrial Robot ROI Calculator](https://roboticsengineering.in/cobot-vs-industrial-robot-roi-calculator/)

## Open-Source Offline CSV/JSON & Python Repos

- [industrial-vfd-fault-codes-and-engineering-tables](https://github.com/Jignesh257/industrial-vfd-fault-codes-and-engineering-tables)
- [industrial-robot-fault-codes-and-ros2-reference](https://github.com/Jignesh257/industrial-robot-fault-codes-and-ros2-reference)
- [plc-and-ros2-field-diagnostics-cli](https://github.com/Jignesh257/plc-and-ros2-field-diagnostics-cli)

## Contribute Technical Articles

- Publish industrial engineering guides on [EngiTech.in Write for Us](https://engitech.in/write-for-us/)
- Publish robotics and ROS 2 guides on [RoboticsEngineering.in Write for Us](https://roboticsengineering.in/write-for-us/)

## License

MIT License.
