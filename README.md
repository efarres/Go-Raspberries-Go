
Presentation and code corresponding to 
**Go, Raspberries, Go**
*Base42 Event - 8 de gener de 2015, Parc Tecnologic de la UdG*

## Objective
The objective of the presentation is describe the Go language and inform of the possibility of run a high level language as is Go 

Gobot and BCM2835 binding as possible ways to take the control of the hardware peripherals of the broadcom BCM2835 SoC.

## Presentation online
"Go and Raspberries" slides are stored in the [preset format](https://godoc.org/golang.org/x/tools/present), you can see the presentation online at [Go and Raspberries](http://go-talks.appspot.com/github.com/efarres/Go-Raspberries-Go/GoRaspberriesGo.slide)

## About bcm2835 library

It provides access to GPIO and other IO functions on the Broadcom BCM2835 chip.

It provides functions for reading digital inputs and setting digital outputs, using SPI and I2C, and for accessing the system timers.

Pin event detection is supported by polling (interrupts are not supported).

BCM2835 is a binding between Go and the bcm2835 C Library, a great C library, very well documented. 

Library source is available at [http://www.airspayce.com/mikem/bcm2835](http://www.airspayce.com/mikem/bcm2835) Author: *Mike McCauley*

For more details see the previous presentation Go, Rapsberries at GDB Barcelona event [GoRaspberry](https://github.com/efarres/GoRaspberry)
