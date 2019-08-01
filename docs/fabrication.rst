Custom Parts
============

The Flight Computer requires the fabrication of some custom components: a printed circuit board (PCB) and several 3D printed parts.

Printed Circuit Boards
----------------------

The PCB files can be found on `GitHub <https://github.com/JohnMLarkin/FlightComputer-HW>`_ in the ``pcb/standard`` folder for the standard-sized Flight Computer and ``pcb/mini`` folder for the mini. The most recent versions are at the top-level of these folders but older versions can be found in the ``archive`` folder.

The PCBs were designed using `Fritzing <https://fritzing.org>`_, an easy to use (and free) electronic prototyping tool suitable for simple designs. Fritzing design files have the extension ``fzz``.  This design is then exported from Fritzing as a collection of *gerber* files, saved as a single zip archive.

There are several companies that can make the PCBs for you from the gerber files. We have had great success with `OSH Park <https://oshpark.com>`_. If you want to order the most recent version of either board directly from them, you can do so (`standard <https://oshpark.com/shared_projects/nXXAHcDw>`_, `mini <https://oshpark.com/shared_projects/EYISRbfR>`_). In July 2019 these were available for $109 (standard, set of 3) or $40 (mini, set of 3) before shipping and any applicable tax.

3D Printed Parts
----------------

A fully assembled Flight Computer also requires some 3D printed parts: a battery holder, a breadboard clip (only for the standard Flight Computer), and an external interface to be mounted on the outside of the pod that holds a switch and indicator LEDs. These can be found in the same GitHub repository as the PCB files (`GitHub <https://github.com/JohnMLarkin/FlightComputer-HW>`_) but under the ``3d_print`` folder. The parts were designed in AutoDesk Inventor (``ipt`` files) and exported for 3D printing as ``stl`` files.

We have printed these parts using an Ultimaker 2+ with ABS filament. The best results have been obtained with a 0.10 mm layer height, 30% fill, and 0.9 mm shell thickness. These settings are most important for the breadboard clips, as these may break off if the infill is too weak.

