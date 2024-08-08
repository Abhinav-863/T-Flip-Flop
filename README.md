# T-Flip-Flop
A T flip-flop, also known as a “Toggle Flip-Flop,” is a fundamental component in the field of digital electronics. It plays a pivotal role in storing and processing binary data, acting as the building block for various digital systems such as counters, shift registers, and memory devices. Essentially, a T flip-flop is a bistable device, which means it has two stable states. It can store one bit of information, either a ‘0’ or a ‘1’. The ‘T’ in T flip-flop stands for “toggle,” which succinctly describes its behavior. When the input or ‘T’ is high (1), the flip-flop toggles its output state. Conversely, when the input is low (0), the output state remains unchanged. 
•	Input T (Toggle): This is the control input of the flip-flop. Depending on its state, the flip-flop either changes or maintains its output.
•	Output Q: This is the main output which reflects the current state of the flip-flop.
•	Output Qbar: This is the inverse of the main output Q. If Q is high, Qbar is low, and vice versa.
•	Clock Input: This input is used to synchronize the flip-flop’s operation with the rest of the digital circuit.

SCHEMATIC OF T FLIPFLOP 
![image](https://github.com/user-attachments/assets/44cd18ad-fee9-4d40-ac36-54b448edf9ba)
Schematic of T flipflop is done using master-slave JK Flipflops by shorting J and K input and connecting to new input T.

Q and Q_BAR acts as input and output. T and CLK  are the input.

SYMBOL
![image](https://github.com/user-attachments/assets/7fabbbdf-6386-4d1e-a164-42cbab99eb1f)

TESTING THE CIRCUIT
![image](https://github.com/user-attachments/assets/86f293fa-f0d8-480b-978a-263f1980dd1a)

OUTPUT WAVEFORM
![image](https://github.com/user-attachments/assets/8c486fb1-55dd-44b7-826b-7e036111e6a5)

Transient analysis of T Flipflops
In the above waveform red color waveforms is clock and green color waveform is T input. In the above waveform we can see that, at the start, the flip-flop has an initial state, typically either set or reset, depending on its design. The flip-flop waits for the clock signal to change from high to low that is, it reacts to the falling edge of the clock signal. The flip-flop has an input called T. If T is high (usually logic 1), the flip-flop toggles its output. If T is low (usually logic 0), the output remains unchanged. If T is high at the falling edge of the clock, the flip-flop toggles its output. If T is low, the output remains the same. The flip-flop maintains its output state until the next falling edge of the clock signal occurs.




