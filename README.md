# parallel-to-serial-converter-with-74hc165
Parallel to Serial Converter with 74HC165 - Shift Register Application

In addition to series-to-parallel converters in digital electronic circuits, parallel-to-series converters are also needed. For example, 8-bit data generated in a circuit may need to be serialized and sent to a remote electronic system via an RF circuit operating at 433 MHz. Here, parallel to serial converters are needed in such cases.

In this application, we will use the 74HC165 IC. The 74HC165 CMOS is an integrated. The 74HCT165 is a TTL IC. The 74HC165 IC can be operated up to 24 MHz frequency.
The functions of the pins of this IC are as follows:

 

74HC165
D0, D1, D2, D3, D4, D5, D6, D7: are data input terminals.
PL: When this pin is HIGH-->LOW, the "1" or "0" at the inputs of the data pins are loaded into the "LATCH" of the IC.
CP: When the clock signal is HIGH-->LOW, one bit is transferred to the serial output. Serial output is taken from pin Q7.
At the end of 8 clocks, 8-bit parallel data is serially exported.
CE: The chip is activated when this pin is LOW.
We used a signal generator for the clock input to the circuit we built on the breadboard. We used a low frequency range (1-10Hz) to understand the operation.

You can find the short video of the application on our youtube channel.

Other details: https://milivolt.news/post/parallel-to-serial-converter-with-74hc165-shift-register-application
Youtube      :https://youtu.be/KFk2akko7qg?si=ablBbIBpVcJkES8B
