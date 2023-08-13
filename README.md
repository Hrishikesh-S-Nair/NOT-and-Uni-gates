# Ngspice Code for NOT, NAND, and NOR Gates

This repository contains Ngspice simulation code for simulating NOT, NAND, and NOR logic gates. Ngspice is a widely used open-source mixed-level/mixed-signal electronic circuit simulator.

## Table of Contents

- [Introduction](#introduction)
- [Contents](#contents)
- [Logic Gates](#logic-gates)
  - [NOT Gate](#not-gate)
  - [NAND Gate](#nand-gate)
  - [NOR Gate](#nor-gate)
- [Usage](#usage)
- [License](#license)

## Introduction

Logic gates are fundamental building blocks in digital electronics. This repository provides Ngspice simulation code to model the behavior of basic logic gates using Ngspice's circuit simulation capabilities. By using Ngspice, you can accurately simulate the functionality of NOT, NAND, and NOR gates, which are essential components in digital logic design.

## Contents

The repository contains the following files:

- `NOT_char.cir`: Ngspice code to simulate a NOT gate.
- `NAND_char.cir`: Ngspice code to simulate a NAND gate.
- `NOR_char.cir`: Ngspice code to simulate a NOR gate.
- `modelcard.nmos` and `modelcard.pmos`: Model cards defining the NMOS and PMOS models for the simulation.

## Logic Gates

### NOT Gate

The `NOT_char.cir` file contains Ngspice code to simulate a NOT gate. A NOT gate, also known as an inverter, produces an output that is the logical complement of its input. When the input is high (1), the output is low (0), and vice versa. The simulation showcases the basic behavior of a NOT gate and demonstrates its input-output relationship.

![BdieB](https://github.com/Hrishikesh-S-Nair/NOT-and-Uni-gates/assets/125496407/423267a4-645c-4866-885d-68f448204d21)

### NAND Gate

The `NAND_char.cir` file contains Ngspice code to simulate a NAND gate. A NAND gate produces a low output only when both of its inputs are high. In other words, it behaves as an AND gate followed by a NOT gate. The simulation demonstrates how the NAND gate's output responds to different input combinations.

![CMOS-implementation-of-a-NAND-gate](https://github.com/Hrishikesh-S-Nair/NOT-and-Uni-gates/assets/125496407/0c541746-bdd0-4d05-9848-05d7bbd0bdaf)


### NOR Gate

The `NOR_char.cir` file contains Ngspice code to simulate a NOR gate. A NOR gate produces a high output only when both of its inputs are low. It behaves as an OR gate followed by a NOT gate. The simulation showcases the behavior of a NOR gate and illustrates its input-output characteristics.

![CMOS-implementation-of-NOR-gate-G-2](https://github.com/Hrishikesh-S-Nair/NOT-and-Uni-gates/assets/125496407/c4a01502-e102-4e12-a644-8ee12d16e7af)

## Usage

To run the Ngspice simulations for each gate:

1. Clone this repository to your local machine.
2. Install Ngspice on your system if not already installed.
3. Open a terminal/command prompt.
4. Navigate to the repository directory.
5. Run the following command for each gate simulation:

   ```sh
   ngspice <gate_file_name>.cir

## Contributing

Contributions to this project are highly encouraged! Whether you find issues or have ideas for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You have the freedom to use, modify, and distribute the code according to the terms of the license mentioned above.

