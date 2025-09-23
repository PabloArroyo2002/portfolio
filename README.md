# Aerospace Engineering Graduate

#### Technical Skills: SolidWorks, CATIA V6, Engineering Drawings, Python, MATLAB, MS Office, Soldering, Basic Circuitry
#### [Email me](mailto:pablo.arroyo.2020@gmail.com)

## Education
- B.S., Aerospace Engineering | Massachusetts Institute of Technology (_May 2025_)

## Areas of Interest
- Propulsion, Advanced Manufacturing, Aero Structures, Energy Generation, and Actuators

## Professional Experience
### Undergraduate Researcher @ MIT HAUS (_June 2023 - Present_)
- Designed, assembled, and successfully implemented a CO₂ pressurization system to create foaming pellets at a new scale for additive manufacturing. Paper coming soon.
- Demonstrated viability of increasing layer height on pile footing prints as a means of reducing print time while maintaining satisfactory performance. [Publication](https://doi.org/10.1007/978-3-031-77697-7_16)
- Reduced the mass of a **HUD compliant** roof design by 30% by using **SolidWorks FEA** to validate new geometries.
- Assisted fellow undergraduate researchers in BAAM use and validated new print surfaces.
- Compiled relevant **ASTM** and **ISO** standards for preliminary characterization of our BAAM 3D printer.

![CO2 Infuser]({{ "/assets/co2-infusion-system.jpg" | relative_url }})
**CO2 Dilution System:** Polymer pellets absorb carbon dioxide while safely residing in a hydraulic accumulator surrounded by a ballistic blanket. Revised designs will swap the hydraulic accumulator for a reusable and lighter solution. Experimentation with polymers other than PET and the use of additives may also produce foam with a higher expansion ratio.

![Demonstration of floor scale]({{ "/assets/scale-example-floor.png" | relative_url }})
**Scale of our Research:** The size of the floor, footings, and concrete bags provides a sense of the scale MIT HAUS regularly operates at. This image was taken during a loading test.

![MIT HAUS Curved]({{ "/assets/mit-haus-curved.png" | relative_url }})
**Pushing Boundaries:** Use of curvature, trusses, and hierarchy allows us to leverage additive manufacturing to create robust yet lightweight structures. Simple FEA cases are verified by testing on small FDM models in light of the modeling challenges posed by the anisotropic nature of additively manufactured parts.

### Engineering Intern @ Radia, Inc. (_June 2024 - August 2024_)
- Sized composite panels according to durability and deflection requirements while minimizing weight by creating a **MATLAB** model relating mass and deflection. Analyzed potential failure modes for composite panels reinforced by hat-stiffeners using hand calcs and relevant NACA literature.
- Proposed a new fairing design and substantiated it with drag impact calculations and analysis on manufacturability. Conducted a trade study to determine ideal panel dimensions subject to transportation, weight, and assembly considerations. Advocated for these and other key design decisions during weekly meetings with other stakeholders.
- Made a **CATIA** model using **3DXPERIENCE** for my team’s structural concept while allowing for interaction with adjacent aircraft systems.

## Projects
### Home-Built Jet Engine
- Developed a ceramic matrix composite that could be manufactured at home and withstand 2000 °C. Molded the composite around 3D printed PLA forms for easy reproducibility and consistency between mating surfaces upon assembly.
- **Milled** different fuel injectors to allow for tuning between runs. Calculated areas for each stage of air addition and fuel injection to reduce exhaust temperatures and extend turbine lifespan.
- Welded a test rig to hold the jet engine, a protective piece of acrylic and pressure and temperature gauges.

![Clean Jet Engine]({{ "/assets/clean-jet-engine.jpg" | relative_url }})
**All systems go?** The engine is almost ready to fire up, except for a missing battery to drive the ignition system and a clamp to restrain the burn chamber.

![Fire Exhaust Jet Engine]({{ "/assets/jet-fire-exhaust.JPEG" | relative_url }})
**Running Hot:** Excessive liquid propane and help from a leaf blower push the jet engine beyond its optimal operating range after a successful test earlier in the day.

![Fuel Injectors]({{ "/assets/fuel-injector.jpg" | relative_url }})
**Injector Selection:** Four fuel injectors machined on a Bridgeport mill boast holes as small as 1/64". 

### Deep Sea Soil Sampler
- Designed and constructed a mechanically activated and actuated sediment collector used at a depth of 11 km following the Five Deeps Expedition. Used aluminum linkages and pulleys to efficiently transfer spring energy to a sample collector where electronics and hydraulics would fail under the pressure.
- Calculated pressure plate area and geometry to avoid premature triggering from shocks and descent in the water column. Tested different scoop designs and end-caps to maximize the sample volume captured and retained.

![Original Prototype Sampler]({{ "/assets/original-sampler.jpg" | relative_url }})
**Surefire Design:** Operating with a simple trigger and a cam, the first prototype was prone to misfiring upon dropping into the ocean but was otherwise reliable. This performance was satisfactory given that the consistency of the landing site was completely unknown at the time.

![Challenger Deep Sample]({{ "/assets/challenger-deep-sample.jpg" | relative_url }})
**Fast Turnaround:** This sample was in Texas within a month of us shipping out the first prototype, and taught us that the floor in the Mariana Trench was soft, informing the design for the next set of samplers.

![Soil Sampler Early]({{ "/assets/soil-sampler-early.jpg" | relative_url }})
**Informed Design:** With a better understanding of the challenge of dropping into the ocean and descending, these samplers were calibrated in a pool to avoid misfires. The amount of material captured was also improved by the addition of relief vents at the top of the tube, allowing water to flow through the snapping sampler claw.

![Soil Sampler Late]({{ "/assets/soil-sampler-late.jpg" | relative_url }})
**Raising the bar:** The demand for stratified soil samples forced an abandonment of the claw mechanism and motivated a design that would push the sample collector perpendicular to the silt upon which it rested.

### Dual Fluid Impeller System
- Designed a fluid impeller and casing for metal and polymer SLS manufacturing, navigating the challenge of uncertain achievable tolerances. Created **engineering drawings** for the impeller and casings. Achieved the lowest leakage of all six teams in the class and avoided near-critical operation. Used **CFD** to create an estimate of pressures and velocities for each impeller. Used a **data acquisition system** to characterize the pump and measure displacement near the critical speed of a rotor system.

![Pump Assembly]({{ "/assets/pump-assembly-4.jpg" | relative_url }})
**Tight Seals:** Despite the need for pipes to reduce the fluids spilling on the table, the use of off-the-shelf O-rings against machined surfaces kept leaks at a minimum. Thrust created by the pressure rise around the impellers was substantial and hurt the alignment of the axle relative to the pump casings, causing more leaks than expected. The ball bearings on the far right of the axle served to resist this thrust, but did not negate the torque created around each of the feet on which the pump casings were mounted.

![Impeller CFD]({{ "/assets/impeller-cfd.png" | relative_url }})
**CFD Modeling:** The force of fluid pushing against blades in impellers cannot be ignored; however, the drops in pressure near the inlet cause cavitation that affects performance much more than any deflection of the blades. CFD failed to capture this effectively because it failed to converge for cavitating cases.  

![Rotordynamics Test]({{ "/assets/rotordynamics-lab-1.jpg" | relative_url }})
**Safety Margin:** Laser-based measurements showed no concerning increases in whirl amplitude as the motor approached 3500 rpm. These velocity sweeps did reveal the importance of lubrication on seals and journal bearings, as one of the journal bearings seized due to thermal expansion. Heating was visible through the use of an infrared camera, although an infrared thermometer could have revealed the same phenomenon at a lower resolution.

![Impeller Photograph]({{ "/assets/am-impeller.png" | relative_url }})
**Early Development:** Initial trials of the additively manufactured water impeller revealed poor efficiency, although not drastically different from the baseline impeller. Although not understood at the time, later use of transparent pipes would reveal that cavitation was likely occurring even below 1500 rpm. During final trials, the blade count of 6 created much less cavitation than other designs with more blades, allowing for higher efficiency at high rpms, albeit only in relative terms. 

### Satellite Design and Analysis
- Designed a fictional probe mission to Europa. Ensured the satellite packaging could fit within a Falcon Heavy fairing and survive the vibrational environment of takeoff. Reduced cantilevers and selected composites where appropriate to eliminate dangerous vibrational modes using **SolidWorks FEA** tools. 
[Download the preliminary report]({{ "/assets/documents/16_83_Structures_final.pdf" | relative_url }}) or the
[risk mitigation report]({{ "/assets/documents/Structures Slide Deck Risk Mitigation.pdf" | relative_url }})

![George CAD]({{ "/assets/more-george.png" | relative_url }})
**G.E.O.R.G.E. CAD Model** This model captures all of the scientific instruments, RTGs, and antennas needed for a successful mission. This model helped the other teams understand the scale of their components and to see how they would physically fit together; however this model does not reflect how the satellite will be launched.

![George FEA]({{ "/assets/george-vibe-test.png" | relative_url }})
**Simplified Model** This simple model captures the behavior of the satellite in its launch configuration, with fewer sensors and antennas deployed. The most sensitive component on launch is the composite parabolic antenna made for communication with the Earth.

- Also created a probe to measure the salinity of a pool into which the satellite deploys, simulating a mock Europa mission. Designed a voltage divider and **Arduino** code to calculate the salinity of the water into which the probe is dropped by using spaced electrodes.
[Download the report]({{ "/assets/documents/Proposal_for_Flight_Demonstration__Final_Draft.pdf" | relative_url }})

![Probe PCB]({{ "/assets/83-probe.jpg" | relative_url }})
**Almost Ready** The perf board has all components soldered in and the salinity sensor is waterproofed. Sealing the whole probe proved a difficult task but was eventually accomplished with EVA glue after extensive testing. The ruggedizing Kevlar proved to be a poor choice in this application as it wicked water through the epoxy and glue used in sealing.

![Probe Complete]({{ "/assets/83-probe-assembled.jpg" | relative_url }})
**Integration** The probe is tuned to the same frequency as the receiver on the main satellite, enabling communication up to the satellite and then to a laptop for data processing. Deployed the satellite via sensor fusion of a thermal camera detecting the cold salty water in the area of interest and a regular camera looking for fewer green pixels, as the trajectory of the satellite was mostly over grass. Detection was successful, but the probe failed to deploy on some late trials as the release mechanism seized.

### Canonical Heat Addition Case
- Produced a report discussing the canonical case of heat addition and removal from a stovepipe ramjet as presented in Oswatitsch's _Gas Dynamics._ Created an analytical model for thrust generation in the supersonic regime and validated it against Ansys. [Download the paper]({{ "/16_120_Final_Project.pdf" | relative_url }})

![Shock Measurement Angles]({{ "/assets/ansys-validation.png" | relative_url }})
**Geometric Agreement:** CFD models show very close alignment to analytical models that solve for shock angles by pressure equilibrium. Overall, analytical and CFD models show the same trends, except for the supersonic choking case, where analytical models fall short.

## Talks & Lectures
- Guest Presentation: MIT HAUS First-of-Kind Prototypes - Dual Use Innovation Day, Spring 2025

## Potential Future Projects
### Manufacturing
- Assembleable minimal surfaces to guide fibers for the creation of dense 3D composites with complex shapes.
- Expanding the range of particle velocity and mass flow rate through cold spray nozzles via revised geometries.

### Robotics
- MEMS cooling system to minimize heat buildup despite smaller apertures achieved through higher back pressure. May enable improvements in air flow following Moore's Law.
- Additively manufactured NiTi compliant mechanisms for high-load applications.

### Propulsion
- Plasma stabilization of high Mach combustion for reduced static temperature rise. Enable the use of less exotic alloys and composites in turbines.

### Athletics
- Portable PSA-based hypoxicator and breathing system for altitude training on the go.
- Replicate CO₂ infusion from PET in PEBA for 3D printed shoe sole prototypes.

![Hypoxicator Schematic]({{ "/assets/hypoxicator-schematic.jpg" | relative_url }})
**Compact vPSA** This early schematic shows a vacuum pressure swing absorption hypoxicator. A more mature design will forego the efficiency provided by the vacuum, given the importance of minimizing weight for long term comfort. Energy efficiency and component weight can be compared by using the energy density of COTS battery packs.

![Spikes On Shoe]({{ "/assets/spike-addition.jpg" | relative_url }})
**Hybrid Running Shoe** Pre-2024 NCAA rules allowed for higher stack heights on the track. This weight could be justified for the steeplechase where the extra height reduces the energy cost of jumping barriers and maximum forces on the ground for athletes who are injury prone. Early trials showed that unsupported track spike holders would tear out given the high shear forces along the ground. Designed and prototyped a tough Kevlar plate to provide stiffness and a surface for attachment of spike holders. Rules have since been amended that make this shoe ineligible for competition in track, but there may still be a place for it for injury-prone athletes in cross country.

![Illustration of Sensitive Foot Areas]({{ "/assets/shoe-ergonomics.jpg" | relative_url }})
**Comfort Priorities** Early reflections on shoe shape and identification of areas on the foot that are prone to calluses, bruises or are otherwise sensitive. There is a lot of room to improve on making more comfortable and fashionable footware.

Ask me about these or other ideas you may want to discuss.

## Publications
1. Perez, A.A., Arroyo, P., Sehnawi, K.H., Chandar, A.S., Hardt, D.E. (2025) Layer Height Treatments on Uniaxial Compression Performance of Industrial Large-Scale Additively Manufactured Polymer Composite Structures. In: Lopresto, V., Papa, I. (eds) Dynamic Response and Failure of Composite Materials. DRAF 2024. Lecture Notes in Mechanical Engineering. Springer, Cham. [https://doi.org/10.1007/978-3-031-77697-7_16]

---

## Other Projects
I have also worked on developing a few automotive concepts, as shown below:

![Istioforo 1]({{ "/assets/istioforo-1.jpg" | relative_url }})
![Istioforo Concepts]({{ "/assets/istioforo-concepts.jpg" | relative_url }})
![Mixed Istioforo Concept]({{ "/assets/mixed-istioforo-concepts.jpg" | relative_url }})
![Istioforo Lean]({{ "/assets/istioforo-lean.jpg" | relative_url }})
![Istioforo Early]({{ "/assets/istioforo-early.jpg" | relative_url }})
![Istioforo Cooling]({{ "/assets/istioforo-cooling.jpg" | relative_url }})
![Istioforo Mixed]({{ "/assets/istioforo-mixed.jpg" | relative_url }})
![Mixed Concepts]({{ "/assets/mixed-concepts.jpg" | relative_url }})
![Amphibious Vehicle]({{ "/assets/amphibious-vehicle.JPG" | relative_url }})
![Testarossa Iteration]({{ "/assets/testarossa-iteration.JPG" | relative_url }})
![Miura Lookalike]({{ "/assets/miura-lookalike.jpg" | relative_url }})
![drkside design front view]({{ "/assets/drkside-design-front-view.jpg" | relative_url }})
![drkside design rear view]({{ "/assets/drkside-design-rear-view.jpg" | relative_url }})
![drkside design side view]({{ "/assets/drkside-design-side-view.jpg" | relative_url }})
![drkside design top view]({{ "/assets/drkside-design-top-view.jpg" | relative_url }})

### Artwork
![Bugatti Chiron]({{ "/assets/bugatti-chiron.jpg" | relative_url }})
![Ferrari 250 GTE]({{ "/assets/ferrari-250-gte.jpg" | relative_url }})
![McLaren in Marker]({{ "/assets/mclaren-marker.jpg" | relative_url }})
![Ferrari 330 P4]({{ "/assets/ferrari-330p4.jpg" | relative_url }})
![Bugatti Painting]({{ "/assets/bugatti-painting.jpg" | relative_url }})
![Aston Martin Rear]({{ "/assets/aston-martin-rear.png" | relative_url }})
![Hap Stern Commission]({{ "/assets/hap-stern-comission.jpg" | relative_url }})
![St. Mark's Campus]({{ "/assets/stmarks-campus.jpg" | relative_url }})
![Violin Oil Painting]({{ "/assets/violin-in-oil.jpg" | relative_url }})
![Still Life]({{ "/assets/miscellaneous-1.jpg" | relative_url }})

## Appendix
![Solar Accumulator]({{ "/assets/solar-accumulator.jpg" | relative_url }})

![AM Stairs]({{ "/assets/am-stairs.jpg" | relative_url }})
![AM Trusses]({{ "/assets/am-trusses.jpg" | relative_url }})
![Anisotropic Considerations]({{ "/assets/anisotropic-considerations.jpg" | relative_url }})
![Aspect Ratio Layers]({{ "/assets/aspect-ratio-layers.png" | relative_url }})
![CO2 Pressurizer 2]({{ "/assets/co2-pressurizer-2.jpg" | relative_url }})
![Hydraulic Accumulator]({{ "/assets/hydraulic-accumulator-1.jpg" | relative_url }})
![BAAM Print 1]({{ "/assets/baam-print-1.jpg" | relative_url }})
![Test Sample Arrangements]({{ "/assets/test-sample-arrangements.jpg" | relative_url }})
![Test Articles 1]({{ "/assets/test-articles-1.jpg" | relative_url }})
![Test Articles 2]({{ "/assets/test-articles-2.jpg" | relative_url }})
![Test Articles Envisioned]({{ "/assets/test-articles-envisioned.png" | relative_url }})
![Baldwin Machine Pile Footing Test]({{ "/assets/baldwin-test.jpg" | relative_url }})

![Cooling Channel]({{ "/assets/cooling-channel.png" | relative_url }})
![Dual Pump CAD]({{ "/assets/dual-pump-cad.png" | relative_url }})
![Pump Characteristic]({{ "/assets/pump-characterization.png" | relative_url }})
![Engineering Drawing]({{ "/assets/engineering-drawing-1.jpg" | relative_url }})

![PLA Molds for Burn Chamber]({{ "/assets/pla-molds.jpg" | relative_url }})
![V2 Burn Chamber and Cart]({{ "/assets/jet-engine-early.jpg" | relative_url }})
![Jet Engine Test Stand Welding]({{ "/assets/jet-frame.jpg" | relative_url }})
![Ignition Coil Test]({{ "/assets/ignition-coil-test.png" | relative_url }})
![Pressure regulation]({{ "/assets/pressure-regulation.png" | relative_url }})
![Self-Sustain]({{ "/assets/self-sustain-1.png" | relative_url}})

![Vaporfly 2 Repair]({{ "/assets/vaporfly-2-repair.jpg" | relative_url }})

![CC V2]({{ "/assets/cc-v2.jpg" | relative_url }})
![CC V2 Idea]({{ "/assets/cc-v2-idea.jpg" | relative_url }})
![Linear Filter Combos]({{ "/assets/linear-filter-combos.jpg" | relative_url }})
![Soil Sampler Concept]({{ "/assets/soil-sampler-concept.jpg" | relative_url }})
![Casa Concept 1]({{ "/assets/casa-concept-1.jpg" | relative_url }})
![Casa Concept 2]({{ "/assets/casa-concept-2.jpg" | relative_url }})
