## FPGA Topics and Concepts to Know

- [Basics of Digital Logic Design]()
- [FPGA Basics]()
  - What is an FPGA? (LUTs, Flip-Flops, Block RAM, DSP Blocks, I/O)
  - Differences Between ASICs and FPGAs
  - FPGA Architecture (Configurable Logic Blocks, Interconnects, Clock Networks)
  - FPGA Vendors: Xilinx, Intel (Altera), Lattice
- [Hardware Description Languages (HDLs)]()
    - VHDL and/or Verilog
	  - SystemVerilog (Optional but useful for advanced verification)
	  - Syntax and Constructs:
      	-	Concurrent vs. Sequential Statements
      	-	Processes and Always Blocks
      	-	Parameterization and Generics
      	-	Testbenches for Simulation

-  [FPGA Design Workflow]()
	  - Design Entry
	      -	Writing HDL Code
	    	-	Using IP Cores for Common Functionalities (e.g., Multipliers, FIFO)
	  - Synthesis and Implementation
	      -	Logic Synthesis (Conversion from HDL to Gate-Level Representation)
	    	-	Place and Route (P&R) for Optimizing FPGA Resource Usage
	    	-	Timing Closure (Critical Path Optimization)
	  - Simulation and Verification
	      -	Functional Simulation (Pre-Synthesis)
	    	-	Timing Simulation (Post-Synthesis)
	    	-	Tools: ModelSim, QuestaSim, Xilinx Vivado Simulator
	  - Bitstream Generation and Programming
	      -	Bitstream File Generation
	  	  - FPGA Configuration and On-Chip Debugging

- [High-Performance and Low-Latency Systems]()
  - Understanding Latency
    - Sources of Latency in FPGA Designs
    - Pipelining for Throughput Optimization
    - Latency vs. Resource Utilization Trade-Offs
  - Optimizing FPGA for HFT
    -	Clock Domain Crossing (CDC)
    -	Low-Latency Data Path Design
    -	Efficient Use of Block RAM and DSP Slices
    -	Ultra-Fast Communication Protocols (e.g., PCIe, Ethernet)
  - High-Speed Interfaces
    -	SerDes (Serializer/Deserializer) Basics
    -	Multi-Gigabit Transceivers (MGTs)
    -	SFP/QSFP Interfaces for Fiber Optics

- [FPGA Design for Trading Applications]()
  - Market Data Feed Handlers
      - Parsing Market Data Feeds (e.g., FIX/FAST Protocols)
  	  -	Handling Bursts of Data with Low Latency
  - Order Execution Engines
      -	Matching Engines and Order Book Management
  	  -	Risk Checks and Validation in Hardware
  - Network and Communication
      - UDP/TCP Offloading to FPGA
  	  -	Kernel Bypass Techniques (e.g., DPDK, RDMA)
  	  -	FPGA NICs (Network Interface Cards) like Solarflare and Napatech
  - Latency Measurement and Profiling
      -	Time Stamping and Precision Timing
  	  -	Latency Profiling Tools for FPGA Systems

- [Advanced FPGA Topics]()
  - High-Level Synthesis (HLS)
    -	Writing FPGA Designs Using C/C++ or OpenCL
  	-	Xilinx Vitis HLS, Intel OpenCL SDK
  -  Custom Algorithms in Hardware
    - Implementing Trading Algorithms (Arbitrage, Market Making) on FPGAs
  	-	Mathematical Operations in Hardware (Floating-Point Arithmetic, FFT)
  - Multi-FPGA Systems
    -	Partitioning Logic Across Multiple FPGAs
  	-	High-Bandwidth Inter-FPGA Communication
  - Power Optimization
    -	Reducing Power Consumption in FPGA Design
  	-	Dynamic Voltage and Frequency Scaling (DVFS)

- [Tools and Platforms]()

  - FPGA Development Tools
  	- Xilinx Vivado, Intel Quartus, Lattice Diamond
  	-	ModelSim, QuestaSim for Simulation
  	-	Synplify Pro (Optional)
 -  Hardware
    - FPGA Boards for HFT:
  	   - Xilinx Alveo Series
  	   - Intel Stratix 10 GX
	 - Ethernet NICs with FPGA Integration


## Books and Resources for FPGA

- [Digital Design]() : 
  - Digital Design: With an Introduction to the Verilog HDL by M. Morris Mano and Michael D. Ciletti
	-	Fundamentals of Digital Logic with Verilog Design by Stephen Brown and Zvonko Vranesic
- [FPGA Basics]() :
  - FPGA Prototyping by Verilog Examples by Pong P. Chu (For hands-on design)
	- FPGA Programming for Beginners by Frank Bruno
- [Hardware Description Languages(HDL)]() :
  - Verilog HDL: A Guide to Digital Design and Synthesis by Samir Palnitkar
	- SystemVerilog for Design and Verification by Stuart Sutherland
- [FPGA Design Workflow]() :
  - HDL Programming Fundamentals: VHDL and Verilog by Nazeih Botros
	-	Advanced Digital Design with the Verilog HDL by Michael D. Ciletti
  -	Principles of Verifiable RTL Design: A Functional Coding Style Supporting Verification Processes by Lionel Bening
	-	Writing Testbenches: Functional Verification of HDL Models by Janick Bergeron
- [High-Performance and Low-Latency Systems]():
  - High-Performance Embedded Computing: Applications in Cyber-Physical Systems and Mobile Computing by Marilyn Wolf
	-	FPGA Design for Embedded Systems by Clive Maxfield
  -	High-Speed Digital Design: A Handbook of Black Magic by Howard Johnson and Martin Graham
	-	Signal Integrity for PCB Designers by Eric Bogatin
- [FPGA Design for Trading Applications]()
  - FIX Protocol and Fast Protocol Guide by FIX Trading Community (Official Documentation)
  - Network Algorithmics: An Interdisciplinary Approach to Designing Fast Networked Devices by George Varghese
- [Advanced FPGA Topics]():
  - C-Based Design for Advanced Embedded Systems by David Andrews
	-	High-Level Synthesis for FPGA-Based Accelerators by Tianshi Chen
  -	Digital Signal Processing with FPGA by Uwe Meyer-Baese
	-	FPGA-Based Implementation of Signal Processing Systems by Roger Woods
  -	Low-Power CMOS VLSI Design by Kaushik Roy and Sharat Prasad
	-	Xilinx Power Estimation and Optimization Guides
- [Knowledge of Trading and HFT Systems]() :
  - Algorithmic Trading: Winning Strategies and Their Rationale by Ernest P. Chan
	-	Inside the Black Box: A Simple Guide to Quantitative and High-Frequency Trading by Rishi K. Narang 
  - Trading Systems and Methods by Perry J. Kaufman
	-	ITCH/OUCH Protocol Guides from NASDAQ
- [Verification and Testing]() :
  - SystemVerilog Assertions and Functional Coverage: A Guide to Language, Methodology, and Applications by Ashok B. Mehta 
















