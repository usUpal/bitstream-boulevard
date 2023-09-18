# What is Programming? (notes from geo hotz's stream)
In the world of computers and programming, there exists a fascinating interplay between input, computation, and output. This relationship forms the core of all digital processes, regardless of the programming language used. Today, we'll explore this concept through the lens of two programming languages: Haskell, known for its functional prowess, and Python, celebrated for its ease of use. This blog is the notes of geo's stream and some of my personal opinion.
## What is a Computer?
At its heart, a computer is a marvel of modern engineering, capable of executing complex tasks with precision and speed. But what makes up this intricate machine? A computer, in essence, can be broken down into two fundamental components: **Processor (CPU)**: This is the brain of the computer, responsible for executing a continuous stream of instructions. It interprets and carries out these instructions, manipulating data and making calculations as needed. **RAM (Random Access Memory):** RAM serves as the working memory of the computer. It temporarily stores both instructions and data needed for processing. Think of it as a workspace where the CPU can quickly access and work with information.
## What is a Program?
A program is the software that instructs a computer on what tasks to perform. It consists of various components, each serving a specific purpose:

- Text: The core of a program is a series of instructions written in a specific programming language. These instructions outline the steps the computer needs to take to achieve a particular goal. The language chosen, such as Haskell on one end of the spectrum known for its functional paradigm or Python on the other known for its ease of use, influences how these instructions are structured.

- BSS (Block Started by Symbol): This section of a program contains static data and is often used in low-level programming like assembly language code. It provides a place to store data that doesn't change during program execution.

- Stack: The stack is a region of memory used for managing local variables and controlling the flow of a program. When functions or procedures are called, their local variables are pushed onto the stack, and when they return, they're popped off. This helps in maintaining the order of execution.

- Heap: The heap is used for dynamic memory allocation, typically through functions like 'malloc' in C. It allows programs to allocate memory as needed during runtime, making it a flexible storage area.

Among these program components, the stack holds a pivotal role. It serves as a temporary storage area for local variables and plays a vital role in managing the flow of a program. Understanding how the stack works is crucial for building efficient and reliable software.
