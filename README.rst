***************************
HABOSC Flight Computer (HW)
***************************

.. image:: https://img.shields.io/github/tag/johnmlarkin/flightcomputer-hw.svg?label=version&style=plastic   :alt: GitHub tag (latest SemVer)
.. image:: https://img.shields.io/github/license/johnmlarkin/flightcomputer-hw.svg?style=plastic   :alt: GitHub license
.. image:: https://img.shields.io/badge/platform-mbed-lightgrey.svg?style=plastic   :alt: Platform
.. image:: https://img.shields.io/badge/microcontroller-lpc1768-lightgrey.svg?style=plastic   :alt: Microcontroller

Overview
========

The High Altitude Balloon Open Source Collection (HABOSC) is a set of interrelated tools for transmitting telemetry from a high altitude balloon, processing and storing that data, and providing user access to the stored data both during and after the flight. The system is designed to be flexible so it can adapt to the needs of various users.

One of the components of the HABOSC is the **Flight Computer**. The Flight Computer consists of a microcontroller and supporting hardware (battery, SD card, and XBee radio module) and comes in two configurations. The *standard* Flight Computer includes a clip to hold a half-size breadboard and the *mini* does not, reducing both its size and weight.

The Flight Computer is intended to be carried by individual experiment pods. The microcontroller can be flexibly programmed to interface with a wide variety of sensors. Data can be stored on the SD card or relayed to the ground using an XBee radio link to the Command Module. The microcontroller's software is written in C++ using the Arm\ :sup:`®` Mbed\ :sup:`™` OS.

This repository contains the *hardware* portion of the Flight Computer and supporting documentation.
