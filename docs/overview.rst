High Altitude Balloon Open Source Collection
============================================

The High Altitude Balloon Open Source Collection (HABOSC) is a set of interrelated tools for transmitting telemetry from a high altitude balloon, processing and storing that data, and providing user access to the stored data both during and after the flight.  The system is designed to be flexible so it can adapt to the needs of various users.

The components of the collection are:

Command Module (hardware)
  This is the essential hardware system carried by the balloon.  The core tracking features are implemented using a GPS receiver and an Iridium satellite modem.
  The operations of the Command Module are coordinated by a microcontroller.  Bluetooth communication allows the Command Module to be configured for the flight shortly before launch (see the Launch Control tool below).
  Communication with experiment pods containing a Flight Computer (see below) is possible through a XBee 802.15.4 radio network operating at 2.4 GHz.

Command Module (microcontroller software)
  Written in C++ using the Arm\ :sup:`®` Mbed\ :sup:`™` OS, this is the code running on the microcontroller that ensures measurements are made and then transmitted to the Iridium satellite network.

Mission Control (server software)
  Running on a server, this Javascript code listens for telemetry packets relayed by the Iridium ground station via email.  The telemetry data is processed and stored in a MongoDB database.  Users interface with Mission Control through a web frontend.  Close to real-time mapping and graphical display of key telemetry is provided.

Launch Control (laptop or desktop application)
  Using the cross-platform Electron framework, this software allows a Bluetooth-enabled computer to communicate with the Command Module prior to launch.  It synchronizes the mission configuration between Command Module and Mission Control.  This application also allows users to monitor communication between the Command Module and linked Flight Computers during the prototyping and debugging phase on the ground.

Flight Computer (hardware)
  This printed circuit board holds an Arm Cortex-M3 microcontroller.  The microcontroller supports reading sensors and logging data to the attached SD card.  An XBee radio modem allows the microcontroller to synchronize its real-time clock with the Command Module as well as to relay data to the Command Module for transmission to Mission Control. An integrated rechargeable battery provides a reliable power source.  A version of the Flight Computer also provides a base for attaching a breadboard if custom circuitry is required.

Flight Computer (software library)
  This Mbed OS library allows users to easily integrate communication with the Command Module into their C++ code.

..  list-table:: Collection Links
    :header-rows: 1

    * - Component
      - Repository
      - Documentation
    * - Command Module (HW)
      - not yet available
      - not yet available
    * - Command Module (SW)
      - `GitHub <https://github.com/JohnMLarkin/Whitworth-CommandModule>`_
      - not yet available
    * - Mission Control
      - `GitHub <https://github.com/JohnMLarkin/Mission-Control>`_
      - not yet available
    * - Launch Control
      - `GitHub <https://github.com/JohnMLarkin/Whitworth-LaunchControl>`_
      - not yet available
    * - Flight Computer (HW)
      - `GitHub <https://github.com/JohnMLarkin/FlightComputer-HW>`_
      - not yet available
    * - Flight Computer (SW)
      - `GitHub <https://github.com/JohnMLarkin/FlightComputer-SW>`_
      - not yet available



