# 2. Digital Modeling for Fabrication
# Research
Day 2 focused on digital modeling for fabrication and how precise models become production-ready files. I learned that a digital model is not only a visual object but a set of machine instructions. Fabrication success begins inside the model, where every dimension and constraint must be accurate. Machines execute exactly what is defined, so errors in geometry or scale lead directly to fabrication failure.
The lecture emphasized precision modeling and scale control. Models must match real-world dimensions, and parametric constraints ensure consistency and adaptability. I studied Design for Manufacturing (DFM) principles, which encourage designing objects that respect machine limits, tool sizes, and material behavior. Simplifying geometry and removing unnecessary features improves manufacturability and reduces production risk.
A key concept was fabrication-ready geometry. For 3D fabrication, geometry must be closed and watertight. For 2D fabrication, vector paths must be clean and continuous. Ambiguous or broken geometry confuses machines and causes errors. I also learned about tolerances and fit — digital models assume perfection, but real fabrication introduces kerf, shrinkage, and tool wear. Designing for imperfection is necessary to ensure proper assembly.
The practical activities reinforced these ideas. In FreeCAD, I created a 3D L-shaped mounting bracket using sketching, extrusion (pad), hole features, and fillets. This exercise demonstrated parametric modeling, constraint-based sketches, and solid geometry required for fabrication. In Inkscape, I designed a 2D press-fit box panel using accurate 1:1 scale vector paths. Slot sizing and clean geometry were critical to ensure parts would assemble correctly in physical material.
I also learned about fabrication file formats such as STL, DXF, and STEP. Choosing the correct format depends on the machine and process. Preparing models for production includes checking dimensions, validating geometry, applying tolerances, and testing prototypes before full fabrication.
Overall, Day 2 strengthened my understanding that a good digital model anticipates how it will be manufactured. Modeling decisions directly affect physical results, so clarity, precision, and manufacturability must guide every step.
## References & Inspiration
The lecture on digital modeling for fabrication emphasized the importance of precision, manufacturability, and machine-readable geometry. The FreeCAD workflow inspired me to treat parametric modeling as a system of controlled design logic rather than simple drawing. The Inkscape vector workflow highlighted how clean geometry translates directly into fabrication accuracy.
The idea that “machines do not guess” influenced my approach to modeling. Every dimension, path, and constraint must be intentional. Design for Manufacturing principles encouraged me to simplify geometry and respect real-world limits. Tolerance design and fabrication-ready geometry provided a practical framework for preparing files that succeed in production.
* Download reference
Digital Modeling for Fabrication lecture slides
FreeCAD parametric modeling workflow
Inkscape vector fabrication workflow
Download reference
Lecture slides and fabrication modeling materials
