# lab_asm_hdl

#NOTES
1 completar codigo en ensamblador completamente funcional
2 completar funciones trap con hacking o con los comentarios ayuda
3 ensamblamos el codigo a hexadecimal


console echo wcmd


#cuteCom

pasar el ensamblador a la direccion 0

probar primero el echo del serial

CUTECOM

send program with hexoutput and hexinput
send numbers with lf end and script mode but hexoutput deactivated
crlf doesnt matter because program ignores cr character
doesnt matter how many stuff is in each line
10ms of delay for keeping good behaviour 
https://www.cyberciti.biz/faq/find-out-linux-serial-ports-with-setserial/
/dev/ttyS0, UART: 16550A, Port: 0x03f8, IRQ: 4
/dev/ttyS1, UART: 16550A, Port: 0x1020, IRQ: 18
/dev/ttyS2, UART: unknown, Port: 0x03e8, IRQ: 4
/dev/ttyS3, UART: unknown, Port: 0x02e8, IRQ: 3
IF YOU HAS 4 HEX VALUES PER LINE YOU DONT ACTUALLY NEED TO DIVIDE BY 2; IS JUST THAT NUMBER
USE RANDOM ORG to generate number text files