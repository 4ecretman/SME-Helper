Title: Additive Manufacturing Fundamentals and Stratasys Systems
Purpose: This briefing document synthesizes the main themes and important ideas from the provided sources, covering fundamental AM concepts, Stratasys technologies, materials, software, and post-processing techniques.
Subject: Review of key concepts in Additive Manufacturing (AM) and the operation/applications of Stratasys FDM and PolyJet systems.
Sources:
	1. Excerpts from "SME CAM-F Study Guide.md"
	2. Excerpts from "STRATASYS SEARCHABLE GUIDE.pdf"

Key Themes and Important Ideas:
1. Additive Manufacturing Fundamentals and Terminology:
	• SME CAM-F: The acronym "SME CAM-F" stands for "Society of Manufacturing Engineers, Certified Additive Manufacturing-Fundamentals." (Source 1, q16)
	• AM vs. Subtractive Manufacturing: The documents highlight the distinction between additive manufacturing (building up material) and subtractive manufacturing (removing material). (Source 2, "Additive manufacturing vs. subtractive manufacturing")
	• Manufacturing Eras: The Neolithic era is characterized by the "Transition from hunting/gathering to agriculture." (Source 1, q18)
	• Topology Optimization: This design technique in AM "Removes excess material while retaining strength." (Source 1, q5)
	• Design for Additive Manufacturing (DfAM): Key considerations in DfAM include minimizing unsupported angles when dealing with overhangs. (Source 1, q8)
	• ASTM Categories: Selective Laser Sintering (SLS) belongs to the "Powder Bed Fusion" ASTM category. (Source 1, q9)
	• In-situ Monitoring (ISM): This refers to "Real-time quality assurance of 3D printers." (Source 1, q20)
2. Stratasys Technologies (FDM and PolyJet):
	• FDM (Fused Deposition Modeling):
		◦ Known for producing "Strong, durable ABS," offering "Economic sparse fill," and providing "Tough, aesthetic colors" and "Versatile Nylon 12." (Source 2, "STRATASYS TECHNOLOGY & MATERIAL BENEFITS")
		◦ Key components include the gantry (positions print heads in the XY plane) (Source 1, q11), liquefier, drive wheels, filament, heater, model tip, and support tip. (Source 2, "FORTUS SYSTEM MATERIAL DRIVE", "SYSTEM")
		◦ Uses both Soluble Support (SR) materials and Breakaway Support Structures (BASS). (Source 2, "FDM SUPPORT MATERIALS")
		◦ FDM printers have specific layer thickness capabilities (e.g., 0.005”, 0.007”, 0.010”, 0.013”). (Source 2, "FORTUS Z - SLICE", "MACHINE SPECIFICATIONS")
		◦ Airflow within the build chamber is important for uniform temperature distribution and layer-to-layer bonding. (Source 2, "ORIENTATION: AIRFLOW", "CHALK TALK 4")
	• PolyJet:
		◦ Offers "Clear transparency," "Multi-material realism," and "Smooth surface finish." (Source 2, "STRATASYS TECHNOLOGY & MATERIAL BENEFITS")
		◦ Jets multiple materials and full CMYK colors. (Source 2, "POLYJET", "Multiple Materials and Colors")
		◦ Digital Materials are created by combining primary and secondary rigid or flexible materials. (Source 2, "GENERATING DIGITAL MATERIALS", "Digital Materials")
		◦ PolyJet is best suited for "small parts when accuracy, detail, and surface finish are essential." (Source 2, "POLYJET")
		◦ Can achieve high build resolution, particularly in the Z-axis. (Source 2, "STRATASYS J735 and J750 SPECS", "MACHINE SPECIFICATIONS")
