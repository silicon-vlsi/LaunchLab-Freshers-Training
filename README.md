# LaunchLab-Freshers-Training
This repository contains all the materials related to the basic MOSFET theory, CMOS technology, circuit and layout design, and basic PDK design.

## Some Useful Videos on IC Design
- **PROCESSING TECHNOLOGY**
  - [Wafer Manufacturing Process](https://www.youtube.com/watch?v=3TOpg1niATg)
  - [Making Memory Chips -- Processing steps](https://www.youtube.com/watch?v=M-wNC3Z3ZX4) -- Micron Technology
  - [Chip Manufacturing Process -- How are chips made](https://www.youtube.com/watch?v=bor0qLifjz4) -- Infeneon
  - [VLSI Fabrication Process](https://www.youtube.com/watch?v=fwNkg1fsqBY)
  - [Photolithography -- Step by Step](https://www.youtube.com/watch?v=oBKhN4n-EGI)
  - [VLSI - Lecture 2b: The Manufacturing Process - Detailed Process Flow](https://www.youtube.com/watch?v=btFk7jkk5e4)
- **MOSFET MECHANICS**
  - [How MOSFETs and Field-Effect Transistors Work](https://www.youtube.com/watch?v=tz62t-q_KEc)
  - [How Transistors Work - The MOSFET](https://www.youtube.com/watch?v=QO5FgM7MLGg&t=4s)
  - [MOSFET: Physical View](https://www.youtube.com/watch?v=wP-ODG_e1i0)
  - [MOSFET Working animation](https://www.youtube.com/watch?v=ItOV1nkTlPU)
  - [What is a CMOS?](https://www.youtube.com/watch?v=docgmTprR5o)
- **NAND FLASH MEMORY**
  - [What's 3D NAND and 2D NAND Flash Memory](https://www.youtube.com/watch?v=Q1djdDh78PA)


## Course Contents

### Week-1: Pre-requisites
- **Fundamentals of RC Circuits**: Test your understanding by solving assignments. [Test: RC Circuit]()
- **Fundamentals of Digital Logic**: Test your understanding by solving assignments. [Test: Digital Logic Design](https://www.dropbox.com/s/k5vwksmb9quau2n/Digital-Circuits-Assignment.pdf)
  - *Reference Book*: Digital Logic and Computer Design by M. Morris Mano. [[Link]](https://ia800607.us.archive.org/3/items/DigitalLogicAndComputerDesignByM.MorrisMano2ndEdition/Digital%20Logic%20And%20Computer%20Design%20By%20M.%20Morris%20Mano%20%282nd%20Edition%29.pdf)
- **Fundamentals of Electrical Circuits**: Test your understanding by solving assignments. [Test: Electrical Circuits](https://www.dropbox.com/s/26f7nwgm0qtkbvw/Electrical-Circuits-Asignment.pdf)
  - *Reference Book*: Fundamentals of Electrical Circuits by Alexander and Sadiku. [[Link]](https://library.iitp.ac.in/images/btech_ebook/Fundementals%20of%20Electric%20Circuits%20by%20Alexander%20and%20Sadiku.pdf)
- **Fundamentals of Semiconductor Devices**: Test your understanding by solving assignments. [Test: comming soon]()
- **Fundamentas of UNIX**: 
  - Practicing basic UNIX commands. [[Link]](https://www.webminal.org/)
  - Practicing frequently used and advanced UNIX commands. [[Link]](https://www.dropbox.com/s/mdcrzaglnirs7z9/Ultimate_Linux_Commands.pdf)
  - Practicing file editing commands. [[Link]](https://www.dropbox.com/s/v0vnute8hbwkrts/vim_tutorial.pdf)
  - Test your understanding by solving assignments. [Test: comming soon]()
  
### Week-2: Introduction to Digital Logic Circuit Design (Gate Level)
- **Logic Gates**: Understanding of basic (NOT, AND, OR), universal (NAND, NOR) and special logic gates (X-OR,X-NOR). 
- **Truth Table & K-Map**: Draw the truth table and find out the logic circuit using K-Map (up to 5 variable). 
- **Combinational Circuit**: Draw the following circuits: Adders, Subtractors, Multiplexers, De-multiplexers, Decoders, Encoders and Code converters.
- **Sequential Circuits**: Draw the following circuits: Latches, Flip-Flops, Resisters, Counters and FSM.
  - Understanding the concept of setup time. hold time, removal time, recovery time etc.
- **Misc.**: Multiplexer and Decoder based logic circuit design, Edge detector circuit design.
- **Logic States**: Understanding the loging states and their relevances: 1, 0, X, Z.
- **Timing Diagram**: Understanding the timing diagram of all the combi and sequential logic circuits.
- *Reference Book*: Digital Logic and Computer Design by M. Morris Mano. [[Link]](https://ia800607.us.archive.org/3/items/DigitalLogicAndComputerDesignByM.MorrisMano2ndEdition/Digital%20Logic%20And%20Computer%20Design%20By%20M.%20Morris%20Mano%20%282nd%20Edition%29.pdf)
### Week-3: Basics of CMOS VLSI Design
- **Introduction**: Fundamentals of VLSI Design and overview of Sand-to-Silicon.
- **IC Design Flow**: Overview of Digital and Custom IC Design Flow and requirement of Computer Aided Design (CAD) Tools and Process Design Kit (PDK).
  - Digital IC Flow:  Spec --> RTL --> RTL Verification --> Gate-level synthesis --> Gate-level simulation --> Physical Design --> Physical Verification --> parasitic extraction --> Post-layout verification.
  - Custom IC Flow (Analog IC Design): Spec --> Circuit Design --> Circuit Simulation --> Layout Design --> Layout Verification --> Parasitic Extraction --> Post-layout Simulation. [[Notes]](https://www.dropbox.com/s/cyu949ln3oxjfef/Custom%20VLSI%20Flow.pdf)
  - Requirements of the different CAD tools and PDK in different phase of the IC Design Flow. [[Notes]](https://www.dropbox.com/s/cyu949ln3oxjfef/Custom%20VLSI%20Flow.pdf)
- **IC manufacturing process**: [[Link]](https://www.dropbox.com/s/zxp1dnwknvpfz8y/Weste-JohnsMartin-CMOSprocessing-Layout-Highlight-annotate.pdf)
     - Difference between Sub-micron, deep sub-micron and ultra-deep sub-micron process.
     - Detailed understanding of sub-micron process.
     - Passive IC devices and its fabrication: Resistor and Capacitor
     - MOSFET and CMOS Inverter fabrication process, cross-sectional view, top view and 3D view.

### Week-4: Fundamentals of MOSFET
- **MOS Structure**: Understanding of Metal-Oxide-Semiconductor structure || understanding of accumulation, depletion and inverssion region of operation || understanding of Q-V and C-V characteristics of MOS structure.
     - *MOS Stucture-1* [[Notes]](https://www.dropbox.com/s/ntcueemzmsbx9vb/2020-0803-15VLSI7T-Module1-Lecture-4-5-MOS-Transistor.pdf) || [[Video]](https://www.youtube.com/watch?v=AxZyFuJh0rM)
  - *MOS Stucture-2* [[Notes]](https://www.dropbox.com/s/85kswvq4ejs08ha/2020-0805-15VLSI7T-Module1-Lecture6-MOS-Transistor.pdf) || [[Video]](https://www.youtube.com/watch?v=zQmV7c30ZDU)
  - *MOS Stucture-3* [[Notes]](https://www.dropbox.com/s/xcipyfkiis1fbo5/2020-0810-15VLSI7T-Module1-Lecture7-8-MOS-Transistor.pdf) || [[Video]](https://www.youtube.com/watch?v=Eyu6TVZRwAE)
- **MOSFET**: Understanding of Metal-Oxide-Field-Effect-Transistor (MOSFET), working principle, regions of operation, Id-Vgs and Id-Vds characteristics, Body effects, Channel length modulations and intrinisic capacitances.
  - *Metal Oxide Semiconductor Field Effect Transistor-1* [[Notes]](https://www.dropbox.com/s/23z0n3p068hkgul/2020-0817-15VLSI7T-Module1-Lecture9-10-MOSFET.pdf) || [[Video]](https://www.youtube.com/watch?v=tfF-K-Gbeb4)
  - *Metal Oxide Semiconductor Field Effect Transistor-2* [[Notes]](https://www.dropbox.com/s/mqzd1o6u5y8qprn/2020-0818-15VLSI7T-Module1-Lecture11-12-MOSFET.pdf) || [[Video]](https://www.youtube.com/watch?v=bPLzXzopsNo)
- **MOSFET Capacitance**: Understanding of different intrinsic capacitances (overlap capacitance, channel capacitance, junction capacitance) of a MOSFET
  - *MOSFET Capacitance* [[Notes]](https://www.dropbox.com/s/xxci3s9zu62b042/2020-0819-15VLSI7T-Module1-Lecture13-MOSFET-Capacitance.pdf) || [[Video]](https://www.youtube.com/watch?v=toIzPbxFwKE)
- **Short Channel Effects**: Understanding of MOSFET scaling and differenct short channel effects: Drain induced barrier lowering (DIBL), Velocity Saturation, Mobility degradaton, Hot carrier effects and Impact ionisation.
  - *Short Channel Effects* [[Notes]](https://www.dropbox.com/s/0b1jc56bo2svz98/Short-Channel-Effect.pdf)
- **Asignments**: [Assignment-1](https://www.dropbox.com/s/7b81grtkhlmnbyx/MOSFET-Asignment.pdf)

### Week-5: Circuit Simulaton using CAD tools
- **Circuit Simulation** Understanding of schematic drawing, SPICE net-list, model file and circuit simulation.
- **Simulation Types** Different type of Simulations: Operating point, DC, Transient and AC.
  - *Schematic Drawing and Symbol Creation* []()
  - *DC Simulation* []()
  - *Transient Simulation* []()
- **MOSFET Characterization**: Simple circuit design using NMOSFET and PMOSFET to characterize Id-Vgs and Id-Vds curves with PVT variations.
- **Parameter Extraction**: Extraction of the simple level-1 parameters (VT0, KP, LAMDA, GAMMA, PHI) from the curve and comparing the results using Level-1 model and BSIM model.
- **PVT Variation**: Understanding of Process, Voltage and Temperature (PVT) variation
- **Sensitivity and mismatch analysis**: Understanding the random variation and mismatch analysis by Monte Carlo simulations.
- **Parametric simulation**: Parametric analysis and circuit simulation using ADE-XL

### Week-6: CMOS Inverter Design
- **CMOS inverter**: Understanding of CMOS inverter design, CMOS advantages, static characteristics, dynamic characteristics, power and energy consumptions.
  - *Static Characteristics* [[Notes]](https://www.dropbox.com/s/6bosq72c78s964j/2020-0824-15VLSI7T-Module1-Lecture14-15-Inverter-Static.pdf) || [[Video]](https://www.youtube.com/watch?v=zXtUMSTi0KY)
  - *Switching Characteristics and Delay Calculation* [[Notes]](https://www.dropbox.com/s/ictagcl13jpd62v/2020-0831-15VLSI7T-Module1-Lecture16-17-Inverter-switching.pdf) || [[Video]](https://www.youtube.com/watch?v=U8spQ_6kLYE)
  - *Static and Dynamic Power Dissipation* [[Notes]](https://www.dropbox.com/s/yasjc7athn4gggx/2020-0901-15VLSI7T-Module1-Lecture18-19-Dynamic-Power.pdf) || [[Video]](https://www.youtube.com/watch?v=IVuvTYa_SUE)
- **Interconnect Parasitics**: Understanding the wiring capacitance: parallel plate capacitance, coupling capacitance, fringing capacitance and different capacitance models.
  - *Interconnect Parasitics* [[Notes]](https://www.dropbox.com/s/1vicae5kih5flm0/2020-0914-15VLSI7T-Module4-Lecture3-Interconnect-Parasitics.pdf) || [[Video]](https://www.youtube.com/watch?v=uQoivq7c5ZQ)
- **Inverter Chain**: Understanding of Inverter chain design to drive a higher capacitive load || Understanding of number of stages ans stage ratio || Understanding of optimal delay.
  - *Inverter Chain Design* [[Notes]](https://www.dropbox.com/s/1in6ofch4lxt7zv/2020-0915-15VLSI7T-Module2-Lecture25-26-Inverter-Chain-Design.pdf) || [[Video]](https://www.youtube.com/watch?v=uQoivq7c5ZQ)
- **Design and Simulation**: Design, simulation and charactrization all of the above.

### Week-7: Other Combinational and Sequential Circuit Design
- **Other Combi**: Design other combinational logics like, NAND gate, NOR gate, MUX and transmission gates.
  - *CMOS Logic Circuits & Complex Logic Circuits [[Notes]](https://www.dropbox.com/s/tpdidw4rtuvk9f4/2020-0907-15VLSI7T-Module2-Lecture20-21-Combinational-Logic.pdf) || [[Video]](https://www.youtube.com/watch?v=uQoivq7c5ZQ)
  - *CMOS Transmission Gate* [[Notes]](https://www.dropbox.com/s/8xkxupbchyv9m9s/2020-0908-15VLSI7T-Module2-Lecture22-23-Transmission-Gate.pdf) || [[Video]](https://www.youtube.com/watch?v=yKiQru_JIpE&t=16s)
  - *Pseudo NMOS Logic* [[Notes]](https://www.dropbox.com/s/d0fsj5oyyjygusu/2020-0909-15VLSI7T-Module2-Lecture24-Pseudo-NMOS-Logic.pdf) || [[Video]](https://www.youtube.com/watch?v=Gi2ipFUubfs)
- **Sequential Logic Circuits**: Understanding of latch and flip-flop design || understanding of setup, hold and propagation time 
  - *Latch and Flip-Flop Circuits* [[Notes]](https://www.dropbox.com/s/0q6lvah7bk2j11e/2020-0921-15VLSI7T-Module2-Lecture28-29-Sequential-Circuits.pdf) || [[Video]](https://www.youtube.com/watch?v=LHw9McKBRJI)
  - *Sequential Logic Circuits* [[Slides]](https://www.dropbox.com/s/uht871k7dje6hnj/2020-0921-15VLSI7T-Module2-Lecture28-29-Sequential-Circuits-Slides%28Kang-Book%29.pdf) || [[Video]](https://www.youtube.com/watch?v=ETCqIvNYOpk)
  - *Setup, Hold and Propagation delay of D-FF* [[Notes]](https://www.dropbox.com/s/xmpueuvrqmcsclv/2020-0922-15VLSI7T-Module2-Lecture30-31-Setup-Hold-Propagation-Delay-of-DFF.pdf) || [[Video]](https://www.youtube.com/watch?v=5Ofx-QubGts)
  - *Hold Time Analysis of D-FF* [[]]() || [[Video]](https://www.youtube.com/watch?v=5HziqKs8luE)
- **Static Timing Analysis (STA)** [[Slides]]() || [[Notes]]()
  - *Delays, timing arc, timing paths, setup and hold constraints, setup and hold time violations, recovery and remova time and its violations*
- **Assignments**: [Assignment-1](https://www.dropbox.com/s/43eetb3b03xw4ei/Setup_Hold%20Assignment.pdf)

### Week-8: Layout Design
- **Layout Basics**: Layer details (Metal, poly, diffusion, OD, N-Well, P-substrate, P+ Diff, N+ Diff, Via, Contact, Ports and Lable etc) || Layer drawing, layer interacting and, port and label creating || Layout Design of NMOS and PMOS
- **Layout Design of Inverter**: Undestanding of Design Rule Check (DRC) || Understanding of Layout Vs Schematic (LVS) || Understanding of Parasic Extraction (PEX) || Understanding of Post Layout Simulation (PLS)
- **Other Layouts**: Layout Design of NAND and NOR Gates || Layout Design of Resistors, Capacitors and BJTs
- **DRC, LVS and PEX in details**: DRC Rule deck file and different rules || LVS rule deck file || PEX rule deck file || Basics of P-Cell
- **Asignment and aassessment**:


## Session Activities
- [Nov-8] Introduction to CMOS VLSI Design Flow [[Video](https://www.youtube.com/watch?v=NVzHuigvpt4)]
  - [*Suggested Reading*]: [Hodges] Chapter-**1**, [Kang] Chapter-**1**
- [Nov-9] Introduction to CMOS PRocessing [[Video](https://www.youtube.com/watch?v=dauFDKM-Eu0)]
  - [*Suggested Reading*]: [Hodges] Section **3.1,3.2**
  - [*Suggested Problems*]: [Hodges] Prob **3.11, 3.12**
- [Nov-10] *Session-1*: Passive Integrated Circuit Devices. *Session-2*: MOS Device-I: Threshold Voltage [[Video:Session-1](https://www.youtube.com/watch?v=3SCYAH57Ixw) | [Video:Session-2](https://www.youtube.com/watch?v=OUZV9N0b3Lc)]
  - [*Suggested Reading*]: [Hodges] Section **3.2.4, 3.2.5**
  - [*Suggested Problems*]: [Hodges] Example **3.1**, Prob **3.13, 3.14**
- [Nov-11] *Session-1*: MOS Device-II: IV Characteristics and MOS Capacitance. *Session-2*: Basic Circuits. [[Video:Session-1](
https://www.youtube.com/watch?v=UUCB_dgFiwA) | [Video:Session-2](https://www.youtube.com/watch?v=OzlsThjjUDA)]
  - [*Suggested Reading*]: [Hodges] Section **2.2.1, 2.2.2, 2.2.3, 2.2.7** [Kang]: Chapter **3** [Uyemura] Section **1.1, 1.2** (Excellent treatment on Vt) [Baker]: Section **6.1, 6.2, 6.3**
  - [*Suggested Problems*]: [Hodges] Example **2.1,2.2,2.3,2.4,2.5,2.11**, Prob. **2.1,2.4,2.5,2.7,2.8**
  - [**Additional Materials**]: MOSFET Capacitance [[Notes]](https://www.dropbox.com/s/xxci3s9zu62b042/2020-0819-15VLSI7T-Module1-Lecture13-MOSFET-Capacitance.pdf) || [[Video]](https://www.youtube.com/watch?v=toIzPbxFwKE)
- [Nov-12] *Session-1* Modeling of MOS Device for Circuit Simulation. *Session-2*: Introduction to Lab on Cloud. *Session-3*: Parameter Extraction. MOS Problem discussion. [Video: [Session-1](https://www.youtube.com/watch?v=mQEryii3McE) | [Session-2](https://www.youtube.com/watch?v=riMKnP0AaRI) | [Session-3](https://www.youtube.com/watch?v=zFpJc6QFUc4)]
  - [*Suggested Reading*]: [Hodges] Section **3.4, 3.5, 3.6, Appendix-A**, [NGSpice Manual](/tools/CppSimLite/CppSimShared/Doc/ngspice-32-manual.pdf)
  - [*Lab Assignment*] MOS Parameter extraction and MOS Level-1 Modeling [Link-to-PDK](docs/2021-0528-Assignment-MOS-SPICE.pdf)
- [Nov-13] *Session-1*: Intorduction to Linux. *Session-2*: Lab-1 -- Parameter extraction. [Video: [Session-1](https://www.youtube.com/watch?v=ZGqEjvjWcqI) | [Session-2](https://www.youtube.com/watch?v=hVf8IAfiDyI)]
  - [**Assignment**] *Session-1*: Solving problems related MOS Device. *Session-2*: Lab-2 Parameter extraction (contd.) [Video: [Session-1](https://www.youtube.com/watch?v=BWagkpkn60w) | [Session-2](https://www.youtube.com/watch?v=bogjUJGIeWM)]
