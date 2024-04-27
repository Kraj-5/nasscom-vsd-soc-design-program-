![Screenshot (62)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/b59df35d-0aff-4629-b968-40e8ff669309)# nasscom-vsd-soc-design-program-
## day-1:
### https://vsdiat.com/course_content?uniqueid=20240130055316#
#### https://vsdiat.com/course_content?uniqueid=20240130055316#
     ![Screenshot (61)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/84fa1260-9116-4900-ad36-2c199df4b43c)
Ardiuno boards are able to read inputs provided by the user and turn it into an desired output.It is bascially an open source electronic platform. It is used for hardware and software purposes.It has different type of boards.Among them, Ardiuno Leonardo is one .Ardiuno Leonardo is a microcontroller board based on the ATmega32u4.It has 20 digital input/output pins out of which 7 can be used as PWM outputs and 12 as analog inputs.Leonardo is different from other Ardiuno boards because it has a microcontroller inbuilt USB 2.0 communication.It also consists of 16MHz crystal oscillator,a power jack,an ICSP header and a reset button.
![Screenshot (62)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/5f0a31a7-878a-41ee-931f-1a6d1830ba2f)
This is the overview of the processor.
* I2C1:(Inter-Integrated Circuit)widely used synchronous,multi-controller/multi-target serial communication bus.
* QSPI2:(Quad Serial Peripheral Interface)flash is a type of non-volatile memory used commonly in storing firmware,configuration data and other critical information.it operates using Quad SPI protocol.
* JTAG:(Joint Test Action Group)is an industry standard for veryfying designs and testing printed circuit boards(PCBs) after manufacture.It's like a backstage pass for testing and interacting with chips on a board.
* UART:(Universal Asynchronous Receiver- Transmitter) is a versatile communication protocol used for asynchronous serial data exchange between electronic devices.
  Example: When an Ardiuno is connected to a computer, it communicates with computer using 
           UART.The Ardiuno sends data bits by bits and the computer's UART reassembles it into 
           computer bytes.
* SDRAM: It is type of random axis memory (RAM).It is volatile memory and are quite fast.
![Screenshot (65)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/55901354-e371-4cba-bfcb-05c4bfa23513)
Here, the outer most layer is called packages and inside it we have chip.
 ![Screenshot (66)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/a402eb69-a7b6-466d-bc5c-c5e1fa4dfffe)
* Pads: It is used to send signals inside and outside the chip.it acts an an intermediate between package and chip.
* Core: It is place where all digital logic accumulates(for example: AND,OR Gates,MUX etc..).
* Die: It is a small block of semiconductor layer. It determines the size of entire chip  to be manufactured on silicon layer.
##### https://vsdiat.com/course_content?uniqueid=20240130055316#
![Screenshot (67)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/07c4260c-e69b-442a-b288-add77ac01ed8)
It is the Architecture of the chip . Inside it is divided into two types-
* Marcos: It is purely digital logic .
* Foundry IP's: Provides essential building blocks for chip design,allowing designers to leverage pre-designed components optimized for specific purpose technologies.
![Screenshot (69)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/faa1eb2d-f5e2-46d7-a4b7-417e645ac2a4)
RISC- Instruction Set Architecture
The flow goes like -
* High level language
* Assembly level language
* Machine level language (converts to binay)
* RTL code
* Layout. 
###### https://vsdiat.com/course_content?uniqueid=20240130055316#