3. Materials and Properties:
	• Material Selection: "Material selection ensures the integrity of the design AND Structural integrity for the final part in it’s end use." (Source 2, "MATERIALS MATTER – THE BAT & BALL")
	• Thermoplastics: Become pliable when heated above their Glass Transition temperature and do not undergo a chemical reaction or curing during cooling. (Source 2, "Model Material")
	• FDM Material Categories: Stratasys FDM materials are categorized as Standard (PLA, ABS-PLUS, ABS-M30, ABSi, ABS M30I, ABS-ESD7, ASA), Engineering (NYLON 12, NYLON 6, PC-ABS, PC-ISO, PC, NYLON CF), and High Performance (ULTEM® 9085, ULTEM® 1010, ANTERO). (Source 2, "Define thermoplastics and their qualities.", "FDM MATERIAL SELECTION")
	• Standard FDM Materials:
		◦ PLA: Low-cost, renewable, higher stiffness than ABS, good tensile strength, ideal for early concept modeling and fast prototyping. (Source 2, "PLA - POLYLACTIC ACID")
		◦ ABS Plus: Mechanically strong and stable, good general-purpose prototyping material. (Source 2, "ABS PLUS")
		◦ ABS-M30: Improved mechanical properties over ABS Plus. (Source 2, "ABS-M30")
		◦ ABSi: Translucent, available in 3 colors (amber, natural, red), durable, accepts threading well. (Source 1, q17; Source 2, "ABSi")
		◦ ABS-M30i: Biocompatible, ABS-M30 properties + ISO10993, suitable for surgical planning models and medical tools. (Source 2, "ABS-M30i")
		◦ ABS-ESD7: Electrostatic Dissipative, for applications where static charge is a concern. (Source 2, "ABS-ESD7")
		◦ ASA: Improved ABS, UV Stability, excellent aesthetics, enhanced mechanical properties allowing for longer bridging in sparse mode. (Source 2, "ASA - ACRYLIC-STYRENE-ACRYLONITRILE")
	• Engineering Grade FDM Materials:
		◦ FDM Nylon 12: Toughness, Strength, Flexibility, highest FDM Z strength (>90% isotropic), used for snap fits, living hinges, fatigue resistant parts. (Source 2, "FDM NYLON 12")
		◦ PC: Widely used industrial thermoplastic, high tensile and flexural strength, moderate heat resistance. (Source 2, "PC - POLYCARBONATE")
		◦ PC-ABS: High impact strength (2nd only to nylon among FDM materials), excellent feature definition and surface finish. (Source 2, "PC-ABS")
		◦ PC-ISO: Biocompatible (ISO 10993 & USP Class VI), sterilizable, superior part properties compared to ABS-M30i. (Source 2, "PC-ISO")
	• High-Performance FDM Materials:
		◦ ULTEM® 9085: High heat and chemical resistance, mechanically superior in nearly all categories, excellent strength to weight ratio, FST Tested. (Source 2, "ULTEM® 9085")
		◦ ULTEM® 1010: Highest heat resistance among FDM materials, stronger and greater temperature resistance than ULTEM 9085, FST Certified, NSF 51 & 10993 Biocompatibility. (Source 2, "ULTEM® 1010")
	• PolyJet Materials: Include Vero family (Rigid Opaque, Rigid Transparent), Simulated Polypropylene Family (Rigur & Durus), Flexible Rubber-like Family (Tango/Agilus), and Digital Materials (Digital ABS). (Source 2, "Name and identify Stratasys PolyJet families of materials:", "POLYJET MATERIALS SUMMARY")
		◦ Vero Family: Durable and rigid in various colors, good for standards plastic simulation and tooling. (Source 2, "VERO FAMILY | RIGID OPAQUE", "POLYJET MATERIALS SUMMARY")
		◦ Tango/Agilus Family: Various levels of elastomer characteristics. (Source 2, "POLYJET MATERIALS SUMMARY")
	• Support Materials: Soluble Support (SR) materials (like SR-110, SR-20, SR-30, SR-100, PC_S, PPSF_S, ULT_S) are washed away, while Breakaway Support Structures (BASS) are manually removed. SR-110 is a soluble support. (Source 1, q19; Source 2, "FDM SUPPORT MATERIALS", "MATERIALS HIGHLIGHTS")
	• Material Testing: The briefing covers various material tests:
		◦ Surface Tension: "Measure of resistance to the flow of electrons on the surface of the material." (Source 1, q2) This description actually aligns with Surface Resistance. Surface Tension is typically measured using methods like the Wilhelmy plate or Du Noüy ring method. There seems to be a discrepancy between the question's description and the technical definition of surface tension.
		◦ Tensile Strength: Force needed to break a sample. (Source 2, "Tensile Strength")
		◦ Elongation to Break: Change in length when a sample breaks. (Source 2, "Elongation to Break")
		◦ Toughness: Energy a sample can absorb before breaking. (Source 2, "Toughness")
		◦ Heat Deflection / Distortion Temp (HDT): Measure of resistance to distortion under load at elevated temperatures. (Source 2, "Heat Deflection / Distortion Temp (HDT)")
		◦ Coefficient of Thermal Expansion (CTE): Indicates dimensional stability over temperature ranges; lower CTE is better for tooling. (Source 2, "COEFFICIENT OF THERMAL EXPANSION")
		◦ Electrical Properties (Static Dissipative, Static Resistance, Volume Resistance): Describe how materials conduct or resist the flow of electrical charge. (Source 2, "ELECTRICAL PROPERTIES | 1", "ELECTRICAL PROPERTIES | 2", "ELECTRICAL PROPERTIES | 3")
		◦ Water Absorption: Determines the amount of water absorbed, indicating distortion in humid environments. (Source 2, "WATER ABSORPTION")
		◦ Shore Hardness: Measures resistance to indentation for flexible (Shore A) and rigid (Shore D) materials; higher Shore level indicates harder material. (Source 2, "SHORE HARDNESS | SCALE A, D")
		◦ Izod Impact: Measures impact resistance. (Source 2, "IZOD IMPACT")
