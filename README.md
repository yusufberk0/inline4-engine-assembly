Inline-4 Engine: Crank-Slider Assembly

Fully parametric SolidWorks model of an inline four-cylinder engine's moving group: engine block, crankshaft, connecting rods with caps, pistons, piston pins and piston rings.




<img width="627" height="367" alt="6Motor Montaj Kesit" src="https://github.com/user-attachments/assets/3c75e6f7-f549-4ddc-93f5-8c74344a3c07" />


Highlights
30-component assembly built from 7 unique part types, fully mated (no floating or over-defined parts)
Crankshaft with four throws, built from one web/journal unit and propagated with mirror and plane features
Connecting rod with I-beam shank, tapered profile and a separate bolted cap
Three-ring piston with ring grooves, pin boss, skirt cut-outs and fillets
Engineering drawings for each component, plus STEP files for use in any CAD software

Developed as part of a university term project at Piri Reis University. The CAD modelling, assembly and technical drawings in this repository are my own work.

Motion study





<img width="800" height="450" alt="Montajgif" src="https://github.com/user-attachments/assets/92ea7b67-9523-4d47-9c28-33640b195c11" />


Components
Part	Qty	Key details
Engine block	1	4 cylinder bores (4 x Ø86 mm), crankcase and main bearing housing
Crankshaft	1	Ø54 mm crankpins, counterweight webs, flywheel flange with bolt holes
Connecting rod	4	201.2 mm center distance, small end Ø33.8 mm, big end Ø54 mm
Connecting rod cap	4	Semi-circular big-end bearing seat, bolt holes
Piston	4	Revolved body, 3 ring grooves, pin bore Ø33.8 mm, skirt cut-outs
Piston pin	4	Connects piston and rod small end
Piston ring	12	Three rings per piston
Design approach
Every part starts from a fully defined sketch and is built with extrude, revolve, cut, fillet and mirror features, so dimensions can be changed from the feature tree.
Rotating interfaces (bore and piston, pin and rod, rod and crankpin) use concentric mates; axial positions are locked with coincident mates.
Mating dimensions are kept consistent across parts: the rod big-end bore and the crankpin share the same Ø54 mm, and the pin bore matches the rod small end at Ø33.8 mm.
Repository structure
inline4-engine-assembly/
├── cad/        SolidWorks parts and assembly (.SLDPRT / .SLDASM)
├── step/       Neutral CAD format (.step), opens in any CAD software
├── drawings/   Technical drawings (PDF)
├── images/     Renders, exploded view, cross-section
└── media/      Motion study animation
How to open the files
SolidWorks: open the assembly file in cad/. All parts are in the same folder, so keep them together.
No SolidWorks? Open the .step files in a free viewer such as eDrawings, FreeCAD or Autodesk Fusion.
Quick look: the PDFs in drawings/ and the images in images/ need no software.
Tools

SolidWorks (part, assembly, drawing, motion study), PhotoView 360 / SolidWorks Visualize for renders.

Contact

Yusuf Berk Say, Mechanical Engineer, Istanbul LinkedIn · yusufberk.say0@gmail.com
