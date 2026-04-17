# Activity 7. Digital Fabrication III: PCB Milling

## Introduction

PCB milling is a subtractive manufacturing process where a CNC machine
removes unwanted copper from a copper-clad board to form electrical traces
and pads. Unlike chemical etching, PCB milling is clean, fast, and
environmentally friendly, making it suitable for rapid prototyping and
small batch production.

The machine used for this process was the Carbide Nomad 3, a desktop CNC
milling machine designed for high precision tasks such as PCB fabrication.
It integrates with Carbide Create for design and Carbide Motion for machine
control, simplifying the workflow from design to fabrication.


## After Class Activity  Milling the PCB from Day 3

In this activity we were supposed to mill the PCB design we created on Day 3
using KiCad. The workflow involved exporting fabrication files, setting up
the machine, and running the milling job.

## Step 1  Exporting Fabrication Files from KiCad

The first step was to export the PCB design from KiCad as fabrication files.
Three files were needed:

- **Gerber file** defines the copper trace layout
- **Drill file** defines hole positions for components
- **Outline file** defines the board boundary for cutting

These files were uploaded to the Carbide3D website to configure page
settings and milling parameters, and to adjust everything to match the
size and limits of the machine being used.

## Step 2 Generating Toolpaths in Carbide Create

After uploading the files, toolpaths were generated for each stage of
the milling process:

- **Isolation milling**  removes copper around traces
- **Drilling** creates holes for through-hole components
- **Board outline cutting** separates the PCB from the blank

Cutting depth, feed rate, and tool diameter were configured carefully
before exporting the final G-code file.

## Step 3 Setting Up the Machine in Carbide Motion

We connected to the Carbide Motion software to control the PCB milling
machine. The following setup steps were completed:

- Secured the copper-clad board to the machine bed
- Installed the correct end mill
- Set the X, Y, and Z axes work coordinates
- Calibrated the Z axis to ensure consistent trace depth

## Step 4  Machine Unavailable

After completing all preparation steps, the milling machine was not
working at the time of this activity. The physical PCB board could
therefore not be produced. The fabrication files are fully prepared
and ready to be used once the machine is available again.

## What I Learned

Even though the physical milling could not be completed, this activity
taught me the full PCB milling workflow from design export to machine
setup. I learned how Gerber files translate a digital schematic into
machine instructions, how toolpaths are generated for different milling
stages, and how important axis calibration is for achieving accurate
trace isolation.

## References
- PCB Milling Process Using Carbide Nomad 3 CNC
- Carbide 3D documentation and user guides
- KiCad Gerber and drill file export workflow
- Course material for Digital Fabrication III