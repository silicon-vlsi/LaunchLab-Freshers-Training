# Sevya-Freshers-Training
This repository contains all the materials related to the basic MOSFET theory, CMOS technology, circuit and layout design, and basic PDK design.

## Course Contents

### Week-1
- **Day-1**: Introduction to CMOS VLSI Design Flow || Tools and PDK walk through
- **Day-2**: Passive Integrated Circuit Devices || MOS structure, MOSFET working principle and Threshold Voltage Calculation
- **Day-3**: MOSFET I-V characteristics || MOSFET intrinsic capacitances
- **Day-4**: MOSFET modelling (level1, level2, level3 and BSIM) || Introduction to spice netlist, circuit simulation
- **Day-5**: Introduction to CMOS Processing || Process Stack diagram (Skywater 130nm PDK) || Parasitics and interconnect effects
- **Day-6**: Asignment and aassessment
### Week-2
- **Day-1**: Layer details (Metal, poly, diffusion, OD, N-Well, P-substrate, P+ Diff, N+ Diff, Via, Contact, Ports and Lable etc) || Layer drawing, layer interacting and, port and label creating || Layout Design of NMOS and PMOS
- **Day-2**: **Layout Design of Inverter**: 1. Undestanding of Design Rule Check (DRC) || Understanding of Layout Vs Schematic (LVS) || Understanding of Parasic Extraction (PEX) || Understanding of Post Layout Simulation (PLS)
- **Day-3**: Layout Design of NAND and NOR Gates || Layout Design of Resistors, Capacitors and BJTs
- **Day-4**: **DRC, LVS and PEX in details**: DRC Rule deck file and different rules || LVS rule deck file || PEX rule deck file || Basics of P-Cell
- **Day-5**: MOSFET Parameter extraction using Level-1 modelling (Lab) || Inverter static characteristics || Noise Margin || Inverter Design and simulation (Lab) || Inverter Dynamic Characteristics || Power, delay and Energy calculation || Inverter Dynamic characteristics (Lab) || Combinational circuits and Transmission Gate || Sequential logics (D-latch, D-FF) || Setup and Hold time calculation (Lab) || Undestanding PVT Variations || Understanding of Device Matching || Standard Cell Basics
- **Day-6**: Asignment and aassessment


