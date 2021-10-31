Hi there 👋🏽

This is a quick post about some terminologies which I learned recently -

**Motherboard** - Circuit board that connects the CPU to the memory and all the other hardware. The circuits are called buses which move instructions and data from one place to another.

**Peripherals** - These are the different devices that we plug into our laptops, such as printers, etc.

**CPU** - You'll know this one! The CPU architecture consists of -

* Core - Each processing unit is called a core. More cores = Faster performance!However, doubling the number of cores will not double a laptop’s speed. These cores have to communicate with each other through channels and this uses up some of the extra speed. A core contains an ALU (performs arithmetic and logical operations), control unit (manages instructions), and registers (a high-speed memory within CPU).
* Clock rate - Indicates how fast the CPU can run (measured in instructions per second, for example, 1 GHz = 1 billion instructions per second)
* Cache - This is a small amount of memory that the CPU has (closer to the CPU than RAM). It is used to temporarily hold stuff that the CPU is likely to reuse. The CPU automatically checks the cache for instructions before requesting data from RAM.
* Processor Type

**Memory** - An area where the laptop stores or remembers data. Memory is sometimes called primary memory. Memory is either volatile or non-volatile.

Whenever we start a program (which is kept in storage), it gets copied to the memory for execution. Storage is also called secondary storage.

The hardware that defines a computer is the CPU and memory. Without these, a computer could not function. CPU, memory, and bus speeds will all affect the overall speed of a computer.

![image](https://user-images.githubusercontent.com/10815402/139592329-27955e5f-e133-4abd-99aa-178cf9c32b01.png)
[Source](https://hazelcast.com/glossary/memory-caching/)

**RAM (Random access memory)** - This is the short-term memory where data is stored temporarily. Let’s say you are working on an Excel file and you make some changes, all this data is stored in your RAM. When you save the file, data is written to your hard drive. The data disappears when the laptop is turned off!

You might have seen that when you open a number of tabs on your Google Chrome, your RAM/memory usage has increased, this is because Chrome stores a lot of information in the memory to provide a faster experience.
![image](https://user-images.githubusercontent.com/10815402/139592348-ed44a765-e060-4d81-acaf-65c64934f70a.png)

That’s why users prefer higher RAM! (RAM is measured in GBs)

Hard disk - As mentioned above, this is long-term storage.

When we talk about “drives” labeled C:, D:, etc., we’re actually talking about partitions, sections of the disk. We must have at least one container (partition) with a file system before we can write any data.

ROM (Read-only memory) - ROM contains the BIOS which checks for the appropriate hardware and then launches the bootloader. The bootloader is responsible for launching the OS.

Operating system - Consider it to be your laptop’s manager. Let us say that a program needs to perform some operation and needs to access CPU, memory, etc. - All this is handled by your OS.

Some of the tasks performed by OS:

* interface - provides the GUI (Graphical User Interface) and the CLI (Command Line Interface) so that the user can interact with the computer
* manages CPU and memory 
* provides a file system and other utilities

When the user starts an application, OS searches for the files on the storage disk, loads them into memory, and then asks the CPU to start executing it.

That’s it for today!
