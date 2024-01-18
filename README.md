# 65uino Memory Hat

This is a hack Hat for the 65uino project to extend the memory to the maximum 4Kb minus the 256 bytes of Zero Page used by the RIOT memory and registers.

Is a hack Hat because it relocates the board ROM to the hat and uses pin headers to bring the ROM pins to the hat board. You will need to add some bodge wires to extend extra pins (A12 and R/WB) not available in the ROM socket.

This board has not been tested as of Rev. 0.2


## Memory Map
RIOT $0000-$00FF
RAM  $0100-$0FFF
ROM  $1000-$1FFF

## 65uino Project
The project author is Anders Nielsen and you can findit here https://github.com/AndersBNielsen/65uino/
You'll find more details at https://hackaday.io/project/190260-65uino
