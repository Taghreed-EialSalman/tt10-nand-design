## How It Works

The NAND gate is the complement of the AND function. Its graphical symbol consists of an AND gate followed by a small circle, which represents inversion. This means that the output of the NAND gate is the inverse of the AND operation.

The design begins by defining a Verilog module, which is the basic building block used to describe hardware in Verilog HDL. The module name NAND_2 identifies the circuit. The module declaration creates a hardware block with defined input and output signals, listed in the port list.

An internal signal is used to store the intermediate result of the logic operation. In Verilog, this signal represents an electrical connection between logic elements and is not included in the module’s port list.

The circuit operates by first applying an AND operation to inputs A and B. The result of this operation is then inverted to produce the final output Y, implementing the NAND logic function.

## How to Test

Verify the NAND gate by applying all possible input combinations for A and B, and checking the output against the NAND truth table.

## External Hardware

None.
