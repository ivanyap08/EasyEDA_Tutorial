# EasyEDA Electronic Design Automation: A Step-by-Step Guide to Schematic Capture & PCB Design
## 1. Introduction

<p align="center">
  <img src="./images/image1.png" width="150" alt="EasyEDA icon">
</p>

### What Is EasyEDA?
EasyEDA is a cloud-based Electronic Design Automation (EDA) suite for designing, simulating, and sharing electronic circuits and PCB layouts, seamlessly accessible directly in a web browser or via dedicated desktop applications for Windows, macOS, and Linux. 

#### Main Uses
1.  Online Schematic Capture – Draw electronic circuit schematics with components and wiring
2.  PCB Design & Layout – Create printed circuit board designs with part placement and trace routing
3.  Circuit Simulation – Test circuit behavior using integrated SPICE simulation before building
4.  Component Libraries – Access extensive electronic component libraries
5.  Collaboration & Sharing – Cloud-based access for teamwork and sharing designs
6.  Manufacturing Integration – Direct integration with PCB manufacturers (e.g., JLCPCB) for ordering fabricated boards or assembled units

#### Core Value Proposition
1.  Accessibility – Runs entirely in the cloud, requires no installation, and works on any device with a web browser
2.  Simplicity – Intuitive UI designed for both beginners and professionals
3.  All-in-One Workflow – Combines schematic capture, simulation, PCB design, and ordering in one platform
4.  Cost Effectiveness – Free for all users
5.  Collaboration – Enables easy sharing and teamwork, supporting open-source hardware and education

---


### Minimum Requirements

| Equipment | Description |
| :--- | :--- |
| **CPU** | 2 or more cores. Supports the following CPU architectures: X86, AMD64, LoongArch64, SW_64, and ARM64 |
| **Memory** | 8 GB of DDR4 memory or more (designs with up to 10,000 pins) |
| **Graphics card** | • **X86 CPU**: Integrated graphics card released after 2019.<br>• **Non-X86 CPU**: A discrete graphics card released after 2017 is required.<br>*Note: Update the graphics card driver to the latest version.* |
| **Disk** | System disk: 128G SSD; Data disk: 100G HDD |
| **Browser** | The latest version of Chrome, Edge, or Firefox. V120 or later, 64-bit, with hardware acceleration enabled. (Older browser engine versions are not supported.) |
| **System** | 1. **Windows**: Windows 10 or above<br>2. **Linux**: Linux kernel 4.9 and above (supports Ubuntu, deepin, etc.)<br>3. **Mac**: macOS 10.12 and above |

---

### Recommended Requirements

| Equipment | Description |
| :--- | :--- |
| **CPU** | i3-9100 and above |
| **Memory** | 16 GB or more (more than 10,000 pins) |
| **Graphics card** | Discrete graphics card (GTX1080 and above) |
| **Disk** | System disk: 128G SSD; Data disk: 100G SSD |
| **Browser** | Chrome (V120+, 64-bit, hardware acceleration enabled) |

---
### Key Terminology

Before diving into the project, here are the definitions of unique concepts, acronyms, and industry terms used throughout this documentation:

| Term / Acronym | Full Name / Definition | Description |
| :--- | :--- | :--- |
| **Std Edition** | Standard Edition | The basic version of EasyEDA, suitable for beginners and simple circuit design. |
| **Pro Edition** | Professional Edition | Offers more advanced features than the basic version and is suitable for complex, multi-layered PCB designs. |


### Basic Electronic Components

#### 1. Resistor

Schematic symbol:\
<img width="504" height="384" alt="image" src="./images/image2.png" />\
Physical appearance:\
<img width="2525" height="1349" alt="image" src="./images/image3.png" />

Typical Applications:

Current limiting\
Voltage dividers\
Pull-up/pull-down resistors\
Biasing circuits

#### 2. Capacitor

Schematic symbol:\
<img width="879" height="496" alt="image" src="./images/image4.png" />\
Physical appearance:\
<img width="1200" height="800" alt="image" src="./images/image5.png" />

Typical Applications:

Power supply filtering\
Signal coupling/decoupling\
Timing circuits\
Energy storage

#### 3. Inductor

Schematic symbol:\
<img width="640" height="320" alt="image" src="./images/image6.png" />\
Physical appearance:\
<img width="2048" height="1088" alt="image" src="./images/image7.png" />

Typical Applications:

Power supply filtering\
Energy storage in switching supplies\
RF (radio frequency) circuits\
Oscillator circuits

#### 4. Diode

Schematic symbol:\
<img width="450" height="403" alt="image" src="./images/image8.png" />\
Physical appearance:\
<img width="1352" height="718" alt="image" src="./images/image9.png" />\
LED:\
<img width="1200" height="632" alt="image" src="./images/image10.png" />


Typical Applications:

Rectification (AC to DC conversion)\
Reverse polarity protection\
Voltage regulation\
Signal demodulation\
Status indicators (LED)

