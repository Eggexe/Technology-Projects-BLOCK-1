# Part 1 – Hardware vs Software

## Explain Hardware
Write **at least 50 words** explaining what hardware is.
---
Hardware can be explained as the physical components within a computer. Some examples are the CPU, RAM, a GPU etc. Hardware is used to interact with software, enacting upon the instructions that gets provided to it.
## Explain Software
Write **at least 50 words** explaining what software is.
---
Software are non-physical applications that live on the computer. They communicate to hardware to perform a task. For example, a browser playing a youtube video needs to speak to speakers to play audio. More niche software includes operating systems, which would handle the memory, scheduling and processor time, networking and user management for a computer, while still being software.
## How Do Hardware and Software Interact?
Write **at least 50 words** describing how they interact.
Software will typically attempt to communicate with hardware via the operating system's kernel and potentially with some other library. For example, for a youtube video to play on any Linux based OS, the browser will attempt to ask the kernel to play audio from the speakers. The kernel has to handle this as allowing software to have unrestricted access to a computer is unsecure. The kernel can log, check accesses or raise errors with the software raising the syscall. Fundamentally, once the syscall is passed to the hardware, some electricity would be passed to various transistors which eventually boils down to audio being played.