## Session Activities
- [Nov-8] Introduction to CMOS VLSI Design Flow [[Video](https://www.youtube.com/watch?v=NVzHuigvpt4)]
  - [*Suggested Reading*]: [Hodges] Chapter-**1**, [Kang] Chapter-**1**
  - [*quick start guide for VIM*]: [[doc1](https://www.dropbox.com/s/9qqno50ls4sntlc/quickStartGuide-VIM.pdf)], [[doc2](https://www.dropbox.com/s/c2t8at6b5ztq0nu/quickStartGuideLinuxCommandLine.pdf)], [[doc3](https://www.dropbox.com/s/v0vnute8hbwkrts/vim_tutorial.pdf)], [[doc4](https://www.dropbox.com/s/b89wggspy84yaff/viHelp.pdf)]
- [Nov-9] Introduction to CMOS PRocessing [[Video](https://www.youtube.com/watch?v=dauFDKM-Eu0)]
  - [*Suggested Reading*]: [Hodges] Section **3.1,3.2**
  - [*Suggested Problems*]: [Hodges] Prob **3.11, 3.12**
- [Nov-10] *Session-1*: Passive Integrated Circuit Devices. *Session-2*: MOS Device-I: Threshold Voltage [[Video:Session-1](https://www.youtube.com/watch?v=3SCYAH57Ixw) | [Video:Session-2](https://www.youtube.com/watch?v=OUZV9N0b3Lc)]
  - [*Suggested Reading*]: [Hodges] Section **3.2.4, 3.2.5**
  - [*Suggested Problems*]: [Hodges] Example **3.1**, Prob **3.13, 3.14**
  - [**Additional Materials**]: Metal Oxide Semiconductor Field Effect Transistor (MOSFET)
  - Metal-Oxide-Semiconductor Stucture-1 [[Notes]](https://www.dropbox.com/s/ntcueemzmsbx9vb/2020-0803-15VLSI7T-Module1-Lecture-4-5-MOS-Transistor.pdf) || [[Video]](https://www.youtube.com/watch?v=AxZyFuJh0rM)
  - Metal-Oxide-Semiconductor Stucture-2 [[Notes]](https://www.dropbox.com/s/85kswvq4ejs08ha/2020-0805-15VLSI7T-Module1-Lecture6-MOS-Transistor.pdf) || [[Video]](https://www.youtube.com/watch?v=zQmV7c30ZDU)
  - Metal-Oxide-Semiconductor Stucture-3 [[Notes]](https://www.dropbox.com/s/xcipyfkiis1fbo5/2020-0810-15VLSI7T-Module1-Lecture7-8-MOS-Transistor.pdf) || [[Video]](https://www.youtube.com/watch?v=Eyu6TVZRwAE)
  - Metal Oxide Semiconductor Field Effect Transistor-1 [[Notes]](https://www.dropbox.com/s/23z0n3p068hkgul/2020-0817-15VLSI7T-Module1-Lecture9-10-MOSFET.pdf) || [[Video]](https://www.youtube.com/watch?v=tfF-K-Gbeb4)
  - Metal Oxide Semiconductor Field Effect Transistor-2 [[Notes]](https://www.dropbox.com/s/mqzd1o6u5y8qprn/2020-0818-15VLSI7T-Module1-Lecture11-12-MOSFET.pdf) || [[Video]](https://www.youtube.com/watch?v=bPLzXzopsNo)
- [Nov-11] *Session-1*: MOS Device-II: IV Characteristics and MOS Capacitance. *Session-2*: Basic Circuits. [[Video:Session-1](
https://www.youtube.com/watch?v=UUCB_dgFiwA) | [Video:Session-2](https://www.youtube.com/watch?v=OzlsThjjUDA)]
  - [*Suggested Reading*]: [Hodges] Section **2.2.1, 2.2.2, 2.2.3, 2.2.7** [Kang]: Chapter **3** [Uyemura] Section **1.1, 1.2** (Excellent treatment on Vt) [Baker]: Section **6.1, 6.2, 6.3**
  - [*Suggested Problems*]: [Hodges] Example **2.1,2.2,2.3,2.4,2.5,2.11**, Prob. **2.1,2.4,2.5,2.7,2.8**
  - [**Additional Materials**]: MOSFET Capacitance [[Notes]](https://www.dropbox.com/s/xxci3s9zu62b042/2020-0819-15VLSI7T-Module1-Lecture13-MOSFET-Capacitance.pdf) || [[Video]](https://www.youtube.com/watch?v=toIzPbxFwKE)
- [Nov-12] *Session-1* Modeling of MOS Device for Circuit Simulation. *Session-2*: Introduction to Lab on Cloud. *Session-3*: Parameter Extraction. MOS Problem discussion. [Video: [Session-1](https://www.youtube.com/watch?v=mQEryii3McE) | [Session-2](https://www.youtube.com/watch?v=riMKnP0AaRI) | [Session-3](https://www.youtube.com/watch?v=zFpJc6QFUc4)]
  - [*Suggested Reading*]: [Hodges] Section **3.4, 3.5, 3.6, Appendix-A**, [NGSpice Manual](/tools/CppSimLite/CppSimShared/Doc/ngspice-32-manual.pdf)
  - [*Lab Assignment*] MOS Parameter extraction and MOS Level-1 Modeling [Link-to-PDK](docs/2021-0528-Assignment-MOS-SPICE.pdf)
- [May 28] *Session-1*: Intorduction to Linux. *Session-2*: Lab-1 -- Parameter extraction. [Video: [Session-1](https://www.youtube.com/watch?v=ZGqEjvjWcqI) | [Session-2](https://www.youtube.com/watch?v=hVf8IAfiDyI)]
  - [Assignment] *Session-1*: Solving problems related MOS Device. *Session-2*: Lab-2 Parameter extraction (contd.) [Video: [Session-1](https://www.youtube.com/watch?v=BWagkpkn60w) | [Session-2](https://www.youtube.com/watch?v=bogjUJGIeWM)]