4. Software (GrabCAD Print and Insight):
	• GrabCAD Print: Used to read native CAD files, connect to Stratasys printers, and provides print management and remote monitoring. (Source 2, "STREAMLINED DESIGN-TO-3D PRINT") It is included with F170, F270, and F370 printers. (Source 2, "Software GrabCAD Print...") It allows for opening VRML files for color textures and printing in multiple materials (on PolyJet). (Source 2, "POLYJET")
	• Insight: Advanced CAM software for Stratasys FDM systems. Used for model setup, orienting parts, slicing, generating toolpaths, creating supports, and sending jobs to the control center. (Source 2, "INSIGHT SOFTWARE", "SLICE FILE", "GENERATE TOOLPATHS") It has capabilities to identify and fix problems like gaps and brown marks. (Source 2, "IDENTIFY AND FIX PROBLEMS", "IDENTIFY PROBLEMS", "FIX PROBLEMS") It can adjust the width of the extrusion based on wall thickness. (Source 2, "IDENTIFY PROBLEMS")
	• Control Center (Insight): Used to place, copy, and add models, finalize jobs, and view system history. (Source 2, "FDM – INSIGHT CONTROL CENTER") All parts packed together share the same machine, material, and slice thickness. (Source 2, "CONTROL CENTER: PACK")
5. Design Considerations:
	• Wall Thickness: The distance between surfaces of a solid part. Minimum wall thickness is determined by the printer's droplet size (extruder/nozzle diameter). (Source 2, "WALL THICKNESS", "MINIMUM WALL THICKNESS")
	• Clearance: The gaps between parts. (Source 2, "Clearance")
	• Supports: Necessary for overhangs and complex geometries. Design considerations include minimizing unsupported angles. (Source 1, q8; Source 2, "SUPPORT", "Supports & Support Removal")
	• Infill: The density of the solid, acting as internal support. (Source 2, "Infill", "SUPPORT")
	• Part Orientation: Significantly impacts build speed, support structures, surface quality, strength (due to non-isotropic properties), support removal, and airflow. (Source 2, "ORIENTATION: SPEED", "ORIENTATION: SUPPORT STRUCTURES", "ORIENTATION: SURFACE QUALITY", "ORIENTATION: SUPPORT REMOVAL", "ORIENTATION: AIRFLOW") For FDM, placing the largest dimension along the X-axis and smallest along the Z-axis is recommended for model quality. (Source 2, "INSURE MODEL QUALITY")
	• Tolerance: The accuracy of a part is a function of resolution and precision. Deviations from perfection are influenced by the mesh file, machine accuracy, resolution, repeatability, control system capabilities, and material rheology. (Source 2, "TOLERANCE", "ACCURACY AND PRECISION", "OTHER CONTRIBUTORS TO TOLERANCE")
	• Nesting: The process of arranging multiple parts on a build tray to optimize space, reduce waste and build time. Applies to both 2D and 3D arrangements. (Source 2, "NESTING & PART ORIENTATION", "NESTING")
6. CAD to CAM Workflow:
	• Mesh: STL is a standard mesh file type that approximates solid surfaces with triangles. The number and size of triangles determine the accuracy of curved surfaces. (Source 2, "CAD to CAM (WHAT IS A MESH?)", "UNDERSTANDING MESH")
	• Creating an STL: Key settings like angle, deviation, and chord height control the smoothness and file size. Balance between file size and detail is crucial. (Source 2, "Creating an STL", "ABOUT THE STL?", "CAD TO STL")
	• STL File Format: Can be ASCII (human-readable, large size) or BINARY (computer-readable, smaller size). BINARY is recommended to save time and file size. (Source 2, "THE STL FILE – STORAGE FORMAT")
	• Multi-Material Printing: Requires separate solid bodies in CAD, which are converted to separate STL files for material assignment. (Source 2, "CAD FOR MULTI-MATERIAL PRINTING")
