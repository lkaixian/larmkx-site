---
layout: post
title: "Experience on ARM On-Demand Training (Day 1 till Day 3)"
date: 2025-08-02
---

First of all, I'm truly grateful to have been selected for the opportunity to participate in the ARM-MY On-Demand Training, a 3 day program hosted by Arm in collaboration with ASEM - Advanced Semiconductor Academy of Malaysia, held from 28 July 2025 to 30 July 2025 at Monash University Malaysia. 
This marked my first in-depth exposure to the ARM architecture and its ecosystem. 

🧠Day 1: Introduction of ARM Architecture & Profiles
- ✨ARM (Advanced RISC Machine) licensing it's own ISA and CPU designs rather than making the chip.
- ✨ARM's family consists of A-profile (Application profile), R-profile (Real-time profile), M-profile (Microcontroller profile) and Neoverse.
- ✨ Biggest difference between ARMv8-a and ARMv9-a is ARMv8-a introduce 64-bit computation while ARMv9-a introduce enhancement of security and AI/ML capabilities.
- ✨ big.LITTLE architecture consists of mix of big and little cores whereas  #DynamIQ architecture are more integrated, removal of L3 cache and replace with DynamIQ Shared Unit (DSU).
- ✨ #AMBA Tree Protocol is ARM's Interconnect where it has numbers of protocols used for communication. Think of them like types of road and number of lanes.

🧠Day 2: SoC Design & ARM System IP
- ✨General SoC Design flow is as below:
Architecture definition (requirements, PPA) → IP integration (RTL & EDA tools) → RTL design & verification (testbench, constraints) → Software co-development (drivers) → Backend Implementation (floor planning) → Tape-out → Validation → Mass production.
- ✨The Core ARM SoC components consists of ARM CPUs, the memory subsystem, AMBA Interconnect, System IP, I/O, NPU, and PCM (Power & Clock management)
- ✨Introduction of ARM  #Corstone SubSystems - prebuilt SoC templates. (Corstone-1000)

🧠 Day 3: AI and ML with ARM
- ✨ Introduction of ARM  #Ethos-U Series NPU - perform from basic CNN to Transformers by offloading NN ops from Cortex-M using ARM  #TOSA (Tensor Operator Set Architecture)
- ✨Introduction of  #Vela compiler where it optimize TFLu (TensorflowLite micro) for NPU execution.
- ✨ Optimization of LLM including Quantization, distillation, pruning, and using DAG (Dynamic Graph - TF 2) or Eager Mode (TF 1)
- ✨ Optimization of Matrix including loop tiling, reordering, loop unrolling and multicore parallelism.

There's still a lot more to cover and so far I had done summary for the 1st day. Special thanks to:
- Blade Lin for detailed explanation (especially on differences between GIC and NVIC in terms of speed and ARM Kleidi framework on SLAM application) and advices.
- Tsung-Chih (Alex) Su for detailed explanation (especially on difference between DMA and SMMU and efficiency on using JIT on DAC) and advices.
- Niki Dow, Graciela Lin, and Jessica Wu for the amazing advices during panel discussion. 
- CK Tseng for the thrilling opening speech🔥

In short, this marked as the first step for the in-depth exploration of ARM's ecosystem. Hope you find this post insightful.
 #STEMEducation  #ASEM  #ARM  #ARMTraining  #Semiconductor  #Monash   #ARMOnDemand

![armphotod1-1.jpg](/assets/armtrain/armphotod1-1.jpg)
<p align="center"><em>My first visit to Monash University! Cool university with easy access to the public transport, and a Zus Coffee inside the campus? (And yes, sorry, I blocked one of the letter.)</em></p>

![armphotod1-2.jpg](/assets/armtrain/armphotod1-2.jpg)
<p align="center"><em>Gracelia Lin presented an overview of ARM's background, including its historical development and real-world application of ARM-based chip.</em></p>

![armphotod1-3.jpg](/assets/armtrain/armphotod1-3.jpg)
<p align="center"><em>Thanks Alex Su for the very detailed explanation especially the difference between GIC and NVIC (Nested Vectored Interrupt Controller), as well as the difference between C2C (Chip-2-Chip) in ARM and AMD's Infinity Fabric.</em></p>

![armphotod2-1.jpg](/assets/armtrain/armphotod2-1.jpg)
<p align="center"><em>Demo of Ollamacpp run deepseek-r1 at 1.5b parameters. I only seen youtubers doing these (Jeff Geerlings, Alex Ziskind and NetworkChuck), and now here we are. (Nothing impressive, but feels so cool when you could literally run AI model on a something like a credit card sized computer)</em></p>

![armphotod2-2.jpg](/assets/armtrain/armphotod2-2.jpg)
<p align="center"><em>And yea, that's the edge device which runs the deepseek-r1 1.5b. Alex Su introduce this with the help of NPU that could perform up to 16 TOPs.</em></p>

![armphotod2-3.jpg](/assets/armtrain/armphotod2-3.jpg)
<p align="center"><em>Thanks Niki Dow for providing us the inspiring advises. I am deeply appreciate for what Niki Dow provides with her vision, experiences, and courages for the young folks.</em></p>

![armphotod3-1.jpg](/assets/armtrain/armphotod3-1.jpg)
<p align="center"><em>Thanks Blade Lin for the very detailed explanation (especially on differences between GIC and NVIC in terms of speed and ARM Kleidi framework on SLAM application) and advices on semiconductor field.</em></p>

![armphotod3-2.jpg](/assets/armtrain/armphotod3-2.jpg)
<p align="center"><em>The ordinary opening of Arm Developer Labs</em></p>

![armphotod3-3.jpg](/assets/armtrain/armphotod3-3.jpg)

<p align="center"><em>I made it till the end of the event! </em></p>
