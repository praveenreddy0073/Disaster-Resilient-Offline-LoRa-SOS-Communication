# Earthquake Emergency SOS Communication System

## Overview

India experiences frequent earthquakes that can damage cellular towers and disrupt internet connectivity. During such emergencies, victims may be unable to communicate their location to rescue teams.

This project provides an infrastructure-independent emergency communication system using ESP32 and LoRa (SX1278) technology. The system enables users to transmit SOS alerts and GPS coordinates over long distances even when conventional communication networks fail.

## Problem Statement

During major earthquakes:

- Cellular towers may become unavailable
- Internet connectivity can be disrupted
- Victims cannot easily communicate their location
- Rescue teams face delays in locating survivors

This project addresses these challenges through a long-range wireless communication network.

## Proposed Solution

The system consists of:

Mobile App
↓
ESP32 User Node
↓
LoRa Communication
↓
Relay Node
↓
Base Station
↓
Rescue Team

The user sends an SOS request through a mobile application. The ESP32 User Node receives the request and forwards it using LoRa technology. Relay Nodes extend coverage and the Base Station receives the alert and displays victim information.

## Key Features

- Long-range communication up to 15 km (Line of Sight)
- GPS-based location sharing
- Infrastructure-independent operation
- Low-power communication
- Emergency SOS transmission
- Relay-based message forwarding
- Rescue acknowledgement system
- Disaster-resilient architecture

## Hardware Components

- ESP32 Development Board
- SX1278 LoRa Module (433 MHz)
- 433 MHz Antenna
- Mobile Device
- Power Supply

## Technologies Used

- ESP32
- LoRa (SX1278)
- Arduino IDE
- Firebase Studio
- Wi-Fi Communication
- GPS Location Services

## Why LoRa?

LoRa was selected because it offers:

- Long communication range
- Very low power consumption
- Strong signal penetration
- No dependency on cellular infrastructure
- Reliable communication in disaster environments

## Applications

- Earthquake Emergency Response
- Disaster Management
- Search and Rescue Operations
- Remote Area Communication
- Emergency Alert Systems

## Future Enhancements

- Automatic earthquake detection sensors
- Solar-powered relay stations
- Offline mapping support
- Multi-user communication network
- AI-based rescue prioritization

## Author

Praveen kumar
B.Tech Electronics and Communication Engineering
REVA University