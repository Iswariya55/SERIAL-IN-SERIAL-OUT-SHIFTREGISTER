# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Truth Table**

![image](https://github.com/user-attachments/assets/57783d85-ca68-4ef0-ae25-d322796ba484)

**Procedure**

/* 1.Type the Verilog program in Quartus Prime to implement the 4-bit Serial-In SerialOut (SISO) Shift Register.
2.Compile and run the program to ensure the design is error-free.
3.Generate the RTL schematic to visualize the cascading D flip-flop connections and
save it for documentation.
4.Create nodes for the serial input (SI), clock (CLK), and serial output (SO) to observe the
shifting process during simulation.
5.Simulate the design for different input serial data patterns and observe the timing
diagrams. */

**PROGRAM**

![image](https://github.com/user-attachments/assets/ada63f4b-aac2-4ede-80dd-26bc7b26b03b)

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:Iswariya RegisterNumber:24900725

*/

**RTL LOGIC FOR SISO Shift Register**

![image](https://github.com/user-attachments/assets/70905508-ec99-4780-a1e7-24fa417939b8)

**TIMING DIGRAMS FOR SISO Shift Register**

![image](https://github.com/user-attachments/assets/178537f6-da9e-45dd-99a9-8a58a3058fcf)
![image](https://github.com/user-attachments/assets/4d2c41dc-ed41-4402-a9dd-16a2efb849cd)

**RESULTS**

Thus, the Serial-In Serial-Out (SISO) Shift Register is implemented using Verilog, and its
functionality is validated with the truth table and timing diagrams
