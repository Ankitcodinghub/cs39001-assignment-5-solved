# cs39001-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [CS39001 Assignment 5 Solved](https://www.ankitcodinghub.com/product/cs39001-assignment-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92932&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS39001 Assignment 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. Linear Feedback Shift Register (LFSR) Design The objective is to design a synchronous sequential circuit using four D Flip-flops, which when loaded by an initial non-zero vector called seed, cycles through all the 15 non-zero binary combinations through its state transitions, before returning to the initial vector (the seed). Thus, this circuit can be used as a modulo-15 counter, although it does not count in exact binary sequence. The only combinational gates required are XORs. These sequential circuits are commonly termed as Linear Feedback Shift Registers (LFSRs), and have extensive use in digital circuit design and testing, communication theory, etc.

Design (using Verilog), simulate (using an appropriate Verilog testbench), and implement (on a FPGA platform supported by your CAD software tool), the 4-bit LFSR shown in Fig. 1. The four stages of the sequential circuit can be loaded by an arbitrary non-zero initialization seed by using the four multiplexers as shown in the diagram. In your testbench, verify that for an initialization seed 1111, the state transition sequence followed by this circuit is as follows: 1111 → 0111 → 0011 → 0001 → 1000 → 0100 → 0010 → 1001 → 1100 → 0110 → 1011 → 0101 → 1010 → 1101 → 1110 → 1111. (20marks)

</div>
</div>
<div class="layoutArea">
<div class="column">
seed[0]

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
– 2 – CS39001

</div>
</div>
<div class="layoutArea">
<div class="column">
2. [Two’s Complement Converter FSM] Design (using Verilog), simulate (using an appropriate Verilog testbench), and implement (on a FPGA platform supported by your CAD software tool), a simple finite state machine (FSM) that in every clock cycle reads an input bit, and outputs a bit such that the bitstring output till that point is the two’s complement of the binary number read till that point, including the most recently read bit (the number is considered to be input from the LSB side). The FSM has one input control signal which resets it to the initial state. Come up with an appropriate interface for your circuit. [Hint: consider a Mealy machine.] (10 marks)

3. [Multiple-of-three Detector FSM] Design (using Verilog), simulate (using an appropriate Verilog test- bench), and implement (on a FPGA platform supported by your CAD software tool), a simple finite state machine (FSM) that in every clock cycle reads an input bit, and outputs a bit which indicates whether the binary number read till that point, including the most recently read bit (the number is considered to be input from the MSB side), is divisible by three. The input number is to be considered an unsigned integer. The FSM has one input control signal which resets it to the initial state. Come up with an appropriate interface for your circuit. [Hint: implement a Mealy machine.] (10 marks)

Figure 2: Sequential unsigned comparator schematic.

4. [Sequential Unsigned Comparator] Consider the task of designing a sequential circuit that can compare two unsigned integers A and B, each of which is 32-bit long. The block-level schematic is shown in Fig. 2, where in every clock cycle, the circuit serially reads one bit each of A and B from their MSB sides at its input ports a and b respectively, and performs state transition of an internal finite state machine (FSM). In every clock cycle, the contents of the registers containing A and B are left-shifted. The circuit has three output lines L, E and G, exactly one of which becomes logic-1 at the end of the session indicating the result. Thus, if A &lt; B, then {L,E,G} = 100; if A = B, then {L,E,G} = 010; if A &gt; B, then {L,E,G} = 001. For simplicity, assume that the machine is in an initial all-zero (reset) state before the beginning of the session (the reset signal has not been shown in the above schematic), and the input control signal OP is at logic-0; as long as OP remains at logic-0, L = E = G = 0. At the end of the session (i.e., after the arrival of least significant bits), OP flips to logic-1, indicating the end of the operation, and that the values of L, E and G are now ready to be read.

Design (using Verilog), simulate (using an appropriate Verilog testbench), and implement (on a FPGA platform supported by your CAD software tool), the above circuit, which in 32 clock cycles generate the comparison results. The circuit has an input control signal to load the shift registers by Parallel Load (instantaneous asynchronous load) operation, and another input control signal to reset the FSM. Come up with an appropriate interface for your implementation. (20 marks)

</div>
</div>
</div>
