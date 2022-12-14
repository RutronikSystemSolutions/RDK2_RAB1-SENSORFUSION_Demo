# RAB1-SENSORFUSION with RDK2 Demo

Rutronik Adapter Board 1 - Sensorfusion with Rutronik Development Kit 2 Demo Application. 

A list of the sensors and their addresses are given below:

```
Designator		Device			7-bit Hex I2C Address
U1			DPS310XTSA1				0x77
U2			SGP40-D-R4				0x59
U3			BMI270					0x68
U5			BME688					0x76
U6			BMP581					0x47
U7			SHT41-AD1B-R2				0x44 

```

Firmware example running on the RDK2 initiates and tests all the sensors on the RAB1-SENSORFUSION board.

 <img src="images/SensorFusion_RDK2.jpg" style="zoom:10%;" />

The data of all the sensors of RAB1-SENSORFUSION is printed out to the KitProg3 UART port.

<img src="images/results.png" style="zoom:100%;" />



## Requirements

- [ModusToolbox® software](https://www.infineon.com/cms/en/design-support/tools/sdk/modustoolbox-software/) v3.0

Using the code example with a ModusToolbox IDE:

1. Import the project: **File** > **Import...** > **General** > **Existing Projects into Workspace** > **Next**.
2. Select the directory where **"RDK2_SensorFusionAdapter_Demo"** resides and click  **Finish**.
3. Update libraries using  a **"Library Manager"** tool.
4. Select and build the project **Project ** > **Build Project**.

### Debugging

If you successfully have imported the example, the debug configurations are already prepared to use with a the KitProg3, MiniProg4, or J-link. Open the ModusToolbox perspective and find the Quick Panel. Click on the desired debug launch configuration and wait for the programming to complete and for the debugging process to start.

<img src="images/debugging.jpg" style="zoom:100%;" />

## Legal Disclaimer

The evaluation board including the software is for testing purposes only and, because it has limited functions and limited resilience, is not suitable for permanent use under real conditions. If the evaluation board is nevertheless used under real conditions, this is done at one’s responsibility; any liability of Rutronik is insofar excluded. 

<img src="images/rutronik_origin_kaunas.png" style="zoom:50%;" />



