# How to Disassemble A Desktop Computer

After diving into assembly language, I found myself drawn to the hardware side of computing. I couldn’t stop watching YouTube videos about building, exploring, and understanding computer components. Luckily, my school recently upgraded its desktop computers, and my professor loaned me one of the retired machines. This was my golden opportunity to disassemble a desktop for the first time. In this guide, I’ll walk you through the entire process step by step, making it accessible even if you’re new to hardware like I am. Along the way, I’ve done plenty of research to deepen my understanding, and I’m excited to share this journey with you. Let’s explore the beauty of hardware together!

<img width="600" alt="image" src="https://github.com/user-attachments/assets/f9c001b3-e8e1-4366-a8e3-550e8c806015">


<br/>

## Before we start…

### Highly recommend to watch this brilliant video from Branch Education

[How does Computer Hardware Work? 💻🛠🔬 [3D Animated Teardown]](https://www.youtube.com/watch?v=d86ws7mQYIg)

Check out these channels to learn more:

* [Branch Education](https://www.youtube.com/@BranchEducation)
* [PowerCert Animated Videos](https://www.youtube.com/@PowerCertAnimatedVideos)

If Chinese is your native language, I also recommend this channel:
* [硬件茶谈](https://www.youtube.com/@user-og1rx7gc6o/featured)

<br/>

## Let's get started!

### Introducing Our Guinea Pigs - **HP ProDesk 600 G1 Small Form Factor PC**

Here is the components table for the computer:

| Component | Description  |
| --- | --- |
| Motherboard | (I couldn't find the model name) |
| CPU | Intel 4th Generation Core i7 processors |
| GPU | AMD Radeon HD 8490 (1GB) PCIe2.0 x 16 |
| RAM | DDR3 non-ECC, Up to 1600 MT/s, 32GB with 4 DIMM slots |
| SSD | Micron M600 in 256GB SATA 6GB/s (MTFDDAK256MBF) |
| Cooling | Cooler Master DC12 0.45A Fan 80x25mm 4W, 6-Inch 4-Wire (FA08025M12LPA) |
| PSU | HP D12-240P2A PCC002 PS-4241-2HF DPS-240AB-3 B power supply |
| DVD | Slim SuperMulti DVD writer |

> Check on the [official website](https://support.hp.com/id-en/document/c03846648) to learn all the details.

<br/>

### All we need: Screwdriver

We only need a **T15 Torx screwdriver** to disassemble this computer!

<img width="600" alt="image" src="https://github.com/user-attachments/assets/0debbc0e-e3e0-4651-aebd-ae85805198ce">

<br/>

<br/>

## Let’s Open This Beauty!

There are several ways to disassemble and assemble computers. I will cover how I open it. But computers can vary; if you can’t follow one of the steps in this order, skip to the next step and remove the other parts until you reach the original component.

### Step 1: Remove side cover

Since it’s a retired computer without a power cord, our first step is to remove the side cover. Different cases have different designs. For this design, it’s really easy to open. Pull the handle and take out the side cover. Easy peasy!

![removing-side-cover](https://github.com/user-attachments/assets/99a80742-4370-48be-b91d-f9a4e00fa906)

<aside>
💡 If it is an on-use computer, please unplug all the cords and cables connecting one component to another before you proceed.
</aside>

<br/>

### Step 2: Removing Graphics Card

I am so curious about the **GPU** that I decided to remove **Graphics Card** first. Also, we need to remove it first before we take out the MoBo (motherboard). The Graphics Card is overlaid on the screw. We need to remove it first before we take out the motherboard.

<img width="600" alt="Graphics Card" src="https://github.com/user-attachments/assets/a7735324-744a-45c8-97fc-52523e1e0135">

Unclip the graphics card from the left side. Hold the left side with your left hand and release the lever on the PCI slot with your right hand. Gently wiggle it, and then we can then pull it out.

<br/>

This is a **AMD Radeon HD 8490 1GB PCIe 2.0 x16 Graphics Card**:

<img width="600" alt="AMD Radeon HD 8490" src="https://github.com/user-attachments/assets/7b4f0e4b-344d-4a1d-9c66-230b640f6b7a">

| Specification | Description |
| --- | --- |
| Form factor | PCIe 2.0 x16 |
| Graphics controller | AMD Radeon HD 8490 |
| Core clock | GPU engine operates at 875 MHz |
| Memory clock | 900 MHz |
| Memory | 1GB, DDR3, SDRAM |
| Display max resolution | Digital 2560 x 1600; Analog 2048 x 1536 |

<br/>

TechPowerUp is a leading technology publication at the forefront of PC technologies. They have their own GPU database, which covers AMD Radeon HD 8490:

[AMD Radeon HD 8490 OEM Specs](https://www.techpowerup.com/gpu-specs/radeon-hd-8490-oem.c2038)

<br/>

The Radeon HD 8490 OEM was a graphics card by AMD, launched on July 23rd, 2013.

Display outputs include 1x Digital Visual Interface (DVI) and 1x DisplayPort (DP) 1.1. 

<img width="600" alt="image" src="https://github.com/user-attachments/assets/1ec90a0f-176c-4671-a89d-8f2a1628f6d0">

<br/>

<br/>

If taking the fan away, we can see the GPU chip under it.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/504d9510-ccb7-4fb0-abb2-b2115b84a519">

The **GPU IC** is in the center, the **SDRAM** chips are on the right side, and the **voltage regulator module (VRM)** is on the left side. 

<img width="600" alt="image" src="https://github.com/user-attachments/assets/686799f2-da16-4b65-90f4-fe690f75128b">

I determined the RAM by several signal lines spreading between the GPU and the RAM. It's similar to the CPU and the DDIM. Also, the brand name on the chips, SK Hynix, is a South Korean supplier of dynamic random-access and flash memory chips. 

<img width="600" alt="image" src="https://github.com/user-attachments/assets/b6a1978b-25d6-4f11-b69f-af2a39ce9404">

<br/>

<br/>

Here are more details about how Graphic Cards work from the Branch Education:
[How do Video Game Graphics Work?](https://youtu.be/C8YtdC8mxTU?si=xji1VMqv7veYGE6W)

<br/>

<br/>

### Step 3: Removing Cooling Fan

Since the Cooling Fan screws with the MoBo and the case, it is our next target!

<img width="600" alt="image" src="https://github.com/user-attachments/assets/bc9b8cc6-992e-4219-bd62-ec6cf1d62bb2">

Unplug the fan from the MoBo and then unscrew the four screws. 

<aside>
💡 When loosening the four screws holding this part, it is recommended not to fully loosen one screw at a time. Instead, slightly loosen one screw first, then move to the screw diagonally opposite it and slightly loosen that one. Next, slightly loosen the screw next to the first one, and then the screw diagonally opposite it. Continue this process gradually.
</aside>

<br/>

<br/>

The fan inside this computer is Cooler Master DC12 0.45A Fan.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/63a79eeb-a24c-43c0-9f75-33c9491a3e0c">

<br/>

<br/>

A **heatsink** is a metal structure (usually aluminum or copper) with **fins** that increase its surface area and **heat pipes** filled with a liquid coolant for heat dissipation. When the CPU heats up, the heatsink absorbs heat from the CPU, the liquid inside the heat pipes evaporates, moves toward the cooler, and ends up as hot air blown by the fan.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/b4561dbe-f339-44d3-8270-9b924da4f3ef">

<br/>

<br/>

<aside>
💡 Heat dissipation is crucial for the performance, stability, and longevity of a CPU.
</aside>

<br/>

<br/>

### Step 4: Removing Motherboard (MoBo)

After removing the Graphic Card and Cooling Fan, we can remove the MoBo now. 

Different brands and manufacturers design their motherboards with varying layouts, features, and aesthetics to cater to a range of user needs and preferences. Here is a brief layout of a motherboard.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/714a9fd5-b61a-4833-8fb4-51a106c5d152">

- **CPU Socket**: This is where the central processing unit (CPU) is installed. The type of socket determines which CPUs are compatible with the motherboard.
- **I/O panels**: These panels are parts of the motherboard that house the various input/output ports and connectors accessible from the back of a computer case. These panels facilitate connections to external devices and peripherals.
- **RAM Slots**: These slots hold the system’s memory modules (RAM). The number and type of RAM slots vary between motherboards, and they determine the amount and type of RAM that can be installed.
- **Expansion Slots**: These slots, such as PCIe (Peripheral Component Interconnect Express) slots, allow for the addition of expansion cards like graphics cards, sound cards, network cards, and other peripheral devices.
- **Southbridge Chipset**: The chipset is a set of electronic components on the motherboard that manage data flow between the CPU, memory, and peripheral devices. It essentially dictates the capabilities and features of the motherboard.
- **Peripheral Interfaces**: These include USB ports, audio jacks, Ethernet ports, and other interfaces for connecting external devices.

These are some details of the MoBo (not everything):

<img width="600" alt="image" src="https://github.com/user-attachments/assets/ede01476-c186-425e-8cf7-488261b6c23e">

- **PWR**: It ensures that all components on the motherboard receive the necessary power to function.
- **DIMM**: DIMM (Dual In-line Memory Module) slots are where we install our RAM (Random Access Memory).
- **PB**: Power Button is the connector for the power button on a computer case.
- **PWRCMD**: Power Command refers to signals and connections related to managing power states, such as sleep, hibernate, and wake functions.
- **SATA Slots**: Connectors for attaching storage devices like hard drives and SSDs (Solid State Drives).
- **SPK**: Speaker connector where we connect the internal speaker of your computer.
- **USB SS**: USB SuperSpeed are ports and connectors which support USB 3.0 or higher, offering faster data transfer rates compared to older USB standards.
- **Media**: Media card reader connector
- **CMOSB**: CMOS (Complementary Metal Oxide Semiconductor) Battery and Button, which stores BIOS settings, including the system clock. The button is used to clear the CMOS, or reset the BIOS to its default settings.
- **Southbridge Chipset**: Part of the motherboard chipset that handles slower tasks and input/output functions, such as USB, audio, and storage controllers.
- **HLCK**: Hood lock connector
- **COMB**: Serial port connector
- **PAR**: Parallel Port (PAR) connector
- **PCIe**: PCIe (Peripheral Component Interconnect Express) Slots for installing expansion cards, such as graphics cards, network cards, and additional storage controllers.
- **AUD**: Connectors for audio components, such as speakers, microphones, and line-in/line-out jacks.
- **IC**: A specific integrated circuit (Nuvoton NPCD379HAKFX) on the motherboard, often used for system management tasks like hardware monitoring and fan control.
- **Audio codec**: An audio codec chip (Realtek ALC221 Audio codec) responsible for converting digital audio signals to analog and vice versa.

<br/>

<br/>

### Step 5: Removing RAM

Random Access Memory (RAM) is a crucial component in computers and other digital devices, acting as the system's short-term memory. It temporarily stores data that the CPU (Central Processing Unit) needs quick access to, allowing for efficient processing and multitasking.

Here are more explanation:

* [How does Computer Memory Work? 💻🛠](https://youtu.be/7J7X7aZvMXQ?si=4aAuDDRcCB_QgsME)

* [RAM Explained - Random Access Memory](https://www.youtube.com/watch?v=PVad0c2cljo)

<br/>

<img width="600" alt="image" src="https://github.com/user-attachments/assets/c93d3ab9-aafb-4bfb-91d1-b400b2c937a4">

<br/>

It’s really easy to remove it. Push the clips on both ends of the module down, and then the module will pop up for easy removal.

They are Hynix 8GB PC3-12800 DDR3-1600MHz RAMs.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/3b025e6f-14f6-4d01-a5f0-758d1a6f2443">

| Feature | Description |
| --- | --- |
| Made By | SK Hynix |
| Capacity | 8GB |
| Type | DDR3 (Double Data Rate Type 3) |
| Voltage | 1.5V |
| ECC | Non-ECC |
| Speed | 1600 MHz |
| Designation | PC3-12800 |
| Data Transfer Rate | 12,800 MB/s (theoretical maximum) |
| Density | 4G |
| Depth | 1G |
| Pins | 204 pin |
| Full DIMM Type | USODIMM |
| Width | x64 |
| Die Generation | 5th |
| Package Type | FBGA |
| CL | 11 |
- **ECC (Error-Correcting Code)**: ECC RAM is a type of memory that can detect and correct common types of internal data corruption, improving the reliability and stability of the system.  ECC DIMM will have 9 memory chips.

    <img width="600" alt="image" src="https://github.com/user-attachments/assets/494b366c-6f2c-4d0a-b1f7-bc2659d5bd38">
    
- **DIMM (Dual In-line Memory Module)**: DIMM is a type of computer memory module that features two independent rows of electrical contacts, one on each side of the module.
    
    <img width="600" alt="image" src="https://github.com/user-attachments/assets/d0fbf85a-3574-4f55-bed3-3762323fb6ea">

    
- **USODIMM (Ultra Small Outline Dual In-line Memory Module)**: USODIMM is a smaller and thinner form factor of RAM typically used in very compact devices like ultrabooks and small form factor PCs.
- Memory Terms Explained:
    - **Density**: Memory density refers to the capacity of a RAM module, typically measured in gigabytes (GB) or megabytes (MB). 
    Example: An 8GB module has a density of 8 gigabytes.
    - **Depth**: The depth of a memory module refers to the number of bits in each memory cell, typically represented as the number of rows in a memory chip.
    - **Pins**: Pins are the physical connectors on a RAM module that interface with the motherboard.
        - DDR3 DIMM: 240 pins
        - DDR4 DIMM: 288 pins
        - SO-DIMM (laptop): Fewer pins than standard DIMMs
    - **Width**: The width of a memory module refers to the data width of the module, typically measured in bits (e.g., 64-bit). It indicates how many bits of data can be transferred in parallel.
- **FBGA (Fine-Pitch Ball Grid Array)**: FBGA is a packaging type for memory chips where the memory is mounted on a grid array of solder balls. This packaging allows for a higher density of connections in a smaller area and is commonly used for modern RAM modules.
- **CL (CAS Latency)**: CAS Latency (CL) is the delay time between when a memory controller tells the memory module to access a particular column in a memory array and when the data is actually read or written. Lower CAS latency generally means faster performance, though it must be balanced with other memory specifications.
Example: CL11 means there is a latency of 11 clock cycles.

<br/>

Here is more information about these RAMs:

[HMT41GS6DFR8C-PB - SK Hynix 1x 8GB DDR3-1600 SODIMM PC3-12800S Dual Rank x8 Module](https://memory.net/product/hmt41gs6dfr8c-pb-sk-hynix-1x-8gb-ddr3-1600-sodimm-pc3-12800s-dual-rank-x8-module/)

<br/>

### Step 6: Removing CPU

The Central Processing Unit (CPU) is often referred to as the "brain" of a computer. It is the primary component responsible for executing instructions and processing data in computing devices.

There is a brilliant video about how CPUs are made:

[How are Microchips Made? 🖥️🛠️ CPU Manufacturing Process Steps](https://youtu.be/dX9CGRZwD-w?si=ZqW2TBkOAFKtiS4J)

<img width="600" alt="image" src="https://github.com/user-attachments/assets/6ec04931-b0da-4dd9-90c5-80bfd265f058">

Press and then pull up the metal lever next to the socket to unlock. Carefully lift the CPU straight up from the socket. Be gentle to avoid bending any pins or damaging the CPU or motherboard.

Although the model number is covered by thermal paste, according to the sticker on the case, it should be an Intel Core i7 4th generation. We can confirm it by the LGA (Land Grid Array) sockets, where the pins are on the motherboard socket, and the CPU has flat contact pads. 

Intel Core i7 processors from the 4th generation, also known as "Haswell," use the LGA 1150 socket. 

Here are some specifications from the official document:

| Feature | Description |
| --- | --- |
| Product Collection | 4th Generation Intel® Core™ i7 Processors |
| Lithography | 22 nm |
| Total Cores | 4 |
| Total Threads | 8 |
| Max Turbo Frequency | 3.90 GHz |
| Processor Base Frequency | 3.40 GHz |
| Cache | 8 MB Intel® Smart Cache |
| Bus Speed | 5 GT/s |
| TDP | 84W |
|  |  |
- **Lithography**: Lithography refers to the manufacturing process used to create the integrated circuits on a CPU. It defines the size of the transistors and other components on the chip.
- **Max Frequency**: Max frequency, also known as clock speed or clock rate, is the highest speed at which a CPU can operate. It is measured in gigahertz (GHz).
- **Cache**: Cache is a small, high-speed memory located inside the CPU that stores frequently accessed data and instructions to speed up processing.
- **TDP**: Thermal Design Power (TDP) represents the maximum amount of heat a CPU is expected to generate under normal operating conditions. It is measured in watts (W).

<br/>

Here are the specifications of the Intel i7-4770:

[Intel® Core™ i7-4770 Processor (8M Cache, up to 3.90 GHz)](https://www.intel.com/content/www/us/en/products/sku/75122/intel-core-i74770-processor-8m-cache-up-to-3-90-ghz/specifications.html)

<br/>

<br/>

### Step 7: Removing Power Supply Unit (PSU)

The Power Supply Unit (PSU) is a critical component in a computer system that converts electrical power from an external source (such as a wall outlet) into a form that the computer's internal components can use.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/6b9b22fb-9e5d-438c-88f2-b0d650d8ba59">

Unscrew the screws on the backside. Press the latch, and then slide the PSU out.

This is **HP DPS-240AB-3 B 240W Power Supply.**

<img width="600" alt="image" src="https://github.com/user-attachments/assets/a8a97767-7bd3-43a8-b3f2-6adb75f810bd">

The first label I see on the information is the “80 PLUS Platinum” certification related to the PSU’s efficiency. Efficiency measures how effectively the PSU converts AC power to DC power. Higher efficiency means less power is wasted as heat.

The 80 PLUS Platinum certification signifies that a PSU meets specific efficiency requirements at different load levels. 

| Efficiency Level | 20% Load | 50% Load | 100% Load |
| --- | --- | --- | --- |
| 80 PLUS Platinum | ≥90% | ≥92% | ≥89% |

<br/>

Also, all cables are attached to the PUS, meaning this is a Non-Modular PSU.

There are three types of PSU:

- **Non-Modular**: All cables are permanently attached to the PSU, which can lead to cable clutter.
- **Semi-Modular**: Some cables are permanently attached, while others can be detached.
- **Modular**: Cables can be attached and detached as needed, reducing cable clutter and improving airflow.

To learn more:

[Power Supplies Explained](https://youtu.be/ZW1wcoERoDU?si=qnweEjeDD9crYWab)

<br/>

<br/>

### Step 8: Ta Da!

Ta Da! We didn't take out everything! Uh… If I take out everything, I also need to route the wires and cables. I didn't know how to do this easily, and it would take a lot of time. I decided to leave most of the things inside. Maybe after I buy my own desktop, I will record the process in the future.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/5a6a42ce-5340-4795-8b0d-20e9e101e97e">

<br/>

<br/>

### Step 9: What is Solid-State Drive (SSD)?

Well… we still can do some research on the rest of the parts. Here comes the SSD!

<img width="600" alt="image" src="https://github.com/user-attachments/assets/ac495e28-012b-4d67-9cc7-2d728eb63f1b">

A Solid-State Drive (SSD) is a type of non-volatile storage device that stores and retrieves data using flash memory. Unlike traditional hard disk drives (HDDs), which use spinning disks and mechanical read/write heads, SSDs have no moving parts, making them faster, more reliable, and more energy-efficient. 

<br/>

Here is the video about how SSDs work:

[How do SSDs Work? | How does your Smartphone store data? |  Insanely Complex Nanoscopic Structures!](https://youtu.be/5Mh3o886qpg?si=QTrl5RelaJsLvIf5)

This computer uses Micron 256GB SATA 2.5-inch Self-Encrypting (SED) Solid State Drive (MTFDDAK256MBF) to store data. 

<img width="600" alt="image" src="https://github.com/user-attachments/assets/c12375e7-306d-419d-9523-c815fba808bb">

Here are its specifications:

| Specification | Description |
| --- | --- |
| Unformatted capacity | 256,186,209,271 bytes |
| Architecture | SED Solid State Drive with 25nm MLC NAND Flash and SATA interface |
| Interface | Serial ATA 2.0 (3.0 Gb/s) |
| NAND Flash | 25nm MLC NAND Flash |
| Bandwidth performance | Sustained sequential 128k read: Up to 450 MB/s |
| | Sustained sequential 128k write: Up to 260 MB/s |
| | Random 4k read: up to 46K IOPs |
| | Random 4k write: up to 56K IOPs |
| Latency |  Read: 55 μs |
| | Write: 55 μs |
| Power | SATA power consumption: 160 mW (active average); less than 85 mW (idle average) |
| Useful drive life | 72TB written, up to 40 GB/day for 5 years |

<br/>

<br/>

### Step 10: What is DVD Writer?

A DVD writer, also known as a DVD burner, is an optical disc drive that allows a computer to read from and write data to DVDs (Digital Versatile Discs). DVD writers can handle various types of DVD media and often support CD reading and writing.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/e5b66ed7-e71e-46a6-b2cb-50305513debc">

<br/>

<br/>

This is an HP Super Multi DVD Writer.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/c2dc4f23-7402-4e1f-808c-138efb4c4e6b">

While optical drives are becoming less common in modern computers, the shift reflects changes in how content is consumed and stored. However, for those who still need optical drives, external solutions are readily available to fill the gap.

I also have a portable DVD writer with me, just in case.

<br/>

## Conclusion

Overall, I am glad I didn’t break anything. Thank you so much, Professor Salviani. After watching so many videos, I finally saw the physical computer parts. I learned a lot from this experience.

<br/>

## References

* [HP Support](https://support.hp.com/id-en/document/c03846648)

* [Branch Education](https://www.youtube.com/@BranchEducation)

* [PowerCert Animated Videos](https://www.youtube.com/@PowerCertAnimatedVideos) 

* [TechPowerUp](https://www.techpowerup.com/)

* [硬件茶谈](https://www.youtube.com/@user-og1rx7gc6o/featured)
