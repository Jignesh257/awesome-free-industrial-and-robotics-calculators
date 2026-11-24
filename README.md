# Awesome Free Industrial & Robotics Engineering Calculators

Engineers waste hours clicking paywalled vendor spreadsheets just to check a pipe wall thickness, an RTD ohm reading, or a robot alarm code. Zero-login browser tools fix that friction. This curated index tracks `25+` free, fast, dual-unit (`SI Metric` + `US Imperial`) calculators, standards charts, and exact OEM troubleshooting references maintained across [EngiTech.in](https://engitech.in/engineering-tools/) and [RoboticsEngineering.in](https://roboticsengineering.in/tools/).

## VFD Fault Code & Drive Troubleshooting

Record drive sub-codes before cycling breaker power (`r0949` on Siemens SINAMICS clears on reboot) and run a `1,000 V DC` megger test (`>100 M-ohm`) before condemning output IGBTs:

- [Multi-Brand VFD Fault Code Troubleshooter (55+ Codes)](https://engitech.in/vfd-fault-code-troubleshooter/)
- [Siemens SINAMICS G120 / V20 Fault Hub](https://engitech.in/siemens-sinamics-vfd-fault-codes-troubleshooting/) & [F30001 / F07801 Overcurrent Checklist](https://engitech.in/siemens-sinamics-f30001-f07801-overcurrent-fix/)
- [ABB ACS580 / ACS880 Fault Hub](https://engitech.in/abb-vfd-fault-codes-troubleshooting/) & [Fault 2330 Earth Leakage / 2310 Fix](https://engitech.in/abb-acs580-acs880-2330-earth-leakage-2310-overcurrent-fix/)
- [Danfoss VLT FC51 / FC302 Fault Hub](https://engitech.in/danfoss-vlt-vfd-fault-codes-troubleshooting/) & [Alarm A13 / A14 Reset Guide](https://engitech.in/danfoss-vlt-fc302-alarm-a13-a14-overcurrent-earth-fault-fix/)
- [Schneider Altivar ATV320 / ATV630 Fault Hub](https://engitech.in/schneider-altivar-vfd-fault-codes-troubleshooting/) & [OCF / SCF1 / OBF Recovery](https://engitech.in/schneider-altivar-atv320-atv630-ocf-scf1-obf-fault-fix/)
- [Delta MS300 / C2000 Fault Hub](https://engitech.in/delta-vfd-fault-codes-troubleshooting/)
- [Yaskawa V1000 / A1000 / GA700 Fault Hub](https://engitech.in/yaskawa-vfd-fault-codes-troubleshooting/)

## Process, Piping, Instrumentation & Mechanical Sizing

- [4-20 mA Scaling Formula & PLC Raw Count Converter](https://engitech.in/4-20ma-scaling-formula-calculator/) & [NAMUR NE43 Loop Fault Guide (`0 mA`, `3.8 mA`, `21.5 mA`)](https://engitech.in/4-20ma-loop-fault-0ma-3-8ma-21-5ma-namur-ne43-troubleshooting/)
- [PT100 RTD Resistance Table (IEC 60751 `-200 C` to `+850 C`)](https://engitech.in/pt100-rtd-resistance-table-iec-60751-chart/)
- [Control Valve Cv / Kv Sizing & Choked Flow Calculator](https://engitech.in/control-valve-cv-kv-sizing-calculator/)
- [Centrifugal Pump Shaft Power & Motor Sizing Calculator](https://engitech.in/pump-power-calculator/)
- [ASME B36.10 Pipe Schedule 40 & 80 Dimensions Chart (`NPS 1/8"` to `24"`)](https://engitech.in/asme-b36-10-pipe-schedule-40-80-dimensions-chart/)
- [ASME B16.5 Flange Dimensions Chart (Class `150` & `300`)](https://engitech.in/asme-b16-5-flange-dimensions-chart-class-150-300/)
- [AWG to mm2 Cable Size & 3-Phase Voltage Drop Calculator](https://engitech.in/awg-to-mm2-cable-size-voltage-drop-calculator/)
- [Metric & Imperial Bolt Torque Chart (ISO `898-1` / SAE)](https://engitech.in/bolt-torque-chart-metric-imperial/)
- [Bearing L10 / L10h Life Calculator (ISO `281`)](https://engitech.in/bearing-life-l10-number-calculator/) & [SKF / FAG / NSK Bearing Chart](https://engitech.in/skf-fag-nsk-bearing-dimensions-size-chart/)
- [Saturated Steam Table & Pressure-Temp Calculator (IAPWS)](https://engitech.in/saturated-steam-table-pressure-temperature-calculator/)
- [Transformer kVA & Bolted Short-Circuit Fault Current Calculator](https://engitech.in/transformer-kva-short-circuit-calculator/)
- [Boiler Efficiency & Excess Air Fuel Loss Calculator](https://engitech.in/boiler-efficiency-fuel-consumption-calculator/)

## Industrial Robot Alarms, Cobots & ROS 2 Tools

Unplanned cell stops cost `$400` to `$2,500` per hour on production lines. Keep direct alarm reset procedures bookmarked ahead of shift changes:

- [Industrial Robot Fault Code Finder (`50+` OEM Codes)](https://roboticsengineering.in/industrial-robot-fault-code-finder/)
- [FANUC Robot Fault Hub (`SRVO`/`MOTN`)](https://roboticsengineering.in/fanuc-robot-fault-codes-srvo-motn-troubleshooting/) & [SRVO-062 BZAL & SRVO-075 Quick Master Fix](https://roboticsengineering.in/fanuc-srvo-062-bzal-srvo-075-pulse-not-established-reset/)
- [Universal Robots Fault Hub (`C150`/`C153`/`C204`)](https://roboticsengineering.in/universal-robots-cobot-fault-codes-c150-c153-c204/) & [C204 Path Sanity & C74 48V PSU Recovery](https://roboticsengineering.in/universal-robots-c204-path-sanity-c74-48v-psu-fault-fix/)
- [ABB IRC5 / OmniCore Fault Hub](https://roboticsengineering.in/abb-robot-fault-codes-irc5-omnicore-troubleshooting/) & [50204 Motion Supervision Reset](https://roboticsengineering.in/abb-irc5-omnicore-50204-motion-supervision-triggered-fix/)
- [KUKA KRC4 / KRC5 Fault Hub](https://roboticsengineering.in/kuka-robot-fault-codes-krc4-krc5-kss-troubleshooting/) & [KSS01133 Gear Torque & KSS01422 Mastering Fix](https://roboticsengineering.in/kuka-krc4-krc5-kss01133-gear-torque-kss01422-mastering-fix/)
- [Yaskawa Motoman Alarm Hub (`DX200`/`YRC1000`)](https://roboticsengineering.in/yaskawa-motoman-robot-fault-codes-troubleshooting/)
- [ROS 2 Error Codes & CLI Cheatsheet](https://roboticsengineering.in/ros2-error-codes-cli-cheatsheet-troubleshooting/) & [ROS 2 TF2 Extrapolation Error Fix](https://roboticsengineering.in/ros2-tf2-extrapolation-into-past-future-error-fix/)
- [PID Controller Tuning Calculator & Live Oscilloscope](https://roboticsengineering.in/pid-tuning-robot-motion/)
- [Robot Payload, Wrist Moment (`N*m`) & Inertia Calculator](https://roboticsengineering.in/robot-payload-inertia-torque-calculator/)
- [ISO `10218-2:2025` & ISO/TS `15066` Cobot Safety Force Calculator](https://roboticsengineering.in/iso-10218-iso-ts-15066-cobot-safety-guide/)
- [Cobot vs 6-Axis Industrial Robot ROI Calculator](https://roboticsengineering.in/cobot-vs-industrial-robot-roi-calculator/)

## Open-Source Offline CSV/JSON & Python Repos

- [industrial-vfd-fault-codes-and-engineering-tables](https://github.com/Jignesh257/industrial-vfd-fault-codes-and-engineering-tables)
- [industrial-robot-fault-codes-and-ros2-reference](https://github.com/Jignesh257/industrial-robot-fault-codes-and-ros2-reference)
- [plc-and-ros2-field-diagnostics-cli](https://github.com/Jignesh257/plc-and-ros2-field-diagnostics-cli)

## License

MIT License.