#### 5. Transistor

Schematic symbol:\
<img width="1208" height="541" alt="image" src="./images/image11.png" />\
Physical appearance:\
<img width="566" height="479" alt="image" src="./images/image12.png" />


Typical Applications:

Switching circuits\
Amplification\
Signal modulation\
Audio amplifiers

#### 6. Integrated Circuit (IC)

Schematic symbol:\
<img width="572" height="435" alt="image" src="./images/image13.png" />\
Physical appearance:\
<img width="762" height="615" alt="image" src="./images/image14.png" />

Typical Applications:

Arithmetic and logical operations\
Data storage and retrieval\
Control of various functions within the device

#### 7. Switch

Schematic symbol:\
<img width="464" height="434" alt="image" src="./images/image15.png" />\
Physical appearance:\
<img width="1968" height="1125" alt="image" src="./images/image16.png" />

Typical Applications:

User input/control\
Circuit enable/disable\
Mode selection\
Reset functions


## 2. Getting Started
1. First, visit the official website and navigate to the download page: \
   👉 [Official Website](https://easyeda.com) \
   👉 [Official Download Page](https://easyeda.com/page/download)

   As of June 1, 2026, the latest stable versions for the Standard and Pro editions are:

   | Edition | Latest Stable Version |
   | :--- | :--- |
   | **Standard (Std) Edition** | v6.5.51 |
   | **Pro Edition** | v2.2.47.7 |


### 🛠 Installation Process

To get started, you need to download the installer from the official website. 

> 💡 **Note:** The following guide will use the **Pro Edition** for the installation demonstration.

---

#### 1️⃣ Step 1: Download the Installer
Click the hyperlink highlighted in the red box on the official download page.
<p align="center">
  <img src="./images/image17.png" width="600" alt="Official Download Page">
</p>

Save the downloaded `EasyEDA.exe` file to your computer via the system dialog.
<p align="center">
  <img src="./images/image18.png" width="500" alt="Download To Computer">
</p>

---

#### 2️⃣ Step 2: Launch the Installer
Open the downloaded file and click **Yes** when the system prompt asks for permission to continue.
<p align="center">
  <img src="./images/image19.png" width="400" alt="Open File Prompt">
</p>

Click **Next** on the setup welcome screen to proceed.
<p align="center">
  <img src="./images/image20.png" width="500" alt="Click Next">
</p>

---

#### 3️⃣ Step 3: License Agreement
Select **"I accept the agreement"** to agree to the terms, then click **Next**.
<p align="center">
  <img src="./images/image21.png" width="500" alt="Accept Agreement">
</p>

---

#### 4️⃣ Step 4: Choose Installation Path & Shortcuts
Select your preferred installation location and click **Next**.
<p align="center">
  <img src="./images/image22.png" width="500" alt="Choose Location">
</p>

Check the box if you would like to create a desktop shortcut, then click **Next**.
<p align="center">
  <img src="./images/image23.png" width="500" alt="Create Shortcut">
</p>

---

#### 5️⃣ Step 5: Complete Installation
Click **Install** to begin the installation process.
<p align="center">
  <img src="./images/image24.png" width="500" alt="Click Install">
</p>

Please wait while the installation completes.
<p align="center">
  <img src="./images/image25.png" width="500" alt="Installing Process">
</p>

Once the process is finished, click **Finish** to exit the installer.
<p align="center">
  <img src="./images/image26.png" width="500" alt="Finish Installation">
</p>


🎉 **EasyEDA is now successfully installed and ready to use!**


## 3. The Interface

### 3.1 Workspace Breakdown

<img width="1916" height="894" alt="image" src="./images/image27.png" />

<img width="1918" height="877" alt="image" src="./images/image28.png" />

### 3.2 Control Elements

<img width="1667" height="567" alt="image" src="./images/image29.png" />
<img width="580" height="458" alt="image" src="./images/image30.png" />
<img width="627" height="603" alt="image" src="./images/image31.png" />

---

### How to adjust the drawing area
Right-click the drawing area and select **Property**. In the right-hand panel, change the paper size from **A4** to **A3**. 
<img width="592" height="791" alt="image" src="./images/image32.png" />


### ⌨️ 3.3 Hotkeys & Shortcuts

#### 3.3.1 Component Hotkeys (Selected Component)
| Shortcut | Action / Description |
| :--- | :--- |
| `Space` | Rotate component |
| `Esc` | Cancel current drawing |
| `Delete` | Delete selected item |
| `X` | Flip horizontally |
| `Y` | Flip vertically |

#### 3.3.2 UI Control Hotkeys
| Shortcut | Action / Description |
| :--- | :--- |
| `D` | Drag |
| `K` | Fit window |
| `Shift + F` | Open shop |
| `Ctrl + A` | Select all |

#### 3.3.3 Schematic Hotkeys
| Shortcut | Action / Description |
| :--- | :--- |
| `Alt + W` | Place wire |
| `Alt + B` | Place bus |
| `Alt + N` | Place Net |
| `Alt + T` | Place text |

#### 3.3.4 PCB Hotkeys
| Shortcut | Action / Description |
| :--- | :--- |
| `Alt + W` | Place Wire |
| `Alt + V` | Place Via |
| `Alt + T` | Switch to Top Layer |
| `Alt + B` | Switch to Bottom Layer |
| `Ctrl + Shift + L` | Align Left |
| `Ctrl + Shift + R` | Align Right |
| `Ctrl + Shift + O` | Align Top |
| `Ctrl + Shift + B` | Align Bottom |

## 4. A Basic Example
Basic Example (ESP32-S3 Development Board)

Reference documentation for ESP32-S3: https://docs.espressif.com/projects/esp-idf/en/v5.3.1/esp32s3/hw-reference/esp32s3/user-guide-devkitc-1.html

ESP32-S3 Schematic: [https://www.espressif.com/sites/default/files/documentation/esp32-s3-wroom-2_datasheet_en.pdf](https://dl.espressif.com/dl/schematics/SCH_ESP32-S3-DevKitC-1_V1.1_20221130.pdf)
<img width="1603" height="788" alt="image" src="./images/image33.png" />

Another example based on the ESP32-S3-DevKitC-1 schematic:
<img width="897" height="634" alt="image" src="./images/image34.png" />


Basic 3D PCB Example (ESP32-S3 Development Board)


Top side:
<img width="1620" height="913" alt="image" src="./images/image35.png" />

---

Bottom side:

<img width="1793" height="951" alt="image" src="./images/image36.png" />


### PCB Design Procedure

Below is the standard step-by-step workflow for electronic design, from initial project creation to final manufacturing file export.

```mermaid
graph TD
    %% Define Styles
    classDef startEnd fill:#FFF2CC,stroke:#D6B656,stroke-width:2px;
    classDef process fill:#DAE8FC,stroke:#6C8EBF,stroke-width:2px;
    classDef drc fill:#F8CECC,stroke:#B85450,stroke-width:2px;

    %% Workflow Nodes
    Start([Create New Project]) --> NewBoard[Create New Board]
    
    %% Schematic Branch
    NewBoard --> NewSchem[Create New Schematic]
    NewSchem --> PlaceComp[Place Components]
    PlaceComp --> Wiring[Wiring]
    Wiring --> DRC1{Check DRC}
    DRC1 --> ToPCB[Convert to PCB]
    DRC1 --> ExportBOM[Export BOM]
    
    %% PCB Branch
    NewBoard --> NewPCB[Create New PCB]
    ToPCB --> NewPCB
    NewPCB --> PlaceFrame[Define Board Outline]
    PlaceFrame --> Layout[Layout Components]
    Layout --> Routing[Routing]
    Routing --> DRC2{Check DRC}
    DRC2 --> ExportGerber([Export Gerber Files])

    %% Assign Styles
    class Start,ExportGerber startEnd;
    class NewBoard,NewSchem,PlaceComp,Wiring,ToPCB,ExportBOM,NewPCB,PlaceFrame,Layout,Routing process;
    class DRC1,DRC2 drc;
```
## Drawing a Simple Schematic
Open a new project folder. \
<img width="581" height="186" alt="image" src="./images/image37.png" /> \
Enter a name and click **Save**. \
<img width="636" height="315" alt="image" src="./images/image38.png" /> \
Double-click **P1**. \
<img width="1919" height="1027" alt="image" src="./images/image39.png" /> \
You can rename the schematic and PCB by right-clicking each item. \
<img width="1919" height="1027" alt="image" src="./images/image40.png" /> \
<img width="377" height="586" alt="image" src="./images/image41.png" /> \
This example includes two sections: the ESP core and the USB circuit. 
---
### Core Circuit
<img width="1400" height="770" alt="image" src="./images/image42.png" /> \
Common components are available on the left-hand side. \
<img width="1508" height="763" alt="image" src="./images/image43.png" /> \
Click **Library** and enter the component name **ESP32-S3-WROOM-1**. Double-click the component, then drag and drop it onto the schematic. \
<img width="1697" height="313" alt="image" src="./images/image44.png" /> \
<img width="1857" height="956" alt="image" src="./images/image45.png" /> \
Follow the reference schematic. Double-click the required components, then drag and drop one resistor and two capacitors onto the schematic. \
<img width="1371" height="715" alt="image" src="./images/image46.png" /> \
Press **Alt + W** to draw wires and connect the resistor and capacitors. \
<img width="920" height="472" alt="image" src="./images/image47.png" /> \
Click **VCC** twice in the floating toolbar to place two VCC symbols.
<img width="1046" height="326" alt="image" src="./images/image48.png" /> \
<img width="975" height="455" alt="image" src="./images/image49.png" /> \
Click **GND** in the floating toolbar and place it in the appropriate location. \
<img width="946" height="524" alt="image" src="./images/image50.png" /> \
Double-click the **VCC** label to edit it. \
<img width="568" height="327" alt="image" src="./images/image51.png" /> \
Change it to the appropriate label. \
<img width="1044" height="539" alt="image" src="./images/image52.png" /> \
Edit the resistor and capacitor descriptions. You do not need to change the reference designators **R1**, **C1**, and **C2** to **R24** or other names. \
<img width="1091" height="518" alt="image" src="./images/image53.png" /> \
Drag **NET LABEL** onto the pin. \
<img width="289" height="192" alt="image" src="./images/image54.png" /> \
<img width="476" height="274" alt="image" src="./images/image55.png" /> \
Then edit all the net labels as shown. Net labels define connections, so you do not need to use exactly the same names as the example, provided that the intended connections are preserved. \
<img width="505" height="582" alt="image" src="./images/image56.png" /> \
Connect GND to EPAD and the GND pins as shown in the circuit.
<img width="840" height="411" alt="image" src="./images/image57.png" /> \
The core section of the schematic is now complete. \
<img width="934" height="639" alt="image" src="./images/image58.png" />
---
### USB Circuit
Schematic:
<img width="1148" height="725" alt="image" src="./images/image59.png" /> \
Search for the Micro USB connector and the diodes **LESD5D5.0CT1G** and **1N5819HW-7-F**. Drag and drop them onto the schematic. \
<img width="1024" height="507" alt="image" src="./images/image60.png" /> \
Draw the wires. \
<img width="1313" height="538" alt="image" src="./images/image61.png" /> \
Add the capacitor, net label, and VCC/+5V symbol. \
<img width="1244" height="538" alt="image" src="./images/image62.png" /> \
Modify the net label. \
<img width="1273" height="542" alt="image" src="./images/image62.png" /> \
Connect the wires. Pay attention to the junction; do not remove it manually. \
<img width="1289" height="546" alt="image" src="./images/image63.png" /> \
<img width="1329" height="511" alt="image" src="./images/image64.png" /> \
Edit the description. \
<img width="908" height="362" alt="image" src="./images/image65.png" /> \
Place the two components in suitable locations. \
<img width="989" height="640" alt="image" src="./images/image66.png" /> \
Draw a rectangle around both components. \
<img width="1549" height="834" alt="image" src="./images/image67.png" /> \
Place the text. \
<img width="1234" height="755" alt="image" src="./images/image68.png" /> \
Place the text in the corner and enter a description. Then adjust the font. \
<img width="1459" height="558" alt="image" src="./images/image69.png" /> \
Then run the DRC. \
<img width="1556" height="968" alt="image" src="./images/image70.png" />
---
How do you convert a schematic into a PCB, design the layout, and route the traces?
Click to convert to PCB. \
<img width="1085" height="586" alt="image" src="./images/image71.png" /> \
Click **Apply Changes**. \
<img width="878" height="621" alt="image" src="./images/image72.png" /> \
Select the **Board Outline** layer to define the PCB dimensions. \
<img width="1918" height="868" alt="image" src="./images/image73.png" /> \
Use the rectangle tool.
<img width="399" height="166" alt="image" src="./images/image74.png" />
Place the first point at the origin, then choose a suitable size. \
<img width="1386" height="696" alt="image" src="./images/image75.png" /> \
Select **Board Outline**. \
<img width="574" height="673" alt="image" src="./images/image76.png" /> \
Click **Confirm**. \
<img width="484" height="620" alt="image" src="./images/image77.png" /> \
Select the top layer, then click **Net** to expand it. \
<img width="1906" height="808" alt="image" src="./images/image78.png" /> \
Hide the GND connections. \
<img width="276" height="320" alt="image" src="./images/image79.png" /> \
Arrange the components in a suitable layout. A good layout is especially important when reducing the board size. \
<img width="1063" height="580" alt="image" src="./images/image80.png" /> \
Press **Alt + W** to route the traces. \
<img width="1201" height="621" alt="image" src="./images/image81.png" /> \
Press **Tab** to adjust the trace width. Use wider traces for power connections. \
<img width="1265" height="561" alt="image" src="./images/image82.png" /> \
You can press **Alt + B** to create a via so that you can connect traces on the bottom layer. Use **Alt + B** to switch to the bottom layer and **Alt + T** to switch to the top layer. \
<img width="1067" height="509" alt="image" src="./images/image83.png" /> \
Connect all the traces. \
<img width="1060" height="549" alt="image" src="./images/image84.png" /> \
Only the GND connections should remain unrouted. Press **Alt + V** to create a via, then change its net to **GND**. \
<img width="1520" height="458" alt="image" src="./images/image85.png" /> \
You can now show the GND connections. \
<img width="268" height="254" alt="image" src="./images/image86.png" /> \
Place several vias near the GND connections. [The footprint was incorrect, so I changed it and rerouted the traces.] \
<img width="1023" height="560" alt="image" src="./images/image87.png" /> \
Select the rectangular copper area tool. \
<img width="716" height="215" alt="image" src="./images/image88.png" /> \
Draw a boundary around the entire board, then click **Confirm**. \
<img width="1033" height="593" alt="image" src="./images/image89.png" /> \
<img width="453" height="632" alt="image" src="./images/image90.png" /> \
Repeat this step on the bottom layer. \
<img width="560" height="699" alt="image" src="./images/image91.png" /> \
Check DRC. \
<img width="1298" height="1077" alt="image" src="./images/image92.png" /> \
Connect GND or place suitable vias near the GND connections, then rebuild the copper area. \
<img width="1640" height="773" alt="image" src="./images/image93.png" /> \
Resolve the errors and run the check again. \
<img width="1599" height="1023" alt="image" src="./images/image94.png" /> \
Click **2D** or **3D** to preview the board.
<img width="1055" height="629" alt="image" src="./images/image95.png" /> \
<img width="1576" height="914" alt="image" src="./images/image96.png" /> \
The PCB is now complete. \
Reminder: The ESP32 requires a complete circuit to operate. This example only demonstrates how to draw a schematic and design a PCB; it is not suitable for use in an actual application. 


## 5. Core Features

|  Features|Description | 
| -------- | -------- |
| Schematic Capture (Circuit Design) | Placing components (resistors, microcontrollers) on a canvas and connecting them with virtual wires. |
| Design Rule Check (DRC)  | Flags errors like unconnected pins or short circuits. |
| PCB Layout & Routing| Arranging physical components on a board and drawing the copper tracks that connect them. |
| 3D Visualization | Inspecting the physical height, clearance, and aesthetic look of the finished PCB. The board can also be exported as a 3D file (STEP or OBJ). |


### 5.1 Creating a Component

<img width="1026" height="537" alt="image" src="./images/image97.png" />

Click **File > New > Component**, enter a component name, and click **Save**.

<img width="1027" height="532" alt="image" src="./images/image98.png" />

Click **Wizard**, choose **DIP**, **QFP**, or **SIP** according to your design, and set the number of pins on each side. Then click **Generate Symbol > Confirm**.

<img width="1027" height="538" alt="image" src="./images/image99.png" />

Click **Tools > Advanced Symbol Wizard**, name the pins, and click **Confirm**. Press **Ctrl + S** to save.

<img width="1027" height="551" alt="image" src="./images/image100.png" />

Return to **Schematic**, then select **Personal > All > J2** (the component name) and click **Place**.

### 5.2 Schematic Capture (Circuit Design)

<img width="1022" height="474" alt="image" src="./images/image101.png" />

Before designing the circuit, choose a larger schematic sheet if needed.

<img width="377" height="539" alt="image" src="./images/image102.png" />

Use the library to place a specific component, as shown below. 
<img width="1919" height="331" alt="image" src="./images/image103.png" />

Double-click the device name or click **Place**, then drag the component onto the schematic.
<img width="1490" height="311" alt="image" src="./images/image104.png" />


Click **Place** to select different components and draw the circuit diagram.

<img width="693" height="421" alt="image" src="./images/image105.png" />

                                 Circuit design example

<img width="1244" height="875" alt="image" src="./images/image106.png" />

                               ESP32-S3-DevKitC-1 Schematic

### 5.3 Replacing a Component Footprint
Click the component to highlight it in red, then click **Footprint**.
<img width="1071" height="482" alt="image" src="./images/image107.png" />

Select the component whose footprint you want to change.
<img width="764" height="354" alt="image" src="./images/image108.png" />

Choose a suitable footprint and make sure it matches your design. Then click **Update**.
<img width="763" height="365" alt="image" src="./images/image109.png" />
If the footprint name changes, the replacement was successful. You do not need to select the checkbox.
<img width="863" height="441" alt="image" src="./images/image110.png" />

Example error: The footprint does not match the component.
<img width="1031" height="622" alt="image" src="./images/image111.png" />


### 5.4 Creating a PCB Model

<img width="940" height="497" alt="image" src="./images/image112.png" />

Click **Design > Import Changes from Schematic**. The board components will be displayed.

<img width="940" height="536" alt="image" src="./images/image113.png" />
                                                
                                                   PCB model

Create the board outline.

<img width="1029" height="556" alt="image" src="./images/image114.png" />

Put the components in the appropriate positions.

<img width="523" height="777" alt="image" src="./images/image115.png" />

### 5.5 Creating a 3D Model

<img width="1031" height="551" alt="image" src="./images/image116.png" />

Click **3D** to display the 3D model. 

<img width="940" height="761" alt="image" src="./images/image117.png" />

                                                   3D model


                               
### 5.6 Design Rule Check (DRC)
**Design Rule Check (DRC)** is a crucial **quality assurance measure** engineered to verify that a physical PCB layout strictly complies with specific **manufacturing process constraints** and capabilities. While PCB design software provides the freedom to create virtually any layout, real-world manufacturing facilities are constrained by **physical limitations**. Consequently, a design that appears flawless on screen may not be **physically manufacturable**.

<img width="940" height="366" alt="image" src="./images/image118.png" />

Go to **Design > Check DRC**.

<img width="1047" height="533" alt="image" src="./images/image119.png" />
After running the check, a list of errors will appear in the Design Manager panel on the left (Reminder: If there are errors, the PCB model cannot be created. Ensure that the circuit design is correct before creating the PCB model.)

### Foundational Ground Rules of PCB Design
The fundamental rules of PCB design cover three areas: **Schematic Logic**, **Physical Routing**, and **Manufacturing Constraints**.

```mermaid
graph LR
    classDef logic fill:#E1F5FE,stroke:#03A9F4,stroke-width:2px;
    classDef electrical fill:#E8F5E9,stroke:#4CAF50,stroke-width:2px;
    classDef dfm fill:#FFEBEE,stroke:#FF5252,stroke-width:2px;

    A[Schematic Entry] --> B[Physical Layout] --> C[Manufacturing / DFM]
    
    class A logic;
    class B electrical;
    class C dfm;
```
---
### Drawing the PCB
After running the check, a list of errors will appear in the Design Manager panel on the left.

Once you have successfully resolved all DRC errors and the Design Manager panel displays a clean slate (Zero Errors), your board is mathematically and electrically compliant with the rules you set.

Click this button to convert the schematic into a PCB.
<img width="940" height="195" alt="image" src="./images/image120.png" />

It looks like this.

<img width="648" height="650" alt="image" src="./images/image121.png" />

---
Arrange the components to minimize overlapping blue connection lines and make routing easier.
<img width="940" height="949" alt="image" src="./images/image122.png" />
If blue connection lines cross, use a via (**Alt + V**) to connect the top and bottom layers. 
<img width="74" height="92" alt="image" src="./images/image123.png" />

During routing, you may find that a component cannot be connected on the current layer. Use a via (**Alt + V**) to switch to the bottom layer.
<img width="455" height="189" alt="image" src="./images/image124.png" />

---
### Routing Procedure 
Step 1: Connect all components, ignoring GND
Route all of your signal lines, data buses, and non-GND power traces (VCC_3V3, etc.) first.
Use both the Top Layer (Red) and Bottom Layer (Blue) to complete these paths.
Leave all GND pads completely untouched.

Reminder: Route traces with enough spacing to leave room for future copper pours.
 
<img width="625" height="1334" alt="image" src="./images/image125.png" />


Step 2: Pour the Ground Plane
- Select **Place > Copper Region**.
- Draw a large boundary around the entire board on the Top Layer and Bottom Layer and assign it to the GND net.
- Adjust or reposition the traces to improve the copper pour. Press **Shift + B** to refill the zone. This connects all through-hole GND pins to the ground plane.

Step 3: Bridge "Ground Islands" (Via Stitching)
- Look for any blue lines that are still stretching across the board. These are "GND Islands"—areas where long signal tracks on the bottom layer have sliced the ground plane in half.
- Drop stitching vias to connect the copper on the top layer to the copper on the bottom layer, creating a bridge over or around those bottom signal traces.

<img width="940" height="949" alt="image" src="./images/image126.png" />

<img width="648" height="1181" alt="image" src="./images/image127.png" />

Step 4: Run the DRC to make sure the **Unrouted Items** count is exactly **0**.

<img width="1745" height="897" alt="image" src="./images/image128.png" />


### Schematic Entry Rules
* **Functional Zoning:** Circuits must be strictly segmented into distinct functional blocks (e.g., Power Management, MCU Core, RF Section, and Analog Signal Inputs). This structured containment prevents complex signal lines from crossing and creating routing chaos later in the physical layout.
* **Left-to-Right Flow:** To maximize readability and streamline debugging, symbols must be arranged to illustrate a logical signal path. Inputs and primary power sources should enter from the left, while outputs and terminal destinations exit to the right.
* **Unique Net Labeling:** Generic or ambiguous net names must be avoided. Distinct power domains must be explicitly and uniquely labeled (e.g., separating `+3V3_MCU` from `+3V3_RF`). This allows the EDA software to recognize separate electrical nodes and assign appropriate routing priorities and widths during layout.
---
### Physical Layout & Routing Rules
* **Mechanical & Component Placement Priority:** The layout must follow a strict structural hierarchy. Fixed mechanical constraints—such as external interfaces (connectors), mounting holes, and enclosure-restricted components—must be locked into position first. Only then should core integrated circuits (e.g., MCUs, PMICs) be placed, immediately followed by their critical local supporting components (e.g., decoupling capacitors, crystal oscillators).

**Top Layer Priority**
* **Rule:** Route traces on the top layer as much as possible.
* **Reasoning:** This minimizes the use of vias, reduces signal propagation delay, and maintains a clean return path on the bottom/inner reference ground planes.

**Power Trace Widening**
* **Rule:** Power traces must be widened to facilitate smooth current flow along the main power paths.

**Routing Angles (> 90°)**
* **Rule:** $90^\circ$ right angles or acute angles within the same layer are **strictly prohibited**. A **135° (45-degree)** routing angle is highly recommended.
* **Reasoning:** Acute and right-angle corners cause transmission line impedance discontinuities, which lead to signal reflections and negatively impact signal integrity.
  
**Capacitor Placement & Current Path**
* **Rule:** Power must first flow through the filtering/decoupling capacitor before reaching the downstream load or IC pins.
* **Best Practices:**
  * Decoupling capacitors must be placed **as close as possible** to the chip's power pins.
  * Ensure the capacitor's ground terminal connects directly to a nearby point on the ground plane (**localized grounding**).

**High-Frequency Signal Routing**
* **Rule:** High-frequency signal traces must be kept **as short as possible** with proper shielding and isolation from other signals.
* **Crosstalk Mitigation:**
  * To reduce crosstalk between adjacent traces, adhere to the **3W Principle** (trace-to-trace spacing should be at least 3 times the trace width).
  * Avoid parallel routing between adjacent layers; traces on adjacent layers should be routed **orthogonally (perpendicularly)** to each other.
* **Differential Pairs:** Differential traces must be routed with equal distance (constant spacing) and equal length (**isometric and equal length**).

**Keepout Zones (Mounting Holes & Board Edges)**
* **Rule:** PCB routing must stay as far away as possible from mounting holes and the board's physical edges.
* **Reasoning:** During PCB drilling, routing, and mechanical profiling/v-scoring, traces placed too close to these areas can easily be cut, nicked, or damaged, causing open circuits or board failure.

**Adding Teardrops**
* **Rule:** **Teardrops** must be added to the junctions between traces and pads/vias.
* **Reasoning:** Teardrops smooth the transition from a narrow trace to a wider pad or via, enhancing mechanical strength (preventing pads from cracking off during manufacturing or soldering) and improving thermal stability and signal integrity.

---


### Design for Manufacturing (DFM) Rules
Manufacturing rules represent the boundaries imposed by physical machinery tolerances and thermal physics during assembly.
* **Clearance (Electrical Isolation):** Chemical etching solutions inevitably exhibit lateral bleed during production. If two copper traces or pads are placed too close together, the copper can fail to separate, resulting in a fatal **short circuit**. Designers must enforce a minimum physical clearance that respects the factory's etching tolerances.
* **Via Dimensions:** The diameters of via holes must strictly comply with the factory's minimum mechanical drill bit capabilities. Overly small vias can cause micro-drill bits to snap instantly during fabrication, yielding incomplete connections.
* **Thermal Management:** Expansive copper planes act as massive heatsinks that rapidly absorb and dissipate thermal energy. When a component pin connects directly to an extensive copper pour, a **Thermal Relief (cross-hatch pattern)** must be implemented. This traps heat locally at the joint during soldering, preventing brittle, unreliable "cold joints" and ensuring proper solder reflow.


## Core Functions of PCB Copper 

In short, filling the blank areas of a PCB with a large sheet of copper is mainly done to solve the three most critical hardware challenges:

### Powerful Anti-Interference (Perfect Ground Return Path)
* **Principle:** Connecting a large area of copper to the Ground (GND) network physically turns it into a massive electromagnetic shield, actively absorbing surrounding RF and high-frequency noise.
* **Core Value:** It provides the shortest and widest "path home" for signal currents, drastically reducing crosstalk between signal traces. For high-frequency boards with Wi-Fi/Bluetooth like the ESP32-S3, this is the key to signal stability.

### Eliminating Ground Resistance
* **Principle:** The wider the conductor, the lower the resistance. Large-area ground pouring is equivalent to widening the originally narrow ground traces by hundreds of times.
* **Core Value:** When a chip requires a sudden burst of high current, it prevents the voltage on the pins from dropping instantly (by lowering impedance). This ensures that the 0V reference point for all components on the board remains absolutely stable and prevents power rails from fluctuating.

### Efficient Thermal Conduction
* **Principle:** Fiberglass boards (FR4) themselves are terrible at dissipating heat, but copper is an excellent thermal conductor.
* **Core Value:** For components that generate a lot of heat, such as the SGM2212 voltage regulator or other power devices, connecting their thermal pads directly to a large copper pour turns the entire PCB into a natural heatsink. This distributes heat evenly into the air, preventing localized overheating from burning out the chip.
---
### 📂 Production Files Required for Professional PCB & PCBA Manufacturing

To move from a finished design to a physical, fully assembled board, you must generate two distinct sets of production data: **Fabrication Files (for the bare board)** and **Assembly Files (for component soldering)**.

#### 1. Bare-Board Fabrication Files (PCB Layout Blueprint)
These files tell the factory how to etch the copper, apply the coatings, and drill the holes:

* **Gerber Files (RS-274X or Gerber X2 format):** The absolute lifeline and industrial blueprint for PCB fabrication. These files deconstruct a complex 3D circuit board into highly precise, layer-by-layer 2D vector slices.
  * **Copper Layers (Top/Bottom):** Define the exact geometric pathways for high-speed electrical traces and copper pours.
  * **Solder Mask (Top/Bottom):** Dictates where the protective liquid photoimageable cover (e.g., green insulating oil) is applied, and where pads are precisely exposed ("opened") for soldering.
  * **Silkscreen (Top/Bottom):** Prints the white component outlines, pin 1 indicators, logos, and reference designators (e.g., `R1`, `U1`) to assist in manual inspection and assembly.


#### 2. Assembly Files (PCBA SMT Specifications)
If you require automated machine assembly where the factory sources and solders components onto the board, you must provide these files alongside your Gerbers:

* **Bill of Materials (BOM Table):** A comprehensive spreadsheet listing every component required. It must include:
  * **Designator:** The component label matching the silkscreen (e.g., `C1`, `R1`, `U1`).
  * **Value / MPN:** The electrical value or Manufacturer Part Number (e.g., `10uF`, `10k`, `ESP32-S3-WROOM-2`).
  * **Footprint:** The physical package size (e.g., `0603`, `SOT-223`, `QFN28`).
* **Pick and Place File (Centroid / Component Coordinate File):** A machine-readable text/CSV file used to program high-speed robotic SMT placement systems. It contains the precise center-point $X/Y$ coordinates, rotational angles ($0^\circ$ to $360^\circ$), and target board side (Top/Bottom) for every surface-mount device.

---

## Exporting Gerber Files from EasyEDA

Follow these steps to generate your Gerber files:

1. **Locate the Export Menu**
   In the top toolbar of your PCB layout screen, click on the **Export** menu, then select **"PCB Fabrication File (Gerber)"** from the dropdown list. \
   <img src="./images/image129.png" alt="export1"> \
   On the pop-up preview screen, click the **"Export Gerber"** button at the bottom. \
   <img src="./images/image130.png" alt="export2">
   
## Exporting a Bill of Materials (BOM)
1. In the top toolbar, click on the **Export** menu.
2. Select **"Bill of Materials (BOM)"** from the dropdown.
3. Click the **"Export BOM"** button to download the file.

### Exporting a Pick and Place File (CPL)
1. Go to the same **Export** menu.
2. Click on **"Pick and Place File (CPL)"**.
3. Click **Export**.


## 6. Miscellaneous (Misc)
Minor but Useful EasyEDA Features
1. Cloud-Based Project Storage\
EasyEDA can save projects online, allowing users to access their designs from different computers without manually transferring files. It makes it easier to continue work across multiple devices.

2. Auto-Save Function\
EasyEDA includes auto-save functionality to reduce the risk of losing work due to browser crashes or accidental closing. This is helpful for beginners and during long design sessions.

3. Easy Project Sharing\
Users can share projects with others using links or public project pages. This is useful for teamwork, teaching, open-source hardware, and peer review.

4. Public Project Library\
EasyEDA provides access to public projects created by other users. Beginners can learn from existing examples instead of starting from scratch.

5. File Export Options\
EasyEDA supports exporting designs in different formats such as PDF, PNG, SVG, Gerber, and project files. This makes it easier to document, share, or manufacture the design.
## 7. Troubleshooting
If you created the component yourself, you need to assign a physical copper layout (footprint) to it. The error text is actually a hyperlink. Click directly on the blue code (e.g., $1I61). EasyEDA will automatically jump to and highlight the problematic component on your schematic.
<img width="525" height="104" alt="image" src="./images/image131.png" />

Click the empty box to open the **Footprint Manager** window.
<img width="1616" height="475" alt="image" src="./images/image132.png" />
After you select a suitable footprint, the right-hand panel should no longer be highlighted in red.
<img width="1300" height="769" alt="image" src="./images/image133.png" />

This warning occurs when EasyEDA detects a wire or pin labeled with a net name (like GPIO1) that does not connect to anything else. Check the wire name.
<img width="940" height="99" alt="image" src="./images/image134.png" />

## 8. Support & Resources
 [EasyEDA Official Tutorial](https://prodocs.easyeda.com/)\
 Beginner-friendly introduction to EasyEDA Standard Edition.

[EasyEDA Official Forum](https://easyeda.com/forum)\
For EasyEDA-specific questions, feature requests, and bug reports.

[EasyEDA Official YouTube Channel](https://www.youtube.com/channel/UCRoMhHNzl7tMW8pFsdJGUIA/videos)\
Official video tutorials, feature demonstrations, and workflow guides.
