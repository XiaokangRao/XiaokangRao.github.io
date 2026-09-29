---
title: "Developing a Smart Structural Health Monitoring System"
date: 2026-09-29
permalink: /posts/2026/09/shm-monitoring-system/
tags:
  - structural health monitoring
  - GNSS
  - IoT
  - sensing
---

Structural Health Monitoring (SHM) combines sensing, data acquisition, communication and data analysis to assess the condition and performance of engineering structures.

My current work focuses on the development of a compact SHM system for infrastructure monitoring. The system integrates high-frequency vibration sensing, GNSS-based time synchronisation, wireless communication and cloud-based data processing.

## System Architecture

A typical monitoring node consists of an inertial measurement unit (IMU), GNSS receiver, microcontroller and 4G communication module. The sensor node continuously records structural vibration data and transmits selected measurements to a remote server.

The combination of GNSS timing and distributed sensing nodes provides a consistent time reference for multi-point vibration measurements.

## Vibration and Modal Analysis

One important application is the identification of structural dynamic characteristics.

Acceleration measurements can be analysed using methods such as Operational Modal Analysis (OMA) and Stochastic Subspace Identification (SSI). The identified natural frequencies and mode shapes can then be compared with numerical models or previous measurements.

Changes in these dynamic characteristics may provide useful information for structural condition assessment.

## Future Development

The next stage of the work will focus on improving the reliability of wireless data transmission, automated modal identification and integration with numerical models.

The long-term goal is to develop a practical and scalable SHM platform that can support continuous monitoring of infrastructure in the field.
