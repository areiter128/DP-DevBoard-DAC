# Digital Power Development Board DAC Example
Code example used as test procedure of the Digital Power Development Board + Digital Power Plug-In Modues. The Digital Power Development Board can be found here on Microchip Technology's website: https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/DM330029

The device used in this exampe is **dsPIC33CK256MP506** mounted on the Digital Power Plug-In Module MA330048, which can be found here on Microchip Technology's website: https://www.microchip.com/DevelopmentTools/ProductDetails/ma330048

### Description:
This code example demonstrates the peripheral configuration requried for a Peak Current Mode Control loop with Slope Compensation. 

The control loop has been disabled in this example as there is no hardware to operate. However, it shows the PWM configuration with high-speed analog comparator and ADC converter. The two on-board potentiometers can be used to set the DAC reference and to emulate the current feedback. Thus it allows the user to evaluate the comparator response and input logic configuration of the PWM module.

