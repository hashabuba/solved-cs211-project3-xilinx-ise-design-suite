Download Link: https://assignmentchef.com/product/solved-cs211-project3-xilinx-ise-design-suite
<br>
In this project, students are expected to use the Xilinx ISE Design Suite (Webpack edition) 14.7 to complete the following tasks.

Please read the instructions carefully. Failing to follow the instructions would lead to significant point deductions.

<strong>Task 1: 2-to-4 Decoder (5 points) </strong>

A 2-to-4 decoder operates according to the following function table.

Implement a 2-to-4 decoder in VHDL using <em><u>structural design</u></em>: Please adopt the following as the entity declaration.

Note that, many logic gates are defined in the <em>UNISIM</em> library. In order to use these gates, you need to add the following lines in your VHDL program to include the <em>UNISIM</em> library.

Write a test-bench program and run simulations to validate your design: Use the given test cases below in your test-bench program. Pay attention to the signal names, signal values, and the time.

<strong>Deliverable(s): </strong>

<strong>Requirement(s): </strong>

<ul>

 <li>You must follow the structural design method.</li>

 <li>You must follow the submission guidelines.</li>

</ul>

<strong><em>Note: no points will be given if any of the requirements are not satisfied.</em></strong>

<strong>Rubric (Report) </strong>

<ul>

 <li>Use your own language to describe the function of the module to be implemented in VHDL.</li>

 <li>Include your VHDL entity declaration(s), architecture definition(s) and the testbench program.</li>

 <li>Show simulation results (e.g. the waveforms). Explain the outcome of <u>each</u> test case with screenshots. Show why the simulation result is correct.</li>

</ul>

<strong>Rubric (Source Code) </strong>

<ul>

 <li>Can compile without any errors.</li>

 <li>Can run simulations without any errors.</li>

</ul>

<strong>Task 2: 3-to-8 Decoder (7 points) </strong>

Implement a 3-to-8 decoder using the 2-to-4 decoder you have implemented in Task 1. The input to the 3-to-8 decoder should be labeled as <strong><em>A</em></strong>. It needs to be a 3bit bus. The output should be labeled as <strong><em>O</em></strong>, which is an 8-bit bus. Please use the following entity declaration for the 3-to-8 decoder.

Note that: (1) please adopt the <em>structural design approach</em>; (2) in addition to the 2to-4 decoders, you also need to include some logic gates to make it work.

In order to use the 2-to-4 decoder from Task 1, you will need to declare the 2-to-4 decoder as a component in the VDHL architecture definition of the 3-to-8 decoder:

Then you can use the decoder like this:

Once you successfully completed the implementation of the VHDL module, write a test-bench program and run simulations to validate your design. Use the given test cases below in your test-bench program. Pay attention to the signal names, signal values, and the time.

<strong>Deliverable(s): </strong>

<strong>Requirement(s): </strong>

<ul>

 <li>You must follow the structural design method.</li>

 <li>You must use the module(s) implemented before.</li>

 <li>You must follow the submission guidelines.</li>

</ul>

<strong><em>Note: no points will be given if any of the requirements are not satisfied.</em></strong>

<strong>Rubric (Report) </strong>

<ul>

 <li>Use your own language to describe the function of the module to be implemented in VHDL</li>

 <li>Draw a circuit diagram of the module to show the design.</li>

 <li>Include your VHDL entity declaration(s), architecture definition(s) and the testbench program.</li>

 <li>Show simulation results (e.g. the waveforms). Use the simulation results to explain why the implemented circuit is working correctly.</li>

</ul>

<strong>Rubric (Source Code) </strong>

<ul>

 <li>Can compile without any errors.</li>

 <li>Can run simulations without any errors.</li>

</ul>

<strong>Task 3: A 4-bit Ripple Adder </strong>

Implement a 4-bit ripple adder, similar to the one we discussed in class. You need to first implement a 1-bit full adder then cascade them to build the 4-bit ripple adder. Please use the following entity declarations for the 1-bit full adder and the 4-bit ripple adder.

Note that: (1) please adopt the <em>structural design approach</em>; (2) please make sure you use the following libraries and packages:

In order to use the 1-bit full adder, you will need to declare it as a component in 4bit ripple adder implementation:

Then you can use the 1-bit full adder like this:

Once you successfully completed the implementation of the VHDL module, use the test-bench program below and run simulations to validate your design.

<strong>Deliverable(s): </strong>

<strong>Requirement(s): </strong>

<ul>

 <li>You must follow the structural design method.</li>

 <li>You must use the module(s) implemented before.</li>

 <li>You must follow the submission guidelines</li>

</ul>

<strong><em>Note: no points will be given if any of the requirements are not satisfied.</em></strong>

<strong>Rubric (Report) </strong>

<ul>

 <li>Use your own language to describe the function of the module to be implemented in VHDL.</li>

 <li>Draw a circuit diagram of the module to show the design.</li>

 <li>Include your VHDL entity declaration(s), architecture definition(s) and the testbench program.</li>

 <li>Show simulation results (e.g. the waveforms). Use the simulation results to explain why the implemented circuit is working correctly.</li>

</ul>

<strong>Rubric (Source Code) </strong>

<ul>

 <li>Can compile without any errors. (1 point)</li>

 <li>Can run simulations without any errors. (1 point)</li>

</ul>





