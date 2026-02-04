# 3. PCB Milling Techniques & Fabrication Process
# Research
The Day 3 activity focused on designing a single-sided microcontroller PCB using KiCad, centered around an ATtiny45 embedded system. The research phase involved understanding the complete KiCad workflow from schematic capture to fabrication-ready outputs, as well as the constraints of PCB milling and hand soldering.
A key concept studied was the relationship between schematic logic and physical PCB layout. The schematic represents electrical intent, while the footprint assignment and routing translate that intent into a manufacturable board. Special attention was given to Design for Manufacturability (DFM), ensuring that trace width, clearance, and component placement were compatible with milling limitations.
The ATtiny45 microcontroller was selected as a beginner-friendly device that supports ISP programming while allowing GPIO reuse. The circuit design integrates power input, LED output control, a push-button input, and a 6-pin ISP header. Research emphasized proper decoupling using a 0.1 µF capacitor to stabilize the supply voltage and reduce electrical noise.
Single-sided routing strategies were explored to avoid vias and minimize jumper usage. Component placement was optimized by positioning the ISP header close to the microcontroller, exposing the LED at the board edge for visibility, and maintaining logical signal flow. Running the Design Rule Check ensured no clearance violations or unconnected nets remained before generating Gerber and drill files.
This activity reinforced that PCB design is not only electrical design, but also a manufacturing problem that requires anticipating fabrication constraints from the beginning.
## References & Inspiration
The primary reference material covered KiCad fundamentals, schematic best practices, footprint verification, routing principles, and milling-oriented DFM rules. Inspiration came from professional PCB workflow methodologies that treat electronics as a full lifecycle process: concept → schematic → layout → verification → fabrication.
Important concepts referenced include:
→ Schematic-first design methodology
→ Symbol-to-footprint consistency
→ Single-sided PCB strategies for milling
→ Clearance and trace rules for isolation routing
→ Gerber inspection before fabrication
→ Embedded system design using ATtiny microcontrollers
* Download reference
PCB Designing with KiCad – From Schematic to Fabrication-Ready PCB

