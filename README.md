## day-1:
![Screenshot (62)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/b59df35d-0aff-4629-b968-40e8ff669309)# nasscom-vsd-soc-design-program-
###   Sky130 - Inception of open-source EDA, OpenLANE and Sky130 PDK 
#### SK1-L1 Introduction to Q-48 Package,chip,pads,core,die and IPs
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
#####  Introduction to RISC-V
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
###### From software Applications to hardware
![Screenshot (73)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/3fc61ce3-5701-4e73-9dd1-1790840abb3d)

![Screenshot (74)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/0595d094-b047-45f1-b545-c1c96947d4d7)

![Screenshot (79)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/202a42a7-12d2-4e35-9872-701613a5b005)
#####  SK3-L1 OpenLANE Directory structure in detail 
 cd= change directory 
ctrl+shift+c = to copy
list =ls

![VirtualBox_vocdesign_03_05_2024_15_48_18](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/a77cdbd3-1987-48e1-9776-3473290972e5)
![VirtualBox_vocdesign_03_05_2024_15_51_14](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/8fae607f-6978-4d16-9d7a-f0b7a52e8195)
sky130_fd_sc_hd =sc-standARD CEL (lib ref)
tlef- tech lef
lib ref- specific to the technology
lib tool- specific to tools
tt-typical
ss-slow slow 
ff-fast fast
docker ./flow.tcl -interactive
ls -ltr(space )
less = to access inbuilt function
pwd = path directry

![VirtualBox_vocdesign_03_05_2024_17_51_04](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/2ed8a06b-a722-4c73-b6ec-bf591dd111a4)
![VirtualBox_vocdesign_03_05_2024_17_51_28](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/13ad5e4e-7476-45af-83c5-796cb05f3d74)
FLIP FLOP Ratio= no. of D-Flip flops/ total No. of cells
                  = 1613 /14876
                  =0.10842968
              percentageof D-FF= 10.84%
#    DAY -2
 ## SK1-L1 Utilization factor and aspect ratio      
     ![IMG-20240504-WA0018](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/ffd0e973-ae4e-42ea-a33a-163f603449bb)
![IMG-20240504-WA0029](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/6fda29b2-595c-4253-aa95-7462c050f5b7)
![IMG-20240504-WA0027](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/39cf31f4-fdba-4902-8189-4ade0199b555)

![IMG-20240504-WA0026](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/cfda2a2d-b62b-4b20-a189-f4f6db735f71)
#### SK1-L2  Concept of pre-placed cells
![IMG-20240504-WA0021](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/3433c303-bc95-4918-94d4-cbd9171af4e3)

![IMG-20240504-WA0020](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/2637322d-fce6-4217-9ca2-8482b1ed8ccb)
![IMG-20240504-WA0019](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/d3c1d082-14a1-4623-b70f-9f0c4de8e53d)

#### SK1-L3 De-coupling Capacitors
![IMG-20240504-WA0015](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/4d584fce-7c37-4bbd-a93c-36a633adf2f1)

preplaced cell(ppc): macros or IPs' which piece of complex logic and re used multiple times.
their locations (ppc) has to be very well defined as they cant be changed once they are palced inside core
they hav to be surrounded by decoupling capacitors.

according to above example d-ff4 's and gate changing from 0 to 1(ouput capacitor is charged) they it needs some current to perform tht and tht current is supplied by vdd in the same way when its changing from 1 to 0 (output cap id discharged)gnd shld take all those current and tht shld be carefully handle by power supply  

decoupling capacitors are the one which gets charged with the help of power supply and whenever the circuit switches it takes the power from decoupling cap (decouples the particular circuit from the main supply) 
it is used because  to reduce voltage drop  which was more while using physical wires.


##### SK1-L4 Power planning
![Screenshot (117)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/92cdd1c2-5590-4017-9755-9fe5cad5d4c4)
decoupling capacitors are the one which gets charged with the help of power supply and whenever the circuit switches it takes the power from decoupling cap (decouples the particular circuit from the main supply) 
it is used because to reduce voltage drop  which was more while using physical wires


let us consider 4 preplaced cells 
input is given to driver passed through 16-bit bus and output is taken from load 
we have given the signal 0 to 1 and the output should be same without fluctuating (there is no decoupling cap in tht path and not usual to use it often or all the time ) so power supply should check all these and should make sure that same signal is getting as output
![IMG-20240504-WA0016](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/50fe8686-2796-4fc2-b675-41fb4a08a8ab)

state between 0 and 1 is called undefined state and if signal  lies in this region it becomes quite unpredictable

