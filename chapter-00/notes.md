# Chapter 0 - Introduction/Getting Started

## 0.1 – Introduction to these tutorials

**In my own words:** The main purpose of learncpp.com is to help you learn the
proper guidelines and best practices for programming in C++ while keeping it
engaging, current, and free to use. There are habits that will ensure you stay
on track: writing the examples by hand, always debugging whenever you encounter
an error, experimenting with the example programs (changing them a bit), not
rushing the quizzes and taking your time with them, and writing simple programs
yourself from what you've learned. The main goal is to practice by writing real
programs. They start small but grow as you learn.

**Key concepts/terms:**

- Debugging: Finding and fixing errors, or bugs, in your program. We can divide
  them, roughly, in three types: syntax errors, runtime errors, and logical
  errors.

  - Syntax errors: Mistakes or typos that break the rules of the programming
    language. These happen at compile time. For example, forgetting to finish a
    statement with a semicolon (;). These are usually simple to catch and fix,
    as your compiler will refuse to build your program, telling you which line
    the error is on, and your text editor will usually give you a hint also.

  - Runtime errors: Errors that make the program crash, or not finish properly,
    when you execute it. For example, dividing an integer by 0.

  - Logical errors: Unexpected behaviour from the program you are writing. The
    program runs, but doesn't do what you intended. These errors often require
    you to know what the program is supposed to do, and make you define what
    "correct" means for your program.

**Gotchas / mistakes I made:** No coding on this lesson.

**Open questions:** No open questions for this lesson.

## 0.2 – Introduction to propgrams and programming languages

**In my own words:**

**Key concepts/terms:**

- **Computer program**: a sequence of instructions that perform a set of tasks
  in a specified order. These are often written in a programming language. A
  programming language allows to write these instructions in human-readable code
  that the computer will understand. These are often compiled to Assembly code,
  then assembled into binary code; which is what the computer can understand. A
  set of 1s and 0s executed into the CPU of your machine. The programs can also
  be intepreted. Scripting languages such as Python and JavaScript don't have to
  be compiled first, making them more portable than compiled languages. But it's
  at the cost of performance.

- **Programming**: the act (or art) of writing computer programs in a
  programming language.

- **Hardware**: the physical components of a computer. Notable parts of hardware
  are:
  - CPU (central processing unit): considered the "brain" of the computer. It's
    what executes the instructions for any software inside the machine.
  - Memory (RAM/VRAM): loads the programs prior to execution.
  - Interactive devices (e.g. mouse, monitor, etc.): allows the user to
    interact/use the computer.
  - Storage devices (e.g. SSD, hard drive, memory flash: stores information
    long-term - even when the computer is turned off.

- **Sofware**: the digital tools and programs that communicates with the
  hardware to perform requested tasks. You can include the OS (operating system)
  of your PC, and more deeply, its kernel (such as the Linux kernel; which
  allows the OS to communicate with the hardware as a middleman). Software can
  be tied to an platform (macOS, Windows, Linux) for its functionabilty. If it
  can be executed in multiple platforms, it is considered portable. Allowing a
  program to run on another platform is called porting.

- Machine language/code: The CPU can only understand machine code - a
  instruction set based on 1s and 0s. These sets are binary, or bits for short.
  CPUs can differ on how they read their instruction sets. Some can only read
  sets up to 32 bits long. As some CPU architectures, such as x86, can vary on
  how they read binary code. Writing machine code was a hard and time-consuming
  task for programmers. That made programmers in the earlier days develop
  Assembly, or ASM - a much more readable language to program with. But, the
  same way as machine code, ASM is tied to the specific CPU architecture of your
  program - making it impossible to read/execute for other CPUs if they aren't
  from the same family. That made necessary to create higher-level programming
  languages such as C to ensure portability and scalability.

- Assembly language (Assembly): Assembly allows a programmer to write
  instructions to be executed by the computer without having to use machine
  code. Assembly is considered a low-level language. A CPU can only understand
  binary code, so you also use an assembler to translate the assembly code into
  machine code. As the instructions in assembly are direct to what binary would
  do, the translation is straightfoward and direct. But these are tied to the
  specific architecture of your CPU. Different CPU families use different
  intructions, naming conventions, etc.
  - Example ASM program: `mov al 0x61`. `mov` being short for `move` - to copy
    bits from one location to another. The register `al` to register the memory
    location to the CPU. It is tied to the convention for your CPU
    architecture - `al` is the one for the x86 CPU family. `0x61` is the
    hexadecimal value for the stored bit value. It also can hold decimal values
    such as `97`.

**Gotchas / mistakes I made:**

**Open questions:**
