# Getting-started-with-LoRa-AT-commands
A small powerful long range radio trans-receiver module, works on 5volts. Let's configure two pairs to set up communication between them.
Get full info from here: https://www.instructables.com/Getting-Started-With-LoRa-AT-Commands/

I got my hands on REYAX Lora modules, and in this tutorial, we will configure these modules to communicate with each other. Lora platform is known for its long range as specified by the name LoRa (Long range radio). The normal communication distance is 8Km with rubber ducky antenna. Internet is not required in these trans-receiver modules. So, used to operate electric appliances in villages with this low-cost module.

We can design a pcb prototype using JLCPCB service, starting just in $2 for 5 pcs.  If you sign-up using this link you will get coupons of $30 and new user rewards. Checkout to JLCPCB and turn your projects into amazing products. https://jlcpcb.com/SSR

The RYLR998 transceiver module feature the LoRa long range modem that provides ultra-long range spread spectrum communication and high interference immunity whilst minimizing current consumption. This one supports UART protocol and has an inbuilt low power Nuvaton’s microcontroller. So, only few connections are needed to be done externally & can be operated on 3.3volts.

Features:
NUVOTON MCU & Semtech LoRa Engine
Excellent blocking immunity
Smart receiving power saving mode
High sensitivity
Control easily by AT commands
Built-in antenna
Get it from here: https://www.amazon.com/REYAX-RYLR998-Interface-Antenna-Transceiver/dp/B099RM1XMG

Connections with Lora:
This radio module has inbuilt nuvoton's microcontroller, which is required to set up the connection using UART(RX-TX). But this need a external programmer board to convert USB data into Serial data.
So here I am using FTDI232RL programmer chip, the connection is very simple as shown in the figure.
First, set the correct COM port and then by choosing Arduino Nano or any other as microcontroller board open the Serial monitor. By default, the baud rate is 115200 and frequency is 865Mhz.

Application and Scope:
LoRa always plays with the range, good range radio modules can be used to do ON/OFF any machine, transfer data and communication without internet. We will make a project using Arduino, display and keypad with JLCPCB prototype service. A good long range LoRa messenger/communicator. Which is absolutely like a walkie talkie.
Most of my projects are completed because of using JLCPCB SMT assembly service. Providing cheapest SMT assembly just in $8 and quality remains amazing.  This is an article on full review of JLCPCB( https://jlcpcb.com/SSR ) assembly, see is it worth?  https://www.hackster.io/sainisagar7294/making-7-segment-display-using-neo-pixel-led-06ffb3