ground bounce : when all caps are discharged at the same tym through single ground tap it forms like a bump (which increases its state from 0 and might enter the unpredictable region)noise margin 
bt after some it goes (gnd)to normal state
voltage droop: shortage of voltage as all cap taps are opened at a time to get charged. it is fine until it enters undefined region
![Screenshot (114)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/1b899a8c-84df-4c2d-9ddc-6a564f172154)
to overcome these probs
instead of one power supply multiple power supplies are used

![Screenshot (119)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/96d944b3-d8eb-4011-afa3-3d99c9604230)


###### SK1-L5 Pin placement and logical cell placement package
![Screenshot (122)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/63de5a18-6b48-4e99-8cea-77e499b60cf5)

###### SK1-L6 Steps to run floorplan using OpenLANE
![Screenshot (123)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/2233c425-d5d0-4980-8a0e-5445665f5841)

#### SK1-L7 Review floorplan files and steps to view floorplan 
![VirtualBox_vocdesign_04_05_2024_00_47_27](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/b0670446-fd45-4a70-8c6c-62a6687b4ebd)

##### SK1-L8 Review floorplan layout in Magic

![VirtualBox_vocdesign_04_05_2024_01_02_05](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/6d089161-950f-46cd-ac24-e0cd6e49c3d5)

![VirtualBox_vocdesign_04_05_2024_01_08_06](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/abd150eb-24e0-40d3-9c41-266aafb4ac4b)

![VirtualBox_vocdesign_04_05_2024_01_12_17](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/76ab8c83-04cf-4ab3-b97d-6290a1e34340)

#### SK2-L1 Netlist binding and initial place design
![IMG-20240504-WA0036](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/18ba08af-22f5-4d80-94b2-4f71734011cb)
![IMG-20240504-WA0035](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/c6d2564f-9039-4355-bdcb-f0266e52a319)

![IMG-20240504-WA0037](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/58bfed3d-6d28-4398-b221-f288eba8c075)
defining the width and height of core and die
- 1 netlist
 - 2 ff- launch flop and capture flop
between simple combination ciruits
and depends mainly on the dimensions of logic gate
whenever the aspect ratio is 1 it signifies that it is a square shaped, 0.5 or other than 1 = rectangle (also says that core is 50% utilized and there is some extra space to utilize )
ex :adding buffers or something like that.

### SK2-L2 Optimize placement using estimated wire-length and capacitance 
#### SK2-L3 Final placement optimization
![VirtualBox_vocdesign_04_05_2024_19_43_25](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/305e4dbe-10c7-4055-a18d-b51edfbbdc2e)
![VirtualBox_vocdesign_05_05_2024_00_40_25](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/1060ab0b-e4e4-4930-874b-1723ab55e950)
![VirtualBox_vocdesign_04_05_2024_19_48_56](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/847da393-ab85-44ea-b203-4e3e0a402a6b)

##### SK2-L4 Need for libraries and characterization

library binding and placement
library : a places where you find all kinds of books which has all the details of gates and timing information of particular gate

2 types of lib 
 one consist of only shape and size
another consists of only delay information

bigger the size of gates in lib = lesser resistance 
+ faster.


###### SK3-L1 Inputs for cell design flow

![Screenshot (146)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/09d2c797-10e8-4fa2-aff8-6aa0f997a600)
![Screenshot (145)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/28![Screenshot (148)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/6da4c594-fd58-470e-8be8-590cbd507dcf)
267331-559e-4745-a339-f6162e7f0402)

###### SK3-L3 Layout design step

 ![Screenshot (157)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/4dd9196b-daf9-4fa8-9ea2-2200aaba1f67)
![Screenshot (159)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/0549afeb-29b6-473d-a366-1e4f63985403)
###### SK3-L4 Typical characterization flow
library characterization and modelling

step 1:

logic synthesis:  first step of convert the functionality into legal hardware.
the output of logic synthesis is arrangements of gates that will represent the original functionality that we have described using RTL

step 2:
Floorplanning:  in this step we import the output of logical                              synthesis  or output of netlist and decide the size of core and die 
the width and height of the core and die is decided by the no. of gates and its sizes ,the area occupied by the logical synthesis.


step 3:
placement : we take the particular logic cell from (logical synthesis part) and place that in on the chip in such a way that logic gates or flip flop placed near the ports(input or output) in order to minimize the delay 

step 4:
 CTS :(clock tree synthesis) if you want zero skew or you want the clk to spread  among logic cells at an equal time (basically all gates should receive clk at the same time) .cts is an edge tree that takes of clock signal reaching at each and every point

step 5 
routing :all the connections.

step 6:
static timing analysis: step where we can see what the setup time and hold time ,what is the maximum achievable frequency of a circuit  
this is the last stage .
![Screenshot (166)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/7eb4a95b-94df-421d-8c96-e19ee5dc1b5c)
![Screenshot (167)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/dd9a86fd-3895-47af-88d4-beb19aef0c8e)
![Screenshot (168)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/41fabc31-39b1-40f9-b7dc-776e62084750)

