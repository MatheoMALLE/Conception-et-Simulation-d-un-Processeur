# Conception-et-Simulation-d-un-Processeur
This project involves the design, simulation, and programming of a simple processor (**CYT-VX8** architecture) implemented in **Logisim**. It includes a custom assembly instruction set as well as a Python compiler that translates an assembly program into a memory image that can be loaded directly into the simulated circuit.

## 🛠️ Roadmap
- creation of the registers and the ALU
- addition of the Fetch module and the decoder
- connection to RAM
- management and connection of various input and output signals

## 🧰 Skills required
- Logisim
- python

![Circuit du processeur](documentation/projet%20Processeur.png)

---
## Documentation
### Create an instruction list
1. Edit the `instruction.txt` file with the desired assembly instructions. Example:
2. From the project root directory, run:
```bash
python3 compile_asm_cyt-vx8.py instruction.txt image
```
### Run the processor:
1. Open the `projet_Processeur.circ` file in Logisim.
2. Load the generated `image` file into the circuit’s memory (ROM/RAM).
3. Run the simulation to observe the program’s execution.

For more details on the architecture, instruction format, and internal workings of the processor, see the documentation/ folder.
