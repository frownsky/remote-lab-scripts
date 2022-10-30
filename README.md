# Remote Lab Server for STM32 Boards

To run the programming/debuggin server (OpenOCD) for a particular board:
```  
openocd -f server1-program.cfg 
```

To run the UART server (ser2net) for a particular board:
```
ser2net -c server1-serial.conf
```
