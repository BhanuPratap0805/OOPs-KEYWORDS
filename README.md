# OOPs-KEYWORDS
COMPUTER - It is mainly divided into three parts

* Computation

* Storage

* Network

# # COMPUTATION :- 
### 1. CPU - It stands for Central Processing Unit.

It’s often called the brain of the computer because it performs all the major calculations, processes instructions, and controls other parts of the system.

#### Main functions of CPU:

* Fetch – Gets instructions from the computer’s memory.

* Decode – Understands what the instruction means.

* Execute – Performs the action (calculation, data movement, etc.).

#### Main parts of a CPU:

* ALU (Arithmetic Logic Unit) – Does mathematical and logical operations.

* CU (Control Unit) – Directs the flow of data and instructions.

* Registers – Small, very fast storage locations inside the CPU.

### 2. GPU - It stands for Graphics Processing Unit.

It’s a specialized electronic circuit designed to rapidly process and render images, videos, and animations.
Originally built for gaming and visual output, GPUs are now also widely used for AI, scientific simulations, and data processing because they can handle thousands of tasks in parallel.

#### Main functions of a GPU:

* Render graphics – Create visuals for your screen (2D/3D images, videos, games).

* Parallel computation – Perform many small calculations simultaneously.

* Accelerate AI & machine learning – Process large datasets faster than CPUs in many cases.

#### Types of GPUs:

* Integrated GPU – Built into the CPU chip (e.g., Intel UHD Graphics).

* Dedicated GPU – Separate card with its own memory (e.g., NVIDIA GeForce, AMD Radeon).

### 3. DPU - It stands for Data Processing Unit

A specialized processor designed to handle data-centric tasks like moving, transforming, encrypting, or compressing data.
Offloads work from the CPU so the CPU can focus on running applications.
Often used in data centers, AI, networking, and cloud computing.

#### Example:

* NVIDIA’s BlueField DPU is used to accelerate networking and security.

* It can manage data flow between storage, networks, and processors without burdening the CPU.

### 4. TPU - It stands for Tensor Processing Unit.

It’s a specialized processor developed by Google specifically for AI and machine learning tasks, especially those involving neural networks and TensorFlow (Google’s AI framework).

#### Key features of a TPU

* Optimized for matrix math (which is the backbone of AI calculations).

* Processes large amounts of data in parallel, like a GPU, but is custom-built for AI workloads.

* Used in Google data centers and available on Google Cloud for researchers and companies.

#### Example use cases:

* Voice recognition (Google Assistant)

* Image recognition (Google Photos)

* Language translation (Google Translate)

* Large AI model training (e.g., ChatGPT-like models)

### 5. NPU - It stands for Neural Processing Unit.

It’s a specialized processor designed to accelerate AI and machine learning tasks, especially those involving neural networks (deep learning models).
You can think of it as the AI equivalent of a GPU — but made specifically for neural network computations.

#### Key features of an NPU
* Handles matrix multiplications and vector operations super efficiently (these are the main math operations in AI).

* Optimized for low power consumption — important for smartphones, laptops, and edge devices.

* Can perform AI inference (using a trained model) much faster than a CPU or GPU in certain cases.

#### Where you’ll see NPUs:

* Smartphones (e.g., Apple Neural Engine in iPhones, Qualcomm Hexagon in Snapdragon chips, Huawei Kirin NPU).

* Laptops (new Intel Core Ultra and AMD AI engines).

* Edge AI devices (smart cameras, IoT AI chips).

### 6. APU - It stands for Accelerated Processing Unit.

It’s a type of processor made by AMD that combines a CPU and a GPU on a single chip.
The idea is to give you both general computing power (CPU) and graphics processing (GPU) in one package, which saves space, reduces cost, and improves efficiency.

#### Key points about an APU:

* CPU part → Handles logic, instructions, and general computing tasks.

* GPU part → Handles graphics rendering and parallel processing.

* Shares the same memory for both CPU and GPU, improving data transfer speed.

* Often used in budget PCs, laptops, and gaming consoles (e.g., PlayStation 4, Xbox One).

### 7. IPU - It stands for Intelligence Processing Unit.

It’s a specialized AI processor created by companies like Graphcore (and sometimes used as a generic term for AI chips).
The IPU is designed specifically for training and running machine learning models, especially deep learning tasks that require huge amounts of parallel computation.

#### Key features of an IPU

* Massive parallelism – Can run many small operations at the same time.

* Fine-grained computation – Optimized for AI workloads where data dependencies are complex.

* Low latency – Designed to process data as quickly as possible with minimal delay.

* High efficiency – Uses memory and processing resources in a way that avoids bottlenecks common in CPUs/GPUs.

#### Where IPUs are used:

* AI research (training large neural networks).

* Data centers focused on machine learning.

* Autonomous systems where quick AI decision-making is needed.

## PROCESSOR ARCHITECTURES

### 1. CISC - It stands for Complex Instruction Set Computer.

It’s a processor architecture where the CPU has a large set of complex instructions, meaning each instruction can perform multiple low-level operations (like memory load, arithmetic, and store) in a single command.

#### Examples of CISC Processors:
* x86 / x86-64 architecture → Intel Core, AMD Ryzen processors.

* Older architectures like VAX and System/360.

### 2. RISC - It stands for Reduced Instruction Set Computer.

It’s a processor architecture that uses a small set of simple instructions, each designed to execute very quickly (often in a single CPU clock cycle).
The focus is on simplicity, speed, and efficiency.

#### Examples of RISC Processors:
* ARM architecture → used in smartphones, tablets, Apple M1/M2 chips.

* RISC-V → open-source CPU architecture.

