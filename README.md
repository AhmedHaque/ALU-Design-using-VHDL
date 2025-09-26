# ALU-Design-using-VHDL
The following program we use VHDL to create a circuit design for a 2 bit input ALU that has a 4 bit selector and that gives a 4 bit output. We use Vivado for writing the circuit design and use the Zybo Z7 board to make an FPGA circuit. The ALU has 5 Functions:
- Compare when the selector is "0000". If A > B we get an ouput of "0001" else we get "0000".
- Add when the selector is "0001". It takes two inputs and gives the signed value output.
- Arithemetic Right Shift when the selector is "0010". Rights Shifts A by the number of times specified in B
- Multiply when the selector is "0100". Multiplies A with B.
- Exclusive OR when the selector is "1000". XOR's A with B.
