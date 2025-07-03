Name: PARUSU KRISHNA VAMSI 
Company: CODETECH SOLUTIONS 
ID:CT06DG1294
Domain:VLSI
Duration:14June to 29July 2025
Mentor: Neela Santosh Kumar 

🔍 Project Overview: FIR Filter Design and Simulation
This project involves the design, implementation, and simulation of a digital Finite Impulse Response (FIR) filter using Verilog HDL. FIR filters are widely used in digital signal processing (DSP) applications due to their inherent stability and linear phase characteristics. The filter is designed to operate on streaming digital input samples and produce a filtered output using a predefined set of coefficients.

🔧 Key Deliverables
Verilog Code

Parameterized FIR filter module

Fixed coefficient bank

Shift register-based sample buffer and multiply-accumulate logic

Simulation Results

Simulated using testbench with impulse and step inputs

Verified impulse response matches expected filter behavior

Output signals traced using $monitor and waveform viewers

Performance Analysis

Latency: Determined by number of taps

Throughput: One output per clock cycle after pipeline fill

Resource Usage: Uses N multipliers and adders for N-tap design

Scalability: Easily extendable to higher-order filters

✅ Conclusion
The FIR filter was successfully designed and simulated in Verilog. Simulation confirmed correct output generation based on convolution with fixed coefficients. The design is modular, scalable, and suitable for integration in digital signal processing hardware such as audio, communications, and image processing systems.