7. Post-Processing Techniques:
	• General Considerations: Most techniques rely on tools and machines, with safety being the most important consideration. (Source 1, q10)
	• Support Removal: Soluble support is removed in a cleaning station with heated water and a cleaning agent. Key considerations include tank agitation, temperature, manually removing some support, keeping parts submerged, and using enclosures for fragile parts. Sparse parts may absorb water and require drainage holes. (Source 2, "SUPPORT REMOVAL / SOLUBLE", "CLEANING STATION OPTIONS")
	• Bonding/Gluing: Used for models larger than the tray size or when printing parts individually is more practical. Requires separating the model in CAD or STL software and adding clearance for the glue. (Source 2, "BONDING / HOT AIR WELDING", "GLUING") Hot Air Welding is the strongest FDM bonding method, while Epoxy is the weakest. (Source 1, q13 - Note: There are two questions with the same ID q13, one stating Epoxy is weakest and the other stating Hot Air Welding is strongest. This indicates a potential discrepancy in the source material, but the briefing reflects both statements as presented.)
	• Plating: Requires adjusting the CAD file for plating thickness, sanding surfaces to remove layer lines, sealing surfaces (Finishing Station, Solvent Dipping, Epoxy coating), curing, and re-sanding. (Source 1, q1; Source 2, "PLATING", "PLATING PROCESS") Coating thickness and temperature of the plating process impact design and material selection for plating, while wall thickness and coating color do not. (Source 1, q1)
	• Mass Finishing: Uses abrasive media to smooth and polish parts. Centrifugal Barrel Machines are best for fine details and a quick, aggressive finish, while Vibratory Tubs are ideal for more fragile parts with complex geometries requiring a gentler finish. (Source 1, Centrifugal Barrel Machines and Vibratory Tubs descriptions) Media shapes and sizes affect cutting action and smoothing. Design modifications may be needed for thin features, narrow channels, or holes. (Source 2, "MASS FINISHING / MEDIA SHAPES")
	• Vapor Smoothing: Seals FDM parts at ambient pressures and liquid applications, limited to ABS materials. (Source 2, "VAPOR SMOOTHING FDM PARTS")
8. Applications of Additive Manufacturing:
	• Medical Field: Custom implants like hip joints or dental crowns are an example of AM use in the medical field. (Source 1, q6) Stratasys technologies are used in medical devices (e.g., creating advanced drug delivery systems, 3D printed hearts for surgical planning) and dentistry (digital orthodontics, partial frameworks, crowns, bridges). (Source 2, "MEDICAL DEVICE: SYQE MEDICAL", "DENTAL")
	• Aerospace: Powder Bed Fusion may be chosen over Material Extrusion for aerospace parts due to "Higher resolution and material strength." (Source 1, q4)
	• Production Parts: Benefits include "Highest degree of customization, optimal supply chain efficiency, increased sustainability, with less material waste/usage." (Source 1, q12)
	• Rapid Prototyping: Offers "Improved time to market, lower cost of development cycles, greater design freedom, highest degree of realism and functionality." (Source 2, "RAPID PROTOTYPING")
	• Tooling: Digital Manufacturing applications include sandcasting, jigs and fixtures, End-of-Arm Tooling (EOAT), blow molding, silicone molding, and injection molding. (Source 2, "Define Digital Manufacturing applications of Sandcasting...") Stratasys materials like ULTEM 1010 and PC are suitable for tooling applications. (Source 2, "Which types of applications ULTEM 1010 best for?", "PC - POLYCARBONATE")
• End-Use Parts: Traditional processes for end-use parts have limitations on quantities, size, manufacturing requirements (thermoplastic properties, thermal resistance, tolerance), added features, and skilled labor requirements. (Source 2, "END-USE PARTS | TRADITIONAL PROCESSES")
9. Safety Considerations:
	• Metal Powders: Safety risks include inhalation of fine particles, fire or explosion hazards, and skin contact hazards. UV radiation exposure is NOT typically associated with handling metal powders in AM. (Source 1, q7)
	• Post-Processing: Safety is the most important consideration when using tools and machines for post-processing. (Source 1, q10)
	• Data Sheets (SDS): Provide information about the properties and safety of materials. (Source 2, "MATERIALS DATA SHEETS & SAFETY DATA SHEETS (SDS)")
10. Economic Impact of AM:
	• AM is contributing to the development of new business models and supply chains, including decentralized manufacturing. (Source 2, "ECONOMIC IMPACT", "NEW BUSINESS MODELS AND SUPPLY CHAINS", "DECENTRALIZED MANUFACTURING")
	• It changes the economics of production, particularly impacting economies of scope (producing a wider variety of products more efficiently) and economies of scale (reducing cost per unit with increased volume). While conventional manufacturing typically benefits from economies of scale, 3D printing can be more cost-effective for lower volumes and higher product variants. (Source 2, "CHANGES IN THE ECONOMICS OF PRODUCTION")