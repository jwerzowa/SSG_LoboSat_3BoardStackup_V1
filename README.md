# LOBOSAT 3-Board PCB Stackup V1

KiCad PCB designs for the LOBOSAT CubeSat, developed as part of UNM's satellite club (LOBOSAT/SSG).
Reach out to Julien Werzowa for any questions. 

## Board Overview

| Boards | 

`Feather_IMU_Board - Telemetry` : Adafruit Feather M0 + ICM-20948 9-DOF IMU 
`Raspberry_PI_Board - Videography` : Raspberry Pi Zero 2W compute board use for Videography
`Lightracker_Battery_Board - Power & GPS` : LightTracker + DFR1015 buck converter (7.4V → 5V) 

## Power Architecture

7.4V LiPo → DFR1015 buck converter → 5V rail distributed across all three boards via 2×8 dual-row headers.

## Tools

- KiCad 8.x
- Fabrication: OSH Park / JLCPCB

## Status

V1 — initial commit. Work in progress.