![Screenshot (169)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/26178b1e-cf90-48e7-9139-348e63b28490)

![Screenshot (171)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/0803cb6a-8218-4ae2-90cc-337345b1e3f5)
![Screenshot (173)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/06642f72-f7aa-443e-a70f-5bb7a42e8c89)

### SK4-L1 Timing threshold definitions 
![Screenshot (183)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/07a77b39-361f-48a7-948f-b4cd7cd0da05)

## SK4-L2 Propagation delay and transition time

![Screenshot (187)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/f06da62a-d184-4447-89dd-c8b96c52cbb0)
![Screenshot (188)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/28c26d44-290b-4e64-8140-57267d6e4b26)

in_rise_threshold: point at 50% rise of input sig  
in_fall_thr :same
out_rise_thr: point at 50% rise of output sig  
out_fall_thr : same 50%

propagation delay:
 delay should be always positive
if it comes negative then it means we have chosen wrong threshold point
another possibility is that the wire delays are high (two buffers or inverters are  placed very far apart).

### DAY-3
## SK1-L0 IO placer revision 
### SK1-L1 SPICE deck creation creation for CMOS inverter
#### SK1-L2 SPICE simulation lab for CMOS inverter
##### SK1-L3 Switching Threshold Vm 
###### SK1-L4 Static and dynamic simulation of cmos inverter
###### SK1-L5 Lab steps to git clone vsdstdcelldesign

![Screenshot (200)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/926f9bba-615e-4e0e-b366-c1d35769bbd1)

![Screenshot (202)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/192c3756-6fe4-41a2-99a2-26a30c768a43)

![Screenshot (203)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/885e9f87-4bae-412a-a12b-ebe128206144)
![Screenshot (204)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/3c1daa71-6b1f-4d19-8240-f4b34b969b91)
![Screenshot (206)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/19d6cfa6-03bd-408f-8734-0ec03b7ac81d)
![Screenshot (209)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/b87bba54-59b8-4a3d-bf29-5f414ec81f86)
![Screenshot (212)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/a0847ea5-4375-42be-ae99-adc84215808f)
![Screenshot (213)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/96f1ca56-cb3e-4119-a17d-940d82fdf554)
![Screenshot (216)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/9627e4e9-60a4-4b19-8441-f913adab07eb)
![Screenshot (217)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/088c02d7-b5ae-484e-a311-2c8cd00d8470)


