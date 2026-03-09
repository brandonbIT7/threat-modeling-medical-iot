# STRIDE Threat Model: Insulin Pump
## Device Overview
-Connected insulin pump (Bluetooth/Wifi)
-Controls: dosage, alerts, remote monitoring
## STRIDE Breakdown
**S**poofing = fake signals, wrong dosage
**T**ampering - hack firmware, overdose
**R**epudiation - no logs, can't blame anyone
**I**nfo Disclosure - leak patient data
**D**enial of Service - jam comms, no alerts
**E**levation - takeover device

See attack flow: ./assets/stride-diagram.md
