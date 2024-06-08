# USART test
The USARTx is configured as follow:
* BaudRate = 115200 baud  
* Word Length = 8 Bits
* One Stop Bit
* No parity
* Hardware flow control disabled (RTS and CTS signals)
* Receive and transmit enabled

# Build
```
cmake -DCMAKE_BUILD_TYPE=Debug -B build
cmake --build build --target all
```
