## How it works

The NAND gate is the complement of the AND function. Its graphical symbol consists of an AND gate followed by a small circle, which represents inversion. This indicates that the output of the NAND gate is the inverse of the AND operation.

The design starts by declaring a Verilog module. In Verilog HDL, a module is the basic building unit used to describe hardware designs. The module name `NAND_2` acts as the identifier for the circuit. The module declaration instructs the compiler to create a hardware block with defined inputs and outputs. The list inside the parentheses is called the port list, and it specifies the input and output ports of the module.

Next, an internal wire is declared:

```verilog
wire Yd;
In Verilog, a wire represents an electrical connection between logic elements. Since Yd is an internal signal, it is not included in the port list.

The logic operations are then defined as:
and (Yd, A, B);
not (Y, Yd);

Here, an AND operation is performed on inputs A and B, and the result is stored in the internal wire Yd. This intermediate result is then passed through a NOT gate to produce the final output Y. The Verilog compiler interprets the AND and NOT statements as hardware logic gates. The endmodule statement marks the end of the module definition.

## How to test

Refer to the truth table for NAND.

## External hardware

NONE