#### 16-MASK CMOSS PROCESS
![Screenshot (219)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/3278ecde-6d6f-4c94-8d60-bcceafdd8c02)
![Screenshot (220)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/6a3f365a-0374-40b0-a62b-684015390f37)
![Screenshot (222)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/0ec40d0d-b2d0-4a10-8f35-90000dd66c94)
![Screenshot (223)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/eb5f9b96-454b-4d5c-978f-9d842268b1e8)
![Screenshot (224)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/1a6e8f97-982f-4e3d-9320-7febd8bb5660)
![Screenshot (228)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/1301013a-2377-4abd-9920-46c770903455)
![Screenshot (229)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/14bd0778-1855-4495-b1f8-510f0f4a878c)
![Screenshot (232)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/38b3128a-053e-4ec6-8d18-665730fbd1c7)
![Screenshot (235)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/ee07d6b8-1148-4ce5-834c-64a6068e0acc)
![Screenshot (239)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/1d4f46d8-8a9a-423d-8e73-3c026cef28d2)
![Screenshot (243)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/08417baf-1962-4819-b2d6-bf3b8ecfe7d9)
![Screenshot (244)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/29e602b2-2240-499d-9b5a-ea11e8562c5b)
![Screenshot (245)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/5a1f31da-15f4-47ec-babc-6e0ef7f1ebc2)
![Screenshot (248)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/409bf1d4-e4ef-4af8-9c3c-2fb6a86334c8)
![Screenshot (249)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/dfa5874a-4111-4a27-af88-4629cf6911d7)
![Screenshot (251)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/a636ed76-caae-4152-9420-b5167e2756fa)
![Screenshot (252)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/9795ebc7-6e99-48c8-83f8-dac948342cbf)
![Screenshot (254)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/88b135f7-1b95-4702-b0c8-226b5ef781d5)
![Screenshot (257)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/cec06ca3-c84c-48ab-8cfc-7f6d85c98142)
![Screenshot (258)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/7fc09608-eaaf-440a-b4b3-621814368e23)
![Screenshot (259)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/2e32d86a-ad7d-4a60-b0e0-9e6b961ebd8b)
![Screenshot (262)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/10c749a4-3f3c-48ce-8d69-aafe04f96775)
![Screenshot (265)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/2149715d-993a-478c-809f-d9570005bb17)
![Screenshot (304)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/d260d3db-58b6-4c7a-885e-08f55eb4079e)
![Screenshot (321)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/871d45c4-22ab-4e1f-a93f-da8a3f4d5376)
![Screenshot (329)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/304c62fd-6765-45e1-9086-cb364e37d072)
![VirtualBox_vocdesign_05_05_2024_20_21_46](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/b889b3b6-6d08-4595-b275-c13fb130a696)
#### DAY -4
![VirtualBox_vocdesign_05_05_2024_20_22_28](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/96a297d7-f94e-4363-9e5a-3cead3974f5a)
![VirtualBox_vocdesign_06_05_2024_16_26_14](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/7c0cc13a-06f2-4d49-82c9-d8d59b414dac)
![VirtualBox_vocdesign_06_05_2024_16_29_37](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/e4c556e9-918b-40bf-ad94-7436c04813a6)
![VirtualBox_vocdesign_06_05_2024_16_41_54](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/7fef31df-0073-4611-bbc4-2611fd76
![VirtualBox_vocdesign_06_05_2024_16_46_39](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/3f6249d5-eb50-43fb-8e18-95e34b04f624)
7a59)
![VirtualBox_vocdesign_06_05_2024_16_56_25](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/8db1ad54-95c9-4cc0-827d-551beba9c40e)
![VirtualBox_vocdesign_06_05_2024_16_57_56](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/7415913e-5992-41cd-8e5e-027a666d4151)
![VirtualBox_vocdesign_06_05_2024_17_21_00](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/0d3c12d1-f86d-48c6-b483-1223b2c75ce1)
![VirtualBox_vocdesign_06_05_2024_19_13_17](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/1c843e1c-0271-48e0-9401-54006abb7f59)
![VirtualBox_vocdesign_06_05_2024_21_10_59](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/ddd8ac85-0576-499c-a593-039932d040b9)
![VirtualBox_vocdesign_06_05_2024_22_51_25](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/05e15601-c221-47b6-9aaf-21470b6f0cb6)
![VirtualBox_vocdesign_06_05_2024_21_31_57](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/cf003d17-56d8-4215-8243-1d61b1116f84)

![IMG-20240507-WA0001](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/2ca72eb5-b356-4b4a-9a17-a9e19100989a)
![IMG-20240507-WA0002](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/98b2459d-1799-48a7-a37a-e1eb5607cb52)
![IMG-20240507-WA0003](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/3f747c85-23e9-44e8-896e-2b4abad6d516)
![IMG-20240507-WA0004](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/1f1625e8-8db0-4c5d-9139-80703a0bc4c4)
![IMG-20240507-WA0005](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/d88fb7fa-40c3-441a-9440-fb11b860705e)
![IMG-20240507-WA0006](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/112e7e48-6576-4c5d-bb1b-bbba86c6a50a)
#### DAY -5
![Screenshot (400)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/6fd273ff-1741-442d-94ef-173dccadfe45)
![Uploading Screenshot (401).png…]()
![Screenshot (402)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/65eeaf05-7678-48ca-a3e2-27434f537bf7)
![Screenshot (403)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/014711b4-4575-4c03-962d-057a91af2fd1)
![Screenshot (404)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/00739d08-29f1-42a0-8155-1cb711e3061a)
![Screenshot (405)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/b709ea1a-8a10-4b7d-8b3c-55fb68282b9e)
![Screenshot (406)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/470d05de-7242-4612-b7b9-c895ebeb4921)
![Screenshot (407)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/49f49b9a-0a3f-4864-a3d0-c32393594074)
![Screenshot (413)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/e19712c0-1a6a-4127-99c7-b95e3d15d3e5)

![Screenshot (414)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/b4e5610f-9254-44ec-8713-28784b2e8c13)
![Screenshot (415)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/1e8838e3-5d53-4b5e-a1d8-a5429d415f81)
![Screenshot (416)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/de69bad0-bc7d-485a-905f-538a6ae19174)
![Screenshot (417)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/4a7a35d5-a24b-458f-be14-e7ab59f0356c)
![Screenshot (419)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/1ed152c6-caf6-4b9d-9928-d41c69089818)
![Screenshot (420)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/42827d06-7eb1-4029-b901-248dd15b89a0)
![Screenshot (421)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/80198095-f0a5-492a-ad8a-fdb1930cc91a)
![Screenshot (422)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/a73b735b-9f69-4d6d-877e-9f98faa1a36a)
![Screenshot (423)](https://github.com/Kraj-5/nasscom-vsd-soc-design-program-/assets/155510184/f539861e-0695-445e-83a0-c9310e615031)
