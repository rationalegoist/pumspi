# terminology
chronometer: 1h

> [!NOTE] SHELL SCRIPTING IN UNIX
>   **shell:** 
>   - kernel⇄user UI (command-line interface)
>   
>   **bash:** 
>   - shell's language ("bash" on unix, "powershell" on windows)
>   ---
>   1. system powers on: CPU reads a fixed address of predefined starting memory location (called "reset vector")
>   2. CPU starts executing the instructions written in firmware (which is stored in ROM)
>   3. BIOS ("basic input-output system" is a type of firmware) initializes hardware and 'tells CPU to load' bootloader 'into RAM'
>   4. bootloader tells 'CPU to load' kernel 'into RAM'
>   5. kernel 'tells CPU to load' essential stuff 'into RAM' = OS is ready to use

> [!NOTE] COMPILER VS INTERPRETER 
> **compiler**: 
> - source code (.c) → machine code (.exe) 
> - compile-time 
> 
> **interpreter:** 
> - source code (.py) → intermediate code (bytecode) → PVM calls the machine code which corresponds to machine code 
> - (this allows us to use the same bytecode at different OSs, PVM transforms it to appropriate machine code for the OS)
> - run-time
---

> [!NOTE] WHY PYHTON? 
> 1. **interpreted runtime execution:**
>    saves time from testing
> 
> 2. **compactness:**
>     2 pages of C = 2 lines of Pyhton
>     doesn't require variable declaration
> 
> 3. **cross-platform:**
>    PVM transforms bytecode to the appropriate machine code for the OS 
> 
> 4. **dynamic typing:**
>    variable types are determined in runtime 


> [!NOTE] Python is "EXTENSIBLE"
> - For computationally intensive tasks, Python's interpreted nature can be a bottleneck. By integrating C or C++ code, which are compiled languages, we can achieve significant performance improvements. For example, scientific computing libraries like NumPy are implemented in C to provide fast array operations.
- **C/C++ Extensions**: There are numerous high - quality libraries written in other languages. Extending Python allows us to use these libraries within the Python ecosystem. For instance, we can use the OpenCV library (written in C++) for computer vision tasks in Python.
- **Python modules**: creating our own library which contains our custom functions (if standart Python library's functions don't meet our needs)
