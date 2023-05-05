Download Link: https://assignmentchef.com/product/solved-cse331-project-4-use-altera-quartus-ii-with-verilog
<br>



In this project, you will use Altera Quartus II with Verilog. You will the 32-bit MIPS processor. The block that you will design will get no inputs from outside. You will have two memories: Data Memory and Instruction Memory. The instructions must be loaded to the instruction memory and the data must be in data memory. You will support <strong>xor, xori,</strong> <strong>slt, sltiu,</strong> <strong>lw, lh, lb, sw, sb, j, jal, jr, beq</strong>, <strong>bne</strong>, <strong>add, sub, and, or, sra, srl, sll, sltu </strong>and <strong>addi, addiu, andi, ori, slti, lui </strong>instructions<strong>.</strong> <u>Insert two <strong>new instructions</strong> on your own to MIPS. <strong>Find two suitable</strong></u><strong> <u>new instructions on your own, define them and design them.</u> </strong>

You will write test bench and simulate your design for verification. You will write the register and memory contents before and after the execution of instructions using <strong>writememh</strong> in your test bench verilog code. You will initialize memory contents using <strong>readmemh</strong>.

The data memory size will be 128KB whereas the instruction memory size will be 32KB. Remember that addressing for a 128KB memory only requires 17 bits instead of 32 bits in regular MIPS. Update your design accordingly.

(Bonus) Each new instruction other than the two, brings up additional 5pts until 20pts.