* MIPS, SPARC, PowerPC → used in servers, routers, embedded devices.

### 3. AISC - It stands for Application-Specific Integrated Circuit.

It’s a custom-designed chip built to perform a specific task or set of tasks rather than being a general-purpose processor like a CPU or GPU.

#### Examples of ASICs:
* Bitcoin mining chips (e.g., Antminer).

* Google TPU (technically an ASIC designed for AI).

* Mobile phone chips for camera image processing.

* Networking hardware in routers and switches.

## OPERATING SYSTEMS (OS)

It’s the main software that manages a computer’s hardware and software resources, and provides a user interface so you can interact with the machine.

#### Main Functions of an OS

* Process Management – Runs and manages multiple programs at the same time.

* Memory Management – Allocates and frees RAM for applications.

* File System Management – Handles storing, reading, and writing files.

* Device Management – Controls hardware like printers, keyboards, and drives.

* User Interface – Provides command-line or graphical interface (CLI/GUI).

#### Examples

* Desktop/Laptop: Windows, macOS, Linux.

* Mobile: Android, iOS.

* Server: Ubuntu Server, Red Hat Enterprise Linux.

# # STORAGE :-

## 1. PRIMARY STORAGE - 
Primary storage (also called main memory or primary memory) is the computer’s immediate working memory — the place where data and instructions are kept while the CPU is using them.

It is fast, directly accessible by the CPU, but usually volatile (contents are lost when power is turned off).

#### Key Characteristics
* High speed – Much faster than secondary storage (like hard drives).

* Volatile – Most types lose data when the computer is shut down.

* Smaller capacity – Usually measured in GBs (secondary storage is in TBs).

* Direct CPU access – CPU can read/write without intermediate steps.

#### Types of Primary Storage
* RAM (Random Access Memory) – Temporary storage for currently running programs and data.

* ROM (Read-Only Memory) – Permanent storage for essential startup instructions (firmware).

* Cache Memory – Ultra-fast memory inside or very close to the CPU for frequently used data.

* Registers – Very small, very fast storage locations inside the CPU.

## 2. SECONDARY STORAGE -

Secondary storage (also called external storage or auxiliary storage) is the type of computer memory used to store data permanently — even when the computer is turned off.
It is slower than primary storage but has much larger capacity and is non-volatile.

#### Key Characteristics
* Non-volatile – Keeps data without power.

* Large capacity – Can store terabytes or even petabytes of data.

* Slower than primary storage – Requires input/output operations.

* Cheaper per GB compared to RAM.

#### Types of Secondary Storage
1. Magnetic Storage

   * Hard Disk Drives (HDDs)

   * Magnetic tapes (backup storage)

2. Optical Storage

   * CDs, DVDs, Blu-ray discs

3. Solid-State Storage

   * SSDs (Solid State Drives)

   * Flash drives (USB)
 
   * Memory cards (SD cards)
 
4. Cloud Storage

   * Google Drive, Dropbox, OneDrive

# # NETWORK :-  

### 1. ISP - It ISP stands for Internet Service Provider.

It’s a company or organization that provides access to the internet for individuals, businesses, and other organizations.

#### Main Functions of an ISP
* Connects you to the internet using different technologies (fiber, DSL, cable, satellite, wireless).

* Assigns you an IP address so your device can communicate online.

* May provide extra services like email accounts, web hosting, and security tools.

#### Examples of ISPs
* In India: JioFiber, Airtel Xstream, BSNL, ACT Fibernet.

* Globally: Comcast, AT&T, Verizon, BT.

#### Types of ISPs
* Dial-up ISPs – Very old, slow telephone-based connections.

* Broadband ISPs – Fast wired connections like fiber, cable, DSL.

* Wireless ISPs (WISPs) – Use radio signals or mobile networks.

* Satellite ISPs – Provide internet to remote areas using satellites.

### 2. IP - Internet Protocol
IP is a set of rules for sending and receiving data across the internet.
It’s part of the TCP/IP model — the foundation of all internet communication.
Data is sent in packets, and IP ensures those packets have the correct address so they reach the right destination.

#### Types of IP
1. IPv4 (Internet Protocol version 4)

    * Uses 32-bit addresses (e.g., 192.168.0.1).

    * About 4.3 billion unique addresses available.

2. IPv6 (Internet Protocol version 6)

    * Uses 128-bit addresses (e.g., 2001:0db8:85a3::8a2e:0370:7334).

    * Almost unlimited addresses — designed to replace IPv4.

#### Functions of IP
* Addressing: Assigns unique identifiers to devices.

* Routing: Directs data packets to their destination.

* Packet fragmentation/reassembly: Breaks large data into smaller chunks and reassembles them.

### 3. STANDARDS -

Standards are agreed-upon technical rules so that devices from different makers can work together.

#### Set by organizations like:

* IETF (Internet Engineering Task Force) → Develops IP, TCP, HTTP, etc.

* IEEE (Institute of Electrical and Electronics Engineers) → Wi-Fi (802.11), Ethernet (802.3).

* ISO (International Organization for Standardization) → OSI model, file formats.

* W3C (World Wide Web Consortium) → HTML, CSS web standards.

#### Examples of Networking Standards
* IEEE 802.3 → Ethernet

* IEEE 802.11 → Wi-Fi

* HTTP/HTTPS → Web data transfer

* SMTP → Email sending

* FTP → File transfer

* DNS → Domain name resolution

### 4. APIPA - It stands for Automatic Private IP Addressing.

It’s a feature in Windows (and some other OSes) that automatically assigns an IP address to a device when it can’t get one from a DHCP server.
