# ESP8266-Client
A client web server based on the ESP8266 accepting http requests to control outputs

Description:
An ESP8266 based web server using the Wemos D1 board with control of
3 Outputs using HTTP GET or PUSH requests to switch accessories ON/OFF.
Sets the board into Client mode with WiFi settings defined by the
header file "wifiParams.h".
Starts the server on port <hostPort> defined in wifiParams.h and
displays LED ON/OFF buttons on the home page
Notes:
   1. Select board, "Wemos D1 R2 & mini"
   2. Select port /dev/cu.wchusbserialfd1330
   3. Wemos Pins are mapped to Arduino pins as follows:
       Wemos D1 Pin       Use Arduino Pin
            D0                   3
            D1                   1
            D2                  16
            D3                   5     OP1
            D4                   4     LED_BUILTIN ?
            D5                  14     OP2
            D6                  12     OP3
            D7                  13
            D8                   0
            D9                   2
            D10                 15
            D11                 13     ?
            D12                 12     ?
            D13                 14     ?
            D14                  4     ?
            D15                  5     ?
