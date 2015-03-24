######################################################
# CC3100MOD Xbee Style Breakout Board                #
######################################################
Contains a diptrace schematic (.dch) and pcb layout (.dip) file

##Schematic:##
* <TT> Bill Of Materials </TT>
 * 1 CC3100MOD Wifi Wireless Network Module
 * 1 AH316M245001-T Antenna
 * 1 1.0pF capacitor
 * 1 3.6nH inductor
 * 2 10kOhm resistors
 * 1 100kOhm resistor
 * 2 10 pin header strips

##Board Layout:##
* <TT> Dimensions </TT>
 * Rectilinear Outline
  * X: 960 mils
  * Y: 1297 mils
 * W/ Two Triangular "Cutouts" On Top
  * X: 299 mils
  * Y: 257 mils
* <TT> Header Pins (From Top To Bottom) </TT>
 * Left Hand Side:
  * H1-1: VDD_3V3 (TI Pins 36, 37, 40)
  * H1-2: UART_TX (TI Pin 46)
  * H1-3: UART_RX (TI Pin 27)
  * H1-4: NC
  * H1-5: /RESET (TI Pin 35)
  * H1-6: /WAKE (TI Pin 4)
  * H1-7: NC
  * H1-8: NC
  * H1-9: NC
  * H1-10: GND (TI Pins 1, 2, 26, 27, 28, 30, 32, 38, 43, 55-63)
 * Right Hand Side:
  * H2-10: HOST_INTR (TI Pin 11)
  * H2-9: NC
  * H2-8: SPI_SCLK (TI Pin 5)
  * H2-7: /SPI_CS (TI Pin 8)
  * H2-6: UART_CTS (TI Pin 51)
  * H2-5: NC
  * H2-4: NC
  * H2-3: SPI_MISO (TI Pin 7)
  * H2-2: UART_RTS (TI Pin 44)
  * H2-1: SPI_MOSI (TI Pin 6)
