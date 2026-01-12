# Home Assistant Configuration

## Overview
Home Energy Management System (HEMS) with intelligent battery management, solar forecasting, and tariff optimization.

## Hardware
- **Inverter:** Solarman (192.168.1.143)
- **Battery:** 19.6 kWh LiFePO4
- **Solar:** [Your PV system size] kWp
- **Grid:** 6.9 kW contract limit

## Directory Structure

/config/
├── packages/hems/          # Feature-based HEMS packages
├── templates/              # Modern template sensors
├── automations/hems/       # HEMS automations
├── scripts/hems/           # Helper scripts
└── input/                  # Input helpers

## Key Features
- Dynamic battery charging based on solar forecast
- Portuguese tri-horário tariff optimization
- HEMS semantic naming (hardware-independent)
- Historical load tracking and learning

## Quick Links
- [Migration Log](MIGRATION_LOG.md)
- [Battery Management](packages/hems/battery_management.yaml)
- [HEMS Abstractions](packages/hems/abstractions.yaml)

## Last Updated
2026-01-11
## Directory Structure
