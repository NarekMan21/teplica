# Greenhouse Automation & Monitoring

This repository is the starting point for a practical greenhouse automation portfolio project.

The goal is to build a real-world system for monitoring and controlling greenhouse processes: soil sensors, irrigation, climate data, Raspberry Pi / Home Assistant integration, and future AI-assisted recommendations.

## Problem

Greenhouse work depends on many changing signals:

- soil moisture
- soil temperature
- pH and EC
- irrigation timing
- water quality
- air temperature and humidity
- equipment status
- manual observations from workers

The business problem is simple: decisions are often made manually, from scattered data, and too late.

## Goal

Create a system that collects sensor data, shows it clearly, and helps make better decisions about irrigation, climate, and plant care.

## Planned architecture

```text
Sensors / controllers
   ↓
ESP32 / ESP8266 devices
   ↓
MQTT or local HTTP API
   ↓
Raspberry Pi / Home Assistant
   ↓
Dashboard + alerts + history
   ↓
AI-assisted recommendations
```

## Main components

- ESP32 / ESP8266 sensor nodes
- Raspberry Pi 4 as local server
- Home Assistant as automation layer
- MQTT for device communication
- Soil sensors: moisture, temperature, pH, EC
- Irrigation pump / valve control
- Web dashboard for monitoring
- Optional AI layer for recommendations and anomaly detection

## Example use cases

- Show current pH, EC, moisture, and temperature by greenhouse zone
- Detect dry zones before plants are stressed
- Log irrigation events and compare them with sensor changes
- Send Telegram alerts when sensor values go outside safe ranges
- Build a daily greenhouse summary
- Recommend watering time based on current conditions and history

## Why this project matters

This is not just a demo project. It connects software with a real business and real physical processes.

It demonstrates:

- IoT architecture
- sensor data collection
- automation thinking
- dashboard design
- practical system integration
- business process understanding

## Roadmap

### Phase 1 — Documentation and structure

- [ ] Add current hardware list
- [ ] Add wiring diagrams
- [ ] Add sensor list and data format
- [ ] Add screenshots from Home Assistant / dashboard
- [ ] Add photos of the greenhouse setup

### Phase 2 — Data collection

- [ ] Define MQTT topics
- [ ] Add ESP32 firmware examples
- [ ] Add local API for readings
- [ ] Save history in a lightweight database

### Phase 3 — Dashboard

- [ ] Show latest readings
- [ ] Add charts by sensor and zone
- [ ] Add irrigation log
- [ ] Add alert thresholds

### Phase 4 — Automation

- [ ] Create irrigation rules
- [ ] Add Telegram alerts
- [ ] Add safety checks for pump/valve control
- [ ] Add manual override controls

### Phase 5 — AI layer

- [ ] Generate daily greenhouse summaries
- [ ] Detect abnormal trends
- [ ] Suggest watering schedule improvements
- [ ] Explain possible plant stress causes from sensor history

## Future case study structure

When the system becomes more complete, this README should include:

1. Real photos of the greenhouse and hardware
2. Sensor topology diagram
3. Dashboard screenshots
4. Example data logs
5. Before/after workflow improvement
6. What worked, what failed, and what was improved

## Target portfolio role

This project supports a portfolio for roles such as:

- IoT Engineer
- AI Automation Engineer
- Technical Product Engineer
- Internal Tools Developer
- Greenhouse / AgTech automation consultant
